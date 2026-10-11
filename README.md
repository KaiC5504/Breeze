# Breeze

A personal build of a cross-platform manga reader written in Flutter, with a Rust core.

## Platforms

- iOS / iPadOS (unsigned IPA, sideloaded)
- Android
- Windows, macOS, Linux

## Building the iOS app

The IPA is built on GitHub Actions, so no Mac is needed locally.

1. Open the **Actions** tab and pick **Build iOS IPA**.
2. Click **Run workflow** on the `main` branch.
3. When the run finishes, download the `ios-ipa` artifact. It contains `Breeze-iOS.ipa`.
4. Sideload the IPA with your usual tool. It is unsigned, so the tool signs it during install.

## Local development

See [AGENTS.md](AGENTS.md) for the toolchain, code generation and per-platform build commands.

## License

[MPL-2.0](LICENSE)

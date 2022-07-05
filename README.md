# Sample Flatpak Configuration for Sonixd

This repo is an example of a Flatpak configuration for [Sonixd](https://github.com/jeffvli/sonixd/). Discord RPC/wrapper from https://github.com/Suhndern/flatpak-discord-rpc-module. To connect to Discord, the Discord application should also be installed via Flatpak.

**Disclaimer**: This is not an official way to get Sonixd. I've made this as a demonstration. It also currently lacks OBS integration.

## Building
If you want to build and install this, you can run the following: 
1. Build the application: `flatpak-builder build-dir org.sonixd.Sonixd.yml`
2. Install it (as a user flatpak): `flatpak-builder --user --install --force-clean build-dir org.sonixd.Sonixd.yml`
3. Run it: `flatpak run --user org.sonixd.Sonixd`

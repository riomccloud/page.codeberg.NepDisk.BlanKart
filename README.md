# page.codeberg.NepDisk.BlanKart

This repo contains the Flatpak package for the [BlanKart](https://codeberg.org/NepDisk/blankart) game.

While the game is in Beta, it will be distributed using `.flatpak` files.

When it reaches stable state, it'll be uploaded to Flathub.

## Installing

Binaries for AMD64 architecture are available in the [Releases](https://github.com/riomccloud/page.codeberg.NepDisk.BlanKart/tags) section.

You can install it with your software manager or using the following command:

### System-wide

```
flatpak install blankart.flatpak
```
### User-wide

```
flatpak install --user blankart.flatpak
```

## Building

To build manually (especially to play the game on other architectures like AARCH64), clone the repo and run the following command:

```
flatpak build-bundle repo blankart2.flatpak page.codeberg.NepDisk.BlanKart --runtime-repo=https://flathub.org/repo/flathub.flatpakrepo
```
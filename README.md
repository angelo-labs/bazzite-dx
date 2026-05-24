# Bazzite Developer Edition

[![Build Bazzite DX](https://github.com/ublue-os/bazzite-dx/actions/workflows/build.yml/badge.svg)](https://github.com/ublue-os/bazzite-dx/actions/workflows/build.yml)

This is just bazzite, but with extra developer-specific tooling, aiming to match [Bluefin DX](https://docs.projectbluefin.io/bluefin-dx/) and [Aurora DX](https://docs.getaurora.dev/dx/aurora-dx-intro) in functionality

[`bazzite-gdx`](https://github.com/ublue-os/bazzite-gdx) will source from here and be focused for game development.

## Installation

To rebase an existing Bazzite NVIDIA installation to Bazzite DX for the first time, use:
```bash
brh rebase ostree-unverified-registry:ghcr.io/angelo-labs/bazzite-dx-nvidia:stable
```

After rebooting into Bazzite DX, the image includes this repo's signing key. Future rebases can use the signed image reference:
```bash
brh rebase ostree-image-signed:docker://ghcr.io/angelo-labs/bazzite-dx-nvidia:stable
```

After running a rebase command, reboot your system to complete the installation. 

## Acknowledgments

This project is built upon the work from [amyos](https://github.com/astrovm/amyos)

## Metrics

![Alt](https://repobeats.axiom.co/api/embed/8568b042f7cfba9dd477885ed5ee6573ab78bb5e.svg "Repobeats analytics image")

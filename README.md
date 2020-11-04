# customize-rpi

## Overview

Customize a Raspberry Pi image for redistribution.

## Pre-requisites

```bash
sudo apt-get install \
  --yes \
  expect \
  systemd-container
```

You need a Raspberry Pi OS Lite image file (.img).

## To run

```bash
sudo ./vdesktop 2020-08-20-raspios-buster-armhf-lite.img
```

## Acknowledgements

This is a fork of the [vdesktop](https://github.com/Botspot/vdesktop) project by [@Botspot](https://github.com/Botspot).

This fork focuses on running Raspberry Pi in unattended scripts, whereas vdesktop focuses on providing support for running Raspberry Pi OS images interactively.

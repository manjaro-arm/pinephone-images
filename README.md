# Manjaro ARM Pinephone
[![iso_build](https://github.com/manjaro-arm/pinephone-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/pinephone-images/actions)

## description

Release Branch for Manjaro ARM images for the Pinephone

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/pinephone-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d pinephone -e $EDITION`

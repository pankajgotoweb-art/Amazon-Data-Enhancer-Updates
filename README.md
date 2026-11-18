# Amazon Data Enhancer — Official Updates

This public repository is used only to distribute signed-off Windows installer releases and provide the update feed for Amazon Data Enhancer.

## Download

Open [Releases](https://github.com/pankajgotoweb-art/Amazon-Data-Enhancer-Updates/releases) and download \`AmazonEnhancer_Setup.exe\` from the release you need.

## Automatic updates

The packaged application checks this repository's public GitHub Releases for a newer version. When an update is available, the application asks before downloading the installer. The download is checked against the SHA-256 digest published by GitHub before the installer is started.

## Release asset naming

Every release must include exactly this installer asset name:

\`AmazonEnhancer_Setup.exe\`

Use a semantic version tag matching the application version, for example \`v1.0.1-beta.1\` or \`v1.0.2\`.

## Security and privacy

This repository contains public installer binaries and release notes only. It does not contain source code, Seller Central credentials, customer workbooks, application settings, logs, or browser profiles.

Source code is maintained separately in a private repository.

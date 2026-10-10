# Tm Visualization Suite releases

This repository hosts public downloads of the Tm Visualization Suite, a set of
visualization extensions for Qlik Cloud Analytics. The source code is
maintained separately.

## Download

Open the [Releases](https://github.com/Tallmaker/TmVisualizationSuite-releases/releases)
page and choose the version you need. Each release holds one archive for each
chart family, named `tm-vis-suite-<family>-<version>.zip`, and a demo app named
`tm-vis-suite-<version>-demo-app.qvf`.

Do not use GitHub's automatic "Source code" archives. Those archives contain no
extension.

## Install

1. Download the archive of the family you need.
2. In the Qlik Cloud management console, open Extensions.
3. Add the archive as a new extension.

Each family needs a license. The `release-manifest.json` asset lists the
extension name and the SHA-256 digest of every archive.

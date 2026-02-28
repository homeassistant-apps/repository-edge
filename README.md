# Edge - Unofficial Home Assistant Apps (Add-ons) Repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

### WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our apps (add-ons):

<https://github.com/homeassistant-apps/repository>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/homeassistant-apps/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Cloudflared][addon-cloudflared]

![Latest Version][cloudflared-version-shield]
![Supports aarch64 Architecture][cloudflared-aarch64-shield]
![Supports amd64 Architecture][cloudflared-amd64-shield]

Use a Cloudflare Tunnel to remotely connect to Home Assistant without opening any ports

[:books: Cloudflared add-on documentation][addon-doc-cloudflared]

### &#10003; [Newt][addon-newt]

![Latest Version][newt-version-shield]
![Supports aarch64 Architecture][newt-aarch64-shield]
![Supports amd64 Architecture][newt-amd64-shield]

Tunneling client to connect Home Assistant to Pangolin.

[:books: Newt add-on documentation][addon-doc-newt]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all my other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

Open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Cloudflared][cloudflared-issue]
- [Open an issue for the add-on: Newt][newt-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2026 [homeassistant-apps][github-org]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-cloudflared]: https://github.com/homeassistant-apps/app-cloudflared/tree/41e47e5
[addon-doc-cloudflared]: https://github.com/homeassistant-apps/app-cloudflared/blob/41e47e5/README.md
[cloudflared-issue]: https://github.com/homeassistant-apps/app-cloudflared/issues
[cloudflared-version-shield]: https://img.shields.io/badge/version-41e47e5-blue.svg
[cloudflared-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[cloudflared-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[addon-newt]: https://github.com/homeassistant-apps/app-newt/tree/cca869b
[addon-doc-newt]: https://github.com/homeassistant-apps/app-newt/blob/cca869b/README.md
[newt-issue]: https://github.com/homeassistant-apps/app-newt/issues
[newt-version-shield]: https://img.shields.io/badge/version-cca869b-blue.svg
[newt-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[newt-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[gitlabci-shield]: https://gitlab.com/homeassistant-apps/repository-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/homeassistant-apps/repository-edge/pipelines
[issue]: https://github.com/homeassistant-apps/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/homeassistant-apps/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html
[github-org]: https://github.com/homeassistant-apps
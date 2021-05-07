# Nginx Config for [DigitalPhoenixX.live](http://DigitalPhoenixX.live)

[![GitHub Release][github_release_badge]][github_release_link]
[![License][license-image]][license-url]

Note: While all the apps included in this project have their own K8s config ready to use. the server used is a 1 GB RAM AWS instance (t3.micro). which doesn't pass k8s minimium requirements. When using other distribution as k3s, the remaining ram isn't enough for multiple projects.

## To Clone

This repo uses git submodules feature. So, use the following to clone the repo

```sh
git clone --recurse-submodules https://github.com/TheDigitalPhoenixX/digitalphoenixx-live-nginx
```

[license-image]: https://img.shields.io/badge/License-MIT-brightgreen.svg
[license-url]: https://opensource.org/licenses/MIT

[github_release_badge]: https://img.shields.io/github/v/release/TheDigitalPhoenixX/digitalphoenixx-live-nginx.svg?style=flat&include_prereleases
[github_release_link]: https://github.com/TheDigitalPhoenixX/digitalphoenixx-live-nginx/releases
# Changelog

## 1.0.0 (2024-06-04)


### ⚠ BREAKING CHANGES

* Move argo workflows server ingress to workflows chart
* Switch to k8s with separate etcd
* Bump vcluster chart version to 0.20.0-beta.5
* Remove namespace manifest from vcluster deployment
* Use db-nvme-storage for vcluster control plane persistence
* Upgrade vcluster helm chart to 0.20.0-beta.2
* Use workflows as release name in vcluster
* Use nvme storage for vcluster database
* Fix vcluster syncer parameters
* Upgrade vcluster helm chart to 0.19.5
* Persist virtual cluster resources
* Use k0s for virtual cluster
* Deploy argo workflows in virtual cluster
* Create virtual cluster chart

### deps

* Bump vcluster chart version to 0.20.0-beta.5 ([b5699be](https://github.com/garryod/release-workflows-please/commit/b5699be1b27c974937c4f169db4661ea3ea1cb5d))
* Upgrade vcluster helm chart to 0.19.5 ([b9f6b88](https://github.com/garryod/release-workflows-please/commit/b9f6b88c700787dcd9b880aea3bfee81a11335a9))
* Upgrade vcluster helm chart to 0.20.0-beta.2 ([b69f7c0](https://github.com/garryod/release-workflows-please/commit/b69f7c0809275fb6bd4d0a12696da3b16606130d))


### Features

* Add different manifests and instructions for dev install ([ec2097c](https://github.com/garryod/release-workflows-please/commit/ec2097c6583c61d322f38e0dbb498a16f909dc8b))
* Add option to enable/disable ingress ([c17e70a](https://github.com/garryod/release-workflows-please/commit/c17e70adbeb14d5cacc5d70c4ed7997e72914783))
* Create virtual cluster chart ([aa3f84f](https://github.com/garryod/release-workflows-please/commit/aa3f84f1c31a062566a84134140708f1bf9a6d2a))
* Deploy argo workflows in virtual cluster ([fdaeb07](https://github.com/garryod/release-workflows-please/commit/fdaeb0738ef2fb8dae846f87bd0a76be2b1d88be))
* Deploy vcluster in a high-availability configuration ([5726cd1](https://github.com/garryod/release-workflows-please/commit/5726cd13880dae19005f4986429d18f97c9517b1))
* Install bitnami sealed secrets in virtual cluster ([77618a5](https://github.com/garryod/release-workflows-please/commit/77618a50b7713f5188cf58bfd07771b9ff83a727))
* Move argo workflows server ingress to workflows chart ([b005750](https://github.com/garryod/release-workflows-please/commit/b005750fbcbf167afcbbfec7e9a2a9b77e22bf8f))
* Only deploy sealed-secrets in dev cluster ([3b7ecb0](https://github.com/garryod/release-workflows-please/commit/3b7ecb0c066af566c3f70893d0f30492f3ee4dd8))
* Persist virtual cluster resources ([608d34d](https://github.com/garryod/release-workflows-please/commit/608d34d2968d94df1f08ca1ac46aa387df1c165c))
* Remove namespace manifest from vcluster deployment ([875542a](https://github.com/garryod/release-workflows-please/commit/875542a6ff7e4b2c1a7d77cb176badf5b5547746))
* Switch to k8s with separate etcd ([ba5849e](https://github.com/garryod/release-workflows-please/commit/ba5849ed4cbed786b9b8a0488fd9391e1c512c2c))
* Use db-nvme-storage for vcluster control plane persistence ([2b30ccf](https://github.com/garryod/release-workflows-please/commit/2b30ccf9e75b68232448cd8c5f442edf74855037))
* Use k0s for virtual cluster ([732b3e2](https://github.com/garryod/release-workflows-please/commit/732b3e27e5cc78c5a0e63312c213d2e8bc93952b))
* Use nvme storage for vcluster database ([ed908d7](https://github.com/garryod/release-workflows-please/commit/ed908d729942101f2c23f62f30caea14d5b73241))


### Bug Fixes

* Fix vcluster syncer parameters ([bb552e4](https://github.com/garryod/release-workflows-please/commit/bb552e4f87d108b48c71334224a22391912ef406))
* Use workflows as release name in vcluster ([560a82f](https://github.com/garryod/release-workflows-please/commit/560a82f42a7e7487552d5bff41b25b49911b1b35))

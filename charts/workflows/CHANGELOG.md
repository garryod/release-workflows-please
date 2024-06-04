# Changelog

## [0.2.0](https://github.com/garryod/release-workflows-please/compare/workflows-v0.1.0...workflows@v0.2.0) (2024-06-04)


### ⚠ BREAKING CHANGES

* Move argo workflows server ingress to workflows chart
* Use high availability postgresql for workflows persistence
* Use db-nvme-storage for vcluster control plane persistence
* Upgrade vcluster helm chart to 0.20.0-beta.2
* Automatically generate workflows secrets on initial install
* Add high availability postgres to workflows deployment
* Use nvme storage for vcluster database
* Upgrade argo-workflows helm chart to 0.41.4
* Update sealed secrets for Argus deployment
* Fixup argo server sso
* Delegate RBAC to namespaces
* Authenticate argo workflows via SSO
* Deploy argo workflows across multiple vcluster namespaces
* Deploy argo workflows in virtual cluster
* Configure default service accounts
* Update SSO credentials
* Enable authentication with OIDC
* Migrate to dedicated namespace
* Setup ingress
* Initial deployment

### deps

* Upgrade argo-workflows helm chart to 0.41.4 ([961aba7](https://github.com/garryod/release-workflows-please/commit/961aba7e759e9cb00a7117baa9574af27927eec6))
* Upgrade vcluster helm chart to 0.20.0-beta.2 ([b69f7c0](https://github.com/garryod/release-workflows-please/commit/b69f7c0809275fb6bd4d0a12696da3b16606130d))


### Features

* Add different manifests and instructions for dev install ([ec2097c](https://github.com/garryod/release-workflows-please/commit/ec2097c6583c61d322f38e0dbb498a16f909dc8b))
* Add high availability postgres to workflows deployment ([2290172](https://github.com/garryod/release-workflows-please/commit/2290172a23f63515dac306f957ae2ba0688c3e1a))
* Authenticate argo workflows via SSO ([8a9ee4b](https://github.com/garryod/release-workflows-please/commit/8a9ee4b66841d107863df7547c5e0b0296cdd011))
* Automatically generate workflows secrets on initial install ([666d381](https://github.com/garryod/release-workflows-please/commit/666d38104fbe9033fc0c11906202683a6a1b9780))
* Configure default service accounts ([f9ee6e3](https://github.com/garryod/release-workflows-please/commit/f9ee6e37fa1322a9a5f1ff543bbe7cb476d9825e))
* Delegate RBAC to namespaces ([43fa47c](https://github.com/garryod/release-workflows-please/commit/43fa47cebae1e51f7bee69858f72856fcd71bb94))
* Deploy argo workflows across multiple vcluster namespaces ([cad61b8](https://github.com/garryod/release-workflows-please/commit/cad61b8442997a5c8de9d3a9460166fb24fa3f1b))
* Deploy argo workflows in virtual cluster ([fdaeb07](https://github.com/garryod/release-workflows-please/commit/fdaeb0738ef2fb8dae846f87bd0a76be2b1d88be))
* Deploy argo-workflows in a high-availability configuration ([0c54a98](https://github.com/garryod/release-workflows-please/commit/0c54a9805b5761df6086c22d08db46610433c25a))
* Enable authentication with OIDC ([5bd9ba2](https://github.com/garryod/release-workflows-please/commit/5bd9ba2b4981ed538f95cd4773a4ee39ad079864))
* Initial deployment ([0813c0c](https://github.com/garryod/release-workflows-please/commit/0813c0c66536e1d217aa20bd8a0b5c6e8dc8c7f7))
* Migrate to dedicated namespace ([8a5147f](https://github.com/garryod/release-workflows-please/commit/8a5147f84dbed7bb73e4b53be2cfb81462fb5bff))
* Move argo workflows server ingress to workflows chart ([b005750](https://github.com/garryod/release-workflows-please/commit/b005750fbcbf167afcbbfec7e9a2a9b77e22bf8f))
* Setup ingress ([b157087](https://github.com/garryod/release-workflows-please/commit/b157087ac63bb9d80e1853c3ea5d10a08066ec8d))
* Use db-nvme-storage for vcluster control plane persistence ([2b30ccf](https://github.com/garryod/release-workflows-please/commit/2b30ccf9e75b68232448cd8c5f442edf74855037))
* Use high availability postgresql for workflows persistence ([1273994](https://github.com/garryod/release-workflows-please/commit/1273994ad2343cb6a37cb7f0f08b3d99117df070))
* Use nvme storage for vcluster database ([ed908d7](https://github.com/garryod/release-workflows-please/commit/ed908d729942101f2c23f62f30caea14d5b73241))


### Bug Fixes

* Fixup argo server sso ([8759cae](https://github.com/garryod/release-workflows-please/commit/8759cae7a79931a5ea47c98468998036cfec0419))
* Update sealed secrets for Argus deployment ([7e109f6](https://github.com/garryod/release-workflows-please/commit/7e109f6157eee1918ebd7c96a39b00b7c4bc084f))
* Update SSO credentials ([b17b155](https://github.com/garryod/release-workflows-please/commit/b17b15561aeb90f1e393c5a1dcdb673729d73115))

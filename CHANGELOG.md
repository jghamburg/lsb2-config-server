# [1.1.0](https://github.com/jghamburg/lsb2-config-server/compare/v1.0.2...v1.1.0) (2019-12-26)


### Features

* **spring:** upgrade spring cloud ([741c9f7](https://github.com/jghamburg/lsb2-config-server/commit/741c9f7e7843230073375ca04ab836e1ba07f6d2))

## [1.0.2](https://github.com/jghamburg/lsb2-config-server/compare/v1.0.1...v1.0.2) (2019-12-24)


### Bug Fixes

* **docker-compose:** fix local startup ([e001e1c](https://github.com/jghamburg/lsb2-config-server/commit/e001e1cb64dcccb688cd6d59af9d4a077f4df255))
* **runtime:** fix local startup config ([e7a3650](https://github.com/jghamburg/lsb2-config-server/commit/e7a3650772b8a56463c99f5600ed048f0901659f))

## [1.0.1](https://github.com/jghamburg/lsb2-config-server/compare/v1.0.0...v1.0.1) (2019-09-02)


### Bug Fixes

* **build:** support semantic release without ci ([0b9864b](https://github.com/jghamburg/lsb2-config-server/commit/0b9864b))

# 1.0.0 (2019-09-02)


### Bug Fixes

* **build:** basic correction for using jib and docker hub ([267a3f4](https://github.com/jghamburg/lsb2-config-server/commit/267a3f4))
* **build:** Cleanup dockerfile ([e27635c](https://github.com/jghamburg/lsb2-config-server/commit/e27635c))
* **build:** cleanup gradle build ([cbf4a3e](https://github.com/jghamburg/lsb2-config-server/commit/cbf4a3e))
* **build:** delete unused dependencies ([1be8d9c](https://github.com/jghamburg/lsb2-config-server/commit/1be8d9c))
* **build:** Upgrade spring cloud release to Greenwich.SR1 ([2eace05](https://github.com/jghamburg/lsb2-config-server/commit/2eace05))
* **build:** use dependencies.implementation in gradle ([f9be3ce](https://github.com/jghamburg/lsb2-config-server/commit/f9be3ce))
* **config:** cleanup actuator endpoints ([e0bd7f0](https://github.com/jghamburg/lsb2-config-server/commit/e0bd7f0))
* **config:** correct path to local git repo ([6c03f74](https://github.com/jghamburg/lsb2-config-server/commit/6c03f74))
* **config:** endpoint configuration ([6e76bee](https://github.com/jghamburg/lsb2-config-server/commit/6e76bee))
* **config:** error running under k8s ([f908d60](https://github.com/jghamburg/lsb2-config-server/commit/f908d60))
* **config:** error running under k8s ([745d228](https://github.com/jghamburg/lsb2-config-server/commit/745d228))
* **config:** fix uri local reference ([9357696](https://github.com/jghamburg/lsb2-config-server/commit/9357696))
* **config:** Reference to local git ([0d55cbb](https://github.com/jghamburg/lsb2-config-server/commit/0d55cbb))
* **config:** reference to local git repo ([c5dc247](https://github.com/jghamburg/lsb2-config-server/commit/c5dc247))
* **config:** stop git clone on startup ([f585eda](https://github.com/jghamburg/lsb2-config-server/commit/f585eda))
* **docker:** add debug to run.sh ([f29aaf3](https://github.com/jghamburg/lsb2-config-server/commit/f29aaf3))
* **docker:** add push to docker hub ([b64e506](https://github.com/jghamburg/lsb2-config-server/commit/b64e506))
* **docker:** use full jvm 11 because req. mods for GitHub access unknown ([ce692c0](https://github.com/jghamburg/lsb2-config-server/commit/ce692c0))
* **helm:** error running under jdk11 ([ccf062d](https://github.com/jghamburg/lsb2-config-server/commit/ccf062d))
* **helm:** fix deployment with configmap ([7c90aea](https://github.com/jghamburg/lsb2-config-server/commit/7c90aea))
* **helm:** update helm plugin to publish proeprly ([38e265a](https://github.com/jghamburg/lsb2-config-server/commit/38e265a))
* **jib:** update base image ([d752b08](https://github.com/jghamburg/lsb2-config-server/commit/d752b08))
* **security:** add security Config with user access ([6c7b58b](https://github.com/jghamburg/lsb2-config-server/commit/6c7b58b))


### Features

* **build:** add docker images with docker-compose ([768c869](https://github.com/jghamburg/lsb2-config-server/commit/768c869))
* **build:** add new support of maven BOM dependencies ([954b966](https://github.com/jghamburg/lsb2-config-server/commit/954b966))
* **build:** add semantic versioning support ([d236ed4](https://github.com/jghamburg/lsb2-config-server/commit/d236ed4))
* **build:** update gradle ([7e3a932](https://github.com/jghamburg/lsb2-config-server/commit/7e3a932))
* **build:** Upgrade grade to 4.8.1 ([2b0e342](https://github.com/jghamburg/lsb2-config-server/commit/2b0e342))
* **build:** Upgrade gradle version ([61a4bf6](https://github.com/jghamburg/lsb2-config-server/commit/61a4bf6))
* **config:** change to external git repo reference ([074a2f0](https://github.com/jghamburg/lsb2-config-server/commit/074a2f0))
* **deploy:** add first helm deployment to gradle build ([4a647fb](https://github.com/jghamburg/lsb2-config-server/commit/4a647fb))
* **docker:** add good practices ([e9c6603](https://github.com/jghamburg/lsb2-config-server/commit/e9c6603))
* **gradle:** upgrade libraries ([195315a](https://github.com/jghamburg/lsb2-config-server/commit/195315a))
* **helm:** add support for helm packaging and installation ([3a83c77](https://github.com/jghamburg/lsb2-config-server/commit/3a83c77))
* **monitoring:** extend actuator endpoint access ([c9386c0](https://github.com/jghamburg/lsb2-config-server/commit/c9386c0))
* **spring-cloud:** Upgrade version ([d4504cb](https://github.com/jghamburg/lsb2-config-server/commit/d4504cb))

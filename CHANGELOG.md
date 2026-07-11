# Changelog

## [2.9.0](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/compare/v2.8.0...v2.9.0) (2026-07-11)


### 🚀 New Features

* add namespace_labels variable to all modules ([ec06635](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/ec06635fd49d3461067a7c4bbdb7f7ef1dcbf5be))
* add namespace_labels variable to all modules ([445c620](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/445c620ea884e75adcbbc44ea885781409e3eb0d))

## [2.8.0](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/compare/v2.7.0...v2.8.0) (2026-05-19)


### 🚀 New Features

* migrate ingress from Traefik IngressRoute to Istio Gateway API HTTPRoute ([2cf43e7](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/2cf43e720c83ececd05aad4832383c7ed2e17031))
* migrate ingress to Istio Gateway API HTTPRoute ([47063da](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/47063daea955778332be664a6a29efd978dd6b91))


### 🔥 Bug Fixes

* avoid nil pointer when httproute values are not defined ([625b879](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/625b879996cf69d9b2ba49343a22f0d068d09260))
* remove loki_credentials from kind/outputs.tf ([d2f47fe](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/d2f47fe274b85a001ddcde544d762bd3cdafaa0e))
* remove loki_credentials output referencing removed htpasswd resource ([37085ed](https://github.com/gersonrs/modern-gitops-stack-module-loki-stack/commit/37085edc2db8df82ed18914079c9e5674d61b0f3))

## [2.7.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v2.6.1...v2.7.0) (2026-01-26)


### 🚀 New Features

* adjust workflows ([8a13c9e](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/8a13c9e23622d61ca5ebdf33b9192b45359168cb))
* **chart:** minor update of dependencies on loki-microservice chart ([470258f](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/470258f0641ec5ae277be99fd468b0d4c6dcfb88))
* **chart:** minor update of dependencies on loki-microservice chart ([f74c51b](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/f74c51b66cdfad78c0ef1589e5ff8103a07e3b59))
* update the things ([1a03462](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/1a0346222d6c65f41cb2ee7b110ab45d699f2632))


### 📚 Documentation

* add Copilot instructions for AI coding assistance ([7b80252](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/7b802521302622c184b4bc5da5352375bc961e1e))

## [2.6.1](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v2.6.0...v2.6.1) (2025-02-08)


### ⌨️ Code Refactoring

* adjust workflows ([9820209](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/9820209a5fa59bd9746c6eafc546946215c7bdb1))
* try adjust code 5 ([55579a2](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/55579a2e00f9a1fe5dcfd2b756d4ccda789966be))

## [2.6.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v2.5.0...v2.6.0) (2025-01-18)


### 🚀 New Features

* update project ([0aa5b3d](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/0aa5b3d48bb942bf2eaa6378d24c0c0d218e5948))
* update project ([f5bfd95](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/f5bfd95c27071e1ee1516b05269219134329b3d0))

## [2.5.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v2.4.0...v2.5.0) (2024-05-01)


### 🚀 New Features

* change chart update to include secrets ([9c8eb0c](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/9c8eb0c463bd9a706ef865fae432c02c7219b1f8))


### 📚 Documentation

* **terraform-docs:** generate docs and write to README.adoc ([089f39b](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/089f39bb568bf8ace98094ca6ffdce3b569064cd))

## [2.4.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v2.3.0...v2.4.0) (2024-05-01)


### 🚀 New Features

* add pre-commit, config release-please workflow and adjust add-to-project workflow ([07f4605](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/07f4605f58a8529ded2c5de3e89e178733d1703e))
* **doc:** update and adjust documentation ([6342707](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/6342707585dc6159fe49da6fb0e2bfd8ebae2f95))
* Finish configuration ([b4f670d](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/b4f670d2425e96e129a0edfb749cf193b4ce1965))
* module modularization ([719e66e](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/719e66ed3686cb53ed34309044532bff2f9bac71))
* module modularization ([92a2e78](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/92a2e7854f1a8af498d90326ad48ad75b27cd014))
* module modularization ([a096837](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/a096837d841f59af5f515a5976d2929ebd774725))
* pull request template ([975f9a5](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/975f9a538ccd0049c001e531863584728f07a8dc))


### 📚 Documentation

* remove sks link ([5de8773](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/5de87735c9a3ca444df60646b71c4e0c903b9d5d))
* **terraform-docs:** generate docs and write to README.adoc ([d43832c](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/d43832c9c1da9ef3b8b3431078b54d2ef975aacc))


### ⚙️ Chores

* release 1.0.0 ([4342d66](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/4342d666ec75f33281397f650d94d354ea7ff75f))
* release 1.1.0 ([41c18fa](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/41c18facdf36e67cb9c5951d178f9ff4417a25b8))
* release 1.2.0 ([0af8d65](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/0af8d6516bfe88cbe54672e239efdda3bae511a0))

## [1.2.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v1.1.0...v1.2.0) (2024-04-26)


### Features

* pull request template ([975f9a5](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/975f9a538ccd0049c001e531863584728f07a8dc))

## [1.1.0](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/compare/v1.0.0...v1.1.0) (2024-04-26)


### Features

* **doc:** update and adjust documentation ([6342707](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/6342707585dc6159fe49da6fb0e2bfd8ebae2f95))

## 1.0.0 (2024-04-24)


### Features

* Finish configuration ([b4f670d](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/b4f670d2425e96e129a0edfb749cf193b4ce1965))
* module modularization ([719e66e](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/719e66ed3686cb53ed34309044532bff2f9bac71))
* module modularization ([92a2e78](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/92a2e7854f1a8af498d90326ad48ad75b27cd014))
* module modularization ([a096837](https://github.com/GersonRS/modern-gitops-stack-module-loki-stack/commit/a096837d841f59af5f515a5976d2929ebd774725))

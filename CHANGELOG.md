# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 1.1.0 - 2022-08-30

### Changed

- Disabled `app_instances` step while we transition to v2.

## 1.0.1 - 2022-07-06

### Changed

- Use different way of fetching app instances to see if that'll have any effect.

## 1.0.0 - 2022-05-25

### Added

- Ingest new entities
  - `netskope_tenant`
  - `netskope_device`
  - `netskope_user`
  - `netskope_user_configuration`
  - `netskope_app_instance`
- Build new relationships
  - `netskope_tenant_has_device`
  - `netskope_device_has_user`
  - `netskope_user_has_configuration`
  - `netskope_tenant_has_app_instance`

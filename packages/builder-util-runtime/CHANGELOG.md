# builder-util-runtime

## 9.0.0-alpha.0

### Major Changes

- [#6556](https://github.com/electron-userland/electron-builder/pull/6556) [`a138a86f`](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222) Thanks [@mmaietta](https://github.com/mmaietta)! - Breaking changes
  Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/
  Fail-fast for windows signature verification failures. Adding `-LiteralPath` to update file path to disregard injected wildcards
  Force strip path separators for backslashes on Windows during update process
  Force authentication for local mac squirrel update server

  Fixes:
  fix(nsis): Adding --INPUTCHARSET to makensis. (#4898 #6232 #6259)

  Adding additional details to error console logging

## 8.9.2

### Patch Changes

- [#6400](https://github.com/electron-userland/electron-builder/pull/6400) [`66ca625f`](https://github.com/electron-userland/electron-builder/commit/66ca625f892329fd7bedf52fddc6659ec83b7cd3) Thanks [@jbool24](https://github.com/jbool24)! - refactor: update Bitbucket publisher to have optional config options for Token and Username (Bitbucket Private Repos)

## 8.9.1

### Patch Changes

- [#6333](https://github.com/electron-userland/electron-builder/pull/6333) [`54ee4e72`](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff) Thanks [@lutzroeder](https://github.com/lutzroeder)! - fix: SnapStoreOptions required properties (#6327)

## 8.9.0

### Minor Changes

- [#6228](https://github.com/electron-userland/electron-builder/pull/6228) [`a9453216`](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8) Thanks [@mmaietta](https://github.com/mmaietta)! - feat: adding Bitbucket publisher and autoupdater

## 8.8.1

### Patch Changes

- [#6193](https://github.com/electron-userland/electron-builder/pull/6193) [`7f933d00`](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e) Thanks [@mmaietta](https://github.com/mmaietta)! - fix: adding snapStore to AllPublishOptions so that it properly is generated via `pnpm schema`

## 8.8.0

### Minor Changes

- [#6167](https://github.com/electron-userland/electron-builder/pull/6167) [`f45110cb`](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f) Thanks [@mmaietta](https://github.com/mmaietta)! - feat: Adding Keygen as an official publisher/updater for electron-builder (#6167)

## 8.7.10

### Patch Changes

- a4eae34f: Synchronizing CLI and package.json versions. Updating auto-publish values + changeset generation to be more frictionless

## 8.7.9

### Patch Changes

- 878671d0: Updating patch number as many deps were updated as parted of RenovateBot integration

## 8.7.8

### Patch Changes

- 1272afc5: Initial introduction of changset config

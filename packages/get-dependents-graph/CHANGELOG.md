# @changesets/get-dependents-graph

## 1.0.1

### Patch Changes

- [`04ddfd7`](https://github.com/atlassian/changesets/commit/04ddfd7c3acbfb84ef9c92873fe7f9dea1f5145c) [#305](https://github.com/atlassian/changesets/pull/305) Thanks [@Noviny](https://github.com/Noviny)! - Add link to changelog in readme

* [`b49e1cf`](https://github.com/atlassian/changesets/commit/b49e1cff65dca7fe9e341a35aa91704aa0e51cb3) [#306](https://github.com/atlassian/changesets/pull/306) Thanks [@Andarist](https://github.com/Andarist)! - Ignore `node_modules` when glob searching for packages. This fixes an issue with package cycles.

* Updated dependencies [[`04ddfd7`](https://github.com/atlassian/changesets/commit/04ddfd7c3acbfb84ef9c92873fe7f9dea1f5145c), [`e56928b`](https://github.com/atlassian/changesets/commit/e56928bbd6f9096def06ac37487bdbf28efec9d1)]:
  - @changesets/types@1.0.1

## 1.0.0

### Major Changes

- [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20) [#290](https://github.com/atlassian/changesets/pull/290) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Initial release of `@changesets/get-dependents-graph`. If you're migrating from `get-dependents-graph`, you will need to pass the `Packages` object(which is returned from `@manypkg/get-packages`) to `getDependentsGraph` and also import `getDependentsGraph` as a named export instead of a default export.

### Patch Changes

- Updated dependencies [[`41e2e3d`](https://github.com/atlassian/changesets/commit/41e2e3dd1053ff2f35a1a07e60793c9099f26997), [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20), [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20), [`2363366`](https://github.com/atlassian/changesets/commit/2363366756d1b15bddf6d803911baccfca03cbdf)]:
  - @changesets/types@1.0.0

# ember-cli-deploy-sentry Changelog

### 0.7.0
- Add ability to associate a commit with a release [#62]
- Make it obvious where to get the keys for hosted accounts [#59]
- Update mock-fs to use more recent versions of Node.js [#55]
- Upload on didPrepare hook to fix gzip issues  [#52]

### 0.5.5
- Remove jQuery usages [#45]

### 0.5.4
- Remove sentryApiKey from required config params [#43]
- Add strictSSL option for request [#43]

### 0.5.3
- Remove </meta> to prevent IE10 from breaking [#40]

### 0.5.2
- Fix deprecation warning for ember-cli/lib/ext/promise [#35]
- Add config documentation [#33]

### 0.5.1
- Remove documentation for `didDeployMessage` config option as its gone

### 0.5.0
Thanks to @kmiyashiro, @Turbo87 and especially @duizendnegen for making this release happen!

- Add bearer token authentication [#21]
- Support ember-cli-deploy-plugin 0.2.9 [#27]

### 0.4.0

- Gracefully handle reuploading sourcemaps for releases with assigned issues
- Several logging improvements
- Fix releaseMetaName not being respected by raven service
- Several Documentation fixes

### 0.3.1

- Fix possibly broken tarball

### 0.3.0

- Rate limit uploaded sourcemaps
- Update mock-fs dependency to support newer versions of node
- Use prepare hook instead of didBuild hook to catch revision data
- Fix windows issues by using form-data library directly

### 0.2.1

- Fix logging

### 0.2.0

- Add service for usage with ember-cli-sentry

### 0.1.0

- Initial release.

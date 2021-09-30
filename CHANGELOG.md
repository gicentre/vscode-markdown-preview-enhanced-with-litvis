## 0.30.1

- Fix `clearCache()` function

## 0.30.0

- Sync fork with the upstream `mume` library
- Upgrade vega to 5.21.0, vega-lite to 5.1.1, vega-embed to 6.19.1 and vega-loader to 4.4.1
- Upgrade some auxiliary dependencies and make a few small refactors

## 0.29.2

- Fix apache arrow loader

## 0.29.1

- Fix extension loading by removing [`@types/vfile`](https://www.npmjs.com/package/@types/vfile)

## 0.29.0

- Upgrade `vega-lite` from v4 to v5
- Change how `vega`, `vega-embed`, `vega-lite`, `vega-loader`, `loader-arrow` and `apache-arrow` are embedded.
  The versions are no longer pinned.
  To upgrade to the latest version in the curren semver major band, all you need is to reinstall the extension.

## 0.28.0

- Upgrade vega to 5.19.1
- Upgrade `immer` to 8.0.1 to mitigate [CVE-2020-28477](https://nvd.nist.gov/vuln/detail/CVE-2020-28477)

## 0.27.2

- Fix issue with package sub-dependencies

## 0.27.1

- Fix minor issue with TypeScript typings

## 0.27.0

- Sync fork with the upstream project
- Upgrade vega to 5.18.0, vega-embed to 6.15.0, apache-arrow to 2.0.0 and vega-loader-arrow to 0.0.9

## 0.26.0

- Upgrade vega to 5.17.0, vega-lite to 4.17.0 and vega-embed to 6.12.2

## 0.25.0

- Upgrade vega to 5.15.0 and vega-lite to 4.15.0
- Bump dependencies

## 0.24.0

- Sync fork with the upstream project
- Upgrade vega to 5.14.0 and vega-embed to 6.11.1, fix CDN vega versions

## 0.23.0

- Upgrade vega-lite to 4.14.1 and vega-embed to 6.10.0

## 0.22.0

- Upgrade vega to 5.13.0, vega-lite to 4.13.1 and vega-embed to 6.9.0

## 0.21.0

- Upgrade vega to 5.10.1, vega-lite to 4.10.2 and vega-embed to 6.5.2

## 0.20.0

- Upgrade vega to 5.10.0, vega-lite to 4.5.1, vega-embed to 6.3.2 and apache-arrow to 0.16.0

## 0.14.1

- Upgrade vega to 5.9.0, vega-lite to 4.0.0 and vega-embed to 6.2.1

## 0.14.0

- Upgrade vega-lite to 4.0.0-beta.11, fix outdated vega versions in CDN links (affects interactive mode only)

## 0.13.0

- Update apache-arrow to 0.15.0, vega to 5.7.3, vega-lite to 4.0.0-beta.10 and vega-embed to 6.0.0

## 0.12.0

- Upgrade vega to 5.7.0, vega-lite to 4.0.0-beta.8, vega-embed to 5.1.3 and vega-loader-arrow to 0.14.1
- Sync with upstream package to resolve various issues in the latest versions of editors (<https://github.com/gicentre/vscode-markdown-preview-enhanced-with-litvis/pull/2)>

## 0.11.0

- Upgrade vega to 5.4.0 and vega-embed to 4.2.0
- Support apache-arrow files in vega specs (<https://github.com/gicentre/litvis/issues/31)>
- Fix incorrect parsing of keys in elm string representation (<https://github.com/gicentre/litvis/issues/29#issuecomment-496008915)>

## 0.10.3

- Upgrade vega to 5.3.5 and vega-lite to 3.2.1
- \[elm-string-representation] Allow any strings in keys except `" = "`

## 0.10.2

- Upgrade vega to 5.3.2, vega-lite to 3.0.2 and vega-embed to 4.0.0
- Use JSDelivr as lib CDN instead of CloudFlare

## 0.10.1

- Downgrade vega from 5.3.0 to 5.1.0 to avoid `Error: Cycle detected in dataflow graph`

## 0.10.0

- New command: _Markdown Preview Enhanced with Litvis: Clear Cache_ (useful when need to upgrade Elm dependencies or when cache is corrupt)
- Fix a number of regressions in Elm output parsing and URL fetching
- Improve error handling in a couple of edge cases
- Upgrade vega to 5.3.0

## 0.9.0

- Upgrade vega to 5.0.0, vega-lite to 3.0.0-rc14 and vega-embed to 4.0.0-rc1 ([gicentre/mume-with-litvis#11bc9651](https://github.com/gicentre/mume-with-litvis/commit/11bc96514feedadd7e125398f3fee3fc5ff3a630))

## 0.8.0

- Add ability to highlight lines of code ([gicentre/litvis#9](https://github.com/gicentre/litvis/issues/9), [shd101wyy/mume#100](https://github.com/shd101wyy/mume/pull/100), [mume-with-litvis#5074ca39](https://github.com/gicentre/mume-with-litvis/commit/5074ca39a24ff86ef8ddc63c35f33b212e2da984))

## 0.7.0

- Upgrade vega to 4.4.0, vega-lite to 3.0.0-rc10 and vega-embed to 3.26.1 ([gicentre/mume-with-litvis#429dcf63](https://github.com/gicentre/mume-with-litvis/commit/429dcf6370191cfc8b421923a6283d4f7bdc7625))

- Fix a few minor bugs ([gicentre/litvis#11](https://github.com/gicentre/litvis/issue/11),
  [gicentre/litvis#12](https://github.com/gicentre/litvis/issue/12),
  [gicentre/litvis#13](https://github.com/gicentre/litvis/issue/13),
  [gicentre/litvis#14](https://github.com/gicentre/litvis/issue/14),
  [gicentre/litvis#15](https://github.com/gicentre/litvis/issue/15),
  [gicentre/litvis#16](https://github.com/gicentre/litvis/issue/16),
  [gicentre/litvis#17](https://github.com/gicentre/litvis/issue/17))

## 0.6.0

- Implement markdown output from litvis blocks ([gicentre/litvis#10](https://github.com/gicentre/litvis/pull/10))

## 0.3.0

- Improve parsing of narrative schemas, support label aliases and fix rules.

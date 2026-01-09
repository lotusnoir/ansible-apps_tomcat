# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1](https://github.com/lotusnoir/ansible-apps_tomcat/compare/0.1.0...0.1.1) - 2026-01-09

### Commits

- add missing ssl packages [`7f999d1`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/7f999d1f1bac62de031dd9c8354a501f0c82afcb)
- remove unsuported distro [`40ffa5e`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/40ffa5ed4a515e0b2e29ba0a473566a24f374df2)

## 0.1.0 - 2026-01-08

### Merged

- feat: add tomcat 11 support [`#58`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/58)
- Update assert.yml [`#51`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/51)
- packet_size doesn't need quotes [`#44`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/44)
- Feature: Make AJP Connector optional [`#40`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/40)
- Increase default packet size set by application [`#38`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/38)
- Allow to chance shutdown pass [`#35`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/35)
- service_state and service_enabled are elements of item [`#34`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/34)
- Allow having the instance service in states other than started [`#33`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/33)
- fix for - Tomcat instance Service fails to start on CentOS 8 [`#31`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/31)
- Issue #25 - introduced config_files  [`#26`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/26)
- fix #17 xmx and xms has no effect unless java_opts is defined  [`#18`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/18)
- Fix: mirror only contains latest [`#15`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/15)
- Use get url. Thanks @brunoleon for you help! [`#12`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/12)
- update version tomcat_version85 to 8.5.35 [`#7`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/7)
- Simpler [`#6`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/6)
- Betterwars [`#3`](https://github.com/lotusnoir/ansible-apps_tomcat/pull/3)

### Fixed

- Merge pull request #18 from DBarthe/master [`#17`](https://github.com/lotusnoir/ansible-apps_tomcat/issues/17)
- fix #17 [`#17`](https://github.com/lotusnoir/ansible-apps_tomcat/issues/17)
- Switch mirror, should fix #11. [`#11`](https://github.com/lotusnoir/ansible-apps_tomcat/issues/11)
- Use a simpler way to start Tomcat. Fixes #8. [`#8`](https://github.com/lotusnoir/ansible-apps_tomcat/issues/8)
- Fixing deprecation warning. Fixes #2. [`#2`](https://github.com/lotusnoir/ansible-apps_tomcat/issues/2)

### Commits

- Initial commit [`3340ed2`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/3340ed276f182febaaee01ba83c2d99dbf6e27c6)
- Drop Ubuntu Focal support, its too old for Ansible (python 3.8) [`5c15500`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/5c155005586c0ff4deaa0c7d55cee84a244465e1)
- Pin Python to a version thats compatible with Ansible. [`6118163`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/6118163cb28d547996379723bbe85c1279c42c27)
- Sweeping commit. [`2dcb198`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/2dcb198509eceafe7b4c2ef2e6283736d36a3295)
- Regenerate docs/ci. [`1c70867`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/1c70867dbbf95d56b7833d67924e88eeb9d74787)
- Sweeping commit. [`893005a`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/893005aed16976db362154242d0dd80ea666c7d2)
- Start it up with the service role. [`56c699b`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/56c699b679caa52390cee44114d7eac7e29e73c9)
- USe tomcat 10, 11 gives issues for now. [`27356d1`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/27356d10282d8d320a510d04031f28241dccecfe)
- Correct path to catalina.run. [`01f234c`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/01f234c83a8528df2def08da7f6bd12541224c44)
- Reorganize variables. [`e412f59`](https://github.com/lotusnoir/ansible-apps_tomcat/commit/e412f5922cd992c37d182a0087738b6b64446b22)

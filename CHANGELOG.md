# Changelog

## [v1.27.0](https://github.com/k1LoW/tbls/compare/v1.26.0...v1.27.0) (2020-02-24)

* Add config.ER.distance [#171](https://github.com/k1LoW/tbls/pull/171) ([k1LoW](https://github.com/k1LoW))
* Fix: `tbls out -t config` does not set default values [#170](https://github.com/k1LoW/tbls/pull/170) ([k1LoW](https://github.com/k1LoW))
* Add output format (PNG, SVG, JPG) [#169](https://github.com/k1LoW/tbls/pull/169) ([k1LoW](https://github.com/k1LoW))
* Use github.com/goccy/go-graphviz instead of dot command [#167](https://github.com/k1LoW/tbls/pull/167) ([k1LoW](https://github.com/k1LoW))
* Bump up goccy/go-yaml version to v1.3.2 and remove workaround [#168](https://github.com/k1LoW/tbls/pull/168) ([k1LoW](https://github.com/k1LoW))
* Change default shell to /bin/sh [#166](https://github.com/k1LoW/tbls/pull/166) ([kkznch](https://github.com/kkznch))

## [v1.26.0](https://github.com/k1LoW/tbls/compare/v1.25.1...v1.26.0) (2020-02-20)

* [BREAKING] Normalize `relations:` of tbls output [#165](https://github.com/k1LoW/tbls/pull/165) ([k1LoW](https://github.com/k1LoW))
* Rename `schema.Relation.IsAdditional` -> `schema.Relation.Virtual` [#164](https://github.com/k1LoW/tbls/pull/164) ([k1LoW](https://github.com/k1LoW))
* Add YAML output format [#163](https://github.com/k1LoW/tbls/pull/163) ([k1LoW](https://github.com/k1LoW))

## [v1.25.1](https://github.com/k1LoW/tbls/compare/v1.25.0...v1.25.1) (2020-02-17)

* [MySQL]Fix constraints/indexes detection bug [#162](https://github.com/k1LoW/tbls/pull/162) ([k1LoW](https://github.com/k1LoW))
* Fix: Empty array is output as null [#161](https://github.com/k1LoW/tbls/pull/161) ([k1LoW](https://github.com/k1LoW))

## [v1.25.0](https://github.com/k1LoW/tbls/compare/v1.24.1...v1.25.0) (2020-02-06)

* lint `exclude:` `lintExclude:` support wildcard (`*`) [#160](https://github.com/k1LoW/tbls/pull/160) ([k1LoW](https://github.com/k1LoW))

## [v1.24.1](https://github.com/k1LoW/tbls/compare/v1.24.0...v1.24.1) (2020-01-16)

* [PostgreSQL]Fix parsing double-quoted table/column name in definition of Foreign Key [#154](https://github.com/k1LoW/tbls/pull/154) ([k1LoW](https://github.com/k1LoW))
* Update README.md [#151](https://github.com/k1LoW/tbls/pull/151) ([ednawig](https://github.com/ednawig))
* Dockerfile use latest version of tbls [#150](https://github.com/k1LoW/tbls/pull/150) ([k1LoW](https://github.com/k1LoW))

## [v1.24.0](https://github.com/k1LoW/tbls/compare/v1.23.0...v1.24.0) (2020-01-11)

* Add `tbls completion` [#149](https://github.com/k1LoW/tbls/pull/149) ([k1LoW](https://github.com/k1LoW))

## [v1.23.0](https://github.com/k1LoW/tbls/compare/v1.22.1...v1.23.0) (2019-12-11)

* Show table names when lint error `unrelated table exists` [#148](https://github.com/k1LoW/tbls/pull/148) ([k1LoW](https://github.com/k1LoW))

## [v1.22.1](https://github.com/k1LoW/tbls/compare/v1.22.0...v1.22.1) (2019-11-21)

* Fix: panic: assignment to entry in nil map [#147](https://github.com/k1LoW/tbls/pull/147) ([k1LoW](https://github.com/k1LoW))

## [v1.22.0](https://github.com/k1LoW/tbls/compare/v1.21.1...v1.22.0) (2019-11-20)

* Add .tbls.yml (tbls config file) output format [#146](https://github.com/k1LoW/tbls/pull/146) ([k1LoW](https://github.com/k1LoW))

## [v1.21.1](https://github.com/k1LoW/tbls/compare/v1.21.0...v1.21.1) (2019-11-11)

* Fix: requireForeignKeyIndex check only FOREIGN_KEY. [#145](https://github.com/k1LoW/tbls/pull/145) ([k1LoW](https://github.com/k1LoW))

## [v1.21.0](https://github.com/k1LoW/tbls/compare/v1.20.0...v1.21.0) (2019-11-11)

* Add `lintExclude` for exclude tables from lint. [#144](https://github.com/k1LoW/tbls/pull/144) ([k1LoW](https://github.com/k1LoW))

## [v1.20.0](https://github.com/k1LoW/tbls/compare/v1.19.0...v1.20.0) (2019-11-02)

* lint rule `requireColumnComment` excludes `table_name.column_name` as well as `column_name` [#143](https://github.com/k1LoW/tbls/pull/143) ([k1LoW](https://github.com/k1LoW))
* Add lint rule `requireForeignKeyIndex` [#142](https://github.com/k1LoW/tbls/pull/142) ([k1LoW](https://github.com/k1LoW))
* Use GitHub Actions [#141](https://github.com/k1LoW/tbls/pull/141) ([k1LoW](https://github.com/k1LoW))
* Remove `MATCH SIMPLE` from my.sql [#140](https://github.com/k1LoW/tbls/pull/140) ([k1LoW](https://github.com/k1LoW))

## [v1.19.0](https://github.com/k1LoW/tbls/compare/v1.18.2...v1.19.0) (2019-09-06)

* Add lint rule `duplicateRelations` [#139](https://github.com/k1LoW/tbls/pull/139) ([k1LoW](https://github.com/k1LoW))

## [v1.18.2](https://github.com/k1LoW/tbls/compare/v1.18.1...v1.18.2) (2019-09-06)

* Remove duplicate relation links [#138](https://github.com/k1LoW/tbls/pull/138) ([k1LoW](https://github.com/k1LoW))
* add error handling [#137](https://github.com/k1LoW/tbls/pull/137) ([toshi0607](https://github.com/toshi0607))
* add Dockerfile [#136](https://github.com/k1LoW/tbls/pull/136) ([peccu](https://github.com/peccu))
* Add gosec [#135](https://github.com/k1LoW/tbls/pull/135) ([k1LoW](https://github.com/k1LoW))

## [v1.18.1](https://github.com/k1LoW/tbls/compare/v1.18.0...v1.18.1) (2019-08-15)

* Fix duplicate output when multiple schemas have the same named table [#134](https://github.com/k1LoW/tbls/pull/134) ([oohira](https://github.com/oohira))
* Support `span://` for Cloud Spanner scheme [#133](https://github.com/k1LoW/tbls/pull/133) ([k1LoW](https://github.com/k1LoW))

## [v1.18.0](https://github.com/k1LoW/tbls/compare/v1.17.2...v1.18.0) (2019-08-13)

* Support Cloud Spanner [#132](https://github.com/k1LoW/tbls/pull/132) ([k1LoW](https://github.com/k1LoW))
* Fix .travis.yml condition [#131](https://github.com/k1LoW/tbls/pull/131) ([k1LoW](https://github.com/k1LoW))
* fix typo for readme [#130](https://github.com/k1LoW/tbls/pull/130) ([kojirock5260](https://github.com/kojirock5260))

## [v1.17.2](https://github.com/k1LoW/tbls/compare/v1.17.1...v1.17.2) (2019-07-15)

* Fix .goreleaser build hooks [#129](https://github.com/k1LoW/tbls/pull/129) ([k1LoW](https://github.com/k1LoW))

## [v1.17.1](https://github.com/k1LoW/tbls/compare/v1.17.0...v1.17.1) (2019-07-08)

* Fix panic when `hyphen-table` [#126](https://github.com/k1LoW/tbls/pull/126) ([k1LoW](https://github.com/k1LoW))
* Update gobuffalo/packr to v2 [#124](https://github.com/k1LoW/tbls/pull/124) ([k1LoW](https://github.com/k1LoW))

## [v1.17.0](https://github.com/k1LoW/tbls/compare/v1.16.1...v1.17.0) (2019-06-12)

* Refactor out/* packages [#123](https://github.com/k1LoW/tbls/pull/123) ([k1LoW](https://github.com/k1LoW))
* Add er.comment for add comment to ER diagram [#122](https://github.com/k1LoW/tbls/pull/122) ([k1LoW](https://github.com/k1LoW))

## [v1.16.1](https://github.com/k1LoW/tbls/compare/v1.16.0...v1.16.1) (2019-06-11)

* Fix loading ER diagram format from .tbls.yml [#120](https://github.com/k1LoW/tbls/pull/120) ([k1LoW](https://github.com/k1LoW))

## [v1.16.0](https://github.com/k1LoW/tbls/compare/v1.15.4...v1.16.0) (2019-06-04)

* Support for Microsoft SQL Server [#118](https://github.com/k1LoW/tbls/pull/118) ([k1LoW](https://github.com/k1LoW))

## [v1.15.4](https://github.com/k1LoW/tbls/compare/v1.15.3...v1.15.4) (2019-05-28)

* Postgres driver support new schema.Constraint schema.Index [#116](https://github.com/k1LoW/tbls/pull/116) ([k1LoW](https://github.com/k1LoW))

## [v1.15.3](https://github.com/k1LoW/tbls/compare/v1.15.2...v1.15.3) (2019-05-27)

* Redshift can not analyze indexes [#115](https://github.com/k1LoW/tbls/pull/115) ([k1LoW](https://github.com/k1LoW))
* Fixed a typo in "repository" [#112](https://github.com/k1LoW/tbls/pull/112) ([AntonNguyen](https://github.com/AntonNguyen))

## [v1.15.2](https://github.com/k1LoW/tbls/compare/v1.15.1...v1.15.2) (2019-05-27)

* Redshift can not analyze constraints [#114](https://github.com/k1LoW/tbls/pull/114) ([k1LoW](https://github.com/k1LoW))
* Revert Postgres driver parsing logic schema.Constaint/schema.Index [#113](https://github.com/k1LoW/tbls/pull/113) ([k1LoW](https://github.com/k1LoW))

## [v1.15.0](https://github.com/k1LoW/tbls/compare/v1.14.0...v1.15.0) (2019-05-26)

* Fix PlantUML output format [#109](https://github.com/k1LoW/tbls/pull/109) ([k1LoW](https://github.com/k1LoW))
* Fix schema.Index [#108](https://github.com/k1LoW/tbls/pull/108) ([k1LoW](https://github.com/k1LoW))
* Fix schema.Constraint [#107](https://github.com/k1LoW/tbls/pull/107) ([k1LoW](https://github.com/k1LoW))
* Add PlantUML output format [#106](https://github.com/k1LoW/tbls/pull/106) ([k1LoW](https://github.com/k1LoW))

## [v1.14.0](https://github.com/k1LoW/tbls/compare/v1.13.3...v1.14.0) (2019-05-15)

* Support Amazon Redshift [#105](https://github.com/k1LoW/tbls/pull/105) ([k1LoW](https://github.com/k1LoW))

## [v1.13.3](https://github.com/k1LoW/tbls/compare/v1.13.2...v1.13.3) (2019-05-13)

* Fix config.RequireColumns is not config.Rule [#104](https://github.com/k1LoW/tbls/pull/104) ([k1LoW](https://github.com/k1LoW))

## [v1.13.2](https://github.com/k1LoW/tbls/compare/v1.13.1...v1.13.2) (2019-05-12)

* Truncate xlsx worksheet name for MS Excel [#102](https://github.com/k1LoW/tbls/pull/102) ([k1LoW](https://github.com/k1LoW))

## [v1.13.1](https://github.com/k1LoW/tbls/compare/v1.13.0...v1.13.1) (2019-05-12)

* Fix BigQuery dataset schema name [#101](https://github.com/k1LoW/tbls/pull/101) ([k1LoW](https://github.com/k1LoW))

## [v1.13.0](https://github.com/k1LoW/tbls/compare/v1.12.0...v1.13.0) (2019-05-12)

* Fix dot file format [#100](https://github.com/k1LoW/tbls/pull/100) ([k1LoW](https://github.com/k1LoW))
* Fix command options [#99](https://github.com/k1LoW/tbls/pull/99) ([k1LoW](https://github.com/k1LoW))
* Support BigQuery [#98](https://github.com/k1LoW/tbls/pull/98) ([k1LoW](https://github.com/k1LoW))
* Refactor drivers [#97](https://github.com/k1LoW/tbls/pull/97) ([k1LoW](https://github.com/k1LoW))

## [v1.12.0](https://github.com/k1LoW/tbls/compare/v1.11.1...v1.12.0) (2019-05-11)

*  Add `exclude` for excluding tables from the document [#96](https://github.com/k1LoW/tbls/pull/96) ([k1LoW](https://github.com/k1LoW))
* Add lint rule `requireColumns` [#95](https://github.com/k1LoW/tbls/pull/95) ([k1LoW](https://github.com/k1LoW))

## [v1.11.1](https://github.com/k1LoW/tbls/compare/v1.11.0...v1.11.1) (2019-04-25)

* Fix loading args when `tbls out` [#91](https://github.com/k1LoW/tbls/pull/91) ([k1LoW](https://github.com/k1LoW))

## [v1.11.0](https://github.com/k1LoW/tbls/compare/v1.10.1...v1.11.0) (2019-04-25)

* Add `--out` option to set output file path. [#90](https://github.com/k1LoW/tbls/pull/90) ([k1LoW](https://github.com/k1LoW))
* Add `xlsx` output format [#89](https://github.com/k1LoW/tbls/pull/89) ([k1LoW](https://github.com/k1LoW))

## [v1.10.1](https://github.com/k1LoW/tbls/compare/v1.10.0...v1.10.1) (2019-03-16)

* Fix .goreleaser.yml for CGO_ENABLED=1 [#88](https://github.com/k1LoW/tbls/pull/88) ([k1LoW](https://github.com/k1LoW))

## [v1.10.0](https://github.com/k1LoW/tbls/compare/v1.9.0...v1.10.0) (2019-03-13)

* Update document [#83](https://github.com/k1LoW/tbls/pull/83) ([k1LoW](https://github.com/k1LoW))
* Update `tbls lint` detect message [#87](https://github.com/k1LoW/tbls/pull/87) ([k1LoW](https://github.com/k1LoW))
* Update `tbls lint` detect message [#87](https://github.com/k1LoW/tbls/pull/87) ([k1LoW](https://github.com/k1LoW))
* Add a temporary installation script for CI [#86](https://github.com/k1LoW/tbls/pull/86) ([k1LoW](https://github.com/k1LoW))
* Add a temporary installation script for CI [#86](https://github.com/k1LoW/tbls/pull/86) ([k1LoW](https://github.com/k1LoW))
* Change `tbls diff` output to unified format [#85](https://github.com/k1LoW/tbls/pull/85) ([k1LoW](https://github.com/k1LoW))
* Change `tbls diff` output to unified format [#85](https://github.com/k1LoW/tbls/pull/85) ([k1LoW](https://github.com/k1LoW))
* Fix config.Config internal [#84](https://github.com/k1LoW/tbls/pull/84) ([k1LoW](https://github.com/k1LoW))
* Fix config.Config internal [#84](https://github.com/k1LoW/tbls/pull/84) ([k1LoW](https://github.com/k1LoW))

## [v1.9.0](https://github.com/k1LoW/tbls/compare/v1.8.3...v1.9.0) (2019-03-09)

* Use goreleaser [#82](https://github.com/k1LoW/tbls/pull/82) ([k1LoW](https://github.com/k1LoW))
* mkdir when document directory does not exists [#81](https://github.com/k1LoW/tbls/pull/81) ([k1LoW](https://github.com/k1LoW))
* Set default doc path `dbdoc` [#80](https://github.com/k1LoW/tbls/pull/80) [e2ec6ed](https://github.com/k1LoW/tbls/commit/e2ec6ed39016fb80a80f7caeeaefb1821fd100a4) ([k1LoW](https://github.com/k1LoW))
* Add `md` to `tbls out` format [#79](https://github.com/k1LoW/tbls/pull/79) ([k1LoW](https://github.com/k1LoW))

## [v1.8.3](https://github.com/k1LoW/tbls/compare/v1.8.2...v1.8.3) (2019-02-25)

* Add requireColumnComment.excludedTables [#78](https://github.com/k1LoW/tbls/pull/78) ([k1LoW](https://github.com/k1LoW))

## [v1.8.2](https://github.com/k1LoW/tbls/compare/v1.8.1...v1.8.2) (2019-02-25)

* Fix lint rules [#77](https://github.com/k1LoW/tbls/pull/77) ([k1LoW](https://github.com/k1LoW))

## [v1.8.1](https://github.com/k1LoW/tbls/compare/v1.8.0...v1.8.1) (2019-02-25)

* Fix `dataPath` to `docPath` [#76](https://github.com/k1LoW/tbls/pull/76) ([k1LoW](https://github.com/k1LoW))

## [v1.8.0](https://github.com/k1LoW/tbls/compare/v1.7.1...v1.8.0) (2019-02-23)

* Add `tbls lint` [#75](https://github.com/k1LoW/tbls/pull/75) ([k1LoW](https://github.com/k1LoW))

## [v1.7.1](https://github.com/k1LoW/tbls/compare/v1.7.0...v1.7.1) (2018-12-08)

* Fix the bug that foreign key constraints are not listed in the document and ER diagram in the case of primary key and foreign key [#74](https://github.com/k1LoW/tbls/pull/74) ([k1LoW](https://github.com/k1LoW))

## [v1.7.0](https://github.com/k1LoW/tbls/compare/v1.6.0...v1.7.0) (2018-11-29)

* Support default config file `.tbls.yml` [#73](https://github.com/k1LoW/tbls/pull/73) ([k1LoW](https://github.com/k1LoW))

## [v1.6.0](https://github.com/k1LoW/tbls/compare/v1.5.1...v1.6.0) (2018-11-24)

* [DEPRACATED] `--add` option is deprecated. Use `--config` [#72](https://github.com/k1LoW/tbls/pull/72) ([k1LoW](https://github.com/k1LoW))
* Add `--config` option [#71](https://github.com/k1LoW/tbls/pull/71) ([k1LoW](https://github.com/k1LoW))
* Load Environment Values [#70](https://github.com/k1LoW/tbls/pull/70) ([k1LoW](https://github.com/k1LoW))
* Rename some code [#69](https://github.com/k1LoW/tbls/pull/69) ([k1LoW](https://github.com/k1LoW))
* Add tbls driver information to JSON [#68](https://github.com/k1LoW/tbls/pull/68) ([k1LoW](https://github.com/k1LoW))
* Support `json://`  [#67](https://github.com/k1LoW/tbls/pull/67) ([k1LoW](https://github.com/k1LoW))
* [BREAKING] Change `tbls dot` to `tbls out` / Support JSON format [#66](https://github.com/k1LoW/tbls/pull/66) ([k1LoW](https://github.com/k1LoW))

## [v1.5.1](https://github.com/k1LoW/tbls/compare/v1.5.0...v1.5.1) (2018-11-20)

* Fix error messages [#65](https://github.com/k1LoW/tbls/pull/65) ([k1LoW](https://github.com/k1LoW))

## [v1.5.0](https://github.com/k1LoW/tbls/compare/v1.4.1...v1.5.0) (2018-11-18)

* [BREAKING] Fix md output ( fix newline ) [#64](https://github.com/k1LoW/tbls/pull/64) ([k1LoW](https://github.com/k1LoW))
* [BREAKING] Add newline at end of file [#63](https://github.com/k1LoW/tbls/pull/63) ([k1LoW](https://github.com/k1LoW))
* [BREAKING] Change `tbls diff` exit code [#62](https://github.com/k1LoW/tbls/pull/62) ([k1LoW](https://github.com/k1LoW))
* mv test/ to testdata/ [#61](https://github.com/k1LoW/tbls/pull/61) ([k1LoW](https://github.com/k1LoW))
* Fix `tbls dot` ( use packr ) [#60](https://github.com/k1LoW/tbls/pull/60) ([k1LoW](https://github.com/k1LoW))
* Use Codecov [#59](https://github.com/k1LoW/tbls/pull/59) ([k1LoW](https://github.com/k1LoW))

## [v1.4.1](https://github.com/k1LoW/tbls/compare/v1.4.0...v1.4.1) (2018-11-14)

* Use gobuffalo/packr [#58](https://github.com/k1LoW/tbls/pull/58) ([k1LoW](https://github.com/k1LoW))
* Remove unused modules in go.mod [#57](https://github.com/k1LoW/tbls/pull/57) ([linyows](https://github.com/linyows))

## [v1.4.0](https://github.com/k1LoW/tbls/compare/v1.3.0...v1.4.0) (2018-11-13)

* Support Go 1.11.x [#56](https://github.com/k1LoW/tbls/pull/56) ([k1LoW](https://github.com/k1LoW))
* Fix PostgreSQL constraints sort rule. [#55](https://github.com/k1LoW/tbls/pull/55) ([k1LoW](https://github.com/k1LoW))

## [v1.3.0](https://github.com/k1LoW/tbls/compare/v1.2.1...v1.3.0) (2018-09-06)

* Add `--er-format` option [#54](https://github.com/k1LoW/tbls/pull/54) ([k1LoW](https://github.com/k1LoW))

## [v1.2.1](https://github.com/k1LoW/tbls/compare/v1.2.0...v1.2.1) (2018-08-09)

* Fix relation rendering of multi-columns foreign key [#53](https://github.com/k1LoW/tbls/pull/53) ([k1LoW](https://github.com/k1LoW))

## [v1.2.0](https://github.com/k1LoW/tbls/compare/v1.1.1...v1.2.0) (2018-08-08)

* Support SQLite FTS3/FTS4 Virtual Table [#52](https://github.com/k1LoW/tbls/pull/52) ([k1LoW](https://github.com/k1LoW))
* Fix SQLite relation support [#51](https://github.com/k1LoW/tbls/pull/51) ([k1LoW](https://github.com/k1LoW))

## [v1.1.1](https://github.com/k1LoW/tbls/compare/v1.1.0...v1.1.1) (2018-08-06)

* Support SQLite CHECK constraints [#50](https://github.com/k1LoW/tbls/pull/50) ([k1LoW](https://github.com/k1LoW))

## [v1.1.0](https://github.com/k1LoW/tbls/compare/v1.0.1...v1.1.0) (2018-08-05)

* Support SQLite [#49](https://github.com/k1LoW/tbls/pull/49) ([k1LoW](https://github.com/k1LoW))

## [v1.0.1](https://github.com/k1LoW/tbls/compare/v1.0.0...v1.0.1) (2018-07-28)

* Add Triggers to Schema.Sort() [#47](https://github.com/k1LoW/tbls/pull/47) ([k1LoW](https://github.com/k1LoW))

## [v1.0.0](https://github.com/k1LoW/tbls/compare/v0.10.2...v1.0.0) (2018-07-28)

* Don't show item when length 0 [#46](https://github.com/k1LoW/tbls/pull/46) ([k1LoW](https://github.com/k1LoW))
* Support analyze TRIGGER [#45](https://github.com/k1LoW/tbls/pull/45) ([k1LoW](https://github.com/k1LoW))
* Change option `--no-viz` to `--without-er` [#44](https://github.com/k1LoW/tbls/pull/44) ([k1LoW](https://github.com/k1LoW))

## [v0.10.2](https://github.com/k1LoW/tbls/compare/v0.10.1...v0.10.2) (2018-07-26)

* Fix MySQL constraints / indexes query [#42](https://github.com/k1LoW/tbls/pull/42) ([k1LoW](https://github.com/k1LoW))
* Add exec `dot` STDOUT to error message [#41](https://github.com/k1LoW/tbls/pull/41) ([k1LoW](https://github.com/k1LoW))
*  Add `UNKNOWN CONSTRAINT` ( This is constraint information that "tbls" still can not support ) [#40](https://github.com/k1LoW/tbls/pull/40) ([k1LoW](https://github.com/k1LoW))

## [v0.10.1](https://github.com/k1LoW/tbls/compare/v0.10.0...v0.10.1) (2018-07-22)

* Fix error handling [#39](https://github.com/k1LoW/tbls/pull/39) ([k1LoW](https://github.com/k1LoW))

## [v0.10.0](https://github.com/k1LoW/tbls/compare/v0.9.3...v0.10.0) (2018-07-22)

* Show errors with stack when `DEBUG=1` [#38](https://github.com/k1LoW/tbls/pull/38) ([k1LoW](https://github.com/k1LoW))
* Add `--adjust-table` option for adjust column width of table [#37](https://github.com/k1LoW/tbls/pull/37) ([k1LoW](https://github.com/k1LoW))

## [v0.9.3](https://github.com/k1LoW/tbls/compare/v0.9.2...v0.9.3) (2018-07-13)

* Support CR `\r` and CRLF `\r\n` [#35](https://github.com/k1LoW/tbls/pull/35) ([k1LoW](https://github.com/k1LoW))

## [v0.9.2](https://github.com/k1LoW/tbls/compare/v0.9.1...v0.9.2) (2018-07-09)

* Support multi-line comment [#34](https://github.com/k1LoW/tbls/pull/34) ([k1LoW](https://github.com/k1LoW))
* Fix `too many open files` [#33](https://github.com/k1LoW/tbls/pull/33) ([k1LoW](https://github.com/k1LoW))
* Add test for many tables [#31](https://github.com/k1LoW/tbls/pull/31) ([k1LoW](https://github.com/k1LoW))

## [v0.9.1](https://github.com/k1LoW/tbls/compare/v0.9.0...v0.9.1) (2018-06-30)

* Support PostgreSQL non-default schema [#30](https://github.com/k1LoW/tbls/pull/30) ([k1LoW](https://github.com/k1LoW))

## [v0.9.0](https://github.com/k1LoW/tbls/compare/v0.8.2...v0.9.0) (2018-06-29)

* Work with Amazon Redshift [#29](https://github.com/k1LoW/tbls/pull/29) ([watarukura](https://github.com/watarukura))

## [v0.8.2](https://github.com/k1LoW/tbls/compare/v0.8.1...v0.8.2) (2018-06-06)

* Fix output dot bug [#25](https://github.com/k1LoW/tbls/pull/25) ([k1LoW](https://github.com/k1LoW))

## [v0.8.1](https://github.com/k1LoW/tbls/compare/v0.8.0...v0.8.1) (2018-06-06)

* Fix table template [#24](https://github.com/k1LoW/tbls/pull/24) ([k1LoW](https://github.com/k1LoW))

## [v0.8.0](https://github.com/k1LoW/tbls/compare/v0.7.0...v0.8.0) (2018-06-05)

* Add schema.Table.Def for show table/view definition [#22](https://github.com/k1LoW/tbls/pull/22) ([k1LoW](https://github.com/k1LoW))
* call dot command with temporary file , graph name in dot file must be quoted [#23](https://github.com/k1LoW/tbls/pull/23) ([kenichiro-kimura](https://github.com/kenichiro-kimura))

## [v0.7.0](https://github.com/k1LoW/tbls/compare/v0.6.2...v0.7.0) (2018-06-02)

* `--add` option support additional comments [#21](https://github.com/k1LoW/tbls/pull/21) ([k1LoW](https://github.com/k1LoW))

## [v0.6.2](https://github.com/k1LoW/tbls/compare/v0.6.1...v0.6.2) (2018-05-31)

* Add `ORDER BY` to sort columns, constraints [#20](https://github.com/k1LoW/tbls/pull/20) ([k1LoW](https://github.com/k1LoW))

## [v0.6.1](https://github.com/k1LoW/tbls/compare/v0.6.0...v0.6.1) (2018-05-30)

* Escape tmpl value because dot file use <TABLE> [#19](https://github.com/k1LoW/tbls/pull/19) ([k1LoW](https://github.com/k1LoW))
* Change style of additional relation edges / can set relation def [#18](https://github.com/k1LoW/tbls/pull/18) ([k1LoW](https://github.com/k1LoW))

## [v0.6.0](https://github.com/k1LoW/tbls/compare/v0.5.1...v0.6.0) (2018-05-30)

* Use Graphviz `dot` to generate ER diagram .png [#17](https://github.com/k1LoW/tbls/pull/17) ([k1LoW](https://github.com/k1LoW))
* `tbls dot` generate dot to STDOUT [#15](https://github.com/k1LoW/tbls/pull/15) ([k1LoW](https://github.com/k1LoW))

## [v0.5.1](https://github.com/k1LoW/tbls/compare/v0.5.0...v0.5.1) (2018-05-29)

* Support Camelize table name like "CamelizeTable" [#16](https://github.com/k1LoW/tbls/pull/16) ([k1LoW](https://github.com/k1LoW))

## [v0.5.0](https://github.com/k1LoW/tbls/compare/v0.4.0...v0.5.0) (2018-05-28)

* Support CHECK constraints [#14](https://github.com/k1LoW/tbls/pull/14) ([k1LoW](https://github.com/k1LoW))
* Support view table [#13](https://github.com/k1LoW/tbls/pull/13) ([k1LoW](https://github.com/k1LoW))
* Add `tbls dot` command [#12](https://github.com/k1LoW/tbls/pull/12) ([k1LoW](https://github.com/k1LoW))

## [v0.4.0](https://github.com/k1LoW/tbls/compare/v0.3.0...v0.4.0) (2018-05-26)

* Add `--add` option for add extra data (relations) to schema [#11](https://github.com/k1LoW/tbls/pull/11) ([k1LoW](https://github.com/k1LoW))
* Support MySQL 8 [#10](https://github.com/k1LoW/tbls/pull/10) ([k1LoW](https://github.com/k1LoW))
* Add db.Ping() for test connection [#9](https://github.com/k1LoW/tbls/pull/9) ([k1LoW](https://github.com/k1LoW))

## [v0.3.0](https://github.com/k1LoW/tbls/compare/v0.2.2...v0.3.0) (2018-05-24)

* MySQL driver support [#8](https://github.com/k1LoW/tbls/pull/8) ([k1LoW](https://github.com/k1LoW))

## [v0.2.2](https://github.com/k1LoW/tbls/compare/v0.2.1...v0.2.2) (2018-05-24)

* Fix typo ;; [#7](https://github.com/k1LoW/tbls/pull/7) ([k1LoW](https://github.com/k1LoW))

## [v0.2.1](https://github.com/k1LoW/tbls/compare/v0.2.0...v0.2.1) (2018-05-22)

* Fix query for tables [#6](https://github.com/k1LoW/tbls/pull/6) ([k1LoW](https://github.com/k1LoW))

## [v0.2.0](https://github.com/k1LoW/tbls/compare/v0.1.2...v0.2.0) (2018-05-21)

* Add `--sort` option for CI easily [#5](https://github.com/k1LoW/tbls/pull/5) ([k1LoW](https://github.com/k1LoW))
* Add go-assets [#4](https://github.com/k1LoW/tbls/pull/4) ([k1LoW](https://github.com/k1LoW))

## [v0.1.2](https://github.com/k1LoW/tbls/compare/v0.1.1...v0.1.2) (2018-05-21)

* Fix defer *.Close() [#3](https://github.com/k1LoW/tbls/pull/3) ([k1LoW](https://github.com/k1LoW))
* Use path/filepath [#2](https://github.com/k1LoW/tbls/pull/2) ([k1LoW](https://github.com/k1LoW))

## [v0.1.1](https://github.com/k1LoW/tbls/compare/131f7e2eb87f...v0.1.1) (2018-05-21)

* Add driver interface [#1](https://github.com/k1LoW/tbls/pull/1) ([k1LoW](https://github.com/k1LoW))

## [v0.1.0](https://github.com/k1LoW/tbls/compare/131f7e2eb87f...v0.1.0) (2018-05-20)

# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

## [2.4.0] - 2022-05-19
### Changed
- Allow using Smarty v4

## [2.3.1] - 2022-05-02
### Fixed
- Fix PHP 8.0 support in composer.json

## [2.3.0] - 2022-01-11
### Changed
- Add support for PHP 8.1

## [2.2.0] - 2021-02-21
### Changed
- Add support for PHP 8.0

## [2.1.0] - 2020-12-07
### Changed
- Require `laminas/laminas-dependency-plugin:^2.0` to support Composer 2.

## [2.0.0] - 2020-03-11
### Changed
- Switch to Laminas.

## [1.0.2] - 2019-10-03
### Fixed
- Revert back to `method_exists()` instead of `is_callable()` to prevent calling non-existant methods.

## [1.0.1] - 2019-10-03
### Changed
- Remove dead code in `SmartyRenderer::setHelperPluginManager()`
- Use `is_callable()` before using `call_user_func_array`


## [1.0.0] - 2019-08-14
### Added
- Initial version.

[Unreleased]: https://github.com/gkralik/zf3-smarty-module/compare/2.4.0...HEAD
[2.4.0]: https://github.com/gkralik/zf3-smarty-module/compare/2.3.1...2.4.0
[2.3.1]: https://github.com/gkralik/zf3-smarty-module/compare/2.3.0...2.3.1
[2.3.0]: https://github.com/gkralik/zf3-smarty-module/compare/2.2.0...2.3.0
[2.2.0]: https://github.com/gkralik/zf3-smarty-module/compare/2.1.0...2.2.0
[2.1.0]: https://github.com/gkralik/zf3-smarty-module/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/gkralik/zf3-smarty-module/compare/1.0.2...2.0.0
[1.0.2]: https://github.com/gkralik/zf3-smarty-module/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/gkralik/zf3-smarty-module/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/gkralik/zf3-smarty-module/releases/tag/1.0.0

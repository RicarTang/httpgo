# Changelog

httpgo 版本更改日志文件。

## [0.30.0] - 2024-04-02

### Fixed
- 修复json数据校验，不符合json格式则会报错

### Changed
- typer更新至0.12.0

## [0.20.0] - 2024-01-10

### Added
- 新增请求过程中的进度效果；

## [0.10.0] - 2023-12-05

### Fixed
- 修复-h选项使用单引号添加请带有‘-’求头时获取错误的bug

## [0.4.0] - 2023-11-24

### Added
- 添加--proxies选项

### Changed
- 选项类型修改
- --help修改部分说明

## [0.3.0] - 2023-11-22

### Changed
- 修改requests会话调用为直接调用
- 修改最低python版本为3.8

## [0.2.0] - 2023-11-21

### Changed
- 修改version与name的获取方式
- 修改最低python版本为3.7

## [0.1.0] - 2023-11-21

### Added
- 类似curl的http工具


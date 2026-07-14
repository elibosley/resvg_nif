# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

---

## [0.6.0] – 2026-07-14
- Add reusable/warm font database support via the `:fontdb` option, so the fontdb::Database can be built once and reused across renders instead of being rebuilt every call.
- Add `svg_string_to_png_binary/2`, returning the PNG as an Elixir binary instead of a byte list.
- Upgrade to Resvg/usvg 0.47.
- Optimize the release profile of the native crate (lto, codegen-units, opt-level) for render-heavy workloads.

## [0.5.0] – 2024-13-10
- Update dependencies.
- Fix typespecs.

## [0.4.0] – 2024-13-10
- Upgrade to Resvg 0.44
- Update dependencies.

## [0.3.3] – 2024-07-04
- Update dependencies.

## [0.3.2] – 2024-06-21
- Update dependencies.

## [0.3.1] – 2024-04-20
- Fix `query_all/2` by loading the fonts to get the correct size.

## [0.3.0] – 2023-07-07
- Add new function `query_all/2`.

## [0.2.0] – 2023-06-22
- Change render types to atom

## [0.1.0] – 2023-06-21
Initial release

# Nuxt Extension Changelog

## [2.0.1] - 2025-09-29

🐛 Bug Fixes

- **Fixed**: Added missing `sanitizeComponentName` in `get-component-documentation` tool

🚀 Improvements

- **Optimized**: Streamlined AI tool sequence - prioritize `get-component-documentation` over `get-component-theme`
- **Enhanced**: `get-component-theme` now only called when explicitly requested for theme configuration
- **Updated**: AI evaluation tests to reflect optimized tool usage patterns

## [2.0.0] - Nuxt UI v4 Upgrade - 2025-09-24

Major Changes

- **Breaking**: Upgraded to Nuxt UI v4 with comprehensive component library updates
- **Enhanced**: Merged Nuxt UI Pro components into the main package for unified access
- **Improved**: Updated component documentation and examples to reflect v4 API changes

✨ New Features

- Unified component library with previously Pro-only components now available
- New `Get Nuxt Documentation` tool to search and browse Nuxt documentation

## [Nuxt Modules Features] - 2025-05-07

- Renamed from "Nuxt UI for Raycast" to "Nuxt for Raycast" to reflect broader scope
- Added new module-related features:
  - `Get Module by Name`: Fetch detailed information about a specific Nuxt module
  - `Get Modules by Category`: Browse modules filtered by category (UI, CMS, SEO, etc.)
  - `Get Module Categories`: List all available module categories
- Improved component-related features:
  - Optimized `Get Available Components` tool
  - Enhanced `Get Component Theme` tool
  - Maintained `Get Component Source Code` functionality

## [Initial Version] - 2025-03-02

- Added the initial version of Nuxt UI for Raycast with the following commands:
  - `Search Component Theme` instantly opens the component theme based on the selected component name (or input)
  - `@nuxt-ui` Get information, tips, create components, etc... all with natural language

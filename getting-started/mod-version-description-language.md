---
description: >-
  This document provides a detailed overview of the version tag language used
  for encoding version information. This language is designed to be concise,
  human-readable, and suitable for encoding in base
---

# Mod version description language

## Syntax & Properties

The version tag language uses a key-value pair structure to describe different aspects of a software release. Here’s a breakdown of the syntax and the properties you can use:

#### Game version <mark style="color:red;">(required)</mark>

* **Description**: Specifies the version of the game or software.
* **Syntax**: `GameVersion -> major.minor.patch` or `GameVersion -> major.minor.patch to major.minor.patch`
* **Example**:
  * Single version: `GameVersion -> 1.2.3`
  * Version range: `GameVersion -> 1.2.3 to 1.3.0`

#### PreRelease

* **Description**: Indicates whether the version is a pre-release or stable version.
* **Syntax**: `PreRelease -> true` or `PreRelease -> false`
* **Example**: `PreRelease -> true`

#### BuildNumber

* **Description**: Specifies the build number associated with the release.
* **Syntax**: `BuildNumber -> numeric_value` or `BuildNumber -> alphanumeric_value`
* **Example**: `BuildNumber -> 12345` or `BuildNumber -> build-xyz789`

#### ReleaseDate

* **Description**: Indicates the date when the version was released.
* **Syntax**: `ReleaseDate -> YYYY-MM-DD`
* **Example**: `ReleaseDate -> 2024-08-05`

#### Compatibility

* **Description**: Lists compatible platforms or systems for the release.
* **Syntax**: `Compatibility -> platform1, platform2, platform3`
* **Example**: `Compatibility -> Windows 11, macOS 13, Linux`

#### SupportEndDate

* **Description**: Indicates the end date for support for this version.
* **Syntax**: `SupportEndDate -> YYYY-MM-DD`
* **Example**: `SupportEndDate -> 2025-12-31`

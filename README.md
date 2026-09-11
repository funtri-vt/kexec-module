# kexec-module-PoC
This project is a WIP, AI-assisted(for now) attempt at getting kexec support for (primarily) chromeos kernels without it.

## Development Status
Unfortunately, active development is currently paused. Due to time constraints, I am unlikely to complete the planned major rewrite for the foreseeable future.
Contributions to the `dev` branch are welcome, especially toward the planned rewrite using manually written, non-AI-generated code. Any help would be greatly appreciated.

## Current Build Status
[![(dev) Build and Inject Kexec Shimboot Image (grunt)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/dev-build-and-inject-grunt.yml/badge.svg)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/dev-build-and-inject-grunt.yml)
[![(dev) Build and Inject Kexec Shimboot Image (octopus)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/dev-build-and-inject-octopus.yml/badge.svg)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/dev-build-and-inject-octopus.yml)
[![(prod) Build and Inject Kexec Shimboot Image (grunt)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/prod-build-and-inject-grunt.yml/badge.svg)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/prod-build-and-inject-grunt.yml)
[![(prod) Build and Inject Kexec Shimboot Image (octopus)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/prod-build-and-inject-octopus.yml/badge.svg)](https://github.com/funtri-vt/kexec-module-PoC/actions/workflows/prod-build-and-inject-octopus.yml)
## Current Targets
| Target Board Name | Current Status          |
|:------------------|:------------------------|
|`grunt`            |In progress(priority)    |
|`octopus`          |In progress(priority)    |

## Board Support Status
| Target Board Name | Speakers | WiFi | Headphone Jack | X11 | Touchscreen | 
|:------------------|:---------|:-----|:---------------|:----|:------------|
|`grunt`            | yes      | yes  | untested       | yes | untested    |

# Changelog

All notable changes to this project will be documented in this file.

## Release 0.8.6

**Features**

* Updated `spectre-meltdown-checker.sh` to v0.35

## Release 0.8.5

**Bugfixes**

* Fixed parameter type (was Boolean, is String now) in `windows_update.ps1`
* Now correctly crediting Michal Gajda for `Get-WUInstall`

## Release 0.8.4

**Features**

* Updated `spectre-meltdown-checker.sh` to v0.33+

**Bugfixes**

Documented class `meltdown`

## Release 0.8.3

**Bugfixes**

Updated CHANGELOG

## Release 0.8.2

**Features**

* Changed task parameters from `Boolean` to `Enum['true', 'false']`, so tasks are easier to use from the command line
* Updated `spectre-meltdown-checker.sh` to v0.32

**Bugfixes**

* Corrected version numbers in `metadata.json`
* Added proper task description to `linux_update.json`

## Release 0.8.1

**Features**

* Support for debian 8,both 32 and 64 bits.
* Support for EL6 (tested on Centos6).

**Bugfixes**

* Debian is now actually supported.

**Known Issues**

* Remediation for Linux is very naive right now, the task just updates the kernel package. This may or may not remediate anything on your specific version of the OS.

# Forged Fabric Loader

[![Build](https://github.com/PortingLab/ForgedFabricLoader/actions/workflows/build.yml/badge.svg)](https://github.com/PortingLab/ForgedFabricLoader/actions/workflows/build.yml)
[![License](https://img.shields.io/github/license/sinytra/ForgifiedFabricLoader?color=orange)](https://github.com/Sinytra/ForgifiedFabricLoader/blob/1.20.1/LICENSE)

A Forgified Fabric Loader 1.16.5, 1.18.2, 1.19.2 backport.

An implementation of Fabric Loader api on top of Forge Mod Loader, allowing Forge mods to access game information as
well as other mod containers. Useful for cross-platform mod development.

### Supported Features

- Accessing FML mod containers/metadata
- Mapping resolver
- Environmental and game information

### Unsupported Features

- Mod initializers
- Loading Fabric mods

## Installation

### Users

The Forged Fabric Loader is bundled with the
main [Papi](https://github.com/MCTeamPotato/Papi) jar. If you already have that installed, no
additional steps are required.

### Developers

In development environments, the Forged Fabric Loader is downloaded as a dependency of the Papi.
This is going to be the case for most developers. See
the [Papi](https://github.com/MCTeamPotato/Papi) repository for installation instructions.

If you wish to depend on the Forged Fabric Loader alone, it is published at `https://www.jitpack.io`
under the `com.github.PortingLab:ForgedFabricLoader` identifier. The versioning scheme follows
a `{forgedloader_version}+{fabricloader_version}+{mc_version}` pattern.

#### NESTED JARS NOTE

In case your mods bundles Fabric API modules rather than depending on the entire mod, keep in mind certain parts of the
API might depend on the Forged Fabric Loader, in which case you'll have to bundle it as well.
More information can be found on Papi's repository.

## License

Licensed under the Apache License 2.0.

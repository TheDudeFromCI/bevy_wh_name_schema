# <p align="center">Wraithaven Name Schema for Bevy</p>

<p align="center"><i>This schema provides a consistent naming convention used by plugins developed for Bevy, by the indie game studio, <strong>Wraithaven Games.</strong> The purpose of this schema is to ensure consitency and readability throughout a project's codebase when developing a plugin for Bevy to ensure ease of both maintaining the codebase as well as user by other projects that rely on APIs provided by the codebase. It is hoped that by establishing a single naming stardard to use will speed up both development of the plugin as well as quicker understanding for how that plugin should be used.</i></p>

This naming and organization schema is still in early development. As such, some tweaks and modifications might be made to further clarify the naming standard or to provide a more meaningful adjustment for the sake of maintainability or clarity of a codebase. This standard is also accepting contributions are recommendations for the future direction that this naming schema might take. Please feel free to open a new issue for discussion, clarifications, or to make suggestions for potential new rules or directions to take this standard.

> [!WARNING]
> This page is still under construction.

---

## Table of Contents:

- [Systems](#systems)
  - [File Layout](#file-layout)

---

## Systems

Systems within Bevy should be grouped together and be seperated from other functions and grouped together in a way that will allow for easy clarification on what systems are available and what they do.

### File Layout

Systems should be placed in a seperate file with the name `systems`. This file should contain only systems and no other functions or structs of any kind.

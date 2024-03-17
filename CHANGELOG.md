# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2023-03-17

### Added

- Modify post-Zelda's Lullaby Impa cutscene to include new camera shot and dialogue mentioning Zora's Domain as an objective
- Modify post-Zelda's Lullaby Navi dialogue to include Zora's Domain as an objective
- Update map sub-menu to flash the Zora's Domain marker after receiving Zelda’s Lullaby
- Move left 3 brown boulders in Child Link's Zora's River beneath level geometry
- Modify post-Master Sword retrieval Sheik cutscene to mention that none of the temples are accessible
- Replace eye switch in Fire Temple Room 6 with a non-toggling crystal switch
- Replace eye switch in Water Temple Room 0 with a toggling crystal switch
  - Change collision flags on the geometry in front of this switch from 0x8 to 0x4 so it can be hit with Hookshot
- Remove Water Temple completion from Nocturne of Shadow cutscene triggers, replace with Door of Time opened event check
- Move small chest in Shadow Temple Room 11 to upper center platform so it can be used as a Hookshot target
- Replace rusted floor switch in Spirit Temple Room 5 with a normal floor switch
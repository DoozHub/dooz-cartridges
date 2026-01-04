# Repo: dooz-cartridges

## Layer
Core

## Purpose
Plugin repository containing cartridge definitions for Dooz Pilot/Bridge. Cartridges are declarative wrappers that give CLI tools graphical interfaces through manifest-based configuration.

## Responsibilities
- Host cartridge manifests and metadata
- Define GUI inputs and command templates
- Maintain registry of available cartridges
- Document cartridge creation guidelines
- Categorize cartridges (free vs pro)

## Explicit Non-Responsibilities
- Must NOT execute commands directly
- Must NOT contain runtime code
- Must NOT implement business logic
- Must NOT store user data
- Must NOT communicate with external services

## Depends On
- None (standalone registry)

## Emits
- Cartridge manifests (JSON)
- Registry index (registry.json)

## Consumes
- None

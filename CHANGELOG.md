# Changelog

## 0.7.0

Adds nested conversation folders and a stacked workbench: native DSH conversation below, native dock tabs for files and other conversations above. Folders are host-persisted within native workspaces. Right-click a project or folder to create an independent chat in that exact workspace; organize, rename, archive and restore without changing cwd. Adds direct incremental reading of Codex control events (including existing HexaShell/OpenRSI output paths), with stable tool cards, actual arguments/results, source identity and camera alongside. Runner stdout remains in Diagnostics. API adapters can emit the documented structured JSONL protocol. This adds no new robot policy or benchmark claim. External control viewing does not imply steering support.

## 0.5.0

Adds durable workspace projects shared across conversations; reproduction, optimization and development objectives; editable work and dependencies; decisions and evidence; explicit user acceptance; revision history and concurrent-edit checks. Runs can link to an objective/work item, and joined conversations can read previous runs in the same workspace. The native project sidebar and agent tools use the same records.

Project state persists, but execution still ends with the DSH host. Background scheduling, budget enforcement, cross-device export and automatic acceptance are not implemented. The desktop installer uses content-addressed archives so reinstalling a development version cannot silently retain older files. This release does not change robot policies or publish new benchmark results.

## 0.4.0

First standalone community preview. Adds native workspace selection and discovery of project configurations, a JSON editor with revision checks, direct recipe launch, incremental logs, camera snapshots and durable run records. The default package includes a local project service and a synthetic integration example; a full LinkMind simulation checkout is optional.

Control/activity visualization is a separate experiment and is not included.

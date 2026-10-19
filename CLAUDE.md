# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

The README is the main documentation. It describes what the plugin does, the development commands, the workflows and the release:

@README.adoc

## Rules for Changes

- Keep the README current. When you change the plugin, a command or a workflow, update the README in the same commit.
- The Android libraries (`android-backend`, `android-utils`, `android-camera-service`, `android-energy-settings`) apply this plugin. A change of the publication changes their published artifacts.
- Follow the rules of the workflows in the README section "GitHub Workflows" for each change of `.github/workflows/`.

## Commit Style

`[TICKET-ID] Short imperative summary`.

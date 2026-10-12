# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a personal "TIL" (Today I Learned) notes repository — a collection of Markdown notes, not a software project. There is no build system, package manager, linter, or test suite, and none should be added unless explicitly requested.

## Structure

Notes are organized into top-level topic directories, with further subdirectories per subtopic/language:

- `language/<language-name>/` — notes on human languages (e.g. `language/english/sentence.md`, `language/chinese/`)
- `certification/` — notes related to certifications

When adding a new note, follow this existing convention: pick (or create) a topic directory, then a subtopic directory or file within it, using lowercase, hyphen-free directory names matching the existing style.

## Working in this repo

- Changes are almost always adding or editing a single Markdown file — keep edits scoped to the note being discussed.
- Don't invent tooling (build scripts, CI, linters) that doesn't exist here.

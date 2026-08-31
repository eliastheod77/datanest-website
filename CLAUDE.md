# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

Design concepts for the [Datanest](https://www.thedatanest.gr) website. The live site runs on Wix, so this repo holds **reference mockups only** — static, self-contained HTML files meant to be opened directly in a browser (or published as an artifact) to preview a design direction. Nothing here is deployed; changes agreed on here get rebuilt by hand inside the Wix Editor.

There is no build, lint, or test step — each `.html` file is fully self-contained (inline `<style>`, no external JS dependencies beyond Google Fonts).

## Current contents

- `hero-concept.html` — homepage hero redesign: a comic/pop-art styled sample dashboard (bars + starburst + speech bubble) plus a trust-strip band, in Datanest's navy/gold/blue palette. Two bracketed placeholders (`[X]+ Dashboards Delivered`, `[X] Industries Served`) need real numbers before anything here is copied into Wix.

## Conventions for new mockups

- Keep each concept a single self-contained `.html` file (light/dark theme aware, per the artifact-design conventions already used in `hero-concept.html`) rather than splitting into separate CSS/JS files — there's no build step to assemble them.
- Note any placeholder or sample data directly in the file (as `hero-concept.html` does) so it's obvious what still needs a real number or asset before it's usable in Wix.

# Ravinsky Catalog — Tablet Content Server

This repo hosts the live content for Ravinsky catalog tablets.
Content is synced automatically from Google Drive via `sync-to-github.sh`.

Tablets poll `version.txt` and download `catalog.zip` when changed.

**Do not edit files directly here** — edit in Drive and run the sync script.

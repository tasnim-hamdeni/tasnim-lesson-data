# Tasnim Hamdeni — public lesson data

This repository contains the public `catalog.json` and lesson documents for Tasnim Hamdeni's lesson library. It starts empty: there are no sample subjects or lessons.

Documents are stored as `documents/<subject-id>/<unique-uuid>.pdf` or `.pptx`. The website admin publishes the document and catalog together in one Git commit. Do not rename files manually without updating the catalog.

**All content is public. Never upload private student information.** Removing a lesson removes its current file and catalog entry; Git history, caches, and downloaded copies may retain it.

The teacher token must be fine-grained, scoped to this repository only, with Contents: Read and write (plus GitHub's automatic Metadata: Read-only). Never commit tokens. No token is required for students.

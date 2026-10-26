# Public lesson data

Website: https://tasnim-hamdeni.github.io/

Teacher: https://tasnim-hamdeni.github.io/tasnim/

`catalog.json` stores **subjects → chapters → documents**. The document array is named `lessons` for compatibility. New files use `documents/<subject-id>/<chapter-id>/<unique-id>.pdf` or `.pptx`. The teacher page commits each file and its catalog entry together. Do not rename documents manually.

Version 1 catalogs remain readable. Existing documents appear in a General chapter with unchanged file URLs; the next teacher edit writes version 2. Never replace a live catalog with an empty starter.

All content is public. Do not upload private student information. Removed documents may remain in Git history or downloaded copies.

Teacher access uses an expiring fine-grained token scoped only to this repository, with Contents: Read and write (Metadata read access is automatic). Enter it only on the teacher page. Never commit tokens. Students do not need a token.

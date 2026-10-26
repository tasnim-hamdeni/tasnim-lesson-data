# Public lesson data

Students: https://tasnim-hamdeni.github.io/

Teacher: https://tasnim-hamdeni.github.io/tasnim/

The catalog stores subjects → chapters → documents. New documents use documents/<subject-id>/<chapter-id>/<unique-id>.pdf or .pptx. Uploads update catalog and file in one Git commit. Original document paths remain supported; version 1 catalogs upgrade safely on the next edit. Never replace a live catalog with an empty starter.

Tasnim signs in using her access code. The separate authentication service holds the repository connection, so she does not need to create or paste a GitHub token. The site owner connects storage once on the service’s setup page and reconnects if its credential expires.

All content is public. Do not upload private student information. Removed documents may remain in Git history and downloaded copies. Never commit credentials.

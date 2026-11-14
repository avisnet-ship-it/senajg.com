# Instructions for Claude (and other coding assistants)

Claude Code reads this file automatically at the start of every session (the `CLAUDE.md` convention). The full rules live in one place, in the project's private repository, `avisnet-ship-it/privado`.

- **Before anything about versions, branches, tags or Releases, read `VERSIONING.md` in the private repository.** Who does what: the author creates the annotated tag, with Git, in a codespace of each repository, and the Release, on the GitHub page; Claude writes the commits, creates the `stable/X.Y.Z` branches through the GitHub tool (the API), prepares the texts and the commands, and checks everything by reading. Claude's environment refuses to push tags and branches with Git (HTTP 403).
- **How the project is built:** `ARCHITECTURE.md` in the private repository. The record of every change: `CHANGELOG.md` in the private repository.
- **The pages of this website are made by the programs in the private repository** (`tools/gen_site_en.py`, from the English pages that the pipeline makes; since rev.67, also `tools/gen_realidade_it.py`, the Italian page). A change to a page goes into the programs, and the reconstruction check must rebuild this website exactly.

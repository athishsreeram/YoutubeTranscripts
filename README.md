# YoutubeTranscripts

A curated collection of YouTube video transcripts, notes, and bite-sized summaries organized by creator or series.

Purpose
-------
- Provide a searchable, readable archive of notable YouTube transcripts.
- Make it fast to find, preview, and link to specific videos or collections.

Repository layout
----------------
- `diaryofaceo/` — diary-style transcripts and summaries.
- `SajjaadKhader/` — individual transcripts collected.
- `SiliconValleyGirl/` — transcripts SiliconValleyGirl.
- Other folders follow the same pattern: folder = creator/series, files = transcripts (.md).

File naming convention
----------------------
- Prefer short descriptive names. Examples you will find here:
	- `01_The Global Politics Expert The Real Global Danger.md`
	- `I Asked Microsoft’s CEO How To Get Hired (Satya Nadella).md`
- When adding new files keep names human-readable and include a leading index if ordering matters.

Quick navigation
----------------
- Open repository in VS Code and use Quick Open (Cmd+P) to jump to a file by name.
- Use ripgrep for fast content search:

	rg "search term" --hidden --glob '!node_modules'

- List recent transcript files:

	find . -maxdepth 2 -type f -name "*.md" | sort | tail -n 50

Example (direct file)
---------------------
- Example transcript: SajjaadKhader/I Asked Microsoft’s CEO How To Get Hired (Satya Nadella).md

Contributing
------------
- Add new transcripts to an existing folder matching the creator/series, or create a new folder for a new creator.
- Include a short summary at the top of the file (2–4 lines) and any relevant metadata.

Contact / Questions
-------------------
- Open an issue in this repository or add a quick note in a new file under `notes/` if you need help organizing content.

This README focuses on making files easier to find and use; tell me if you want automated indexes, tags, or a table of contents added.

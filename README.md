# HASHEM ENGINEERING — Multi-Book Engineering Library

A mobile-first, local-first Progressive Web App prototype.

## Run locally
- For best results serve this folder from an HTTPS host or localhost.
- Example: `python -m http.server 8000` then open `http://localhost:8000`.
- Service worker/PWA installation requires HTTPS (localhost is accepted for development).

## Install on phone
- Deploy the folder to an HTTPS static host.
- Android: open the deployed address in Chrome → menu → Install app / Add to Home screen.
- iPhone: open in Safari → Share → Add to Home Screen.

## Included
- 12 engineering categories; add custom categories.
- Independent books with PDF upload stored in IndexedDB.
- Independent chapter/topic hierarchy.
- Per-topic explanations, equations, notes, bookmarks.
- Learning progress records.
- Unified search across book metadata, chapters, topics and equations.
- Basic calculators and a first-order step-response simulation.
- Exam creation and simple answer checking.
- JSON backup/restore for metadata and learning data.

## Important current limitations
- PDF upload stores the original PDF and lets you open it, but automatic OCR/table-of-contents extraction and AI explanation are not implemented yet. Add chapters/topics manually from the book's actual contents.
- The exam editor uses a simple `question | exact answer` format, not a full MCQ authoring system.
- JSON backup excludes PDF binary files to keep backups manageable. Keep original PDFs separately.
- Data is local to the browser/device. Clearing browser site data can erase it. Export backups regularly.
- This is a functional first version, not yet a production-hardened release. Test backup/restore before storing important material.

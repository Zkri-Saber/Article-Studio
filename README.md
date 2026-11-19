# AI Manuscript & Style Forensics

A browser-based editorial auditing tool hosted on GitHub Pages that scans manuscripts (`.docx`, `.pdf`, `.md`, `.txt`, `.html`) for AI-favored buzzwords, formulaic transitions, filler phrases, and passive agency using the Gemini API.

## Features
- **100% Client-Side File Parsing:** Extracts text from `.docx` (Mammoth.js) and `.pdf` (PDF.js) locally without uploading your manuscript to third-party storage.
- **Automatic Chapter Chunking:** Splits long manuscripts into ~2,000-word sections to audit full books or reports cleanly.
- **Structured Rewrites & Exports:** Filters flagged phrases by category and exports editing checklists as `.md` or `.json`.
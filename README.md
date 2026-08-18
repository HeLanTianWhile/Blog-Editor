# Blog‑Editor
A lightweight bright‑minimalist blog editor for frontend‑only use.
Supports Markdown, HTML and WYSIWYG editing modes, import / export, and image embedding.

**English | [简体中文](./README_zh‑CN.md)**

## Introduction
Blog‑Editor is a zero‑dependency single‑file web editor for blog content creation.
Everything runs locally inside your browser, no server side required.

The same document can be edited under three interchangeable modes: Markdown source, HTML source, and WYSIWYG rich text.
Real‑time preview is placed on the right‑hand side. Toolbar provides common text formatting operations. Selected text will auto‑activate related style buttons in WYSIWYG mode.

## Features
- Three editing modes for one document: Markdown / HTML / WYSIWYG
- Split layout: edit area on left, live preview on right
- Format toolbar: bold, italic, strikethrough, heading, list, blockquote
- Style detection: auto‑toggle toolbar states for selected text
- Insert images via remote URL or local file upload
- Import local Markdown and HTML files
- Export content as Markdown or HTML files
- Auto content synchronization when switching modes
- Bright minimalist theme
- Pure frontend, no backend, no installation

## Usage
1. Open `index.html` in any modern web browser
2. Switch edit mode from top control bar
3. Use toolbar buttons to format text and insert images
4. Import existing files or export to save your work

## Notes
- Content lives in browser memory. Export manually to prevent data loss.
- Local images are converted to Base64 and embedded directly into document.
- Markdown‑HTML conversion is optimized for regular blog writing scenarios.

## License
[MIT](./LICENSE)
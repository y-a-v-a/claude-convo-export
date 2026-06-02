# Claude Conversation Export Viewer

A minimal, single-file HTML viewer for Claude AI conversation exports.

![Screenshot](Screen%20Shot%202026-06-02.png)

## Usage

Open `index.html` in a browser and upload a conversation JSON file. The viewer renders the conversation with:

- Human and assistant messages visually distinguished
- Collapsible thinking blocks
- Collapsible conversation summary
- Dark and light mode (defaults to OS preference)
- Print-friendly output with all thinking blocks expanded

## Printing / PDF

Use your browser's print function. The viewer automatically hides UI controls and expands all thinking blocks.

## Schema

`convo-schema.json` documents the expected structure of conversation export files.

# Stackroom — Undo / Redo, Made Visible

Stackroom is an interactive web app that shows how stacks power undo and redo. Edit the note and watch each saved version appear on the history stack.

## Use the app

Open [Stackroom](https://hashimamin510.github.io/stackroom/) in a modern browser. Type in the note, then use **Undo** or **Ctrl+Z** to reverse your last change. Use **Redo** or **Ctrl+Y** to restore it. Select **Reset** to clear the note.

## Why a stack?

A stack follows last-in, first-out (LIFO): the newest item is the first one removed. That makes stacks a natural fit for undo history. Other examples include function calls, browser back navigation, bracket matching, depth-first search, reversing a sequence, and nested dialogs.

## Run locally

Open `index.html` in any modern browser. No install or build step is required.

## GitHub Pages

This repository is configured to publish from the `main` branch and repository root. GitHub Pages serves the app directly from `index.html`.

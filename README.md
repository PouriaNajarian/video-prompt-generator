# Video Prompt Generator

A browser based prompt designer for planning AI generated videos and motion graphics.

## Features

- Build a story brief and generate separate prompts for Gemini, Google Flow, and a code based motion graphics renderer.
- Plan a written storyboard in Gemini, then create a still image storyboard and video clips in Google Flow.
- Keep narration, music, sound effects, captions, and visual layers separately described for the final edit.
- Generate distinct frame sizes for each selected publishing destination.
- Choose from translated options in English, French, Spanish, Chinese, Arabic, German, and Persian.
- Add, remove, and select custom dropdown options.

## Use

Open `index.html` in a modern browser. The app runs locally and stores its form choices in that browser. It does not call Gemini or Google Flow directly; it prepares prompts for those tools.

## Publishing

The GitHub Pages workflow deploys the root folder when changes are pushed to `main`. The site needs GitHub Pages to be configured to use GitHub Actions.

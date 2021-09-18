# resume

The source code for my resume.

## Installation

Fonts required for two-column version:

- Sans Serif
  - Liberation Sans
  - Helvetica Now Display
  - IBM Plex Sans
- Monospace
  - Cascadia Code

Fonts required for one-column version:

- Sans Serif
  - Helvetica Now Display
  - IBM Plex Sans
- Monospace
  - Cascadia Code

If you're forking your own version of this, you can change these to whichever fonts you want by modifying their respective variables in `(one-col|two-col)/style.scss`.

## Generating PDF

To generate a PDF version of the resume, run `yarn dev`, go to http://localhost:1234, and run your browser's print command (usually done by pressing Ctrl+P). Then, select "Save as PDF".

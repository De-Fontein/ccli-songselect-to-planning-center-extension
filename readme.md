# CCLI SongSelect to Planning Center integration

A browser extension to simplify the process of importing songs from CCLI SongSelect to Planning Center, including ChordPro, lead sheets, and vocal sheets.

*Note that this browser extension **requires** an active PlanningCenter and CCLI SongSelect subscription.*

## Usage

1. Install the browser extension
- For [Firefox](https://addons.mozilla.org/en-US/firefox/addon/songselect-to-planning-center/)
- For [Chrome](https://chromewebstore.google.com/detail/ccli-songselect-to-planni/flajcckkgnpmjcpobjekhdjlkalgkipf)
2. Navigate to a SongSelect song page
3. Click on the extension icon and select "Import current song"
4. Follow the steps provided to you by the browser extension.

## The problem

PlanningCenter does not import ChordPro files automatically. Adding editable songs is a 24-step process, which is too complicated for most people.

## The goal

This project aims to automate the 24-step process through a userscript.

## TODO:

Rewrite this extension:
- Remove the dependency on CCLI since PC can import ChordPro nowadays.
- Add autofixes in the lyrics & chords editor.
- Add highlighting for non-auto fixable issues in the lyrics & chords editor.


## Development guide

1. Run `npm install` to install the required dependencies.
2. Run `node .` to bundle everything together.
3. Find the (ZIP) files you need for Firefox or Chrome in `./dist/`

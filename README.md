# BrowserSearch for macOS

Website: https://giridharmb.github.io/BrowserSearch_Docs/

Find any open browser tab in a keystroke.

Press **⌥Space** (or your own shortcut), type a few letters of a tab's title or URL, use **↑ / ↓** to pick,
and press **↩**. BrowserSearch switches to that browser, raises the right window and selects the tab.

## Features

- Global hotkey that works from any app, configurable in Settings
- Tabs grouped by browser and window; fuzzy search as you type (`gh pull`, initials like `pr`)
- Recent tabs: a live most-recently-used list across browsers, with jump-back and reopen
- ⌘1–9 to jump, ⌘W to close a tab, ⌘C to copy its address, Esc to dismiss
- Searches Google Chrome, Safari and Firefox at the same time; only browsers that are already open are searched
- Lives in the menu bar, optional launch at login
- Nothing leaves your Mac: no network access; recent tabs are stored locally and can be cleared

## Requirements

macOS 14 Sonoma or later.

## Permissions

| Permission | Why | When |
|---|---|---|
| Automation → Google Chrome / Safari | Read tab titles and URLs, switch tabs | macOS asks the first time you search while that browser is open |
| Accessibility | Read and switch Firefox tabs (Firefox has no scripting support for tabs) | Only if you use Firefox: Settings → Browsers → Grant… |

You can review or revoke these in System Settings → Privacy & Security.

## Keyboard

| Key | Action |
|---|---|
| ⌥Space (default) | Open / close the search panel |
| ↑ / ↓ | Move the selection |
| ↩ | Switch to the selected tab |
| ⌘1–9 | Switch to result 1–9 |
| ⇥ | All tabs ⇄ Recent |
| ⌘W / ⌘C | Close tab / copy its address |
| Esc | Close |

## Known limitations

- Firefox tabs are matched by title only (no URL).
- Other Chromium browsers (Brave, Edge, Arc) are not supported yet.

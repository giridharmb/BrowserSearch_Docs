# BrowserSearch for macOS

Website: https://giridharmb.github.io/BrowserSearch_Docs/

Find any open browser tab in a keystroke.

Press **⌥Space** (or your own shortcut), type a few letters of a tab's title or URL, use **↑ / ↓** to pick,
and press **↩**. BrowserSearch switches to that browser, raises the right window and selects the tab.

## Features

- Tab archive: ⌘E closes tabs but keeps them, with page text, searchable from All Tabs; ↩ reopens. Optional auto-archive of stale tabs
- Saved sessions: ⌘S saves windows across browsers, ↩ in the Saved view restores them
- Global hotkey that works from any app, configurable in Settings
- Tabs grouped by browser and window; fuzzy search as you type (`gh pull`, initials like `pr`)
- Recent tabs: a live most-recently-used list across browsers, with jump-back and reopen
- Saved tab groups: ⌘T to tag tabs `#work`, `#tag` to filter, ⌘↩ reopens a whole group; automatic site groups
- Bulk actions: mark with ⇧↑↓ / ⌘-click / ⌘A, then close, tag, pin, move or copy as Markdown links
- Duplicate finder (⌘D), Stale view for tabs you haven't looked at in a week
- Pins (⌘P) and keywords (⌘K: type `jira` ↩ to jump), move to front window (⌘M), open in another browser (⌘O)
- Page text search (⌘F), previous-tab shortcut (⌃⌥⇥), Shortcuts/Siri actions
- Shortcut conflict warnings (macOS, other apps, launchers like Raycast/Alfred/ChatGPT)
- ⌘1–9 to jump, ⌘W to close a tab, ⌘C to copy its address, Esc to dismiss
- Searches Chrome, Safari, Brave, Edge, Vivaldi and Firefox at once; only browsers that are already open are searched
- Lives in the menu bar, optional launch at login
- Nothing leaves your Mac: no network access; recent tabs, the archive and sessions are stored locally and can be cleared

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
| ⇥ | All tabs · Recent · Tags · Stale |
| ⇧↑↓ / ⌘A | Mark tabs / mark all |
| ⌘T / ⌘K / ⌘P | Tag / keyword / pin |
| ⌘D / ⌘M / ⌘O | Close duplicates / move to front window / open in another browser |
| ⌘F / ⌘/ | Search page text / show every key |
| ⌃⌥⇥ | Previous tab, from anywhere |
| ⌘W / ⌘C | Close tab / copy its address |
| Esc | Close |

## Known limitations

- Firefox tabs are matched by title only (no URL).
- Other Chromium browsers (Brave, Edge, Arc) are not supported yet.

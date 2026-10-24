# BrowserSearch — App Store Connect listing

Bundle ID `com.giridharmb.BrowserSearch` · Platform macOS · Category Productivity · Price Free · SKU `browsersearch-mac`

## Name
BrowserSearch

## Subtitle (30)
Find any browser tab instantly

## Promotional text (170)
Press one shortcut, type a few letters, and jump to any open tab in Chrome, Safari, Brave, Edge or Vivaldi. Now with hashtags to group tabs your way.

## Description
Too many tabs, too many windows? BrowserSearch finds the one you want in a keystroke.

Press your shortcut from any app, type a few letters of a page's title or address, and press Return. BrowserSearch brings the right browser window forward with that tab selected.

• Every browser at once: Google Chrome, Safari, Brave, Microsoft Edge and Vivaldi, grouped by browser and window.
• Fuzzy search: matches titles and addresses, initials ("pr" finds Pull requests), and highlights what matched.
• Recent tabs: a live most-recently-used list across browsers. Jump back to the previous tab in two keys, or reopen one you closed.
• Hashtags: press ⌘T to tag a tab #work, then type #work to see just those. Tabs from the same site are grouped automatically.
• Keyboard first: ↑↓ and Return, ⌘1–9 to jump, ⌘W to close a tab, ⌘C to copy its address, Esc to dismiss.
• Smart shortcut setup: warns if your shortcut clashes with macOS, another app or a launcher.
• Lives in the menu bar, optional launch at login.
• Private: no network access, no analytics. Recent tabs and tags stay on your Mac and can be cleared anytime.

BrowserSearch only reads browsers that are already open; it never launches one.

## Keywords (100)
tabs,browser,tab switcher,search,chrome,safari,hotkey,launcher,productivity,menu bar,brave,edge

## Support URL
https://giridharmb.github.io/BrowserSearch_Docs/support.html

## Marketing URL
https://giridharmb.github.io/BrowserSearch_Docs/

## Privacy policy URL
https://giridharmb.github.io/BrowserSearch_Docs/privacy.html

## App Privacy (nutrition label)
Data Not Collected.

## Review notes
BrowserSearch is a tab switcher. It uses Apple Events to read the titles and URLs of open tabs in web browsers and to select the tab the user picks; that is the app's only function. Because these browsers don't publish scripting access groups, the app uses `com.apple.security.temporary-exception.apple-events` for exactly these bundle IDs: com.google.Chrome, com.apple.Safari, com.brave.Browser, com.microsoft.edgemac, com.vivaldi.Vivaldi. macOS asks the user for Automation permission per browser before any access; nothing is sent off the device.

To test: open Safari with a few tabs, launch BrowserSearch (menu bar icon), allow the Automation prompt, press ⌥Space (or choose Search Tabs from the menu bar icon), type part of a tab's title and press Return.

## Screenshots
Use images/panel-all.png, panel-search.png and panel-recent.png from this repo, padded onto 2880×1800 (or 1440×900) canvases.

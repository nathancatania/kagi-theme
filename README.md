# Kagi Darker (with personal tweaks)

When I switched to Kagi from Google/DuckDuckGo, the default theme was drastically different to what I was used to.

I really liked the [Kagi Darker theme by realrogue](https://github.com/realrogue/kagi-darker/), so I adapted it to more closely resemble the search results pages of Google and DuckDuckGo, making it more familiar to me.

All modifications are implemented as overrides at the end of the CSS file and clearly indicated with a comment. Any updates to the Kagi Darker theme can be easily transferred by copy/pasting.

## Sample
<img width="1321" height="1136" alt="example search" src="https://github.com/user-attachments/assets/1e54dfb8-b0fa-46ff-97f0-6f9c213dd854" />

## Appearance Settings
<img width="1409" height="882" alt="image" src="https://github.com/user-attachments/assets/54642203-b8f3-410b-ab9f-c8a946a737ba" />

## Changes Made
**Font:**
- Switched to Google Sans

**Link styling:**
- "Google blue" #8ab4f8 for search result links, lighter blue #aecbfa on hover.
- Underline links on hover
- Visited links are purple (Kagi Darker theme color)
    
**Misc:**
- Added slight margin between the Kagi tabs and the search result filters. On Firefox based browsers (e.g. Zen), the shadow from the App Header area (where the search bar is) was obscuring the top of the filters.
- Added slight margin between the search filters and the Quick Answer button as this was missing for me on Firefox.

# VenueBoard
A Dalamud plugin for Final Fantasy XIV venue hosts to manage, preview, and copy reusable venue macros with placeholders and presets.
# VenueBoard Installation

VenueBoard is a private/custom Dalamud plugin for Final Fantasy XIV venue hosts.  
It lets you manage venue macros, DJ shouts, greets, announcements, and quick-use macro buttons.

## Requirements

1. Install **FFXIVQuickLauncher**.
2. Enable **Dalamud** in XIVLauncher settings.
3. Run Final Fantasy XIV through **XIVLauncher**.

VenueBoard will not work if the game is launched through the normal Square Enix launcher.

---

## Installation

1. In game, type:

   `/xlsettings`

2. Open the **Experimental** tab.

3. Scroll down to **Custom Plugin Repositories**.

4. Read and accept the warning if needed.

5. Paste this URL into the Custom Plugin Repositories box:

   `https://raw.githubusercontent.com/penzfan23/VenueBoard/main/repo.json`

6. Click the **+** button to add the repo.

7. Click the **Save** button.

8. Close Dalamud Settings.

9. In game, type:

   `/xlplugins`

10. Search for:

   `VenueBoard`

11. Install and enable VenueBoard.

12. Open VenueBoard with either command:

   `/venueboard`

   or

   `/vb`

---

## Notes

- This is a private test build.
- Quick Use buttons send macros immediately.
- Use **Settings** to enable Compact Grid Mode.
- Use **Help** inside the plugin for placeholder examples.
- Report bugs with screenshots and what you were doing when the issue happened.

---

## Common Issues

### VenueBoard does not show up in `/xlplugins`

Make sure the custom repo URL was added correctly:

`https://raw.githubusercontent.com/penzfan23/VenueBoard/main/repo.json`

Then click **Save** in Dalamud Settings and reopen `/xlplugins`.

### The repo link does not work

The GitHub repo must be public for Dalamud to read the repo file and download the plugin.

### The plugin installs but will not load

Make sure the build matches the current Dalamud API level and that the zip contains:

- `VenueBoard.dll`
- `VenueBoard.json`
- `VenueBoard.deps.json`

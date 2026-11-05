# Time Block Planner (releases)

Newport-style time-block planning in Obsidian: Plan and Actual columns drawn from sections of your daily notes, with confirm-copy, details and color pairing. Week, month, quarter and year views and a Tasks panel can be turned on in settings.

This repo holds the release builds. The source is developed in a separate private repo, so issues here may not get a reply.

## Install with BRAT

1. In Obsidian, install and enable **BRAT** from Community plugins.
2. In BRAT's settings, choose **Add beta plugin**.
3. Enter `masonroyal/time-blocking-releases` and pick the latest version.
4. Enable **Time Block Planner** under Community plugins.

No GitHub token is needed. BRAT can keep the plugin up to date from here.

## First run

Open the plugin's settings and point it at your daily notes. The defaults are `Journal/YYYY/days/YYYY-MM-DD.md` for the path, and `## Plan` and `## Actual` for the two sections. Tasks and the longer views are off until you turn them on.

## Install by hand

Download `main.js`, `manifest.json` and `styles.css` from the latest release into `<your vault>/.obsidian/plugins/time-blocking/`, then enable the plugin.

This is beta software. Back up your vault before trying it.

# Lolo's Lumalou 🌙

Local Bluetooth control for the Fisher-Price **Lumalou** (Better Bedtime Routine System, product code `gld09`), after the official Smart Connect app was discontinued. Built with love for Lorenzo "Lolo" Bonifacio Rodriguez. 💛

Single self-contained `index.html` — no build, no install, no cloud, no account. Everything runs locally in the browser over Web Bluetooth.

## What it does
- **Bedtime routine** — build the step routine *and* **activate it** (enable + start + live step controls). This is the piece the official app never sends, so the live routine actually runs here.
- **Weekly schedule** (Nanna/Sveglia) — self-activating sleep/wake times + wake alarm.
- Light (10 colours, brightness, timers), audio (playlists + sound effects, volume, timers), nap timer + alarm, Ready-to-Rise, clock sync, live device-state readback.
- UI in **Italian, Spanish, English** (auto-detects browser language).

## How to use
Open in **Chrome or Edge** (desktop or Android), or **Bluefy** on iPhone/iPad. Turn on Bluetooth, keep the cloud nearby, press **Connect**, and pick the device — it shows up with a **numeric name** (e.g. `1102184718`), not "Lumalou".

## Credits & safety
Protocol based on the open-source reverse-engineering by [stramanu/lumalou](https://github.com/stramanu/lumalou) (MIT). Not affiliated with Mattel / Fisher-Price. The app never touches the firmware-update (DFU) service. Use at your own risk.

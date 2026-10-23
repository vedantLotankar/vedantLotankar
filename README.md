<a href="https://github.com/vedantLotankar?tab=repositories">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/00-signal-dark.gif">
<img src="assets/00-signal-light.gif" alt="Vedant Lotankar. Apps, automation and machine-learning experiments. An animated signal mesh on a neon grid." width="1000">
</picture>
</a>

I build apps and automation, then work through what breaks. The shared projects below were pair-built with [Rishi Sangare](https://github.com/rishi-sangare), from design through debugging.

### 01 / ProTanki Commander
Eight mock clients, one controller. The interesting part is checking that each click actually worked.

<a href="https://github.com/rishi-sangare/multi-account-game-automation">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/02-commander-dark.gif">
<img src="assets/02-commander-light.gif" alt="ProTanki Commander, pair-built with Rishi. Eight mock windows feed a capture, detect, click and verify loop, with retry and fallback input. The demo uses mock clients." width="1000">
</picture>
</a>

### 02 / Call Lab for Bolna
Same dropped call. Different causes. Trace the failed stage instead of guessing.

<a href="https://github.com/rishi-sangare/bolna-call-lab">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/03-call-lab-dark.gif">
<img src="assets/03-call-lab-light.gif" alt="Call Lab for Bolna, pair-built with Rishi. A Twilio-protocol caller feeds Bolna and a log analyzer. Five scenarios distinguish silence, TTS, STT, missing media and corrected configuration." width="1000">
</picture>
</a>

<details>
<summary>Quick diagnosis: a transcript exists, but the agent voice never plays. What next?</summary>

Check the TTS voice configuration and playback logs. Increasing the silence timeout can hide the broken stage. [Inspect the scenarios](https://github.com/rishi-sangare/bolna-call-lab#what-it-does).

</details>

### 03 / ChefMate · solo build
A cooking-assistant MVP connecting recipe context to AI chat.

<a href="https://github.com/vedantLotankar/ChefMate">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/04-chefmate-dark.gif">
<img src="assets/04-chefmate-light.gif" alt="ChefMate, a solo React Native and Express cooking assistant MVP. Schematic screens show recipe browsing and contextual chat. Some features are unfinished." width="1000">
</picture>
</a>

### 04 / Wholesale Voice Desk
Lead intake, consent checks, call routing and CRM handoff as one workflow.

<a href="https://github.com/rishi-sangare/wholesale-voice-desk">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/05-voice-desk-dark.gif">
<img src="assets/05-voice-desk-light.gif" alt="Wholesale Voice Desk, pair-built with Rishi. Lead intake branches on duplicates, do-not-call, consent and calling hours, then routes call results into CRM and booking." width="1000">
</picture>
</a>

### 05 / Elsewhere
Route playback with a session supervisor. Simulator path documented; real-device testing remains open.

<a href="https://github.com/rishi-sangare/elsewhere">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/06-elsewhere-dark.gif">
<img src="assets/06-elsewhere-light.gif" alt="Elsewhere, pair-built with Rishi. Route playback, a Swift session supervisor, simulator and device backends. The Simulator path is documented working; the real-device path needs testing." width="1000">
</picture>
</a>

**Also built:** [Telegram Content Bot](https://github.com/rishi-sangare/telegram-content-bot-demo) with Rishi · [ML experiments](https://github.com/vedantLotankar/Supervised-Learning) · [Reinforcement learning](https://github.com/vedantLotankar/Reinforcement-Learning).

[Talk about a build →](https://github.com/vedantLotankar/vedantLotankar/issues/new?title=Let%27s%20build%20something)

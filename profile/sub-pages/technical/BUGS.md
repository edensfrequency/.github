<div align="center">

![edensfrequency-banner-with-text.png](../../assets/images/branding/edensfrequency-banner-with-text.png)

---

[![Website](https://img.shields.io/badge/Website-edensfrequency.online-C9A66B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.edensfrequency.online)
[![GitHub](https://img.shields.io/badge/GitHub-EdensFrequency-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edensfrequency)
[![Products](https://img.shields.io/badge/Public%20Products-3-8B5CF6?style=for-the-badge)](https://github.com/edensfrequency)

</div>

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[🥈 Decks](../products/decks/boom-bap-producer-decks.md)** &nbsp;·&nbsp; **[🥉 Keys](../products/key-sampler/boom-bap-producer-key-sampler.md)** &nbsp;·&nbsp; **[🔧 Technical](README.md)** &nbsp;·&nbsp; **[❓ FAQs](../faqs/README.md)**

</div>

---

# Bugs

> We shipped 3 public products and got real feedback from early testers. Every bug that's come up so far has been found and fixed.

## Fixed Since Last Update (2026-08-12 - 2026-09-02)

All of the below is from Pads (v1.32.0 through v1.109.0) - Decks (still v0.4.0) and Keys (still v0.2.0) had no releases in this window, so nothing to report there. Full detail for any of these lives in each version's entry on the [release page](RELEASES.md).

- Presets could forget the first row of pads when reloaded - fixed
- Live-Record didn't respond when the plugin was loaded in a DAW unless you also pressed the DAW's own transport play button - it now works as soon as you arm it and start hitting pads
- Presets could break if you later deleted their original sample files - saving a preset now copies every sample it uses into its own data folder alongside it
- Trim Silence now shows up under Undo - previously it couldn't be undone at all
- Growing the plugin window taller now actually gives the pad grid, sample editor, and DSP panel more room, instead of just adding empty space at the bottom
- A rebuild wasn't always picked up by the installed plugin - fixed at the build-system level
- The DISCOVER tab's YouTube embed wasn't loading on some systems and showed a confusing script error - it now plays properly, with a graceful fallback message on systems where it still can't load
- The plugin window was too large by default and didn't fit properly in some DAWs - it now opens at half its previous size and resizes freely in either direction
- Check for Updates was silently checking the wrong location and never finding anything - fixed
- The 5 new Insert FX types could revert to the wrong effect after saving/reloading a project - fixed
- Some toolbar controls (BPM, Metronome) were rendering too small to use at certain window sizes - fixed
- The Saturation (Console) effect had gone missing from the per-pad Insert FX menu - restored
- Resizing the plugin by dragging one edge could distort its proportions - it now always keeps its shape
- The keyboard strip at the bottom could leave an empty gap on the right at some window sizes - fixed
- A brief window-proportions regression was reverted - the toolbar is back to 2 compact rows instead of 1 very wide one
- The BASS tab was leaving a lot of empty space below its controls - it now fills the space it's actually given
- Turntable Vinyl Sim settings (Wow/Flutter, Vinyl Noise, Saturation, Motor Ramp) were silently resetting to off on reload instead of saving with the project - fixed
- Humanize was ignoring a pad's Favorite protection and couldn't be undone, unlike every other pattern-changing button - fixed
- Several TURNTABLE tab layout bugs, worst in 2-Decks mode (clipped control rail, truncated buttons, a squashed platter/rail split) - the tab now stays usable and fully visible at any window size
- A window-resize sizing bug could let the toolbar's tab buttons overlap or spill off-screen at small window sizes - fixed
- Bank-to-bank copy wasn't refreshing the pad grid when pasting into the bank you were currently viewing - fixed

Pads gets the most frequent updates since it's our flagship - check the [release page](RELEASES.md) around 18:00 CAT most days for the latest build. See **[🧪 Development Status](DEVELOPMENT-STATUS.md)** for what's currently being worked on.

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[🥈 Decks](../products/decks/boom-bap-producer-decks.md)** &nbsp;·&nbsp; **[🥉 Keys](../products/key-sampler/boom-bap-producer-key-sampler.md)** &nbsp;·&nbsp; **[🔧 Technical](README.md)** &nbsp;·&nbsp; **[❓ FAQs](../faqs/README.md)**

</div>

---

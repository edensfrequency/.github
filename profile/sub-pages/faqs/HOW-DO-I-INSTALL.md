<div align="center">

![edensfrequency-banner-with-text.png](../../assets/images/branding/edensfrequency-banner-with-text.png)

---

[![Website](https://img.shields.io/badge/Website-edensfrequency.online-C9A66B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.edensfrequency.online)
[![GitHub](https://img.shields.io/badge/GitHub-EdensFrequency-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edensfrequency)
[![Products](https://img.shields.io/badge/Public%20Products-1-8B5CF6?style=for-the-badge)](https://github.com/edensfrequency)

</div>

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[📣 One Product](../ONE-PRODUCT.md)** &nbsp;·&nbsp; **[🔧 Technical](../technical/README.md)** &nbsp;·&nbsp; **[❓ FAQs](README.md)**

</div>

---

## 📥 How Do I Install a Plugin?

These steps are for [Boom Bap Producer Pads](../products/pads/boom-bap-producer-pads.md), our one product now (Decks and Key Sampler are part of it).

### Recommended for Pads: the installer

Pads now ships a Windows installer - download `BoomBapProducerPadsSetup-X.Y.Z.exe` from its [Releases page](https://github.com/edensfrequency/boom-bap-producer-pads/releases) and run it. It installs both the VST3 and the standalone app for you, no manual copying needed, and it never touches your presets or settings, even when reinstalling over an existing version. Decks and Key Sampler don't have an installer yet - use the manual steps below for those.

### As a VST3 or CLAP plugin (inside a DAW), manually

1. Go to the product's GitHub page and open its **Releases** tab.
2. Download the `.vst3.zip` file from the latest release and unzip it (Pads also offers a `.clap.zip` if your host supports CLAP instead of VST3).
3. Copy the whole `.vst3` (or `.clap`) folder/file into your system's plugin folder: `C:\Program Files\Common Files\VST3\` for VST3, `C:\Program Files\Common Files\CLAP\` for CLAP.
4. Rescan plugins in your DAW (Options/Preferences → Plug-Ins → rescan). The name shows up under Generators or Instruments.

If a previous version was already loaded in an open project, close and reopen the DAW, or remove and re-add the plugin, so it doesn't keep the old binary in memory.

### As a standalone app (no DAW needed)

Download the `-Standalone.zip` from the same Releases page and run the `.exe` directly. No install step, no host to configure. Pick your audio output device on first launch.

### Requirements

Windows only for now, macOS support is planned for later. Confirmed working in Reason, FL Studio, and Ableton Live. See **[supported DAWs](SUPPORTED-DAWS.md)** for the full picture.

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[📣 One Product](../ONE-PRODUCT.md)** &nbsp;·&nbsp; **[🔧 Technical](../technical/README.md)** &nbsp;·&nbsp; **[❓ FAQs](README.md)**

</div>

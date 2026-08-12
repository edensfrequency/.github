<div align="center">

# EDENSFREQUENCY

### Independent Music Technology · Audio Software · Creative Tools

**Building tools for producers, beatmakers, DJs, samplers and musicians.**

<br>

[![Website](https://img.shields.io/badge/Website-edensfrequency.online-C9A66B?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.edensfrequency.online)
[![GitHub](https://img.shields.io/badge/GitHub-EdensFrequency-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edensfrequency)
[![Products](https://img.shields.io/badge/Public%20Products-3-8B5CF6?style=for-the-badge)](https://github.com/edensfrequency)

<br>

> **Make music. Flip samples. Scratch. Experiment. Build.**

</div>

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[🥈 Decks](../products/decks/boom-bap-producer-decks.md)** &nbsp;·&nbsp; **[🥉 Keys](../products/key-sampler/boom-bap-producer-key-sampler.md)** &nbsp;·&nbsp; **[🔧 Technical](README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[❓ FAQs](../faqs/README.md)**

</div>

---

## 🔍 Behind the Scenes

A question we get: why do the repos here look thin compared to what the products actually do? Here's how it actually works.

### Two repos per product

Every product is built in a private repository first. That's where the real work happens: source code, build configuration, internal planning and design notes, work in progress that isn't ready for anyone else to see yet.

What you see here on `edensfrequency` is a separate, public repository per product. It doesn't mirror the private one. It's a deliberately smaller surface: end-user docs (install steps, usage guide, changelog, license), a couple of screenshots, and the actual built binaries you download.

### What crosses over, and when

Nothing gets pushed to the public side casually. Each time we cut a release:

1. The plugin gets built and run through validation.
2. End-user documentation is synced across from the private repo, rewritten where needed so it doesn't reference anything private-only.
3. The built VST3 and standalone binaries get packaged and staged alongside that documentation.
4. Everything gets committed, tagged with a version number, and pushed.
5. A GitHub Release is cut on the public repo with the binaries attached, so anyone can grab the latest build without touching source at all.

The private repo gets tagged too, at the same version, so the two stay in step even though only one of them is visible to you.

### Why split it this way

Two reasons. First, the source, the internal architecture decisions, the half-finished experiments, none of that needs to be public for the product to be genuinely open about its progress. You still get real changelogs, real bug tracking, and real releases, not just marketing copy.

Second, it keeps the public repos honest. What's in the public `dist/` folder or Releases page is exactly what got built and tested, not a hand-picked snapshot. If a release is broken, it's broken in public, and that's tracked on **[Bugs](BUGS.md)** and **[Development Status](DEVELOPMENT-STATUS.md)** the same as everything else.

### Where to actually look

- **[Releases](RELEASES.md)** - when new builds land and how versioning works
- **[Bugs](BUGS.md)** - what's currently broken
- **[Development Status](DEVELOPMENT-STATUS.md)** - what's being worked on right now
- **[Technology](TECHNOLOGY.md)** - the stack all of this is built on

---

<div align="center">

**[🏠 Home](../../README.md)** &nbsp;·&nbsp; **[🚀 Products](../products/README.md)** &nbsp;·&nbsp; **[🥇 Pads](../products/pads/boom-bap-producer-pads.md)** &nbsp;·&nbsp; **[🥈 Decks](../products/decks/boom-bap-producer-decks.md)** &nbsp;·&nbsp; **[🥉 Keys](../products/key-sampler/boom-bap-producer-key-sampler.md)** &nbsp;·&nbsp; **[🔧 Technical](README.md)** &nbsp;·&nbsp; **[🎯 About](../ABOUT.md)** &nbsp;·&nbsp; **[❓ FAQs](../faqs/README.md)**

</div>

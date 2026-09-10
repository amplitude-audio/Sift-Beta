<div align="center">

<img src="assets/sift-icon.png" width="128" alt="Sift">

# Sift

**Renames and organises audio files for delivery.**
Set the rules. See exactly what you'll get. Then commit.

[![Latest release](https://img.shields.io/github/v/release/amplitude-audio/Sift-Beta?color=3D73B6&labelColor=1B1B19&label=latest)](../../releases/latest)
[![macOS 12+](https://img.shields.io/badge/macOS-12%2B-3D73B6?labelColor=1B1B19)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/amplitude-audio/Sift-Beta/total?color=3D73B6&labelColor=1B1B19&label=downloads)](../../releases)

### [⬇︎ Download the latest beta](../../releases/latest)

</div>

---

Build your rules on the left, see the exact folder tree you'll end up with on the right, then press the button. Nothing changes on disk until you do.

### What it does

- Groups loose stems into folders by channel suffix — `mix.L.wav` + `mix.R.wav` → `mix/`
- Stacks further layers on top, grouping by keyword or by how alike names are
- Renames with find/replace, prefix/suffix and insertion rules, keeping channel markers and extensions intact
- Runs rename and grouping in either order, so folders take their names from the old names or the new ones
- Moves or copies, in place or into a destination folder
- Shows the exact tree you'll get, and refuses to run if the preview has gone stale
- Undoes any run, including files a conversion created
- Combines mono stems into a poly WAV, splits a poly into multi-mono, or wraps audio into a MOV
- Measures loudness three ways — gated (1770-4), ungated (1770-1), dialogue-gated for Netflix — plus true peak
- Plays any file, or a whole stem folder mixed together

### Install

Download **Sift.dmg**, unzip nothing, drag Sift to your Applications folder. Builds are signed and notarised by Apple, so they open normally.

macOS 12 (Monterey) or later, Apple Silicon or Intel.

Sift checks this page once when it launches and tells you when a newer beta is out. It never downloads or installs anything on its own.

### Found a problem?

[Open an issue.](../../issues) The most useful reports say what the preview showed and what landed on disk instead, plus your Sift version (**Sift ▸ About Sift**) and your macOS version.

If Sift did something to your files you did not expect, lead with that.

---

<div align="center">
<sub>Release artifacts and issues only — the source lives elsewhere.</sub><br>
<sub>© Amplitude Audio LLC</sub>
</div>

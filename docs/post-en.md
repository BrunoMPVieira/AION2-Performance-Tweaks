![AION 2 Performance Tweaks · developed by Kharnoxy](../assets/banner.svg)

<div align="center">

# Your PC. Your preset. Your way to play.

**AION 2 — Performance Tweaks 2.3.0** · Windows 10/11 x64 · English / Português

[⬇ Download for Windows](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/AION2-Tweak-Desempenho-v2.3.0.zip) · [View version 2.3.0](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/tag/v2.3.0) · [Explore the project](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks)

</div>

## Why I created this project

Not everyone has a recent graphics card. I created this application to help people playing AION 2 on more modest computers experiment with graphics settings, reduce demanding effects, and find a balance between appearance and performance.

The idea is simple: put the tweaks in an accessible interface, explain what each choice does, and keep a way back. You decide how much detail to preserve and which effects you are comfortable reducing.

![Steam or PURPLE configuration screen](../assets/setup-screen.png)

## What you can do

- **13 ready-made presets**, including Quality, Balanced, Low-end PC, Light ultrawide · FSR, and experimental Clay graphics.
- **25 individual controls** to experiment with shadows, blur, textures, foliage, reflections, view distance, and effects.
- **My PC assistant**: detect or enter RAM, processor, and graphics card details to build an editable suggestion.
- **Personal presets** and an interface in English or Portuguese.
- **Original Preset**: save this computer's starting configuration and use **Restore original** whenever you need it.

![Hardware assistant](../assets/hardware-assistant.png)

![Individual graphics controls](../assets/tweaks.png)

The assistant uses local hardware rules. It prepares a starting point for you to review, without applying changes by itself or promising a particular frame rate.

## Getting started

1. [Download the version 2.3.0 ZIP](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/AION2-Tweak-Desempenho-v2.3.0.zip) and extract it.
2. Launch **AION 2 Tweak de Desempenho.exe**. Python is not required.
3. Start AION 2 through your usual launcher, **Steam or PURPLE**, enter once, then close the game normally.
4. Select the detected `Engine.ini`. If several appear, check which configuration your game uses.
5. Choose a preset or use **My PC**, customize it, then select **Review and apply** with the game closed.
6. Start the game and compare the same area. Found a combination you like? Save your preset.

To locate the file manually, paste `%LOCALAPPDATA%\AION2` into File Explorer and look for `Saved… → Config → Windows… → Engine.ini`. Detection refreshes the list every three seconds; you can also select a folder or file. A folder name alone does not identify the launcher.

## Experiment with a way back

Before the first tweak, the app saves an exact copy of `Engine.ini` on each person's computer. Later presets do not replace that copy. **Restore original** recovers the saved file; backups are kept separately for each configuration.

> If the file already contained mods or tweaks during first setup, the saved original contains them too. Restore the game before the first capture if you want an unmodified starting point. The app restores only `Engine.ini`.

## What to expect

Changes take effect when the game starts again. Some settings may be ignored by the game version, and results depend on your hardware and the scene. There is no guaranteed FPS target or promise that every computer can run the game.

Experimental particle controls are global and may hide skills, attack warnings, and portals. Test carefully; the assistant does not enable global particle hiding.

---

**Independent project, not affiliated with NCSOFT. Software distributed under the MIT license.**

Found a problem? [Open an issue](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/issues) with your hardware, preset, and a description of what happened, without attaching personal configuration files.

[⬇ Download and try it](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/AION2-Tweak-Desempenho-v2.3.0.zip) · [Leia este anúncio em português](post-pt-br.md)

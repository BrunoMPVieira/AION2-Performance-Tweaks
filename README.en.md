![AION 2 Performance Tweaks · developed by Kharnoxy](assets/banner.svg)

<div align="center">

### Tune the game for your PC. Compare presets. Restore your starting point anytime.

**Independent Windows 10/11 x64 application · English / Português**

[⬇ Download version 2.3.0](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/AION2-Tweak-Desempenho-v2.3.0.zip) · [View release](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/tag/v2.3.0) · [Leia em português](README.md)

[PT-BR announcement](docs/post-pt-br.md) · [English announcement](docs/post-en.md)

</div>

## Built for practical testing

Not everyone plays on a high-end PC. **AION 2 — Performance Tweaks** brings `Engine.ini` options together in a straightforward interface, so you can try combinations and decide what works on your computer. It does not promise a specific FPS or apply a preset before you review it.

![Steam or PURPLE configuration screen](assets/setup-screen.png)

## What is included

- **13 ready-made presets**, from Quality and Balanced to Low-end PC, Light ultrawide · FSR, and experimental Clay graphics.
- **25 individual controls** for shadows, blur, scale/FSR, textures, foliage, reflections, lighting, and effects.
- **My PC assistant**: detect or enter RAM, processor, and GPU; choose a priority and review an editable suggestion.
- **Custom presets** saved locally, with an interface in English or Portuguese.
- **Original Preset**: a copy of this PC's `Engine.ini`, with **Restore original** to recover it.

![Hardware assistant](assets/hardware-assistant.png)

![Individual graphics controls](assets/tweaks.png)

## Get started

1. [Download the version 2.3.0 ZIP](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/AION2-Tweak-Desempenho-v2.3.0.zip), extract it, and launch **AION 2 Tweak de Desempenho.exe**. Python is not required.
2. Start AION 2 through your usual launcher, Steam or PURPLE, enter once, then close the game normally.
3. Select the detected `Engine.ini`. If several appear, choose the configuration your game uses.
4. Choose a preset or build a suggestion in **My PC**. Customize it under **Tweaks**.
5. With the game closed, review and apply. Start the game and compare the same scene; save the combination if you like it.

Detection searches local configuration folders and refreshes the list every three seconds. To locate the file manually, paste `%LOCALAPPDATA%\AION2` into File Explorer and look for `Saved… → Config → Windows… → Engine.ini`. You can also select a folder or file. Folder names alone do not identify Steam or PURPLE.

## Keep a way back

Before the first tweak, the app saves an exact copy of the selected `Engine.ini` on this computer. Later presets do not replace it. **Restore original** recovers the saved file and keeps separate backups for each configuration.

The saved file is the one already present on first use. If it contained mods or tweaks, they will be in the copy too. Restore the game before the first capture if you want an unmodified baseline. The app restores only `Engine.ini`.

## Known limits

Changes take effect the next time the game starts. The game version may ignore some values, and results depend on hardware and scene. The assistant uses local rules; it is not a benchmark or FPS guarantee.

Experimental particle controls are global and may hide skills, attack warnings, and portals. There is no verified control for limiting how many players are visible. Test these settings carefully; automatic suggestions do not enable global particle hiding.

## Download integrity

ZIP SHA-256: `9E87DCE730A364308905849C5A63217A76AC8494B631D633F342C8761B65BF92` · [checksum file](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/releases/download/v2.3.0/SHA256SUMS.txt)

Issues and suggestions: [open an issue](https://github.com/BrunoMPVieira/AION2-Performance-Tweaks/issues) with your hardware and reproduction steps. Please do not attach personal configuration files.

**Independent project, not affiliated with NCSOFT. Developed by Kharnoxy.**

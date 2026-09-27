<p align="center">
  <a href="https://quietcut.me">
    <img src="https://quietcut.me/logo_yellow.png" alt="QuietCut Silence Remover logo" width="96" height="96">
  </a>
</p>

<h1 align="center">QuietCut Silence Remover</h1>

<p align="center">
  <b>Remove silence from videos automatically. No AI, no cloud, no subscription.</b><br>
  Desktop app for Windows and macOS · <a href="https://quietcut.me">quietcut.me</a>
</p>

<p align="center">
  <a href="https://github.com/MahsumPlays/quiet-cut-releases/releases/latest"><b>⬇ Download the latest version</b></a>
  ·
  <a href="https://quietcut.me">Website</a>
  ·
  <a href="https://quietcut.me/de">Deutsch</a>
  ·
  <a href="https://discord.gg/8RDznExUuJ">Discord</a>
</p>

---

QuietCut finds the quiet parts in your recordings and cuts them out automatically, entirely on your own computer. It is built for long recordings like Twitch VODs, let's plays, podcasts, tutorials and talks.

This repository hosts the official QuietCut installers and powers the in-app auto-update. The source code is not public.

![QuietCut audio tracks: Discord, game sound and mic read separately, the waveform shows in red what gets cut](https://quietcut.me/step-2-tracks.jpg)

## Why QuietCut

- **Fast.** A 2 hour video with 2 audio sources takes around 15 to 30 seconds for the XML export on an NVMe SSD. The timeline is written without re-encoding your video.
- **Local.** Your files never leave your machine. No upload, no file size limit, no AI guessing what to cut.
- **Multiple audio tracks.** Every track in your recording is read separately with its own dB threshold, for example mic, game sound or Discord.
- **Your editor, your workflow.** Export as MP4 for a finished video, or as XML to keep editing in Premiere Pro, DaVinci Resolve or Final Cut.
- **Autopilot** (Premium). Point QuietCut at a folder and every new recording is cut automatically in the background, even after you close the window.
- **Clip Exporter.** (Premium) Every OBS chapter marker becomes its own named clip. Can be linked with Autopilot.
- **Full control.** dB threshold, minimum pause and speech length, margins, Do Not Touch passages, presets and settings history.

## Download

Get the installer for your system from the [latest release](https://github.com/MahsumPlays/quiet-cut-releases/releases/latest) or from [quietcut.me](https://quietcut.me/#download):

| System | File |
| --- | --- |
| Windows | `QuietCut-Setup-<version>.exe` |
| macOS | `QuietCut-Setup-<version>.dmg` |

The `.yml`, `.blockmap` and `.zip` files are used by the auto-update and do not need to be downloaded.

### Windows SmartScreen warning

QuietCut is not signed with a paid code-signing certificate yet, so Windows or your browser may warn about the file. Click **More info → Run anyway** (SmartScreen) or **Keep anyway** (browser). Only download QuietCut from [quietcut.me](https://quietcut.me) or this repository.

## Pricing

| Plan | Price | |
| --- | --- | --- |
| Basic | Free | 1 hour of processing per month |
| 30-day pass | 9,90 € one-time | All Premium features, ends on its own |
| Premium Lifetime | 44,90 € one-time | All Premium features, forever |

No subscription. Nothing renews automatically. Details on [quietcut.me](https://quietcut.me/#pricing-heading).

## Guides

- [QuietCut Silence Remover](https://quietcut.me/silence-remover)
- [Remove silence from video](https://quietcut.me/remove-silence-from-video)
- [Cut silence from Twitch VODs](https://quietcut.me/cut-silence-twitch-vods)
- [Silence removal for Premiere Pro & DaVinci Resolve](https://quietcut.me/remove-silence-premiere-pro-davinci-resolve)
- [Remove silence from podcasts](https://quietcut.me/remove-silence-from-podcast)
- [Automatic jump cuts](https://quietcut.me/automatic-jump-cuts)

## Official website

The only official website of QuietCut is **[quietcut.me](https://quietcut.me)**. QuietCut is developed by 925studios e.U. (Austria). Other websites using a similar name are not affiliated with QuietCut.

## Support

- Bug reports and questions: [Discord](https://discord.gg/8RDznExUuJ) or <support@925studios.net>
- Please include your QuietCut version, operating system and, if possible, a screenshot or log.

---

<details>
<summary><b>Deutsch</b></summary>

**QuietCut Silence Remover** schneidet Stille automatisch aus Videos, komplett lokal auf deinem Rechner, ohne AI, ohne Cloud, ohne Abo. Ideal für Twitch VODs, Let's Plays, Podcasts und Tutorials.

- Ein 2-Stunden-Video mit 2 Audioquellen braucht für den XML-Export auf einer NVMe-SSD rund 15 bis 30 Sekunden.
- Mehrere Audiospuren mit eigener dB-Schwelle, Export als MP4 oder XML für Premiere Pro, DaVinci Resolve und Final Cut.
- Autopilot (Premium) schneidet neue Aufnahmen in überwachten Ordnern automatisch, der Clip Exporter macht aus OBS-Markern einzelne Clips.
- Basic kostenlos, 30-Tage-Pass 9,90 €, Lifetime 44,90 €, jeweils einmalig.

**[Neueste Version herunterladen](https://github.com/MahsumPlays/quiet-cut-releases/releases/latest)** · **[quietcut.me/de](https://quietcut.me/de)**

Die einzige offizielle Website ist [quietcut.me](https://quietcut.me). Warnt Windows SmartScreen, auf „Weitere Informationen → Trotzdem ausführen" klicken.

</details>

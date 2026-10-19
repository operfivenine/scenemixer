<p align="center"><img src="assets/readme/scenemixer-logo.png" width="174" alt="SceneMixer logo"></p>

<h1 align="center">SceneMixer</h1>
<h3 align="center">Find the scenes. Build the mix.</h3>

<p align="center">
  <img src="assets/readme/badge-windows.svg" alt="Windows desktop">
  <a href="https://ffmpeg.org/"><img src="assets/readme/badge-ffmpeg.svg" alt="FFmpeg / ffprobe"></a>
</p>

<p align="center">
  <a href="https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SceneMixer-21.0-R4-WIN01-Setup-x64.exe"><img src="assets/readme/button-download.svg" alt="Download for Windows"></a>
  <a href="docs/user-guide.md"><img src="assets/readme/button-guide.svg" alt="User guide"></a>
  <a href="https://boosty.to/oper59"><img src="assets/readme/button-support.svg" alt="Support SceneMixer"></a>
</p>

<p align="center"><a href="README.md">English</a> · <a href="README.ru.md">Русский</a></p>

**SceneMixer turns local video footage into scene-based edits.** Detect scenes automatically or choose exact fragments with Cutter, combine material from several sources, preview your mix, and export a finished video. Your original files stay unchanged.

**Add videos → Detect or cut → Build a mix → Preview → Export**

<a id="download"></a>

## Download

**SceneMixer 21.0 R4 · WIN01 · Windows x64 · Pre-release**

**[Download the installer — 167.2 MiB](https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SceneMixer-21.0-R4-WIN01-Setup-x64.exe)** · [Release notes](https://github.com/operfivenine/scenemixer/releases/tag/v21.0-r4-win01) · [SHA-256 checksums](https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SHA256SUMS.txt)

Download and run the installer, then follow its steps. Close SceneMixer before updating an existing installation. WIN01 is a public test package; the tested-system matrix and minimum hardware requirements are still pending.

Already have a build? Follow the [first-mix guide](docs/tutorials/01_First_Mix.md).

## What you can make

Collect moments from several videos into one edit, extract a set of manually chosen fragments, or compare different scene orders before exporting.

| Find scenes | Select and organize | Build the video |
| --- | --- | --- |
| Automatic detection with adjustable sensitivity | Exact in/out selection in Cutter | Assemble selected scenes in Scene Mixer |
| Multiple local video sources | Adjust boundaries and merge neighbors in SCM | Check the order with Quick Preview |
| Optional TransNetV2 detection | Save `.smx` projects and `.scm` scene maps | Choose codec, quality, resolution and FPS |

## Your videos, projects and scene maps

| File | What it stores |
| --- | --- |
| Original video | Your footage; project editing does not overwrite it. |
| `.smx` project | Media references, scene selection, edits, settings and Mix state. |
| `.scm` scene map | Scene boundaries and related data for one source. |

Projects and scene maps **do not embed your videos**. Keep the source files; use **Project → Project files… → Relink file…** if they move. [Projects and SceneMaps →](docs/project-files.md)

## More ways to work

Enable the tools you need in **Settings → Optional Features**:

- **Mix variants:** compare edits from the same scene selection, Keep favorites, and regenerate the rest. Overlap controls request fewer shared scenes; the limit may be impossible with a small scene pool.
- **Find Originals:** match edited fragments to higher-quality source footage, then review or assign matches manually.
- **Converter:** convert a video separately from the project’s Mix export.

The interface and searchable built-in FAQ are available in English and Russian. Press **F1** for help. [Optional tools →](docs/optional-tools.md)

## Help in the app

Press **F1** to open the searchable built-in **FAQ** in English or Russian. Use the [user guide](docs/user-guide.md) for step-by-step instructions and [troubleshooting](docs/troubleshooting.md) for common problems.

## Built with

SceneMixer uses PySide6 / Qt, PySceneDetect, OpenCV and [FFmpeg](https://ffmpeg.org/) / [ffprobe](https://ffmpeg.org/ffprobe.html). Optional TransNetV2 detection uses ONNX Runtime. [Technology credits →](docs/credits.md)

## Feedback and support

[Support oper59 on Boosty](https://boosty.to/oper59). Supporting development is optional.

Found a bug? [Open an issue](https://github.com/operfivenine/scenemixer/issues) with your SceneMixer version, Windows version and reproduction steps. See [what to include](docs/troubleshooting.md#report-a-problem).

**Operator: oper59.**

---

<p align="center"><strong>Find the scenes. Build the mix.</strong></p>

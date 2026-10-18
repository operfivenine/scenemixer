<p align="center"><img src="assets/readme/scenemixer-logo.png" width="174" alt="SceneMixer logo"></p>

<h1 align="center">SceneMixer</h1>
<h3 align="center">Find the scenes. Build the mix.</h3>

<p align="center">
  <img src="assets/readme/badge-windows.svg" alt="Windows desktop">
  <a href="https://ffmpeg.org/"><img src="assets/readme/badge-ffmpeg.svg" alt="FFmpeg / ffprobe"></a>
</p>

<p align="center">
  <a href="#download"><img src="assets/readme/button-download.svg" alt="Download status"></a>
  <a href="docs/user-guide.md"><img src="assets/readme/button-guide.svg" alt="User guide"></a>
  <a href="https://boosty.to/oper59"><img src="assets/readme/button-support.svg" alt="Support SceneMixer"></a>
</p>

<p align="center"><a href="README.md">English</a> · <a href="README.ru.md">Русский</a></p>

**SceneMixer turns local video footage into scene-based edits.** Detect scenes automatically or choose exact fragments with Cutter, combine material from several sources, preview your mix, and export a finished video. Your original files stay unchanged.

**Add videos → Detect or cut → Build a mix → Preview → Export**

<a id="download"></a>

## Download

**SceneMixer 21.0 R4 · public download pending.** A Windows x64 WIN01 test installer exists; its public release has not been approved. A verified installer link and release checksums will appear here after approval.

Already have a build? Follow the [first-mix guide](docs/tutorials/01_First_Mix.md).

## What you can make

Collect moments from several videos into one edit, extract a set of manually chosen fragments, or compare different scene orders before exporting.

| Find scenes | Select and organize | Build the video |
| --- | --- | --- |
| Automatic detection with adjustable sensitivity | Exact in/out selection in Cutter | Assemble selected scenes in Scene Mixer |
| Multiple local video sources | Adjust boundaries and merge neighbors in SCM | Check the order with Quick Preview |
| Optional TransNetV2 detection | Save `.smx` projects and `.scm` scene maps | Choose codec, quality, resolution and FPS |

## Two ways to your first video

### 1. Let SceneMixer find the cuts

1. Click **Add video** and choose your source files.
2. Select a file in **Current source**, then click **Detect scenes**. Repeat for other sources as needed.
3. Mark the scenes you want to use.
4. Open **Scene Mixer** and click **Mix Scenes**.
5. Check the sequence in **Quick Preview**.
6. Review **Quality…**, click **Export**, and choose the output file.

### 2. Pick the fragments yourself

1. Add your videos and open **Cutter**.
2. Set a fragment’s start and end, then click **Add scene**.
3. Repeat for the fragments and sources you want.
4. Use **All scenes → Mixer**, then **Mix Scenes**.
5. Check **Quick Preview**, review the quality, and **Export**.

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

## User guide

| I want to… | Read |
| --- | --- |
| Make my first mix | [Automatic workflow](docs/tutorials/01_First_Mix.md) |
| Choose clips by hand | [Cutter](docs/tutorials/02_Manual_Cutter.md) |
| Understand Full, Selective and Seed | [Mix, preview and export](docs/tutorials/03_Mix_Preview_Export.md) |
| Save work or restore moved files | [Projects and scene maps](docs/project-files.md) |
| Compare variants or match originals | [Optional tools](docs/optional-tools.md) |
| Find a shortcut or solve a problem | [Shortcuts](docs/keyboard-shortcuts.md) · [Troubleshooting](docs/troubleshooting.md) |

[Open the full guide →](docs/user-guide.md)

## System requirements

SceneMixer is a Windows desktop application. The WIN01 test package targets **Windows x64**. Supported OS builds and minimum CPU, RAM, GPU and disk requirements await release testing. [Requirements and verification status →](SYSTEM_REQUIREMENTS.md)

## Help in the app

Press **F1** to open the searchable built-in **FAQ** in English or Russian. Use the [user guide](docs/user-guide.md) for step-by-step instructions and [troubleshooting](docs/troubleshooting.md) for common problems.

## Built with

SceneMixer uses PySide6 / Qt, PySceneDetect, OpenCV and [FFmpeg](https://ffmpeg.org/) / [ffprobe](https://ffmpeg.org/ffprobe.html). Optional TransNetV2 detection uses ONNX Runtime. [Technology credits →](docs/credits.md)

## Feedback and support

[Support oper59 on Boosty](https://boosty.to/oper59). Supporting development is optional.

Found a bug? [Open an issue](https://github.com/operfivenine/scenemixer/issues) with your SceneMixer version, Windows version and reproduction steps. See [what to include](docs/troubleshooting.md#report-a-problem).

**Operator: oper59.** Distribution terms will be stated with the approved release.

---

<p align="center"><strong>Find the scenes. Build the mix.</strong></p>

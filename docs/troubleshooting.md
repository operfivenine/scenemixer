# Troubleshooting

[← SceneMixer](../README.md) · [Русский](troubleshooting.ru.md)

## Video is missing or will not open

Check that the file exists and is selected in **Current source**. If importing is still running, wait. If the file moved, use **Project → Project files… → Relink file…**. For drag and drop, use the **player area**.

## Too many scenes or a suspicious cut

Review Sensitivity; higher values detect smaller changes. Inspect the scene and use SCM to adjust boundaries or merge neighbors. Boundary warnings are review aids, not automatic proof of an error.

## Preview or export cannot find FFmpeg

Open Settings and use **Refresh FFmpeg** to recheck its status. WIN01 packaging materials list FFmpeg/ffprobe as bundled; if an installed package cannot find them, check that its files are intact and report the exact message. Follow the published package instructions once a final release is available.

## No Pause button

Pause/Resume applies to the main Mix encode workflow when the button appears. A different operation may not support pausing.

## A tool is missing

Check **Settings → Optional Features** for Converter, Originals search and multiple Mix variants. Press **F1** and search the built-in FAQ for the tool.

## SceneMap says Missing source or Problem

Missing source means the saved media path is unavailable; restore or relink the video. Problem means the map could not be read or failed validation. Keep a copy of the file before investigating and include the exact status in your report.

<a id="report-a-problem"></a>

## Report a problem

Use the [bug-report form in Issues](https://github.com/operfivenine/scenemixer/issues/new?template=bug_report.yml). Include the SceneMixer version and package revision, Windows version, reproduction steps, expected result and actual result. For media problems, include container/codec, resolution and frame rate if known. Share a small permitted sample only when needed.

Diagnostic logs can be enabled in Settings → Logs. Review screenshots and log excerpts before sharing; remove personal paths and private content.

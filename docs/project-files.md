# Projects and SceneMaps

[← SceneMixer](../README.md) · [Русский](project-files.ru.md)

| Object | Contents | Keep in mind |
| --- | --- | --- |
| Source video | Actual media | Removing it from the project does not delete the disk file. |
| `.smx` project | Source references, scenes, edits, settings and Mix state | Keep the referenced videos; they are not embedded. |
| `.scm` scene map | Scene boundaries and related source data | A map belongs to a source; it does not replace the project or embed video. |

## Save, reopen and relink

Use **Ctrl+S** to save, **Ctrl+Shift+S** to Save As, and **Ctrl+O** to reopen. On first save, choose a project name. Legacy `.scenemixer.json` projects are listed as supported in the 21.0 project metadata.

If media moves, open **Project → Project files…**, select a missing file, and choose **Relink file…**. Point to the new location. When multiple files are missing, project opening can also offer a folder search.

Use **Settings → Backup** to configure safety copies before overwrite or create a manual backup. Autosave is configured separately in data/project settings. Back up your source footage too.

## Edit scenes with SCM

SCM edits scenes that have already been detected or saved: adjust boundaries, delete a scene or merge neighbors. Boundary warnings identify cuts worth reviewing; inspect the boundary preview and decide whether to change it.

Normal edits are stored in the `.smx` project. They do not rewrite the source video or automatically overwrite an existing `.scm` map.

## Read SceneMaps Library

| Status | Meaning |
| --- | --- |
| Ready | Valid map, ready to use |
| Used / Unused | Referenced / not currently referenced by a project |
| Modified | A linked project contains local scene changes |
| Missing source | The source is absent at the saved location |
| Legacy | Older compatible map format |
| Problem | Reading or validation failed |
| Exact | Saved frame count matched the expected count |

Exact describes a frame-count check; it does not certify every cut as visually correct.

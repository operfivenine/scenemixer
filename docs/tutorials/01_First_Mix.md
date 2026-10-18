# Your first mix: automatic scene detection

[← SceneMixer](../../README.md) · [Русский](01_First_Mix.ru.md)

**Result:** a video assembled from scenes you selected, saved as a separate output file.

1. Click **Add video**, or drop video files onto the **player area**. The files appear in **Current source**.
2. Choose the source to analyze. Adjust **Sensitivity**, then click **Detect scenes** and wait for the scene table. Higher sensitivity detects smaller visual changes as boundaries.
3. Double-click a scene row, or select it and press **Enter**, to inspect its start. Mark the scenes you want to include. Repeat detection and selection for other sources as needed.
4. Open **Scene Mixer**. Use **Full** to use the selected scene pool; **Selective** takes a chosen part of it. Click **Mix Scenes**.
5. Open **Quick Preview** to check the order and overall edit. This is a short preview, rather than the final render.
6. Review **Quality…**, click **Export**, and choose a new output file. Wait for completion and open the result to check it.
7. Press **Ctrl+S** to save a `.smx` project if you want to continue later. Keep the source videos on disk.

If detection creates too many fragments, lower sensitivity and review again. Use SCM to adjust existing boundaries or merge neighboring scenes. For deliberate in/out selection, use [Cutter](02_Manual_Cutter.md).

**Next:** [Mix settings and export](03_Mix_Preview_Export.md).

# Build, preview and export a Mix

[← SceneMixer](../../README.md) · [Русский](03_Mix_Preview_Export.ru.md)

## Choose the scene pool

**Full** uses the complete set of selected scenes. **Selective** uses part of that set, such as a chosen percentage or count. Click **Mix Scenes** to build the sequence.

**Seed** controls randomized ordering. The same sources, scenes, settings and Seed can reproduce the same randomized version. Change Seed to try another order.

## Check the sequence

**Quick Preview** creates a short preview of the current Mix. Check the order and overall feel before committing to a full export. If you change the selection or Mix settings, rebuild the Mix and check the current result again.

## Choose quality and export

1. Open **Quality…** beside Export, or **Settings → Export**.
2. Review codec, quality/bitrate, resolution and frame rate. Available choices depend on the current build and export mode.
3. **Source FPS** uses the source frame rate; for mixed frame rates, SceneMixer selects a suitable stable output rate.
4. **Frame accurate** follows stored scene start/end frames as precisely as possible. It can make export slower; it is not a guarantee for every kind of input.
5. Click **Export**, choose an output name and location, and wait for completion. Check the exported file in a player.

The main Mix encode workflow supports **Pause / Resume** when those controls appear. If there is no Pause button, the current operation does not support it. Cutter and Find Originals exports have their own purposes and controls.

For alternate edits, see [Mix variants](../optional-tools.md). If preview or export cannot find FFmpeg, see [troubleshooting](../troubleshooting.md).

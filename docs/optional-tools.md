# Optional tools

[← SceneMixer](../README.md) · [Русский](optional-tools.ru.md)

Open **Settings → Optional Features** and enable only the tools you need.

## Multiple Mix variants

1. Enable **Multiple mix variants**. A variants section appears in Scene Mixer.
2. Use **Generate variants** to build edits from the same selected scene pool.
3. Switch variant numbers and preview the results.
4. **Keep** protects a variant; **Regenerate unkept** rebuilds the rest. Unkeep a variant before regenerating it.

**Overlap** limits shared scenes between variants. A small pool or strict constraints may prevent the requested limit from being met; different variants are not guaranteed to be unique.

## Find Originals

Enable **Originals search**, open Find Originals, add higher-quality original files and start automatic matching. Review found matches. For a missed fragment, use **Manual Search** to locate and assign a section yourself.

Exporting matched fragments is a separate operation from exporting the project’s Mix. Review what is matched before exporting.

## Converter

Enable **Converter** to show its button in the main interface. This tool converts video through FFmpeg without changing the project edit. It is separate from Mix export; use the controls and output options presented by Converter.

## TransNetV2 detection

Standard detection uses PySceneDetect. TransNetV2 is an additional ONNX detection method. Development setups can obtain the model separately. WIN01 packaging notes and manifest list the model and ONNX Runtime as included in that test package. Confirm the final release contents before assuming a download is required.

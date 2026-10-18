# System requirements and verification status

[← SceneMixer](README.md) · [Русский](SYSTEM_REQUIREMENTS.ru.md)

The public release compatibility matrix is pending. The following distinguishes package configuration from tested application support.

| Item | Evidence currently available |
| --- | --- |
| Platform | Windows desktop; WIN01 is an x64 test package. |
| Installer OS gate | WIN01 packaging specifies Windows 10 build 19045 or later. This is an installer setting, not confirmation of runtime support on each OS. |
| Tested Windows builds | No installed-release test matrix supplied for this review. |
| CPU / RAM / GPU | Minimum and recommended values not established. |
| Free disk space | Installed footprint, temporary analysis and export needs not measured here. |
| Runtime components | WIN01 packaging notes list Python/Qt, media libraries, FFmpeg/ffprobe and TransNetV2/ONNX Runtime as bundled. Final package contents require release verification. |
| Other platforms | macOS, Linux, Windows ARM64 and emulation not verified. |

The local WIN01 installer exists, but availability and PE version metadata do not prove a successful installation, playback or export. No speed, memory, codec coverage or export accuracy benchmark is claimed here.

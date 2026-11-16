# claude-real-video

Import-ready packaging of the **claude-real-video** skill, copied from
[`HUANGCHIHHUNGLeo/claude-real-video`](https://github.com/HUANGCHIHHUNGLeo/claude-real-video)
(path `skills/claude-real-video/`). All credit goes to the original author
(LeoAido). The upstream repository is unchanged; this repo only repackages the
skill so it can be imported directly (SKILL.md at the repository root).

## Layout

- `SKILL.md` — the skill, byte-identical to upstream
- `LICENSE` — the original MIT license (LeoAido)
- `ATTRIBUTIONS.md` — the original upstream attributions file

## Requirements

- `pip install "claude-real-video[whisper]"` (installs the `crv` CLI; needs Python 3.10+ and ffmpeg)
- The `[whisper]` extra is required for speech-to-text; the first transcription downloads a whisper base model (~139 MB)

See `SKILL.md` for usage.

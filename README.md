# VX models

Speech models downloaded on first use by VX Player's auto-subtitles feature.
Files live on the GitHub releases of this repo, so the URLs stay stable.

All files are mirrored unmodified from the [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)
model zoo (ONNX exports by k2-fsa). Only the file names changed.

## Release `asr-v1`

| File | Source | Licence |
|---|---|---|
| `silero_vad.onnx` | [Silero VAD](https://github.com/snakers4/silero-vad) via sherpa-onnx `asr-models` | MIT |
| `dolphin-base-ctc.int8.onnx`, `dolphin-base-tokens.txt` | [Dolphin base](https://github.com/DataoceanAI/Dolphin) via `csukuangfj/sherpa-onnx-dolphin-base-ctc-multi-lang-int8-2025-04-02` | Apache-2.0 |
| `whisper-base-encoder.int8.onnx`, `whisper-base-decoder.int8.onnx`, `whisper-base-tokens.txt` | [OpenAI Whisper base](https://github.com/openai/whisper) via `csukuangfj/sherpa-onnx-whisper-base` | MIT |

SHA-256 checksums are in `SHA256SUMS`; the app verifies every file after download.

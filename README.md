# VoiceCar language packs

The language packs of **VoiceCar**, the offline voice assistant for Honda Connect head units.
Each car downloads the pack of the language it uses, once, automatically.

| Release | File | Language |
|---|---|---|
| `voicecar-ar-2` | `voicecar-ar-pack-2.zip` | Arabic |
| `voicecar-en-1` | `voicecar-en-pack-1.zip` | English |

**Do not rename or delete these releases or their files** — the app's download links depend on
the exact tag and file names. Every pack is checked against its SHA-256 fingerprint by the app;
a changed file is refused.

## Licences of the models inside the packs

The packs contain third-party open-source models, each under its own licence:

| Model | Source | Licence |
|---|---|---|
| Arabic speech recogniser `vosk-model-small-ar-tn-0.1-linto` | alphacephei.com/vosk/models | Apache 2.0 |
| Arabic voice Nabra-82M | huggingface.co/oddadmix/Nabra-82M-v0.1 (via k2-fsa/sherpa-onnx) | Apache 2.0 |
| English speech recogniser `vosk-model-small-en-us-0.15` | alphacephei.com/vosk/models | Apache 2.0 |
| English voice Piper "Amy" (low) | Piper voices; dataset: github.com/MycroftAI/mimic3-voices | CC BY-SA 4.0 |
| Pronunciation data `espeak-ng-data` | github.com/espeak-ng/espeak-ng | GPL-3.0 |

These models remain under their licences; the files here are the unmodified models.

VoiceCar itself is proprietary software: © 2026 Ehab Mahmoud Awad. All rights reserved.

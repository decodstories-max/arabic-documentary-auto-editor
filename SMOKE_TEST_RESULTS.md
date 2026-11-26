# HyperFrames + GSAP Smoke Test — Results

**Status: PASS (infrastructure smoke test only)**

Run: https://github.com/decodstories-max/arabic-documentary-auto-editor/actions/runs/45874992715  
Commit: `20c8f691f62dd4b1af177e9b543b7a57a61ae981`  
HyperFrames CLI: `0.9.99`

## Verified execution

- GitHub-hosted runner: Ubuntu 24.04
- Node.js: 22.23.5
- npm: 10.9.9
- FFmpeg / FFprobe: 6.1.1
- HyperFrames managed Chrome Headless Shell: 158.0.8127.88
- GSAP dependency install: passed
- HyperFrames browser ensure: passed
- HyperFrames doctor command: executed successfully; optional whisper-cpp, Kokoro TTS and MusicGen integrations are not installed. These optional tools are not required for rendering this composition.
- HyperFrames lint: `ok: true`, 0 errors, 0 warnings, 0 infos; 2 files scanned; no unmounted compositions.
- HyperFrames render: passed
- FFprobe verification: passed
- GitHub artifact upload: passed

## MP4 verification

- Container/video codec: MP4 / H.264
- Resolution: 1920 × 1080
- Frame rate: 30/1 fps
- Frames: 150
- Duration: 5.000000 seconds

Artifact: `hyperframes-gsap-smoke-preview`  
Artifact ID: `15143583372`  
SHA-256 of artifact ZIP: `a666083b3903c782a6c071ddb5e9e70dbd120f1af5a5e00127eabb2181eed83a`  
Retention: 3 days from upload (created 2026-11-26T18:20:50Z).

## Scope and limitations

This is a generic technical smoke test. It contains no documentary script, voice-over, research, Binance branding, project images, or private assets.

It proves that a remote GitHub-hosted runner can install HyperFrames and GSAP, install/launch the managed browser, lint a composition, render an H.264 MP4, inspect its metadata, and upload the result.

It does **not** approve the visual design or rendering of any documentary Beat. No Binance project Beat was rendered. The project's visual QC, voice-over synchronization, audio mix, and user approval gates remain separate and mandatory.

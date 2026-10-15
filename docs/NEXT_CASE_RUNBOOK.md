# CASE-002 onward — repeatable production runbook (V2, based on CASE-001)

## Privacy and ownership first
GitHub repository is PUBLIC. Keep source investigation reports, photographs containing nonpublic plant details, personnel information, MP4/MP3/WAV and editable assets under local `media/CASE-NNN/` (gitignored). Only commit cleared high-level metadata, generic prompts and lessons. Verify publication permission before exporting a public video.

## Roles
- User: provides cleared report, technical judgment, selects/approves scenes and style, generates 6s clips manually at Higgsfield Wan 3.0/Prime, creates ElevenLabs voices and Google Flow Music track, downloads files.
- Assistant: analyzes report; proposes storyboard; creates **two separate** start/end PNG images per shot; supplies English motion prompt and Korean narration for each; reviews MP4; creates controlled post edits, assembled preview and narration/music mix; keeps GitHub docs updated **only when explicitly written**, not automatically.

## Stage-by-stage gate checklist
0. `git pull --ff-only origin main` only after inspecting `git status`. Start `projects/CASE-NNN/` record and local `media/CASE-NNN/` workspace.
1. Intake: reconstruct timeline with evidence source/page, plant state and cause; distinguish FACT / RECONSTRUCTION / EDUCATIONAL. No speculative voltages or mistaken plant designs.
2. Storyboard: default 6s per shot; allocate additional final narration time using a longer held end shot (CASE-001: final scene 18s, assembled 48s). Define each scene's action, beginning and ending *physical state*, camera and image restrictions.
3. Style lock: toy plastic miniature, **simplified consistent people without distinctive faces**, scene continuity; in a *control room* never add safety helmets unless clearly required by source. Avoid branded blocks and real plant identity drawings.
4. Images: create standalone 16:9 START and END PNGs. Verify separately opening files and actual differences (not identical or split-screen). Reject caption boxes, false digits, inappropriate PPE, added people/objects, and mismatched camera/geometry. Deliver exact filenames and working downloads; ZIP both as fallback. Save only approved files. 
5. Motion: provide copy-ready English prompt; Higgsfield manual Start/End Image-to-Video, default 6s, 16:9, 1080p if available, AUDIO OFF. User saves `CASE-NNN_S01_MOTION_V01.mp4`, uploads for review.
6. Visual QC: check full duration and frame sample (early / middle / end), all characters and equipment, transformation artifacts, technical chronology, labels and operational plausibility. Classify ACCEPT / CONTROLLED_EDIT / RETRY / HOLD. Do not claim exact mechanical behavior solely from an illustrative frame.
7. Controlled edit: preserve motion original; overlay independently rendered factual captions/graphics in fixed regions. No invented values; use `CASE-NNN_S01_CONTROLLED_EDIT_V01.mp4`. Optional graphic PNG is a source asset, not extra step for viewer. Limit overlays to essential points.
8. Assembly: build silent rough cut from accepted versions only. Verify boundaries, proportions, playability, actual duration and voice-room timing before generating audio.
9. Narration (ElevenLabs): one agreed Korean voice across all scenes. Export scene-specific files; measure actual lengths rather than estimates. 6s slots need room for breathing, avoid overlapping neighboring scenes.
10. Music (Google Flow Music): one instrumental score extending over full duration (generate longer if needed), no vocals, subdued, non-disaster, with soft intro and outro. Download WAV/MP3. Optional minimal SFX, clearly illustrative.
11. Sound mix: mix narration as primary track; attenuate/duck music beneath speech, fade in/out, check intelligibility and clipping. Inspect audio/video sync at *words/ideas*, not only scene boundary. CASE-001 correction: lessons were voiced at ~37s but showed at 42s; move lessons panel to 37s, retain to end. Seek user acceptance.
12. Deliver: mark approved visual/audio mix as CURRENT USER-APPROVED REVIEW MASTER, not 1080p FINAL unless exported and verified at 1920×1080 with explicit final QC. Preserve source versions and a simple asset inventory.
13. GitHub: keep `projects/CASE-NNN/` production status, shot/cue sheet and handoff summary updated in a branch, PR, merge; do not assume chat files or local media auto-sync to GitHub.

## Recommended case timeline (customize)
S01~S05: 6 seconds each = 30 seconds. Final S06: 18 seconds, with sufficient text hold and VO alignment. Total 48 seconds. For different cases, shot number and durations can vary freely.

## Quality lessons from CASE-001
- A visually plausible electrical flow animation may mislead: favor breaker state and restrained indicators over moving red/blue cable currents.
- Inconsistent START vs END frames create morphs/crossfades; compare *actual* images before generating.
- S06 helmets reappeared mid-clip due to image mismatches: control-room workers should have consistent uncovered heads in approved references and prompts.
- Avoid AI-rendered technical numerals: exact VPL 64.55% previous, 11.68% intended, 6.67% entered; overlay precise values in post only.
- EDG 01B already running on standby: show output breaker closing, not engine starting.
- Reuse good image/motion instead of endless retries; fix only representational issues that a caption cannot resolve.
- Explicitly verify download artifacts, generate true standalone START and END, plus ZIP for reliability.
- Review the voice-to-screen *semantic* timing; freeze or extend ending as needed.

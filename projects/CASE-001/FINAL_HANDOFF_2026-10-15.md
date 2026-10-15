# CASE-001 final handoff — 2026-10-15

## Current state (honest status)
User reviewed `CASE-001_FULL_VOICE_BGM_MIX_V02_SYNCED.mp4` and said the lesson voice/screen alignment now looks good. This **48s, 1280×720 review master is user-accepted**. Do NOT call it final 1080p: a verified 1080p re-export and final publication QC were not completed. The main report and media are deliberately not stored in this public repo.

Subject: Saeul Unit 3 during commissioning, 2026-08-11, reactor auto-trip caused by VPL setpoint input error followed by RCP slowdown; SW02B undervoltage and EDG 01B supplying the B-train safety bus, then EOP stabilization. 3D plastic toy educational visualization **not authentic plant drawings or CCTV**.

## Verified event guardrails
- 80% load rejection commissioning test finished; during house-load operation planned change of VPL mistakenly set to 6.67%; intended CVR+0.5% = 11.68%; preceding VPL 64.55%.
- Turbine control valve restricted, turbine generator output/frequency decreased. Frequency ~59.7→55.8 Hz; turbine rpm ~1794→1689; RCP ~1190→1130 rpm. Reactor protective trip; no meltdown, explosion or nuclear release.
- Electrical timeline: UAT→SAT residual voltage transfer; SW02B had undervoltage, SAT breaker transiently closed then opened, EDG 01B *already running for the test* output breaker energized SW01B and SW02B; never animate diesel as newly starting.
- EOP: safety functions maintained; station stabilized in shutdown. DO NOT imply return to power generation or literal glowing reactor core behavior.
- Report has a nonpublic information redaction appendix: keep original private and use only cleared public-safe narrative.

## Approved shot inventory
| Shot | Content | Motion selected | Current visual treatment |
|---|---|---|---|
| S01 | Intro toy facility | `CASE-001_S01_MOTION_V02.mp4` | approved |
| S02 | VPL entry error | `CASE-001_S02_MOTION_V01.mp4` | approved |
| S03 | turbine valve restricting | `CASE-001_S03_MOTION_V01.mp4` | `CASE-001_S03_CONTROLLED_EDIT_V01.mp4` numeric callout |
| S04 | RCP slowdown / protective auto trip | `CASE-001_S04_MOTION_V01.mp4` | `CASE-001_S04_CONTROLLED_EDIT_V01.mp4` RCP/RPS overlays |
| S05 | SW02B low voltage / EDG supply | `CASE-001_S05_MOTION_V01.mp4` | `CASE-001_S05_CONTROLLED_EDIT_V01.mp4` SAT/EDG context |
| S06 | operator EOP stabilization, without helmets | `CASE-001_S06_MOTION_V02.mp4` (using START/END V03) | `CASE-001_S06_CONTROLLED_EXTENDED_V01.mp4`, 18s |

Note: S05 initially contained confusing red/blue power-flow lines; corrected into breaker-state visualization. S06 first attempt had sudden helmets; revised V03 reference frames and V02 motion corrected this.

## Assembly and audio
- Runtime 48 seconds = 5×6s + 18s ending, rough cut `CASE-001_FULL_VISUAL_ROUGHCUT_V01.mp4`.
- Narration: user supplied SIX ElevenLabs MP3s `CASE-001_S01_VO_V0.mp3` through `CASE-001_S06_VO_V0.mp3`. Durations (s): 4.52, 5.80, 5.64, 5.56, 5.49, 14.45. All contained within scene slots.
- Music: user supplied `CASE-001_BGM_FLOW_V01.wav` (about 61.97s, 48 kHz stereo). 48s section used, roughly -20.4dB gain relative to source, 1.5s fade-in, 4s fade-out, without SFX.
- Intermediate `CASE-001_FULL_VOICEOVER_PREVIEW_V01.mp4` (no BGM) → `CASE-001_FULL_VOICE_BGM_MIX_V01.mp4` → `CASE-001_FULL_VOICE_BGM_MIX_V02_SYNCED.mp4` (current).
- Crucial correction: S06 lesson narration begins around video t=37s, lesson panel had appeared t=42s. V02 advances lesson panel to **37s through 48s**, preserves VO/BGM.
- Current user-approved review master: `case001_final/CASE-001_FULL_VOICE_BGM_MIX_V02_SYNCED.mp4` (48s, 1280×720, H264/AAC, ~23MB). This refers to user/chat working assets, not a file tracked by Git.
- End screen safety lessons: prior review, cross-check/clear communication, procedure-based response. Avoid describing unapproved regulatory status.

## Known outstanding items
1. Verified 1080p export using available approved source shots, technical final image/audio QC, and explicit human review.
2. No separate user-approved SFX track is included. BGM + narration only.
3. Distribution/publication rights, original report sensitive portions and final audio/music licensing to be checked prior to public release.
4. Archive all local media and original mix project if reproducibility is required. GitHub stores text docs only; don't mistake it for an MP4 backup.

## Next case
Open `docs/NEXT_CASE_RUNBOOK.md` and `docs/CASE_TEMPLATE.md`. Create `projects/CASE-002/` and local `media/CASE-002/`, preserving CASE-001 assets. New case starts with the report intake, **not** by reusing this incident's facts or narration. Don't copy S06 helmets or S05 electric flow animations.

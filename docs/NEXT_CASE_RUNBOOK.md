# Next-case production runbook V3 — 8-second Wan 3 / master-first (2026-10-20)

> Supersedes V2 defaults **for CASE-004 onward**. Earlier CASE-001~003 approvals, runtimes, and deliverables remain historical records. No automatic re-edit.

## Scope and publication
- Repository is PUBLIC. Never commit original investigative PDFs, non-public technical drawings, confidential data, staff details, media files, or actual plant identity to public docs absent explicit clearance.
- Video narration and screen: anonymize plant and unit; use only source-validated generic equipment and system terms. Explain simplified educational reconstructions and do not pass generic 3D scenes as exact as-built representations.
- CASE-004 source has **not** been selected: the currently re-uploaded RE-013G report belongs to CASE-003. Keep it separate.

## Actual manual Higgsfield configuration (user-confirmed UI, 2026-10-20)
- Model Wan 3.0; duration **8 seconds** per motion; **1080p** selected; Unlimited toggle ON; aspect ratio 16:9; motion audio OFF when possible.
- Unlimited is a screenshot of current user UI, not a guarantee of permanent service terms or API allowance. Verify at each generation session.
- ~**120s finished film** target: typically 15 × 8-second slots INCLUDING intro and ending/held lesson cards. Length may flex with report evidence and measured voice. Scene durations need not equal speech; don't fabricate filler.
- Prior 6s or 48/54s language refers to older cases, not the current default.

## First action: local workspace setup, before analysis
```zsh
cd /Users/kevin/Projects/Simple_Wan3 || exit 1
CASE=CASE-004
mkdir -p "projects/$CASE" "media/$CASE"/{reference,storyboard,base_images,images,motion,audio,edits,deliverables,archive}
find "media/$CASE" -maxdepth 1 -type d | sort
```
Work is non-interactive; commands return to normal zsh shell. Check `git status` before `git pull --ff-only`. Do not silently overwrite local edits.

## Mandatory upstream gates before any scene images or paid/manual generations
1. **Investigate:** carefully read the case report, full chronology, appendices / diagrams, plant operating state, cause, actual operator actions, radiation/safety effects, corrective actions. Build an evidence table with report page/section, `FACT / INFERENCE / EDUCATIONAL` tags and uncertainty/clearance. No unsupported operations or invented numbers.
2. **Storyboard:** propose scene-by-scene objectives, 8s slot allocation totaling about 120s, location ID, equipment ID, character ID, camera, START state, END state, VO draft, overlays, technical pitfalls. Human signs off storyboard before scene stills.
3. **Base image / continuity bible:** create and separately approve reusable **locations**, **equipment and topology**, **people / clothing / scale**, and **control/technical display** masters, with stable IDs `LOC-xx`, `EQ-xx`, `CHAR-xx`, `CTRL-xx`; save under `media/CASE-NNN/base_images`. Draw images based on approved masters, not from scratch with each shot.
4. **Shot stills:** generate independent standalone START and END PNG, no side-by-side composites, headings, subtitle strips, fake monitor labels or technical numbers. Exact numbers and text only in post overlays. Independently inspect both frame images for same scene, camera, equipment geometry, pipe connections, characters and **exactly two arms/two hands**.
5. **Image handoff at every pair:** supply TWO verified individual PNG download links with names `CASE-NNN_Sxx_START_Vnn.png` / `CASE-NNN_Sxx_END_Vnn.png`, verified ZIP, Mac copy commands, 8s start+end Wan motion prompt, file name `CASE-NNN_Sxx_MOTION_Vnn.mp4`, VO draft, and next QC action **in the same response**.
6. **Manual Wan motion:** upload approved START and END to Wan 3.0 8s/1080p/Unlimited UI; fixed camera, single logical action, no morphological changes, no audio; save original untouched.
7. **QC gate:** probe actual MP4 duration, fps, resolution and audio; inspect start/mid/end and abnormal frames for limbs, continuity, data, physical path. `PASS / CONTROLLED_EDIT / RETRY / HOLD`; user accepts explicitly before lock. If output is 8.08s or another duration, edit intentionally rather than silently truncating.
8. **Controlled assembly:** approved clips only; animation alone for physical state, accurate captions and schematics drawn independently, not AI-text. Arrange silent edit to measured timeline. Preserve each original. Lesson cards have clear separate timings, hold as needed.
9. **Narration:** ElevenLabs voice chosen per case, consistent across scenes; **tagged UTF-8 TXT** (`[INTRO]`, `[S01]` ... `[Sxx_ACTION]`, `[Sxx_LESSON]`) and simple Python `dotenv` + `ElevenLabs` stream-save batch. Model `eleven_multilingual_v2` by default; Voice ID configured via .env or approved case setting. Do not commit API keys.
10. **BGM:** Google Flow Music instrumental, no vocals, restrained atmosphere, create ≥ finished duration; mix under intelligible narration, duck and fade out.
11. **Semantic sync & delivery:** compare exact voice phrase onset with graphic/card onset, particularly ending lessons (CASE-001 and CASE-003 lessons timing). Check loudness, clipping, duration, codec, missing tracks and human acceptance. Never call a preview '1080p FINAL' without actual 1920×1080 file proof.
12. **Continuous improvement:** each case handoff contains `LESSONS_LEARNED.md` (good, failures, mitigations, new rules). Update global runbook after user requests; don't claim GitHub/local synced without verification.

## Base masters acceptance contract
- Locations: spatial anchors, room proportions, camera orientation, lighting, scene access; avoid false placement of physically separate nuclear plant systems.
- Equipment: topology and relative scale, VCT vs EDT distinctions, pressurizer inside containment when relevant; no unsupported colored fluid paths or direct pipe into ventilation.
- People: fixed cast sheet with wardrobe/hairstyle/PPE by location, 2 arms, 2 hands, anatomical consistency. Control rooms generally no hardhats unless source.
- Display: generic blank schematic/status placeholders; source-validated values/symbols added as independent controlled overlays only.
- Each shot references approved master IDs and a single clear change from START to END.

## ~120s example slot plan (adapt after evidence review)
| Portion | Slots | Duration |
|---|---:|---:|
| Intro | 1 | 8s |
| Background | 2 | 16s |
| Event / causal chain | 5 | 40s |
| Response / analysis | 3 | 24s |
| Improvements / lessons | 4 | 32s |
| **Total** | **15** | **120s** |

## Checkpoint artifact paths
- `projects/CASE-NNN/CASE_FACTS_AND_UNCERTAINTIES.md`
- `projects/CASE-NNN/STORYBOARD_V01.md`
- `projects/CASE-NNN/BASE_MASTER_REGISTRY.md`
- `projects/CASE-NNN/LESSONS_LEARNED.md`
- local `media/CASE-NNN/{reference,storyboard,base_images,images,motion,audio,edits,deliverables,archive}/`

Production ownership: human selects case, approves technical/visual gates, runs Higgsfield and audio generation. ChatGPT helps analyze, storyboard, imagery, prompts, QC, edit, and only updates GitHub when performed through tools or explicit code.

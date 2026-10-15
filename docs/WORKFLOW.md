# Lightweight production workflow V1

## Roles (only two)
- **Assistant / creative+technical lead:** report analysis, storyboard, shot cards, first/last image specifications and generation, prompts, review feedback.
- **Human / director+operator:** verify facts, approve images and shots, operate Higgsfield manually, download and review outputs.
No Hermes orchestration, manifest bureaucracy, API keys or automatic paid generation.

## Stage gates
1. **Intake:** receive report privately; extract verified event chain and uncertainties. Never upload a sensitive report to this public repo.
2. **Script:** short educational sequence; 4–10 shots initially (adjust after reading report). Mark FACT / INTERPRETATION / RECONSTRUCTION / EDUCATIONAL.
3. **Style:** lock toy-diorama materials and reusable environment/characters.
4. **Frames:** for each shot create START.png and END.png at matching aspect ratio with consistent objects and positions. Approve visually.
5. **Manual generation:** in Higgsfield choose Wan 3.0 or Wan 3.0 Prime, Image-to-Video, add start/end frames if UI permits, paste one-shot motion prompt, set duration/resolution/aspect ratio, generate, download.
6. **QC:** check action order, moving parts, character continuity, readable visuals, no fictional labels, no misleading reconstruction; accept or revise.
7. **Assembly:** arrange accepted clips chronologically, add neutral narration/captions and optional BGM, export final MP4.

**Default:** 16:9, 6s per shot, 1080p target when available, sound off for first motion trials to avoid inconsistent voices; add controlled audio in post. Defaults are not hard model limits.

## Naming
`CASE-001_S01_START.png`
`CASE-001_S01_END.png`
`CASE-001_S01_MOTION_V01.mp4`
`CASE-001_S01_SHOT.md`

## Review thresholds
**PASS:** incident sequence accurate, material/shape continuity, no unexpected transformations, camera movement comprehensible, no fake evidence.
**RETRY:** serious drift in object geometry, temporal reversal, introduced false equipment operation, unexplained character appearance.
**HOLD:** technical facts unresolved; human verifies before depiction.

Model/platform subscription terms and model features can vary. Confirm the 7-day unlimited entitlement and UI support before each batch; do not assume API usage is free.

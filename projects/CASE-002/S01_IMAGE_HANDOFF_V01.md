# CASE-002 S01 image handoff V01

Storyboard V1: HUMAN APPROVED in chat, 2026-10-15. Approval covers storyboard, not individual S01 images or final video.

## S01 images
- `media/CASE-002/images/CASE-002_S01_START_V01.png` — wide illustrative generic plant exterior, 1672×941 PNG
- `media/CASE-002/images/CASE-002_S01_END_V01.png` — closer view of generic maintenance access/filter-preparation area, 1672×941 PNG
- Original imagery generated in ChatGPT conversation and downloadable separately or as `CASE-002_S01_START_END_V01.zip`; not committed to PUBLIC GitHub.
- Style: plastic-toy educational reconstruction, generic plant, not site-specific drawing, no labels or precise engineering representations.
- Image pair status: GENERATED, AWAITING USER VISUAL QC; NOT LOCKED.

## Higgsfield image-to-video plan
- Model: Wan 3.0 / Prime I2V (user manual), 6s, 16:9, audio OFF. Set START and END separately.
- Movement: gentle continuous push-in from wide exterior towards maintenance service bay, preserving structures/crew/location, no morphs, no extra humans, no reactor startup or leakage.
- Output expected: `media/CASE-002/motion/CASE-002_S01_MOTION_V01.mp4`. Requires user upload for technical QC.

## Draft S01 Korean VO
`2025년 9월, 정비 중이던 월성 2호기에서 감속재정화계통 필터 교체 작업이 시작됐습니다.`
Voice recording deferred pending duration measurement.

## Publication control
Store media and report locally only; source report remains outside public repo. Human video rights and clearance check required.

## S01 motion QC after user upload (2026-10-15)
- Received Higgsfield `hf_20261015_130212_0623c812-f0e7-40e8-888d-1ae944feff0d.mp4`; renamed review copy `media/CASE-002/motion/CASE-002_S01_MOTION_V01.mp4` (local/chat only).
- ffprobe: 6.060s, 1918×1080 (note width is 1918, not full 1920), 30fps, H264 video; AAC audio stream exists in file despite audio-OFF intention. This must be muted/replaced at mix stage.
- Contact sheet sampled 0~5 seconds: wide plant -> consistent push-in toward maintenance access/crew; no major catastrophic morphs or erroneous leakage/startup depiction. **Assistant recommendation: ACCEPT_PENDING_HUMAN**, not human-approved or final locked.
- S01 VO V01 7.706s; V02 revised narration 7.079s. Both overrun 6-second slot. Preserve both; audio timing correction pending, recommend natural speed-adjusted V02 test or shortened line.
- End-to-end S01 scene retains 6-second video slot; do not retime visuals without coordinating next scene.
- Next human gate: watch original S01 and approve imagery. After approval, S02 separate START/END images and motion prompt; final narration/BGM mix deferred until approved visual rough cut.

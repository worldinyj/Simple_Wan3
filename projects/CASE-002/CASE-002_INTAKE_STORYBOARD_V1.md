# CASE-002 — 월성2호기 감속재정화계통 필터 상부 덮개 중수 누설
Status: INTAKE_REVIEW / STORYBOARD_V1_PROPOSED / NOT_APPROVED
Date prepared: 2026-10-15
Source: KINS 원전 사고·고장 조사보고서 2025-07호(250919W2), 2026-03-23, 40-page provided copy.
Privacy: DO NOT upload source PDF, figures, plant-specific drawings, redacted details, personal data, or media to public GitHub. Public-safe abstractions only.

## Case essentials (report-grounded)
- Occurrence: 2025-09-19; report threshold confirmed 12:03, 24h >= 200kg heavy water within facility. Wolsong-2; PHWR/CANDU; Mode 5 assured shutdown, reactor power 0% (report pages 3-5).
- Preexisting internal leak of five filter upstream valves was known; ice plugging used for isolation.
- 09/18 16:30 ice plugging starts (three positions), 17:40 drain/depressurization begins, 18:10 and 18:15 completion presumed; 18:20-18:41 upper-cover bolt loosening reveals water leak; 19:00-19:30 re-tightening; 19:35 personnel depart without emergency re-freezing/monitoring.
- Residual D2O and pressure dislodged inner sealing O-ring; re-tightening crushed/displaced O-ring. Thawing and upstream valve internal leakage sustained leak.
- 09/18 20:40 calandria moderator level starts dropping; 09/19 02:10 first recognized (7480→7452mm); 04:00 leakage confirmed; 04:32 moderator pump stopped; 12:03 initial 265.4 kg liquid recovered/reportability established; 09/21 03:50 sealing O-ring replaced and leaking path finally controlled (report pages 5-15).
- Detector ME-28 mounted above design sump floor location failed to alarm promptly (p.18-20).
- Initial 265.4kg recovery IS NOT total evaluated leakage: total 1,311.15kg-D2O, of which approximately 1,306.01kg recovered and 5.14kg vented during evaluated period. Tritium incremental release 1.52e12 Bq, 0.08% of annual discharge limit; public dose evaluated 1.78e-4 mSv/yr; max individual worker dose 3.63 mSv; reactor remained safely shutdown, shutdown cooling remained effective (report pp.3-4, 19-23). Avoid describing full total as 'spilled all at once'.
- Report pre-assessed base INES Level 0, final evaluation to be determined separately; no assertion of final level.

## WHY / technical and organizational contributors
1. Incomplete advance verification of partial drain volume/time and pressure relief; sight glass mounted ~3.3m above top cover couldn't verify level at cover.
2. Changed ice-plug locations/partial drainage not adequately incorporated into approved work plan; high-risk prejob briefing before final approval.
3. Bolt loosening used as status confirmation despite remaining internal pressure.
4. Emergency plan required re-ice-plugging and monitoring until thaw; it was not followed.
5. Longstanding valve leaks, weak CAP/OE follow-up, detector siting deficiency. These are distinct causal layers.
6. Never render actual unredacted equipment layout and valve piping topology. The 28th-page diagram is evidence for conceptual understanding only.

## Storyboard V1 — six shots, 16:9, 3D plastic toy miniature, tentative 48 seconds
All shot visuals educational reconstructions, NOT actual facility footage.
| Shot | Video clock | Shot purpose / visual start → end | Visual guardrail | Spoken Korean narration DRAFT |
|---|---|---|---|---|
| S01 | 00-06 | Miniature generic CANDU facility in shutdown maintenance → gentle camera approach to generic filter module | No reactor startup, core glow, disaster effects, actual site plan | 2025년 9월, 정비 중이던 월성 2호기에서 감속재정화계통 필터 교체 작업이 시작됐습니다. |
| S02 | 06-12 | Same filter and pipes, three generic frost bands established → air drain schematic, incomplete drain not falsely marked complete | No exact real piping; no misleading pressure gauges/numbers; steady physical geometry | 배관을 결빙하고 배수와 해압을 수행했지만, 완료 상태를 충분히 확인하지 못했습니다. |
| S03 | 12-18 | Same top filter flange sealed ring → loosened bolts, O-ring dislodges, re-tightening pinches inner ring | Simplified cutaway; one clear physical change sequence; no massive explosion | 내부 압력이 남은 채 볼트를 풀자 중수가 새었고, 다시 조이는 과정에서 오링이 손상됐습니다. |
| S04 | 18-24 | Frozen pipe sections thaw → small steady seep from damaged upper flange | Valves can leak internally despite 'closed'; no fake open-valve motion; no alarming flooding | 이후 결빙이 풀리자 내부누설 밸브를 거친 중수가 손상된 틈으로 계속 누설됐습니다. |
| S05 | 24-30 | Control room moderator trend slowly declines, no alarm shown → on-site inspection and controlled pump stop icon/state | Operators in control room no helmets; show alert via trend not fictitious alarm; no reactor trip | 운전원은 감속재 수위 감소를 확인하고 현장에서 누설을 발견한 뒤 펌프를 정지했습니다. |
| S06 | 30-48 | Controlled double isolation and O-ring replacement → freeze/hold lesson card from approx 36-37s to 48s | Don't show reactor restart; legal final INES unknown; accurate sentence-to-visual alignment | 손상된 오링을 교체해 누설을 차단했습니다. 교훈은 세 가지입니다. 작업 조건은 수치로 확인하고, 비상조치계획은 반드시 이행하며, 누설감시 설비는 설계대로 유지해야 합니다. |

Timings are placeholders until actual ElevenLabs MP3 durations are measured. S06 lesson panel must enter when lesson VO begins, NOT late (CASE-001 audio/visual defect). Default S01-S05 6s and S06 18s; shorten voice script after measured TTS if required. Distinct START and END 16:9 PNG per shot, real difference. No baked captions/numerals in AI frames; add factual overlays in controlled edit.

## Visual specification & filenames
- Style: clean, rounded plastic toy miniatures; navy/soft teal/ivory and restrained cyan D2O; generic unbranded plant and nonspecific simplified piping; operator consistent navy workwear; no facial details; control room no hardhat.
- Keep one stable filter asset, top cover, seal groove and pipe positions from S02-S04. Device geometry does not morph between START and END.
- S03 show inner O-ring physically displaced and pinched only in educational sectional abstraction; actual detailed mechanics inferred from investigation, not photographs of sequence.
- `CASE-002_S01_START_V01.png`, `CASE-002_S01_END_V01.png` ... S06; `CASE-002_S01_MOTION_V01.mp4`; `CASE-002_S01_VO_V01.mp3`; `CASE-002_BGM_FLOW_V01.wav`.
- Higgsfield image-to-video 6s per shot; 16:9; audio OFF; 1080p if available. Human uploads results for full-frame QC. S06 motion may be 6s with extended static editor hold (12s) to 18s.

## Shared English prompt scaffold (draft; individual shot prompts after image lock)
Maintain exact camera, miniature geometry and prop consistency with supplied START and END images. Create one gentle, physically comprehensible transition over six seconds. Fixed filter/pipe positions; no morphology changes. Clean 3D rounded plastic toy educational style, soft diffuse lighting, restrained liquid motion. No text, numbers, logos, on-screen captions, real control-panel designs, extra personnel, dramatic smoke, fire or flooding. No audio.

## Lessons / controls
- Scope of report: already redacted publication copy has additional marked nonpublic categories; keep the full PDF local.
- FACT/RECONSTRUCTION/EDUCATIONAL differentiation on all shot cards; human technical QC mandatory.
- Report references: report body pp.3-24; annex 1 p.28; annexes 5-6 pp.34-36.
- Source publication rights and official clearance need a human confirmation before publishing finished video.

## Next gate
Human review/approval of causal storyline, scene division and narration BEFORE generating S01 START/END imagery. Next: lock visual style and generate separate S01 PNGs, with a specific motion prompt. Track draft vs approved status.

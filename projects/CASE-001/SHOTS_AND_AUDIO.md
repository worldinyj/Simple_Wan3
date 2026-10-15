# CASE-001 — Shot prompts, narration and audio cue sheet V1

Status: **working record**, narration is draft only and has not been synthesized/mixed. 6s/shot target, total ~36s. Names must match local media/CASE-001 files.

## S01 — establishing (APPROVED V02)
**Motion prompt (EN):**
Single continuous 6-second camera shot. Begin with wide establishing view of miniature plant. Slowly dolly toward control room, preserving exact plant geometry, pipes, staff, color, and lighting. No zoom-out, crossfade, double exposure, sudden camera move, alarms, or object morphing.
**Narration (KO draft):** 2026년 8월, 새울3호기는 부하상실 시운전시험을 마치고 소내부하운전 중이었습니다.
**BGM/SFX:** neutral documentary bed, no alarm, quiet control-room ambience.

## S02 — VPL input error (APPROVED V01)
**Motion prompt (EN):**
One continuous 6-second shot in miniature plastic-toy control room. Standing senior operator calmly instructs seated turbine operator, who presses console buttons. Senior leans slightly forward. Fixed camera, same simplified no-face or minimal-face toy workers, no cuts, morphing or pop-in text.
**Narration (KO draft):** 계통병입을 준비하던 중, 운전원은 터빈제어밸브 위치제한기 설정값을 잘못 입력했습니다.
**Critical editing note:** intended 11.68%, entered 6.67%; actual previous setting 64.55%. Numeric overlay only in controlled edit.
**BGM/SFX:** soft button press, restrained unease.

## S03 — turbine valve closure (MOTION V01, CONTROLLED EDIT)
**Motion prompt (EN):**
One continuous 6-second miniature toy turbine control valve and generator. Valve stem slowly moves downward. Turbine generator gradually slows in response to reduced steam flow. Keep equipment, pipes, lighting and locked camera stable; no cuts, morphing, dramatic alarm or animated numbers.
**Narration (KO draft):** 잘못된 설정값으로 터빈제어밸브가 닫히면서 발전기 주파수와 터빈속도가 감소했습니다.
**Overlay:** generator frequency 59.7 -> 55.8 Hz; turbine speed 1794 -> 1689 rpm. Visual valve movement alone does not prove turbine rotation change.
**BGM/SFX:** controlled low mechanical deceleration, no catastrophic sound.

## S04 — RCP decrease and reactor trip (MOTION V01, CONTROLLED EDIT APPROVED)
**Motion prompt (EN):**
One uninterrupted 6-second miniature plastic toy plant cutaway. RCPs gradually slow in an illustrative manner; reactor protection system responds and plant trips. Dim reactor-core illustrative glow, illuminate limited control-room status lights. Maintain all geometry, neutral stable camera, no fire, smoke, or destruction.
**Narration (KO draft):** 냉각재펌프 속도가 보호기준까지 떨어져 원자로보호계통이 작동하고 원자로가 자동정지했습니다.
**Overlay:** approximately 1190 -> 1130 rpm; High-LPD / Low-DNBR protection trip. Core glow is symbolic, not literal reactor appearance.
**BGM/SFX:** short restrained signal, then soft controlled room ambience.

## S05 — SW02B LOV and EDG power (FRAMES REVISED, MOTION PENDING)
**Motion prompt (EN):**
One continuous six-second shot of a miniature 3D plastic toy electrical switchgear diorama. SW02B low voltage indication is present; SAT incoming breaker stays OPEN. Emergency diesel generator EDG 01B is already running and waiting, NOT starting. The EDG output breaker transitions OPEN to CLOSED, then the B-train bus is shown as supplied, with a clean green energized-flow indicator. Maintain exactly identical panel geometry, camera angle, operators and machine positions. No cuts, no morphs, no invented numerical values or extra switching.
**Narration (KO draft):** 안전모선 SW02B에 저전압이 발생하자 대기 중이던 비상디젤발전기가 B계열 안전모선에 전력을 공급했습니다.
**Chronology note:** report records SW02B LOV at 20:56:17.159, SAT closing then opening, EDG breaker close near 20:56:18.759/786. These remain editorial narrative, not literal real-time six-second replay.
**BGM/SFX:** brief restrained breaker click; calm stable power hum.

## S06 — stabilization and lesson (PLANNED)
**Motion prompt (EN; preliminary only):**
Quiet miniature toy control-room scene. Operators methodically follow emergency procedures, monitoring stabilized plant indications. Slow static camera, stable identical simplified toy characters, no panic or dramatic damage. Final frame calmly emphasizes stable conditions without text morphing.
**Narration (KO draft):** 운전원은 비상운전절차를 수행해 안전기능을 유지했습니다. 정확한 확인과 의사소통이 재발방지의 핵심입니다.
**BGM/SFX:** gentle resolution, fade-out.

## Audio production V1
- Separate **Narration (KO)**, **BGM** and **SFX** stems; don't generate speech within Wan clip.
- One voice, consistent neutral instructional Korean tone, WAV 48 kHz where possible.
- BGM instrumental, no lyrics; low level beneath narration; avoid alarm-like effects.
- SFX: minimal console action, breaker clicks, low industrial ambience; distinguish sonic decoration from real recorded evidence.
- Work order: lock six video shots -> review timing -> synthesize voice -> select/generate music -> assemble/duck BGM -> QA final MP4.
- Do not call draft narrations final until timing and factual review; 6s voice durations must be measured.

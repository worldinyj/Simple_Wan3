# CASE-001 audio workflow

Status: scripts/prompts READY; rendered voices/BGM NOT YET CREATED.

## Timeline
S01 00:00–00:06; S02 00:06–00:12; S03 00:12–00:18; S04 00:18–00:24; S05 00:24–00:30; S06 00:30–00:48.

## ElevenLabs
Compare Korean voices Hyunbin / Bin (and Chris as alternative) using identical passage:
“원자로냉각재펌프 속도가 떨어지자, 보호계통이 작동해 원자로가 자동정지했습니다. 원자로의 자동정지는 설계된 보호기능의 작동입니다.”
Choose ONE voice for all scenes. Produce 6 separate MP3s. Target each 6s scene narration to ~4.8–5.6s; S06 <=16.5s. Review natural speed and correct technical diction. Do not treat estimated durations as measured.

| Scene | Filename | Narration draft |
|---|---|---|
| S01 | CASE-001_S01_VO_V02.mp3 | 새울 삼호기는 부하상실시험 후 소내부하운전 중이었습니다. |
| S02 | CASE-001_S02_VO_V02.mp3 | 계통병입 준비 중, 터빈제어밸브 위치제한기 설정값을 잘못 입력했습니다. |
| S03 | CASE-001_S03_VO_V02.mp3 | 그 결과 제어밸브가 닫히면서 터빈속도와 발전기 주파수가 감소했습니다. |
| S04 | CASE-001_S04_VO_V02.mp3 | 냉각재펌프 속도가 떨어지자 보호계통이 작동해 원자로가 자동정지했습니다. |
| S05 | CASE-001_S05_VO_V02.mp3 | 안전모선 저전압 이후, 대기 중이던 비상디젤발전기가 전원을 공급했습니다. |
| S06 | CASE-001_S06_VO_V02.mp3 | 운전원들은 비상운전절차에 따라 안전기능을 확인하고 발전소를 안정화했습니다. 이번 사건은 운전조작 전 사전검토, 상호확인과 명확한 의사소통, 그리고 절차에 따른 대응의 중요성을 보여줍니다. |

Download locally to media/CASE-001/audio (gitignored). Upload MP3s to chat for synchronized final mixing.

## Flow Music
Google Flow Music (https://flowmusic.google): create ONE instrumental 48-second score; if exact length unsupported create ~60s and trim.

Prompt:
Instrumental underscore for a serious but approachable Korean nuclear power plant incident educational film, rendered as 3D plastic toy miniatures. 48 seconds total. 0–12s calm ambient technical pulse; 12–30s subtle and restrained tension, not danger; 30–42s quiet stabilization; 42–48s warm professional closing resolution. Sparse soft piano, subtle analog synth pads, gentle rhythmic ticks. Leave room for Korean male narration. No vocals, lyrics, choirs, sirens, impacts, alarms, trailer drums, heavy bass or disaster atmosphere. Smooth continuous transitions and soft ending.

Save as CASE-001_BGM_FLOW_V01.wav or .mp3. Music ducks under speech; preserve natural fades. All assets are local; no generated audio included in this repository.

## Source control
Scene narrations are draft scripts subject to human review; original report and audio stay local/private.

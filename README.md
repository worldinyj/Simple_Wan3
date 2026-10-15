# Simple Wan3 — Toy-Style Incident Video Studio

원전 사건조사보고서를 **3D 플라스틱 장난감/미니어처 톤**으로 설명하는 **경량 수동 제작 파이프라인**입니다. Hermes 멀티에이전트 구조 없이 ChatGPT가 사건 분석·이미지·프롬프트·QC·편집을 돕고 사용자가 Higgsfield에서 수동으로 Wan 3.0/Prime 영상을 만듭니다.

## CASE-001 첫 검증: 2026-10-15
- [CASE-001 완료 인수인계](projects/CASE-001/FINAL_HANDOFF_2026-10-15.md): 6 scenes, 총 48초, S06 18초 엔딩, ElevenLabs 나레이션 + Google Flow Music BGM, 사용자 확인된 **720p 음성/BGM 편집본 V02**.
- *1080p 최종 마스터 검증은 아직 완료되지 않았습니다.* 실제 MP4, MP3, WAV, 사건 원문은 공개 GitHub에 올리지 않습니다.
- 가장 중요한 최종 수정: 나레이션 교훈 시작 약 37초에 맞춰 교훈 화면 시작을 42초에서 **37초**로 조정.
- 영상 내 3D 미니어처는 교육용 개념도이며 원전 실제 설계·설비 형상과 동일하지 않습니다.

## 다른 사건 시작하기 (CASE-002 이상)
1. **[새 사건 제작 런북](docs/NEXT_CASE_RUNBOOK.md)** 읽기.
2. **[새 케이스 템플릿](docs/CASE_TEMPLATE.md)** 복사하여 `projects/CASE-002/`에 문서 생성, 로컬에 `media/CASE-002/` 폴더 준비.
3. 조사보고서는 채팅으로 공유하되 외부공개 승인되지 않은 원문·실제 민감 설비 도면을 공개 GitHub에 넣지 말기.
4. 사고 사실 검증 → 6초 단위 샷 계획 → 각각 분리된 START·END PNG → Higgsfield 수동 생성 → 영상 QC → 통제형 편집 → ElevenLabs VO → Google Flow Music → 합성·동기화 QC.
5. 승인 기록과 최종 영상/음성 파일명을 GitHub **문서**에 반영; 실제 미디어는 로컬에 별도 보관.

추가 참고: [workflow](docs/WORKFLOW.md) · [style](docs/STYLE_BIBLE.md) · [audio](docs/AUDIO_POST.md) · [manual](docs/HIGGSFIELD_MANUAL.md) · [CASE-001 cues](projects/CASE-001/SHOTS_AND_AUDIO.md).

로컬 동기화: `cd ~/Projects/Simple_Wan3 && git status && git pull --ff-only origin main` (uncommitted changes가 있으면 먼저 확인).

# Simple Wan3 — Toy-Style Incident Video Studio

원전 보고대상사건을 **3D 플라스틱 미니어처/블록 장난감 스타일**의 교육용 영상으로 제작하는 경량 수동 파이프라인입니다.

**원칙:** 사건보고서 → 사실 검토 → 짧은 샷 구성 → 시작/종료 프레임 생성 → 사용자가 Higgsfield Wan 3.0 / Prime에서 직접 영상 생성 → 육안 검수 → 편집.

- **No Hermes agents, no automatic Higgsfield calls, no mandatory API keys.**
- 핵심 작업은 사람이 승인합니다. 영상·이미지의 추정 연출은 사실과 구분합니다.
- 동일한 캐릭터/설비/환경을 반복 사용하도록 스타일 문서 및 shot card를 둡니다.
- 16:9 / 6초를 **초기 권장값**으로 사용하되, 사건과 모델 결과에 따라 바꿀 수 있습니다.
- 보고서 원문에 보안·개인정보·비공개 정보가 있다면 공개 저장소에 업로드하지 마세요.

## 시작하기
1. [워크플로](docs/WORKFLOW.md)와 [스타일 가이드](docs/STYLE_BIBLE.md)를 읽습니다.
2. 사건자료가 오면 `projects/CASE-001/` 아래 샷 카드와 영상 설계안을 채웁니다.
3. 시작/종료 이미지를 제작하고 사용자 승인 후 Higgsfield에 **수동 업로드**합니다.
4. 생성한 MP4는 로컬 `media/` 폴더에 두고 `docs/SHOT_TEMPLATE.md`를 따라 결과를 기록합니다.
5. 로컬 동기화: `git clone https://github.com/worldinyj/Simple_Wan3.git`.

저장소 구성과 검수 정책은 `docs/`에 있습니다. **실제 보고서/영상 파일은 아직 포함되지 않았습니다.**

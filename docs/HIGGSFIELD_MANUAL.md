# Higgsfield manual runbook (Wan 3.0 / Prime)

1. Check actual subscription status in your Higgsfield account. The advertised seven-day unlimited window is account-specific; UI plan availability, queue/fair-use rules and eligibility may differ from API billing.
2. Choose Wan 3.0 or Wan 3.0 Prime **Image to Video** mode. Upload shot START, then END if the account UI exposes a last-frame control.
3. Paste shot card **motion prompt**, not a lengthy general script.
4. Initial trial: 6 seconds, 16:9, 720p for preview or 1080p if supported. Turn native sound off for clean post-production unless desired.
5. Verify start/end stills, animation logic, model displayed and output. Download MP4.
6. Save as `media/CASE-001/CASE-001_S01_MOTION_V01.mp4` (local-only by default). Record model/settings/status in shot card. Retry only failed clips.
7. No auto-generate button, no API scripts and no credits consumed by repository operations.

Higgsfield public API documentation indicates Prime image-to-video accepts a first image and optional last image, duration 2–30s and common aspect ratios; this does not guarantee identical controls in the website subscription UI.
Reference: https://open.higgsfield.ai/models/alibaba/wan-3.0-prime/image-to-video/api-reference

# CASE-004 — Root Cause Analysis V02 (public-safe production summary)

Status: DRAFT / HUMAN TECHNICAL REVIEW REQUIRED. Source report retained **locally only**. No report PDF, drawings, equipment photos, voice, images, audio, MP4 or site/unit identity are uploaded to this public GitHub repository.

## 3. Three-tier cause classification

This is a **production-oriented reclassification** of an investigation report, not a statement that the report formally issued these exact categories.

| Category | Definition | Interpretive question |
|---|---|---|
| Direct cause (직접원인) | An activity or condition that immediately initiates the event | What physical state / operation actually triggered the event? |
| Root cause (근본원인) | The deepest justified procedural, system, organizational or human-performance reason for the failure / state | Why was the state created or allowed to persist? |
| Contributing cause (기여원인) | Factors that interact with the chain of events to elevate likelihood/severity or defeat timely detection | What made the event more likely or less likely to be intercepted? |

### Direct cause
- A discharge-path valve and an isolation valve remained in an incorrect non-isolated condition after the preceding authorized transfer.
- A recirculation pump was started with that unintended discharge path still present; the initiating **activity** was pump startup, and the initiating **state** was incorrect valve alignment.

### Root cause — preliminary RCA classification
- **Procedure / work execution:** mandatory procedures were not used, so restoration and pre-start verification steps were missed.
- **Organizational practice / human performance:** established convenience practices prevailed over prescribed isolation and were not challenged; questioning attitude and stop-when-uncertain behaviors were inadequate.
- **Design assurance for monitoring barrier:** design-document coordination, functional commissioning checks, and cross-unit design-change feedback did not fully implement a flow-triggered monitoring function. This is a systemic cause **of the failed monitoring/control barrier**, not the same thing as the immediate cause of unplanned release.

### Contributing causes
- Ambiguous valve-open/closed visual feedback; status not independently confirmed.
- Inconvenient access and separation of valve location from local indications reinforced the operational shortcut.
- Lack of independent cross-check during a one-person task and incomplete operational shift records.
- Recirculation pre-start alignment checks and post-start level/flow monitoring were not carried out, delaying detection.
- Automatic effluent sampling/control transition was unavailable because the flow-triggered input was not implemented; the downstream monitor did not perform effective surveillance during the release.

### Important boundary between causal outcomes
1. **Why did the unplanned release start?** Wrong valve alignment + pump startup, with procedure/verification and operating-practice weaknesses.
2. **Why was it not detected/controlled in time?** Incomplete process-variable checks + ineffective effluent-monitor automation due to design-implementation gaps.

The absence of an automatic monitor is **not** described as starting the release. Do not depict an alarm or protective actuation that did not occur. Do not imply large offsite dose from this event.

## Storyboard/editorial handoff
- Show an **ordinary system-operations schematic**, then a fixed-geometry educational view of unintended flow.
- Distinguish valve state from human initiation action.
- Visualize procedure-use, questioning attitude, and verification steps **without blame-focused dramatization**.
- Show the monitoring barrier as unavailable/inoperative during the event; protective function shown later only as a documented corrective-action concept.
- Separate **completed short-term actions** from **long-term plans**; never present planned work as completed.
- Use source-confirmed technical IDs and numeric overlays **only in approved controlled post-production**; never rely on AI-rendered instrument texts.
- Script and shot-list approval precedes location/equipment/character base-master generation.

## Evidence and confidentiality
The local confidential/working source mapping is maintained outside public GitHub in `media/CASE-004/reference/` or local-only files. Before public publication, obtain clearance for case-specific incident facts, source citations and any more detailed equipment naming.

## Next review gate
Human technical expert approves cause allocation and representation; only then freeze the storyboard and base-image registry.

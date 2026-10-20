# CASE-004 BASE MASTER REGISTRY V01 — REVIEW GATE
Status: Design APPROVED as planning concept; generated initial reference images remain REVIEW ONLY pending matching technical and style QC. GitHub stores only this text, NO images/audio/video/reports.
Default 3D style: soft believable matte plastic miniature, engineering-accurate conceptual topology, generic/unbranded, consistent blue uniform and white hardhat for field operations, 16:9.

## Location IDs
| ID | Purpose | Shots | Visual anchor |
|---|---|---|---|
| LOC-01 | Generic liquid waste-processing hall overview | S00–01 | clear overall silhouette; no claim actual spatial adjacency |
| LOC-02 | Main tank, discharge pump and local panel | S02,07–09 | large tank / lower adjacent pump / panel, keep scale and relative geometry |
| LOC-03 | Discharge valve closeup | S04–05,10 | round-wheel valve, side stem status must be readable visually |
| LOC-04 | Isolation valve platform / accessibility | S06,10 | elevated valve position, guarded access, safe pose |
| LOC-05 | Liquid effluent monitor | S03 | sampling/monitoring panel in *distinct* system space |
| LOC-06 | RCA briefing room | S11–13 | restrained review panels, no fictional technical values |

## Equipment IDs
| ID | Purpose | Fidelity rule |
|---|---|---|
| EQ-01 | Waste liquid tank, editorial code TK5 | Same vessel geometry and tank scale in each reused shot |
| EQ-02 | Tank discharge pump, editorial code P5 | Distinct motor/pump; don't invent rotary parts |
| EQ-03 | Discharge valve, editorial code V21 | Distinguish actual stem position from locked handle; side view when required |
| EQ-04 | Downstream isolating valve, editorial code V53 | Keep separated from V21 with believable accessibility; avoid showing tied to wrong outlet |
| EQ-05 | Liquid effluent monitor LEM | Do not fake alarm or automatic actuation during incident |
| EQ-06 | Local liquid-waste panel | Blank/mock indicators; post exact labels as separate graphics |
| EQ-07 | Recirculation versus discharge *conceptual* pipe topology | Separate arrows/overlay from base images; no invented exact plant piping |

## Cast and graphic masters
| ID | Identity | Rule |
|---|---|---|
| CHAR-01 | Field operator | Same haircut/face-neutral silhouette, blue utility uniform, white helmet, exactly 2 arms / 2 hands |
| CHAR-02 | Health physics staff | Consistent distinct accessory such as clipboard, no extra body parts |
| CHAR-03 | Control room operator | Consistent outfit, no hardhat without source basis |
| CHAR-04 | Incident analyst | Generic human; no identifiable real person |
| CTRL-01 | Generic event-chain / technical scheme | Source-checked directions only; exact text as controlled overlay |
| CTRL-02 | Procedure/checklist improvement status | Pending vs completed differentiated |
| CTRL-03 | 120s intro/end lessons template | Overlay after motion, synchronize voice and text |

## First base images generated in the conversation — proposed save locations (not yet verified as independently mounted files)
Do **not** commit these image files to GitHub. Save images manually from the chat image menu to the following Mac local-only filenames:

| Master | Local relative filename | Current QC |
|---|---|---|
| LOC-02 / EQ-01 / EQ-02 / EQ-06 overview | `media/CASE-004/base_images/CASE-004_BASE_LOC-02_TK5_P5_PANEL_V01_REVIEW.png` | REVIEW: generic plausible hall; tag/text may be generated; style more realistic than previous miniature look |
| LOC-05 / EQ-05 monitoring area | `media/CASE-004/base_images/CASE-004_BASE_LOC-05_LEM_V01_REVIEW.png` | REVIEW: no verified exact LEM functional details |
| LOC-03 / EQ-03 valve closeup | `media/CASE-004/base_images/CASE-004_BASE_LOC-03_V21_V01_REVIEW.png` | REVIEW: side valve geometry not identical to actual case valve; technical correction needed |
| LOC-04 / EQ-04 elevated valve | `media/CASE-004/base_images/CASE-004_BASE_LOC-04_V53_V01_REVIEW.png` | REVIEW: safe access visually; do not portray actual piping layout |
| LOC-06 / CHAR-04 RCA briefing | `media/CASE-004/base_images/CASE-004_BASE_LOC-06_RCA_V01_REVIEW.png` | REVIEW: diagram on screen is AI illustrative only |

## Base image QC pass conditions
1. Single 16:9 scene, no split panels / text banners / incorrect numbers.
2. Across approved related images: consistent spatial anchors, geometry, static camera and same human design.
3. People have exactly two arms and two hands, no morphing; safety PPE scene appropriate.
4. Correct conceptual topology and relative equipment role; human reviews before final MASTER_LOCK.
5. All images and videos stay ONLY in `media/CASE-004/` locally. Real report PDF stays local.
6. After review, rename accepted masters `..._APPROVED.png` and record SHA-256/hash and human approval in private local log; text-only approval status to GitHub.

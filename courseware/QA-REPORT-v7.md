# QA Report — AI for Lean Manufacturing v7.0

**Course code:** TGS-2023020425  
**QA date:** 19 August 2026  
**Result:** PASS with disclosed Drive legacy-file exceptions

## Courseware alignment

- Current title and course code appear across PPT, Learner Guide, Lesson Plan and all four assessment documents.
- Registered LO1–LO9, K1–K8 and A1–A6 are preserved and mapped across the slide map, Learner Guide, Lesson Plan, activities and assessments.
- The original assessment instruments remain Written Assessment (8 questions, 60 minutes) and Practical Performance (6 tasks, 90 minutes).
- Procedures, scenario questions, evidence requirements and acceptance criteria are carried by the Learner Guide and activity packs rather than the slide deck.

## Presentation QA

- 134 slides at 16:9.
- All 134 slides carry fade or push transitions.
- Three editable native PowerPoint charts and seven working hyperlinks.
- Full-slide rendered review passed with no clipping, overlap or off-canvas objects.
- Cover spacing and the two delivery-model slides were corrected after the first visual review and passed a fresh second review.

## Document and activity QA

- Learner Guide: 33 rendered pages; stable PDF-ready contents page.
- Lesson Plan: 8 rendered pages; two-day schedule totals 480 minutes per day excluding lunch and includes the 60+90 minute assessment block.
- Ten self-contained activity folders.
- 42 activity Markdown files and 42 same-basename PDFs: parity PASS.
- Activity evidence includes mock CSV data, scenarios, worksheets and evidence checklists.

## Assessment QA

- Four DOCX files built: WA candidate, WA answer key, PP candidate and PP answer key.
- Structural verifier result: PASS for all four rendered documents.
- Grading appears on candidate-paper page 2; no trailing “For Official Use Only” block.
- Candidate papers only are linked on LMS-TMS. Answer keys remain outside the public repository and current public course folder.

## Publication QA

- Google Drive readback MD5 matches local PPT, PDFs, LG, LP and all four uploaded assessment source files before answer-key privacy separation.
- `Activities/` readback: 94 files.
- LMS-TMS readback: all seven courseware URLs live; non-target fields preserved.
- TMS title readback: `AI for Lean Manufacturing`; protected link, course-code, hours and assessment fields preserved.

## Disclosed Drive exceptions

- Two legacy Learner Guide files could not be moved to archive because Drive returned `insufficientFilePermissions`; the v7.0 files are current and selected by LMS-TMS.
- Two legacy answer keys in the archived Assessment folder could not be removed for the same permission reason. Current v7.0 answer keys were moved to a separate private trainer folder and anonymous download was denied.

## GitHub boundary

Public release includes learner-facing courseware and activities only. `.env`, assessments, answer keys, references, QA renders, generated source assets and build tooling are excluded.

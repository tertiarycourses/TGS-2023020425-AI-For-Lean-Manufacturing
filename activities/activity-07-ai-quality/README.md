# Activity 7: AI Visual Quality Pilot

**Level:** Advanced  
**Duration:** 75 minutes  
**Mapping:** K3 A6  
**Tools:** Use-case worksheet; sample predictions CSV; checklist

## Goal

Design a human-in-the-loop visual-quality pilot with suitable data, class metrics, thresholds and fallback.

## Learner output

Use-case canvas, data plan, confusion-matrix interpretation, decision rights and pilot acceptance criteria.

## Files in this folder

- `README.md` / `README.pdf` - activity guide and detailed procedure
- `scenario.md` / `scenario.pdf` - case facts and questions
- `worksheet.md` / `worksheet.pdf` - structured response template
- `evidence-checklist.md` / `evidence-checklist.pdf` - acceptance record
- `data.csv` - mock dataset when analysis is required

## Detailed procedure

1. Define the quality decision and current inspection baseline.
2. List defect classes, severity and available image sources.
3. Review predictions.csv and calculate true positives, false positives, true negatives and false negatives for critical defects.
4. Calculate recall for critical defects and precision for AI flags.
5. Set a conservative triage threshold and mandatory human-review condition.
6. Define lighting, camera, product-mix and label controls.
7. Specify fallback when the model or connection is unavailable.
8. Set pilot acceptance, stop and revalidation criteria.

## Verification

Complete every acceptance item in `evidence-checklist.md`. Submit the worksheet plus calculations, exported tool output or screenshots named in the worksheet.

## Safety, privacy and responsible AI

Use only the supplied scenario data unless your organisation has authorised another dataset. Remove personal, confidential and export-controlled information. AI outputs are suggestions until verified by the named human decision owner.

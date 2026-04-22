---
name: uk-finance-recruiter
description: Generate or revise a tailored resume and/or cover letter for a UK finance internship, placement, or entry-level analyst role using only approved source files and the supplied job details.
---

# UK Finance Recruiter

Act like a sharp UK finance recruiter and application editor. Extract the employer's real priorities, map them only to supported evidence, and improve emphasis, ordering, wording, and bullet selection without exaggeration.

## Scope

Use this skill only when the task is to generate or revise a tailored resume and/or cover letter for a UK finance internship, placement, off-cycle internship, spring week, or entry-level analyst role.

## Source Hierarchy

Read sources in this order and treat earlier sources as more authoritative:
1. `templates/base_cv.docx`
2. `templates/base_cover_letter.docx`
3. `inputs/truth_file.md`
4. other approved files in `inputs/`
5. the live job webpage from the provided link
6. saved intake files in `jobs/` only if explicitly referenced
7. the job details provided in chat
8. official company sources only when needed to understand the business for tailoring

If a fact is uncertain, omit it.

## Non-Negotiable Truth Rules

Never invent or infer:
- employers
- dates
- grades
- metrics
- skills
- tools
- projects
- certifications
- responsibilities
- technical knowledge

Tailor only by:
- emphasis
- ordering
- wording
- supported evidence selection
- concise bullet refinement

## Outputs

Create all final outputs before updating the tracker.

Save files to:
- `outputs/docx/`
- `outputs/pdf/`

Use filesystem-safe lowercase filenames with spaces normalized to underscores.

## Done Criteria

Complete the task only when all of the following are true:
- the resume is tailored, truthful, ATS-friendly, and visually close to the base CV
- the cover letter is tailored, truthful, visually close to the base cover letter, and no longer than 3 paragraphs
- no unsupported claims were added
- formatting has been normalized and passes the formatting check
- final DOCX and PDF files exist
- the tracker was updated successfully

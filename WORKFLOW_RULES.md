# Workflow Rules

## Purpose

This workspace is for generating tailored application materials for UK finance internships, placements, and entry-level analyst roles.

Use these rules for every future resume or cover letter generation task in this workspace.

## Approved Source Files

Use the following source hierarchy in order:

1. `templates/base_cv.docx` for resume facts, structure, and formatting reference
2. `templates/base_cover_letter.docx` for cover letter facts, style, structure, and formatting reference
3. `inputs/truth_file.md` for truth constraints
4. Other files in `inputs/` only when they support or confirm existing facts
5. The job information provided directly in chat
6. A saved intake file in `jobs/` only if explicitly requested
7. PDF versions of the base templates only as optional visual references if needed

If sources conflict, prefer the higher-priority source. If a fact is uncertain, omit it.

## Core Rules

- Never invent facts.
- Never invent dates, employers, titles, projects, skills, grades, metrics, responsibilities, or certifications.
- Tailor only by emphasis, bullet selection, ordering, and wording.
- Do not add new factual claims unless they are directly supported by approved source files.
- Do not infer missing achievements or finance knowledge from the job description.
- Do not claim experience with tools, markets, transactions, or technical concepts unless the source files support it.

## Formatting Rules

1. Resume text must always use Times New Roman throughout.
2. Resume body text must always be 9 pt.
3. Resume section headings must always be 10 pt.
4. Resume subheadings must always be 9.5 pt.
5. Company names and employer names in the resume must always be Times New Roman, 9 pt, and bold.
6. Cover letter text must always use Times New Roman throughout.
7. Cover letter main body text must always be 12 pt.
8. Do not introduce mixed fonts, fallback fonts, or size drift.

## Document Integrity Rules

- Do not reconstruct the document layout from scratch.
- Treat the base DOCX templates as locked layout masters.
- Only replace text inside the relevant content sections.
- Preserve date alignment, bullet indentation, and header integrity.
- The final resume must always be one page only.

## Tailoring Process

1. Read the job details.
2. Open the job link when provided and scan the webpage.
3. Understand the company and role.
4. Match the role requirements only to supported evidence.
5. Tailor the resume and cover letter by emphasis, selection, and wording only.
6. Run a final QA pass for truthfulness, formatting, and layout integrity.
7. Create final DOCX and PDF files.
8. Update the tracker only after all final files are successfully created.

## Standard

Every generated document must be truthful, grounded, ATS-friendly, concise, visually close to the base templates, and credible for UK finance recruiting.

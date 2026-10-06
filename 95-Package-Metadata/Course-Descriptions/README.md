# CMU Academic Calendar 2026/27: Course Descriptions Package

This package contains **31 subject files** plus the introductory course-description material. It also contains **723 parsed course records** in JSON and CSV formats.

## Contents

- `00-Course-Descriptions-Index.md`
- `40-Course-Descriptions/00-Introductory-Explanations.md`
- `40-Course-Descriptions/` with one Markdown file per subject field
- `90-Structured-Data/courses.json`
- `90-Structured-Data/courses.csv`
- `Course-Extraction-Report.json`
- `course-descriptions-manifest.json`

## Authority and validation

Markdown files preserve the source section wording and are marked `official_transcription`. Structured fields such as prerequisites, corequisites, exclusions, and clean descriptions were parsed automatically and remain `validation_status: pending`. The complete extracted wording is retained in `description_and_notes` so that no parsed field needs to stand alone as the source of authority.

## Recommended AI use

1. Retrieve by exact course code when one is supplied.
2. Use the subject Markdown file as the citation context.
3. Use JSON fields for filtering, but confirm answers against `description_and_notes` or the Markdown source.
4. Cite the course section ID and calendar year.
5. Do not infer that a course will be offered in a particular term unless the calendar explicitly says so.

# CLEANUP CHECKLIST

## Purpose

This document exists to help future AI assistants identify repository clutter, redundant files, structural inconsistencies, and maintenance issues.

The goal is not to modify research conclusions.

The goal is to improve repository quality and maintainability.

---

## File Structure Audit

Review all repository files.

Tasks:

- Identify unused files.
- Identify temporary files.
- Identify duplicated files.
- Identify obsolete files.
- Identify unclear filenames.
- Identify files that should be renamed.

Special attention:

- delete/
- extensionless files
- duplicate markdown documents

Deliverable:

- File Structure Audit Report

---

## Thesis Audit

Review thesis.md.

Tasks:

- Detect duplicate explanations.
- Detect repeated definitions.
- Detect overlapping sections.
- Detect inconsistent terminology.
- Detect unnecessary repetition.

Examples:

- Layer Structure
- Checkerboard Pattern
- XOR/XNOR explanations
- Gray Code explanations

Deliverable:

- Thesis Cleanup Report

---

## Figure Audit

Review all images and references.

Tasks:

- Verify image numbering.
- Verify figure numbering.
- Verify captions.
- Verify image-to-text correspondence.
- Detect unused images.
- Detect missing images.

Deliverable:

- Figure Audit Report

---

## Repository Consistency Audit

Review:

- README.md
- thesis.md
- AI_HANDOVER.md
- NEXT_STEPS.md

Tasks:

- Verify terminology consistency.
- Verify naming consistency.
- Verify project description consistency.
- Verify repository title consistency.

Questions:

- Is the repository name still appropriate?
- Does the thesis title match the actual contribution?
- Are all documents describing the same project?

Deliverable:

- Consistency Report

---

## Deletion Candidates

Identify files or folders that may be removable.

For each candidate:

1. Explain why it may be unnecessary.
2. Estimate risk of deletion.
3. Recommend:
   - Keep
   - Archive
   - Delete

Do not delete automatically.

Deliverable:

- Deletion Candidate List

---

## Final Review Question

Assume a new researcher encounters this repository for the first time.

Can they understand:

1. What the research is about?
2. What has already been completed?
3. What remains unfinished?
4. Which files are important?

If not, identify obstacles and propose improvements.

---

## Final Deliverables

Produce:

1. File Structure Audit Report
2. Thesis Cleanup Report
3. Figure Audit Report
4. Consistency Report
5. Deletion Candidate List
6. Repository Cleanup Recommendations

Update AI_HANDOVER.md and NEXT_STEPS.md if major structural issues are discovered.

# Using Generative AI Tools - Boon or Bane

REIT6811 Applied Class 6 | Student ID 49536599

This student repository is a fork of the instructor's [KMarshallX/bob_study_allFiles](https://github.com/KMarshallX/bob_study_allFiles) repository. The exercise is to organise the supplied research materials and practise Git version control. The 58 supplied files are empty placeholders, classified by their filenames; they contain no participant data or analysis results.

## 1. Storage and accessibility

Organised storage helps team members find the files they need and avoid working on an old version. Keeping raw data separate from analysis files also makes it easier to check the results. Access should be limited for files containing personal information.

## 2. File storage methods

Consent forms, participant identity records and any identifiable survey responses, interviews, photographs or recordings need restricted access because they can reveal personal or sensitive information. I would store these files in approved university storage and give access only to authorised researchers. This public fork contains only the instructor's empty exercise files.

## 3. Why is a good naming convention important?

Clear file names help the team tell files apart without opening each one ([Harvard Medical School, n.d.](https://datamanagement.hms.harvard.edu/plan-design/file-naming-conventions)). For example, `Survey_Data_Responses_February_2024.xlsx` identifies the material and its date. Consistent names also make searching and sorting easier and help people distinguish versions.

## Project structure

| Folder | Files | Contents |
| --- | ---: | --- |
| `literature_review/` | 8 | Reviews, books, white papers and media articles |
| `quantitative_analysis/` | 16 | Survey questions, CSV and Excel data, Python scripts and survey reports |
| `qualitative_analysis/` | 16 | Interview transcripts and reports, consent forms and qualitative charts |
| `drafts_and_reports/` | 4 | Research proposal drafts and final reports |
| `misc/` | 14 | Information sheets, photographs, workshop material and a poster |

Choose the folder for the material's research purpose, then find the item by its descriptive filename. README.md and .gitignore remain in the repository root.

## File naming and versions

The instructor's filenames have been retained. For future files, use clear topic names, underscores and dates or versions where needed, such as `20260916_survey_responses_v01.csv`. This is a suggested future name; no such data file was created in this exercise.

## Collaboration guidelines

1. Read the folder guide and check which repository and branch you are working in.
2. Fetch and pull the latest changes into your local clone before starting.
3. Create a branch with a useful name, such as `docs/update-folder-guide`.
4. Put new files in the appropriate folder, preserve original materials and review the changes before committing.
5. Commit with a meaningful message, push the branch to your own fork and open a pull request to the agreed project repository.
6. Ask a team member to review the pull request. Resolve comments and any conflicts before merging, then pull the updated main branch.

These are instructions for future collaboration. The optional three-person review and conflict-resolution exercise has not been completed.

## Data access and backup

Keep identifiable research data out of this public fork. Use a separate approved backup and test recovery; Git history alone is not a complete backup plan.

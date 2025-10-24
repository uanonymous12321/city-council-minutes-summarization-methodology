# meeting-minutes-summarization-methodology

Short project overview
This repository contains the annotation manual and example annotated minutes used in the paper "Designing a Structured Methodology for Meeting Minutes Summarization" (LREC 2026). The dataset consists of manually produced, de-identified summaries of municipal executive meeting minutes in European Portuguese, plus the annotation guidance used by annotators.

Full Dataset (summary)
- Size: 120 meeting minutes (administrative term 2021–2024).
- Source: Minutes collected from six municipalities (20 annotated files per municipality).
- Language: European Portuguese.
- Organization:  Each JSON file contains an array of annotated segments (one entry per agenda item / textual subject).
- De-identification: All personal identifiers were manually de-identified prior to release.

Some JSON fields 
- id: internal identifier for the segment
- municipality: municipality name or id
- topic: closed-list topic (e.g., "Environment", "Finance")
- theme: short standardized theme/title of the segment
- text: original (de-identified) textual segment from the minutes
- summary: human-written plain-language summary produced according to the manual

License
This dataset and repository are distributed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license. See the included LICENSE file for details.

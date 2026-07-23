# Make.com Automation

## Overview

I connected the research-triage workflow to Google Sheets using Make.com.

The automation follows this process:

1. Google Sheets detects a new paper row.
2. The paper title and abstract are sent to an AI prompt.
3. The AI produces a structured research summary.
4. The generated draft is written back into the correct spreadsheet row.
5. The output is reviewed manually before being treated as reliable.

## Workflow

Google Sheets → Simple Text Prompt → Google Sheets

## What the automation produces

The output includes:

* Plain-English summary
* Biological problem
* Methods
* Main findings
* Possible drug-discovery relevance
* Limitations and unanswered questions
* Claims requiring human verification

## Testing and improvement

The first test produced an accurate but overly detailed response. I changed the prompt to limit each section to two or three sentences and reduced the verification checklist to three key points.

This made the output more concise and practical for a research tracker.

## Human review

The automated output is treated as a draft rather than a final scientific assessment.

Each summary must be checked against the original abstract because AI can introduce reasonable-sounding assumptions that are not supported by the source.

## Current limitations

* The workflow requires the title and abstract to be entered manually.
* The generated output is stored in one cell.
* Human review is still required.
* The workflow does not assess the quality of the full study.

## Possible next steps

* Automatically collect abstracts from approved sources.
* Split the AI response across separate spreadsheet columns.
* Add a review-status field.
* Send completed summaries to Notion.
* Compare results across different AI models.

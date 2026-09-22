# yourname-genai-8

Your course repository for CoreSmart's Applied GenAI & Agentic AI Engineering course. One repository for the whole course: every graded project on its own branch, merged into `main` by a pull request, and the capstone assembled at the end from the eight milestones you leave behind.

Rename the title above to your name. Then fill in the block below; it is the first thing a reviewer, and later a hiring manager, reads.

## About me

_Two or three sentences: who you are, what you did before this course, and what you want to build after it._

## The seventeen builds

Guided builds live in the course labs repository (`labs-genai-8`) and are never submitted. Graded projects are built here, one folder each, on a branch named after the folder, and submitted as a pull request into `main`. The capstone is assembled in `capstone/` after Module 8.

| # | Build | Kind | Module | Where | Status |
|---|---|---|---|---|---|
| 1 | ReleaseBot | Guided | 1 | labs-genai-8/module-01/releasebot | |
| 2 | MinuteMaker | Graded | 1 | project-02-minutemaker/ | |
| 3 | IntentIQ | Guided | 2 | labs-genai-8/module-02/intentiq | |
| 4 | FeedbackSorter | Graded | 2 | project-04-feedbacksorter/ | |
| 5 | TicketStream | Guided | 3 | labs-genai-8/module-03/ticketstream | |
| 6 | ReviewRouter | Graded | 3 | project-06-reviewrouter/ | |
| 7 | KnowledgeVault | Guided | 4 | labs-genai-8/module-04/knowledgevault | |
| 8 | PaperFinder | Graded | 4 | project-08-paperfinder/ | |
| 9 | CitationRAG | Guided | 5 | labs-genai-8/module-05/citationrag | |
| 10 | DocuRAG | Graded | 5 | project-10-docurag/ | |
| 11 | BreakRAG | Guided | 6 | labs-genai-8/module-06/breakrag | |
| 12 | RAGBench | Graded | 6 | project-12-ragbench/ | |
| 13 | OpsAssist | Guided | 7 | labs-genai-8/module-07/opsassist | |
| 14 | ResearchAgent | Graded | 7 | project-14-researchagent/ | |
| 15 | TriageFlow | Guided | 8 | labs-genai-8/module-08/triageflow | |
| 16 | DeskOrchestrator | Graded | 8 | project-16-deskorchestrator/ | |
| 17 | Capstone | Graded | Capstone | capstone/ | |

Fill the Status column as you go: the pull request link once submitted, the score once it is back.

## How submission works

1. Branch from a fresh `main`: `git checkout -b project-02-minutemaker`.
2. Build inside the matching folder. Fill in every section of that folder's `README_TEMPLATE.md` and rename it `README.md`.
3. Open a pull request into `main` titled exactly `Project 2 · MinuteMaker` (the number and the name). The checklist appears automatically.
4. Paste the pull request URL (it must contain `/pull/`) into the Submit item in the course. Only the state at the moment you paste is reviewed.
5. Merge your own pull request once your scorecard is back. Nobody else needs to approve it.

The Student Submission Guide in Prep Week is the authority on scoring, timing and resubmission.

## What is protected

`.gitignore` already excludes `.env`, virtual environments and caches. Your API key goes in `.env` and nowhere else. If a key is ever committed, rotate it at the provider immediately; removing the commit is not enough.

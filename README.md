# Applied GenAI and Agentic AI Engineering

This repository was generated from the course template. Each folder below holds
one reviewed project. The full brief for every project lives in the LMS; the
README in each folder is only a stub.

## Your reviewed projects

| Module | Project | Folder |
|---|---|---|
| 1 | MinuteMaker | `project-02-minutemaker/` |
| 2 | ReviewRouter | `project-04-reviewrouter/` |
| 3 | DocuRAG | `project-06-docurag/` |
| 4 | RerankLab | `project-08-reranklab/` |
| 5 | RAGBench | `project-10-ragbench/` |
| 6 | ResearchAgent | `project-12-researchagent/` |
| 7 | DeployGuard | `project-14-deployguard/` |
| 8 | Capstone | `capstone/` |

### Why the folders skip numbers

Every module has two builds. The odd-numbered ones are guided labs, which you
build alongside a walkthrough and which nobody scores. They live in the labs
repository, not here. The even-numbered ones are the reviewed projects, and
those are the folders above.

Seven guided labs, seven reviewed projects and the capstone make fifteen builds
by the end of the course.

## Getting started

1. Copy `.env.example` to `.env` and fill in `LLM_BASE_URL`, `LLM_API_KEY` and
   `LLM_MODEL` for the provider you chose in the setup page.
2. Never commit `.env`. It is already listed in `.gitignore`.
3. Work on a branch named after the project, for example
   `project-02-minutemaker`.
4. Open a pull request into `main` and complete the checklist in the PR
   template before requesting review.
5. Paste the pull request link into the LMS. That is the submission. A pull
   request left open on GitHub is not one.

Do not edit anything inside a `data/` folder. Those files are what your build
is tested against.

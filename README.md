

Repo structure:
/data/                # keep raw data OUT of the repo; store READMEs or sample rows only
/notebooks/           # EDA & modeling notebooks
/src/                 # reusable Python modules/scripts (optional for now)
/reports/             # figures, exported tables, PDFs
/docs/                # project docs (proposal, sprint memos, etc.)
README.md             # see template below
.gitignore

# Criminal Justice Project - <Team 1A>

**Overview:** How can we use info about the victim and what they experienced, to predict what potential crime would occur to them in the future?

## Team
- Matthew Otabor (Developer)
- Unni Prasad (Developer)
- Tanmay Ashok (Researcher)

## Repo Structure


/data/ (raw data NOT stored here)
/notebooks/
/src/
/reports/
/docs/
README.md
.gitignore


## How to Run
- Python: 3.10+ (recommended)
- Install deps: `pip install -r requirements.txt`  *(optional)*
- Open notebooks in `/notebooks/`

## Data Access
Raw data is stored in <shared drive/path>. To reproduce EDA:
1) Obtain dataset from <link or contact>.
2) Place files under your local `data/` (excluded from Git).
3) Run notebooks in `/notebooks/`.

## Milestones & Issues
We track Sprint tasks under the “Sprint 2 - Data Prep & EDA” milestone and Issues in GitHub.
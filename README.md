Built an explainable candidate ranking platform: create jobs, upload resumes (PDF/TXT) or add candidates manually, then run Claude Sonnet 4.5 (via Emergent Universal LLM key) to score each candidate on skills / experience / education / culture fit with rationales, strengths and gaps.
Features: Swiss-brutalist dashboard (Cabinet Grotesk + IBM Plex), jobs CRUD, PDF parsing (pypdf), leaderboard with expandable AI reasoning, side-by-side comparison view, CSV shortlist export.
Backend: FastAPI + MongoDB, 11 /api/* endpoints. Frontend: React Router 7 with 5 routes and dense data-testid coverage.
Testing agent: 15/15 backend tests passing, 100% of frontend flows verified. No bugs found.

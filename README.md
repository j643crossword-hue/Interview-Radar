# Interview Radar

Interview Radar is an interactive workspace for early-career AI professionals to compare roles, inspect supporting evidence, identify skill gaps, and turn research into a weekly preparation plan.

## Live demo

[Open Interview Radar](https://pluck-radial-15587032.figma.site/)

## Product areas

- **Radar Overview** — compare target roles, fit signals, evidence, gaps, and deadlines.
- **Role Clusters** — inspect related roles and shared competency patterns.
- **Evidence Library** — preserve the sources behind career and interview claims.
- **Gap Review Queue** — review uncertain AI-generated claims with a human in the loop.
- **Weekly Battle Plan** — turn gaps into concrete preparation work.
- **Evaluation & Trace** — expose model confidence and provenance instead of hiding it.

## Why this project exists

Job research is usually fragmented across job descriptions, interview reports, community posts, and personal notes. AI can summarize that material quickly, but its conclusions are difficult to trust without traceable evidence and human review. Interview Radar explores a workflow where AI accelerates synthesis while the user retains judgment.

## Run locally

```bash
npm install
npm run dev
```

Create a production build with:

```bash
npm run build
```

## Current status

This repository contains the deployable front-end prototype published from Figma Make. Its sample data is illustrative; production data ingestion and model-backed evaluation are planned next.

## Built with

- React
- Vite
- Figma Make

## License

[MIT](./LICENSE)

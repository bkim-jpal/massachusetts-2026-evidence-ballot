# The Evidence Ballot — Massachusetts 2026

A public, independent, nonpartisan election guide: https://massachusetts-2026-evidence-ballot.vercel.app

This repository contains the public web application's source code. The website is an educational tool, not an official ballot or voting service.

## Data and methodology
- Massachusetts 2026 candidate roster: Secretary of the Commonwealth, official list retrieved November 2, 2026 (validated against 160 House, 40 Senate and nine congressional district names).
- Legislative boundary queries: MassGIS ArcGIS services (2021 district lines).
- Town, ward, precinct queries: Massachusetts 2022 ward/precinct geometry (ArcGIS service); split precincts require location verification.
- Ballot questions: 2026 official voter guide and cited policy research, with research design and external-validity cautions.
- Prediction markets: Kalshi read-only market prices when source available; not endorsements or forecasts by this application.

## Privacy
Practice ballot selections are kept in browser memory and are never intentionally transmitted. No vote-collection endpoint or account system is implemented. Ordinary infrastructure logs may be retained by the hosting provider. This repository intentionally contains **no secrets**.

## Contributions and publishing
Everyone can inspect or fork the public repository. Only users with write permissions can push here. Community members may propose changes using pull requests, which should be reviewed and tested before acceptance. The Vercel production deployment is managed separately; this repository is not automatically authorized to deploy outside contributions.

Official sources: https://www.sec.state.ma.us/divisions/elections/research-and-statistics/2026-state-election-candidates.htm ; https://www.sec.state.ma.us/WhereDoIVoteMA/WhereDoIVote/ .

**Coverage limitation:** The map automatically resolves congressional/state House/state Senate races. County, municipal, Governor's Council and other precinct-specific contests may require official sample-ballot confirmation.

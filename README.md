# media-bias-monitor
An automation tool used to check propaganda levels of articles, and bot responses on major Social Media outlets.


Open Media Analysis & Bias Monitor

A non-commercial, open-source toolkit for analysing UK media bias, detecting coordinated influence patterns in social-media comments, and presenting transparent findings through a public dashboard.

This project combines article analysis, sentiment scoring, outlet bias data, and bot-likelihood detection to provide a clear, accessible view of the narratives shaping online discourse. All findings and tools are made available for public, educational, research, and non-commercial use only, under the terms of the PolyForm Noncommercial License 1.0.0.

Purpose

This project aims to provide a transparent, verifiable, and openly accessible system that helps users identify:

Media framing and bias across major UK outlets

Emotional, political, and narrative tone in news articles

Potential bot activity or coordinated influence in comment sections

Shifts in public sentiment around major stories

Automated summaries, charts, and insight dashboards

The goal is clarity, transparency, and public understanding of online information influence.

Features

Article ingestion from public news sources and RSS feeds

Outlet bias lookup via public APIs (AllSides, MBFC, etc.)

NLP-based sentiment, tone, framing, and keyword analysis

Social-media comment retrieval (Reddit, YouTube, X/Twitter depending on API availability)

Bot-likelihood and behaviour scoring using recognised research tools

Integrated “Bias Index” and “Bot Influence Score”

Front-end dashboard hosted on GitHub Pages

Optional automated reporting to a dedicated social-media account

All analysis methods follow strict legal and ethical OSINT guidelines.

Repository Structure
/frontend/        → Dashboard UI (static site for GitHub Pages)
/data/            → JSON output data from analysis scripts
/scripts/         → Optional public tools for ingestion, scoring, and processing
/docs/            → Methodology, criteria, API references, and explainer content

Non-Commercial Licensing

This project is licensed under the PolyForm Noncommercial License 1.0.0, which allows:

✔ Public use
✔ Personal use
✔ Educational use
✔ Research use
✔ Modification and redistribution for non-commercial purposes

and forbids:

✖ Selling the software
✖ Selling services built on the software
✖ Packaging or redistributing it commercially
✖ Using any part of it in commercial tools, dashboards, or products

Anyone wishing to use this project for commercial purposes must contact the author to request a commercial licence.

See the LICENSE file for full terms.

Requirements (Development)

Python 3.10+

Node.js (optional, for front-end tooling)

API keys for chosen integrations:

News APIs

Reddit / YouTube APIs

OpenAI / Claude for NLP analysis

Bot detection services (e.g., Botometer)

GitHub Pages for hosting the dashboard

Roadmap

 Establish core front-end dashboard layout

 Implement article ingestion pipeline

 Integrate outlet bias and credibility scoring

 Add sentiment + tone analysis

 Implement comment ingestion for Reddit/YouTube

 Add bot-likelihood scoring module

 Publish first public dashboard iteration

 Add weekly summary automation

 Build exportable public datasets

 Optional: Develop API endpoints for external use

Ethical & Legal Standards

This project strictly adheres to:

UK Computer Misuse Act 1990

Platform Terms of Service

Ethical OSINT practices

Public-data principles

Non-commercial licensing protections

No private data, unauthorised access, or scraping of restricted endpoints is used.

Contributions

Contributions for non-commercial use are welcome.
Please open an issue or submit a pull request.

If you are unsure whether your intended use counts as commercial, open a discussion first.

Commercial Use

If you wish to use, integrate, or distribute this project in any commercial product or service, please contact the project owner to negotiate a commercial licence.

License

This repository is distributed under the PolyForm Noncommercial License 1.0.0.
See the LICENSE file for full details.

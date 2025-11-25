<div align="center">
  <h1>Open Media Analysis & Bias Monitor</h1>
  <p>A non-commercial, open-source toolkit for analysing UK media bias, article framing, sentiment trends, and coordinated influence patterns in social-media comments.</p>
</div>

<hr>

<h2>Purpose</h2>
<p>This project provides a transparent, verifiable system for identifying:</p>

<ul>
  <li>Media bias and editorial slant across UK outlets</li>
  <li>Emotional tone, sentiment, and framing in news articles</li>
  <li>Potential bot activity or coordinated influence in comment sections</li>
  <li>Shifts in public response to news events</li>
  <li>Narrative trends and polarisation indicators</li>
</ul>

<p>All findings are presented through a public dashboard.</p>

<hr>

<h2>Key Features</h2>

<ul>
  <li>Article ingestion via RSS feeds and news APIs</li>
  <li>Outlet bias lookups using existing public databases</li>
  <li>NLP analysis for sentiment, tone, framing, and keyword intensity</li>
  <li>Social-media comment retrieval (Reddit, YouTube, and optional X/Twitter if allowed)</li>
  <li>Bot-likelihood scoring using recognised research tools</li>
  <li>Combined "Bias Index" and "Bot Influence Score"</li>
  <li>Dashboard hosted using GitHub Pages</li>
  <li>Optional automated reporting to a dedicated social account</li>
</ul>

<hr>

<h2>Repository Structure</h2>

<pre>
/frontend/        - Static dashboard UI for GitHub Pages
/data/            - JSON output from analysis pipelines
/scripts/         - Optional utilities for ingestion and scoring
/docs/            - Methodology, criteria, API references
</pre>

<hr>

<h2>Licensing (Non-Commercial)</h2>
<p>This project is licensed under the <strong>PolyForm Noncommercial License 1.0.0</strong>.</p>

<p>Allowed under this licence:</p>
<ul>
  <li>Personal use</li>
  <li>Educational use</li>
  <li>Academic research</li>
  <li>Non-profit use</li>
  <li>Non-commercial redistribution and modification</li>
</ul>

<p>Not allowed without explicit permission:</p>
<ul>
  <li>Selling this software</li>
  <li>Selling services or products built using it</li>
  <li>Using any part of it in commercial dashboards or tools</li>
  <li>Packaging it into commercial offerings</li>
</ul>

<p>A commercial licence is required for any commercial use. See the LICENSE file for details.</p>

<hr>

<h2>Development Requirements</h2>

<ul>
  <li>Python 3.10 or later</li>
  <li>Node.js (optional, for frontend tooling)</li>
  <li>API keys for relevant integrations:
    <ul>
      <li>News APIs</li>
      <li>Reddit API</li>
      <li>YouTube API</li>
      <li>Optional X/Twitter API</li>
      <li>OpenAI or Claude for NLP analysis</li>
      <li>Bot detection services</li>
    </ul>
  </li>
  <li>GitHub Pages for hosting</li>
</ul>

<hr>

<h2>Roadmap</h2>

<ul>
  <li>Frontend dashboard layout</li>
  <li>Article ingestion pipeline</li>
  <li>Bias and credibility scoring module</li>
  <li>Sentiment and framing analysis</li>
  <li>Reddit and YouTube comment ingestion</li>
  <li>Bot-likelihood scoring system</li>
  <li>Public dashboard release</li>
  <li>Automated summary generation</li>
  <li>Public dataset export tools</li>
  <li>Optional external API endpoints</li>
</ul>

<hr>

<h2>Ethical and Legal Standards</h2>
<p>This project complies with:</p>

<ul>
  <li>UK Computer Misuse Act 1990</li>
  <li>Platform Terms of Service</li>
  <li>Ethical OSINT practices</li>
  <li>Public-data processing standards</li>
  <li>Non-commercial licensing restrictions</li>
</ul>

<p>No private data or unauthorised access is used.</p>

<hr>

<h2>Contributions</h2>
<p>Contributions for non-commercial use are welcome. Please open a pull request or an issue.  
If unsure whether your intended use qualifies as non-commercial, start a discussion first.</p>

<hr>

<h2>Commercial Use</h2>
<p>Commercial use requires a paid commercial licence.  
Contact the project owner for details.</p>

<hr>

<h2>License</h2>
<p>This project is licensed under the <strong>PolyForm Noncommercial License 1.0.0</strong>.  
See the LICENSE file for all legal terms.</p>

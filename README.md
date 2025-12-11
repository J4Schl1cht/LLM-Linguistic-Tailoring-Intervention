<h1>Linguistic Tailoring Intervention – Study 4 Analysis</h1>

<p>
  This repository contains the analysis workflow for the <strong>LLM-based Linguistic Tailoring project</strong>, 
  which tested whether <strong>AI-tailored persuasive messages</strong> influence adolescents’ 
  plant-based lunch choices.
</p>

<hr>

<h2>Study Summary</h2>
<p>
  The intervention compared three conditions:
</p>
<ul>
  <li>No intervention</li>
  <li>Non-tailored messages</li>
  <li>AI-tailored (linguistically tailored) messages</li>
</ul>

<p>
  <strong>Primary outcome:</strong> Plant-based lunch choice (yes / no).<br>
  <strong>Secondary outcomes:</strong> Message relevance, personalization, linguistic similarity, liking, shareability, source liking, and source trust.
</p>

<h2>Hypotheses</h2>
<ul>
  <li><strong>H1:</strong> Receiving any intervention message (vs. no message) increases plant-based lunch choices.</li>
  <li><strong>H2:</strong> Tailored messages (vs. non-tailored messages) increase message responses (e.g. message liking, relevance).</li>
  <li><strong>H3:</strong> Tailored messages improve message and source responses (e.g., source liking, source trust).</li>
</ul>

<h2>Statistical Overview</h2>
<ul>
  <li><strong>IVs:</strong> Intervention contrast, tailoring contrast, time (day).</li>
  <li><strong>DV:</strong> Daily plant-based lunch choice (binary).</li>
  <li><strong>Models:</strong> Mixed-effects logistic models (frequentist and Bayesian).</li>
  <li><strong>Random effects:</strong> Random intercepts for participants.</li>
</ul>

<h2>Repository Structure</h2>
<pre>
notebooks/
   01_preprocessing_frequentist.ipynb
   02_bayesian_analysis.ipynb
   03_exploratory_analysis.ipynb
src/
   utils.py
   plotting.py
models/      (Bayesian traces)
figures/     (descriptive plots & diagnostics)
README.md
</pre>

<h2>Data Availability</h2>
<p>
  🔒 Data Availability
<p>
  Fully anonymized data required to reproduce the analyses are included directly in this repository under 
  <code>/data/</code>. Additional materials (e.g., transcripts, coding files, or session documents) 
  may be made available upon reasonable request to the corresponding author.
</p>

📬 Contact
For questions about the project:
Jonas Schlicht — j.schlicht@t-online.de
  </a>
</p>

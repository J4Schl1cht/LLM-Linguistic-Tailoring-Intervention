<h1>Linguistic Tailoring Intervention – Study 4 Analysis</h1>

<p>
  This repository contains the full analysis workflow for the 
  <strong>LLM-based Linguistic Tailoring project</strong>, which tested whether 
  <strong>AI-tailored persuasive messages</strong> influence adolescents’ 
  plant-based lunch choices in a real-world field experiment.
</p>

<hr>

<h2>Study Summary</h2>
<p>The intervention compared three conditions:</p>
<ul>
  <li>No intervention</li>
  <li>Non-tailored messages</li>
  <li>AI-tailored (linguistically tailored) messages</li>
</ul>

<p>
  <strong>Primary outcome:</strong> Plant-based lunch choice (yes/no).<br>
  <strong>Secondary outcomes:</strong> Message relevance, personalization, linguistic similarity, liking, shareability, source liking, and source trust.
</p>

<h2>Hypotheses</h2>
<ul>
  <li><strong>H1:</strong> Receiving any intervention message (vs. none) increases plant-based lunch choices.</li>
  <li><strong>H2:</strong> Tailored messages (vs. non-tailored) improve message responses (e.g., relevance, liking).</li>
  <li><strong>H3:</strong> Tailored messages enhance source responses (e.g., trust, perceived similarity).</li>
</ul>

<h2>Statistical Overview</h2>
<ul>
  <li><strong>Independent variables:</strong> Intervention contrast, tailoring contrast, time (day)</li>
  <li><strong>Dependent variable:</strong> Daily plant-based lunch choice</li>
  <li><strong>Models:</strong> Bayesian mixed-effects logistic regression</li>
  <li><strong>Random effects:</strong> Participant-level intercepts</li>
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
data/        (anonymized dataset for replication)
README.md
</pre>

<h2>Data Availability</h2>
<p>
  Fully anonymized datasets required to replicate the analyses are included in <code>/data/</code>. 
  Additional materials (e.g., transcripts, coding files, session guides) can be provided upon reasonable request.
</p>

<h2>📬 Contact</h2>
<p>
  For questions about the project:<br>
  <strong>Jonas Schlicht</strong> — <a href="mailto:j.schlicht@t-online.de">j.schlicht@t-online.de</a>
</p>

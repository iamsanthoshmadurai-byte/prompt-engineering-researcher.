# Prompt Documentation — AI Research \& Knowledge Assistant

Prepared by: \[Your Name]  
Topic: AI-Assisted Research \& Knowledge Verification Architectures

## 1\. Generated Knowledge Prompt

Generate a factual summary detailing the core architecture, scalability limits, setup complexity, and cost structures of:

* Kubernetes
* Docker Swarm
* AWS Fargate

Focus on raw specifications, official documentation facts, and industry statistics. Do not write a comparison or recommendation yet. Separate confirmed facts from uncertain or context-dependent claims. Include source URLs for every important technical limit or pricing claim. Do not invent a maximum limit if official documentation does not specify one.

## 2\. ERA Research Prompt

\[EXPECTATION]: Write a detailed comparison report comparing Kubernetes, Docker Swarm, and AWS Fargate. Use H2 headers: Introduction, Technology Overviews, Detailed Comparison, and Final Verdict. Do not write a summary table yet. Clearly label judgments as judgments and explain context-dependent trade-offs.

\[ROLE]: Act as a Lead Systems Architect.

\[ACTION]: Write the report using the verified background facts pasted below. Compare architecture, scalability, setup complexity, operational overhead, and cost model. Recommend the best option for a fast-growing startup prioritizing delivery speed over infrastructure scaling. Do not invent unsupported version limits, prices, or guarantees.

=== BACKGROUND FACTS ===
\[Paste the Generated Knowledge fact sheet here, with source URLs.]
===

## 3\. CoVe Question Formulation Prompt

Read the baseline draft below. Formulate exactly four specific verification questions that can be answered using official developer documentation. Focus on claims, numbers, version limits, operational dependencies, and pricing rules. Do not answer the questions yet.

\[BASELINE DRAFT]:
\[Paste baseline\_draft.txt here.]

## 4\. CoVe Question Answering Prompt

Answer each of the following four verification questions one by one. Rely on official developer documentation and the official AWS pricing page. Provide a source URL for each answer. If a limit or price is not stated by the source, explicitly say that it was not found; do not guess.

\[FOUR QUESTIONS]:
\[Paste the four questions from the previous step.]

## 5\. CoVe Correction Prompt

Review the original baseline draft. Rewrite the report incorporating the verified corrections below. Replace every conflicting or unsupported claim with the verified answer. Do not preserve old unverified statistics. Keep version-specific limitations and pricing caveats. Include source links for important claims.

\[BASELINE DRAFT]:
\[Paste baseline\_draft.txt here.]

\[VERIFIED CORRECTIONS]:
\[Paste the verified answers here.]

## 6\. Assumption Audit Prompt

Analyze the finalized technology comparison below. Identify exactly three hidden assumptions. For each, explain how it could introduce bias and how to reduce that bias. Consider total cost, future workload complexity, team skills, portability, and infrastructure control.

\[FINALIZED REPORT]:
\[Paste the corrected report here.]

## 7\. Comparison Matrix Prompt

Create a Markdown table comparing Kubernetes, Docker Swarm, and AWS Fargate across:

* Technology
* Scalability (High/Med/Low)
* Setup Complexity (High/Med/Low)
* Operational Overhead (High/Med/Low)
* Cost Model

Explain that ratings are relative judgments rather than official vendor scores. Do not label open-source software as “free to operate.”

## 8\. Executive Summary Prompt

Write a 150-word executive summary synthesizing the comparison findings. Recommend the best technology for a fast-growing startup prioritizing speed over infrastructure scaling. Mention the conditions that could change the recommendation.

## 9\. CoVe run log

1. Draft created from background fact sheet.
2. Four verification questions formulated.
3. Official Kubernetes, Docker, and AWS documentation checked.
4. Corrected draft updated to reflect version-specific scale guidance, built-in Swarm mode, no unsupported universal Swarm node maximum, and usage-based Fargate pricing.
5. Three latent assumptions documented.
6. Comparison matrix and executive summary created.


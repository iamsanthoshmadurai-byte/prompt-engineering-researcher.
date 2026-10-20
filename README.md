# AI Research \& Knowledge Assistant

**Topic:** AI-Assisted Research \& Knowledge Verification Architectures  
**Prepared by:** \[Your Name]

## Objective

Compare Kubernetes, Docker Swarm, and AWS Fargate using Generated Knowledge Prompting, the ERA framework, and a four-question Chain of Verification (CoVe) process.

## Project files

* `research\_report.md` — background facts, verified comparison, CoVe questions and answers, correction log, assumption audit, matrix, and references.
* `executive\_summary.md` — executive summary.
* `comparison\_matrix.md` — comparison matrix and rating notes.
* `prompt\_documentation.md` — prompt templates and CoVe run log.
* `baseline\_draft.txt` — initial unverified draft template for the demonstration.
* `loom\_walkthrough\_script.md` — suggested 3–4 minute screen-recording script.

## Main conclusion

For a fast-growing startup prioritizing delivery speed over infrastructure scaling, AWS Fargate is a conditional starting recommendation if the workload fits its constraints and the team uses AWS. Validate costs, quotas, and workload needs before committing.

## Primary sources

* Kubernetes large clusters: https://kubernetes.io/docs/setup/best-practices/cluster-large/
* Docker Swarm mode: https://docs.docker.com/engine/swarm/
* Docker Swarm key concepts: https://docs.docker.com/engine/swarm/key-concepts/
* Docker nodes: https://docs.docker.com/engine/swarm/how-swarm-mode-works/nodes/
* AWS Fargate pricing: https://aws.amazon.com/fargate/pricing/

## GitHub upload

1. Replace `\[Your Name]` with your name.
2. Review the files and make any edits required by your instructor.
3. Create a public repository named `prompt-engineering-researcher` on GitHub.
4. In a terminal inside this folder, run:

```bash
git init
git add .
git commit -m "Initialize Prompt Engineering Research Assistant project"
git branch -M main
git remote add origin https://github.com/YOUR\_USERNAME/prompt-engineering-researcher.git
git push -u origin main
```

Replace `YOUR\_USERNAME` with your GitHub username. Do not share passwords or access tokens in the repository.


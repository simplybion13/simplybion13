# Product Manager by Trade, AI Builder by Curiosity

**AI Agents • LLMs • Evaluations • Experimentation**

I'm a product manager learning to build AI systems, not just define products that use them.

My goal is to develop the technical judgment to design, prototype, evaluate, and improve AI applications myself. I'm doing that through hands-on projects, testing assumptions, examining failures, and documenting what I learn.

I bring a product lens to the engineering: **Does it solve the right problem? How do we know it works? What does reliability cost?**

### Currently building

**[SRE Agent Evals](https://github.com/simplybion13/sre-agent-evals)**

A synthetic CI/CD build-pool support agent built with the OpenAI Agents SDK. I use it to explore how evidence gathering, agent orchestration, model selection, and evaluation design affect reliability and cost.

A few things I'm learning from it:
- **Architecture matters.** Moving diagnostic evidence collection into a deterministic, read-only controller improved measured reliability on the same 50 synthetic development tickets.
- **Evaluation is a product decision.** Separating strict graders from an LLM judge helps expose disagreements between expected actions and useful customer responses.
- **Cost and quality belong together.** On the same V4 synthetic benchmark, a lower-cost current model matched the higher-cost candidate's observed strict solve rate at substantially lower estimated inference cost.

These are results from a small, repeatedly studied synthetic dataset, not proof of production readiness or general model superiority. The project includes the regressions, tradeoffs, and limitations, not just the wins.

### What I'm exploring

- **Agents and orchestration:** Tool use, evidence boundaries, and reliable workflows
- **LLMs:** Model behavior, structured outputs, capabilities, and tradeoffs
- **Evals:** Ground truth, grading, failure analysis, and judge calibration
- **Experimentation:** Building hypotheses, measuring outcomes, and iterating responsibly

### How I learn

**Build. Evaluate. Learn. Improve.**

I use AI coding tools to accelerate implementation, then work to understand and defend the design decisions, tests, and tradeoffs. This GitHub is a record of that process. The aim is to get better at building AI, one experiment at a time.

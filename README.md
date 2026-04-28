<div align="center">

## Hi! I'm Abhishek P, alias [abhiigatty](https://abhiigatty.com). Human in Tech. 👋

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=111111&center=true&vCenter=true&width=820&lines=Backend+engineer+who+loves+to+build+and+scale.;AI+forward.+Product+minded.+Always+shipping.;Orchestrating+a+swarm+of+agents.+Moving+fast%2C+together.;From+spec+to+scale%2C+with+evals+all+the+way." alt="typing"/>

</div>

I'm a senior backend engineer who spends most days writing specs, skills, and evals, and managing a swarm of agents. Some are Claude. Some live in Cursor. Some live on OpenRouter. They do the typing. I do the thinking, the taste, and the evals.

## What I'm Doing Right Now

* Working at **[@asymmetric-labs-ai](https://github.com/asymmetric-labs-ai)**.
* Building side projects with builders I trust.
* Part of the **[Sahyadri Open Source Community](https://github.com/so-sc)**.

## The Swarm I Work With

```mermaid
flowchart LR
    Me([me])
    subgraph Agents[the swarm]
      C[Claude<br/>spec + code]
      K[Cursor<br/>in editor]
      O[OpenRouter<br/>specialist models]
    end
    Spec[spec + skills + evals]
    Diff[diff]
    Eval[eval suite]
    Ship[ship]

    Me --> Spec
    Spec --> C
    Spec --> K
    Spec --> O
    C --> Diff
    K --> Diff
    O --> Diff
    Diff --> Me
    Me --> Eval
    Eval --> Ship

    classDef me fill:#111111,stroke:#000,stroke-width:2px,color:#ffffff
    classDef agent fill:#ffffff,stroke:#111111,stroke-width:1.5px,color:#111111
    classDef artifact fill:#f5f5f5,stroke:#111111,stroke-width:1px,color:#111111
    classDef ship fill:#111111,stroke:#000,color:#ffffff
    class Me me
    class C,K,O agent
    class Spec,Diff,Eval artifact
    class Ship ship
```

The agents are fast. The eval is what makes me trust the diff. The taste is what decides if it ships at all.

A few things I've learned.

* **Evals are the new tests.** Unit tests check that a function does what you wrote. Evals check that the system does what you *meant*.
* **Taste is the bottleneck.** Anyone can generate a thousand lines of code now. Far fewer people can tell you which fifty lines are worth keeping.
* **Specs beat prompts.** A good spec survives a model swap. A clever prompt usually doesn't.

## The Toolkit

**Agents.** Claude · Claude Code · Cursor · OpenRouter · OpenAI

**Backend.** Python, Go, Django, FastAPI · Postgres, Redis, DynamoDB · RabbitMQ, Celery, AsyncIO

**Infra.** AWS, Docker, Kubernetes, Jenkins, ArgoCD, Cloudflare, Prometheus, Elasticsearch

## What I Worked On Before This

| company | role | the gist |
|---|---|---|
| **InstaViewAI** | Sr. Backend Engineer | AI interview infra, where the model meets the user |
| **UniCourt** | SDE | Big data, search, court records, PACER |
| **Velotio** | SDE | Consulting across backend, mobile, hardware, cloud |
| **Kami Vision** | SDE | Computer vision adjacent backend, IoT, video pipelines |

The thread through all of it. Data heavy backends, distributed systems, and a healthy paranoia about correctness.

## A Small Example Of What I Mean By "Evals Over Vibes"

Picking a model based on a 5 prompt spot check feels good and tells you almost nothing. A workflow I actually run.

```bash
# 1. write 30 to 50 real inputs from production logs
# 2. write a grader, LLM as judge or rule based
# 3. run the candidate change against the eval suite
# 4. compare pass rate, p50 and p95 latency, cost per run
# 5. only then decide
```

It's slower than vibing. It also stops me shipping regressions I'd otherwise miss until a user finds them.

The tradeoff. Writing the eval set is the most annoying part of the job. I keep doing it because every time I skip it, I regret it within a week.

---

<div align="center">

[abhiigatty.com](https://www.abhiigatty.com) · [𝕏](https://twitter.com/abhiigatty_) · [GitHub](https://github.com/AbhiiGatty) · [LinkedIn](https://www.linkedin.com/in/abhiigatty) · [Instagram](https://www.instagram.com/abhiigatty) · [Email](mailto:abhiigatty@gmail.com)

</div>

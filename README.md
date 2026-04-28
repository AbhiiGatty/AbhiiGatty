<div align="center">

# Abhishek P

### Human in Tech

**Fast by design. Detailed by obsession.**

I build reliable backend systems, full-stack products, and AI enabled tools.

<br/>

<a href="https://www.abhiigatty.com">abhiigatty.com</a>
·
<a href="https://twitter.com/abhiigatty_">𝕏 @abhiigatty_</a>
·
<a href="https://github.com/AbhiiGatty">GitHub</a>
·
<a href="https://www.linkedin.com/in/abhiigatty">LinkedIn</a>
·
<a href="https://www.instagram.com/abhiigatty">Instagram</a>
·
<a href="mailto:abhiigatty@gmail.com">Email</a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=111111&center=true&vCenter=true&width=720&lines=Senior+backend+engineer.+Now+a+product+person.;I+write+specs%2C+skills%2C+and+evals.;The+agents+do+the+typing.+I+do+the+thinking.;Evals+%3E+vibes." alt="typing"/>

</div>

---

## hi, I'm Abhishek 👋

I'm a senior backend engineer who loves products, infrastructure, and solving puzzles. These days most of my day goes into writing specs, skills, and evals, and managing a swarm of agents. Some are Claude. Some live in Cursor. Some live on OpenRouter. They do the typing. I do the thinking.

I sit in the loop. I have opinions about taste. I trust evals more than vibes.

## what I'm doing right now

* Working at **[@asymmetric-labs-ai](https://github.com/asymmetric-labs-ai)**.
* Part of the **[Sahyadri Open Source Community (so-sc)](https://github.com/so-sc)**.
* Living in Bangalore, India. UTC +05:30.

## the swarm I work with

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

A few things I've learned from doing it this way for a while.

* **Evals are the new tests.** Unit tests check that a function does what you wrote. Evals check that the system does what you *meant*. If you can't measure it, you can't trust it, and you definitely can't ship it.
* **Backend reflexes still earn their keep.** Knowing how a queue, a cache, or a slow query actually behaves is the fastest way to spot when a model is confidently wrong.
* **Taste is the bottleneck.** Anyone can generate a thousand lines of code now. Far fewer people can tell you which fifty lines are worth keeping. That's the job.
* **Specs beat prompts.** A good spec survives a model swap. A clever prompt usually doesn't.

## the toolkit I actually pull from

**agents and AI**
Claude · Claude Code · Cursor · OpenRouter · OpenAI

**languages and frameworks**
Python · Go · Django · Flask · FastAPI · Gin · AsyncIO

**databases and caching**
PostgreSQL · MySQL · SQLite · Redis · AWS DynamoDB · PgBouncer

**queues, async, and realtime**
RabbitMQ · Celery · NGINX · uWSGI · Gunicorn · WebRTC · MQTT

**cloud and infra**
AWS (EC2, Lambda, S3, IoT Core, Kinesis, SNS, SES, SQS) · DigitalOcean · Docker · Kubernetes · Jenkins · ArgoCD · Rancher · Cloudflare · Prometheus · Kibana · Elasticsearch

**auth, comms, and SaaS I've shipped against**
Keycloak · OAuth 2.0 · OpenID · Twilio · SendGrid · Mailgun · Braze · Zendesk · Swagger · Postman

**version control and shell**
Git · GitHub · GitLab · Linux · Bash · Vim · VS Code

## where I split my time these days

```mermaid
%%{init: {"pie": {"textPosition": 0.75}, "themeVariables": {"pie1": "#111111", "pie2": "#333333", "pie3": "#666666", "pie4": "#999999", "pie5": "#cccccc", "pieTitleTextSize": "16px", "pieSectionTextSize": "13px", "pieSectionTextColor": "#ffffff", "pieOuterStrokeColor": "#000000"}}}%%
pie showData
    title where the hours actually go
    "writing specs and skills" : 35
    "reading agent diffs" : 25
    "writing and running evals" : 20
    "product thinking" : 15
    "still writing some code by hand" : 5
```

## what I worked on before this

| company | role | the gist |
|---|---|---|
| **InstaViewAI** | Sr. Backend Engineer | AI interview infra, the part where the model meets the user |
| **UniCourt** | SDE | Big data, search, court records, PACER, law-as-a-service |
| **Velotio** | SDE | Consulting across backend, mobile, hardware, and cloud |
| **Kami Vision** | SDE | Computer vision adjacent backend, IoT, video pipelines |

The thread through all of it. Data heavy backends, distributed systems, and a healthy paranoia about correctness. Domain-driven design, SOC 2, OEM portals, subscription systems, and a lot of glue between hardware, cloud, and the user.

## things I care about

| | | |
|---|---|---|
| **Open source** | **Big data and distributed systems** | **InfoSec and pentesting** |
| The license isn't the part that matters. The people who show up are. | My old habitat. Still the lens I reach for first. | Paranoid by default. It's a feature. |

**AI product craft.** The interesting gap right now is between "the demo works" and "users trust it every day." Most of that gap is evals, taste, and a lot of patient iteration.

## a small example of what I mean by "evals over vibes"

Picking a model based on a 5 prompt spot check feels good and tells you almost nothing. A workflow I actually run.

```bash
# 1. write 30 to 50 real inputs from production logs
# 2. write a grader, LLM as judge or rule based
# 3. run the candidate change against the eval suite
# 4. compare pass rate, p50 and p95 latency, cost per run
# 5. only then decide
```

A made-up but representative comparison from a recent model swap.

```mermaid
%%{init: {"themeVariables": {"xyChart": {"backgroundColor": "transparent", "titleColor": "#111111", "xAxisLabelColor": "#111111", "yAxisLabelColor": "#111111", "xAxisTitleColor": "#111111", "yAxisTitleColor": "#111111", "plotColorPalette": "#111111, #999999"}}}}%%
xychart-beta
    title "candidate vs incumbent on the same eval set"
    x-axis ["pass rate %", "p50 ms", "p95 ms", "cost / 1k runs $"]
    y-axis "value" 0 --> 100
    bar [62, 38, 71, 44]
    bar [78, 22, 49, 28]
```

Solid bar is the candidate. Light bar is the incumbent.

It's slower than vibing. It also stops me shipping regressions I'd otherwise miss until a user finds them.

The tradeoff. Writing the eval set is the most annoying part of the job. I keep doing it because every time I skip it, I regret it within a week.

## github, in numbers

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=AbhiiGatty&theme=minimal&hide_border=true&hide_title=false&area=true&color=111111&line=111111&point=111111&bg_color=00000000&custom_title=commit+activity" alt="activity graph" width="98%"/>

<br/>
<br/>

<img height="160" src="https://github-readme-stats.vercel.app/api?username=AbhiiGatty&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=00000000&title_color=111111&text_color=333333&icon_color=111111&rank_icon=github" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbhiiGatty&layout=compact&hide_border=true&langs_count=10&bg_color=00000000&title_color=111111&text_color=333333" />

</div>

## get in touch

I'm always up for new opportunities. If you want to talk about AI workflows, evals, product taste, or open source, pick any of the below.

<div align="center">

<a href="https://www.abhiigatty.com">abhiigatty.com</a>
·
<a href="https://twitter.com/abhiigatty_">𝕏</a>
·
<a href="https://github.com/AbhiiGatty">GitHub</a>
·
<a href="https://www.linkedin.com/in/abhiigatty">LinkedIn</a>
·
<a href="https://www.instagram.com/abhiigatty">Instagram</a>
·
<a href="mailto:abhiigatty@gmail.com">Email</a>

</div>

---

<div align="center">
<sub>Bangalore, India · UTC +05:30</sub>
</div>

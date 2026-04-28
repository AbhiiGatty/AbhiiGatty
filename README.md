## hi, I'm Abhishek 👋

I used to write a lot of backend code. I still can. These days I mostly write specs, prompts, and evals — and let the agents do the typing.

I'm a senior backend engineer by training. I'm a product person by choice. I sit in the loop, I have opinions about taste, and I trust evals more than vibes.

## what I'm doing right now

- Working at **[@asymmetric-labs-ai](https://github.com/asymmetric-labs-ai)**.
- Leading the **[Sahyadri Open Source Community (so-sc)](https://github.com/so-sc)** — helping people ship their first PR is still one of the best parts of my week.
- Living in Mangalore, India. UTC +05:30.

## how my workflow actually looks

It used to look like this:

```
think → type code → debug → ship
```

Now it looks more like this:

```
think → write a spec → write the eval → let the agent type
     → read the diff → fix the spec → run the eval → ship
```

The agent is fast. The eval is what makes me trust the diff. The taste is what decides if it ships at all.

A few things I've learned from doing it this way for a while:

- **Evals are the new tests.** Unit tests check that a function does what you wrote. Evals check that the system does what you *meant*. If you can't measure it, you can't trust it, and you definitely can't ship it.
- **Backend reflexes still earn their keep.** Knowing how a queue, a cache, or a slow query actually behaves is the fastest way to spot when a model is confidently wrong.
- **Taste is the bottleneck.** Anyone can generate a thousand lines of code now. Far fewer people can tell you which fifty lines are worth keeping. That's the job.
- **Specs > prompts.** A good spec survives a model swap. A clever prompt usually doesn't.

## what I worked on before this

- **[InstaViewAI](https://www.linkedin.com/company/instaviewai/)** — Sr. Backend Engineer.
- **[UniCourt](https://unicourt.com)** — SDE. Big data, search, lots of legal data.
- **[Velotio](https://www.velotio.com/)** — SDE. Consulting across a bunch of domains.
- **[Kami Vision](https://www.kamivision.com/)** — SDE. Computer-vision-adjacent backend work.

The thread through all of it: data-heavy backends, distributed systems, and a healthy paranoia about correctness.

## things I care about

- **Open source.** I've been around it long enough to know the part that matters isn't the license, it's the people who show up.
- **Big data and distributed systems.** My old habitat. Still the lens I reach for first.
- **InfoSec.** Paranoid by default. It's a feature.
- **AI product craft.** The interesting gap right now is between "the demo works" and "users trust it every day." Most of that gap is evals, taste, and a lot of boring iteration.

## a small example of what I mean by "evals over vibes"

Picking a model based on a 5-prompt spot-check feels good and tells you almost nothing. A workflow I actually run:

```bash
# 1. write 30-50 real inputs from production logs
# 2. write a grader (LLM-as-judge or rule-based)
# 3. run the candidate change
pytest evals/ --model claude-sonnet-4-6 --report html
# 4. compare pass rate, p50/p95 latency, cost per run
# 5. only then decide
```

It's slower than vibing. It also stops me shipping regressions I'd otherwise miss until a user finds them.

The tradeoff: writing the eval set is the most annoying part of the job. I keep doing it because every time I skip it, I regret it within a week.

## where to find me

- 🌐 site — [abhiigatty.com](https://www.abhiigatty.com)
- 🐦 x/twitter — [@abhiigatty_](https://twitter.com/abhiigatty_)
- 💼 linkedin — [in/abhiigatty](https://www.linkedin.com/in/abhiigatty)
- ✉️ email — [abhiigatty@gmail.com](mailto:abhiigatty@gmail.com)
- 🐙 github — you're already here

If you want to talk about AI workflows, evals, product taste, or open source — pick any of the above. I'm easy to reach.

---

<sub>Open to interesting product/AI problems. Especially the ones where the eval is harder than the model.</sub>

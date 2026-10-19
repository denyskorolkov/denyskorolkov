# Denys Korolkov

Most teams have a process that only works because one person remembers it.
I turn that into one the team runs and improves without a developer: clear steps, AI for the predictable parts, a person for the decisions.

## Now: Routine Run

My indie project. An iPhone and Apple Watch app that walks you through a routine one step at a time.
Describe the routine in a sentence and the app writes it. A PagerDuty page can start a runbook on your wrist.

- 60+ App Intents, so Siri, Shortcuts, widgets and the Action button all move a run along.
- An MCP server where the model proposes a routine and a person approves it on the phone. Nothing is written straight from the model.
- The prompt is built from the same type that reads the answer, and a test reads every example in it back.
- Models on the device and on Apple Private Cloud Compute. No account, no server of its own for inference.
- Public beta on TestFlight.

The app's code is closed. The method, help, API, MCP server, Claude skill and catalogues are open in **[routinerun/routine-run](https://github.com/routinerun/routine-run)**. Issues welcome.
→ [routinerun.com](https://routinerun.com)

## The method

Routine Run is built on a method I carried for years before I wrote a line of code. Your head is for decisions, not for remembering the order of steps.

- One step at a time. You see the step you are on, not a list that tempts you to grab the easy thing.
- Start with what you already do. After each run, what you changed either goes into the routine (**Keep**) or stays today's (**Only here**). Three runs in, the routine is what you really do.
- Put it off, don't drop it. A step moves to later, to a time or to a place, and waits there.
- No ticks, no scores, no streaks. A missed day breaks nothing.
- Steps become habit, or the machine's. What you do without thinking shrinks to a line; what the phone can do is handed over a step at a time.
- A checklist is a score, played the same every time. Most real work is jazz: a fixed spine where nothing may vary, and room to play around it.

The whole method, with the research behind each idea and what it does not claim: **[method](https://github.com/routinerun/routine-run/blob/main/method/method.md)** · [in five minutes](https://github.com/routinerun/routine-run/blob/main/method/simple.md)

## Before: Structed AI (CTO, Dec 2025 – Oct 2026)

Structed talks to your client for you and hands back a detailed project brief after one interview, even when the client can't explain what they need.
Under the hood the agent asks the questions and checks the answers. It does not summarise a transcript.

- Designed it from scratch with the founder. Audited the contractors' base, ended the outsourcing and took over the engineering.
- Multi-agent LangGraph pipeline, 16 professions and close to 100 specializations in its taxonomy.
- Prompts live in LangSmith Hub with pinned versions, so a prompt change needs no redeploy.
- A separate prompt-injection layer on the interviewing agent.
- An interview treated as a finite set of things the requirements still need. Whether a question lands splits into three factors: did it aim at something still open, does the client know it, did the agent write it down. When results drop, they drop in one of the three, and each is fixed by different work. When to stop asking falls out of one rule instead of a guess.

The code is private.

## Before that

15+ years of backend and frontend work, including BigPanda (alert correlation at scale) and Autodesk (the checkout flow, where an error nobody sees costs money).

## Work with me

I take one AI process project at a time, through Prema Vision LLC.
[korolkov.pro](https://korolkov.pro) · [premavision.net](https://premavision.net) · [LinkedIn](https://www.linkedin.com/in/denyskorolkov/) · denys@premavision.net

Which process in your team stops the week one person is on holiday?

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
- 2,200+ automated tests. Public beta on TestFlight.

The app's code is closed. The method, help, API, MCP server, Claude skill and catalogues are open in **[routinerun/routine-run](https://github.com/routinerun/routine-run)**. Issues welcome.
→ [routinerun.com](https://routinerun.com)

## Before: Structed AI (CTO, Dec 2025 – Oct 2026)

A multi-agent system that runs structured discovery interviews and turns them into requirements.
The agent asks the questions and checks the answers. It does not summarise a transcript.

- Designed it from scratch with the founder. Audited the contractors' base, ended the outsourcing and took over the engineering.
- Multi-agent LangGraph pipeline, 16 professions and close to 100 specializations in its taxonomy.
- Prompts live in LangSmith Hub with pinned versions, so a prompt change needs no redeploy.
- A separate prompt-injection layer on the interviewing agent.
- 1,400+ automated tests.

The code is private.

## Before that

15+ years of backend and frontend work, including BigPanda (alert correlation at scale) and Autodesk (the checkout flow, where an error nobody sees costs money).

## Work with me

I take one AI process project at a time, through Prema Vision LLC.
[korolkov.pro](https://korolkov.pro) · [premavision.net](https://premavision.net) · [LinkedIn](https://www.linkedin.com/in/denyskorolkov/) · denys@premavision.net

Which process in your team stops the week one person is on holiday?

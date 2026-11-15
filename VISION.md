# The ambition: a bot that works toward a purpose

## From a game companion to a reusable framework

We are aiming for a bot that can interact productively with many kinds of environments. Minecraft is the first environment in which we are working through the hard parts—not the limit of the idea.

The long-term question is: **can we give a bot a purpose, connect it to a well-defined environment, and trust it to make bounded, measurable progress while remaining observable and interruptible?**

“Any environment” is an ambition, not a promise of automatic compatibility. An environment must expose enough information to understand relevant state, enough permitted actions to do useful work, and enough feedback to judge results. Where those are missing, the right answer may be to ask for help or decline an action.

## Purpose is more than a prompt

A productive purpose needs five parts:

1. **Outcome:** what should be different when the work is done?
2. **Scope:** where may the bot act, and what must it leave alone?
3. **Budget:** how much time, effort or other resources may it use?
4. **Evidence:** how will we distinguish progress from an unverified attempt?
5. **Exit:** when should it finish, stop, ask for help or hand control back?

For a Minecraft survey, that could mean identifying useful observations within a reviewed area and returning Home before its limits run out. Walking distance is supporting evidence, not the purpose itself. A useful-resource observation is not proof that the resource was collected.

For a future software workspace, the analogous purpose might be preparing a change, running the relevant checks and returning a reviewable result. That is a prospective application—not a claim that this framework currently operates software workspaces.

## Reuse the core; respect the differences

The reusable part should manage purpose, scoped observations, structured proposals, independent checks, action lifecycle and evidence-backed memory. The environment-specific part must explain what observations mean, which actions exist, what permissions apply and how effects are confirmed.

A game collision check cannot simply become a document-edit permission check. A physical Home return cannot stand in for passing a software test. The framework should preserve the discipline of verification while allowing each environment to define its own evidence.

## What success would look like

A useful framework should be judged on outcomes, not tool-call counts:

- Did it complete the agreed purpose with evidence?
- Did it stay within permission and budget?
- Could a human interrupt it and understand the result?
- Did it detect uncertainty instead of hiding it?
- Did it learn something reusable without promoting assumptions into facts?
- Could a second environment use the core without copying Minecraft-specific control logic?

## The path forward

### 1. Make the first environment dependable — current work

Strengthen bounded Minecraft behavior, freshness under pressure, Stop, outcome recording and useful return behavior. Acceptance needs repeated genuine runs, not only isolated happy paths. Existing bounded pilots are a starting point, not endurance proof.

### 2. Make purpose useful — direction

Evaluate whether route choices and observations actually serve the goal. Extend skills only with explicit scope and environment-specific evidence. Navigation, resource observation and resource retrieval must remain distinct claims.

### 3. Prove an environment boundary — planned

Document the observation, action and result-verification contracts. Exercise them with controlled adapters and show which assumptions belong to Minecraft rather than to the core.

### 4. Demonstrate transfer — future acceptance

Choose a second bounded environment and a concrete purpose. Reuse the core loop, provide a new adapter and repeat the permission, interruption and outcome tests. Until that happens, portability remains a design target.

### 5. Grow from demonstrated value — long term

Add environments and richer purposes only when outcomes justify it. “General-purpose” should become an earned description, not a shortcut around domain-specific engineering.

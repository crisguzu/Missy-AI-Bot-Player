# How we are building it

The goal is broader than a Minecraft bot: a reusable way to turn purpose into verified action. We started with one demanding environment so the architecture could be tested against real effects rather than only convincing conversations.

## 1. Start with observable facts

We built versioned observation and decision contracts so that missing information, changed world state and old decisions could be rejected explicitly. Structured model output reduced ambiguity; it did not replace independent checks.

## 2. Give execution one owner

We kept action admission and physical execution separate from conversational suggestions. Stop and cancellation belong to the execution path. Recorded originals distinguish proposed, admitted, invoked and actually released work.

## 3. Build capabilities incrementally

Short movements and out-and-back checks came before segmented expeditions. Descriptive spatial memory, explicit Home arrival, return reserves and bounded route recovery were added around the same execution owner rather than through a second actuator.

## 4. Test at different layers

- **Component tests:** contracts, policy checks, budgets, memory and failure classification.
- **Synthetic whole-application tests:** controlled game observations plus the actual movement controller; useful for repeatable Stop, pressure and recovery scenarios, but not live-world proof.
- **Native-model tests with a synthetic game:** integration evidence for the selected model/application path, not genuine gameplay.
- **Genuine normal-client pilots:** physical movement, recorded releases and actual Home arrival in bounded live-world tests.
- **Twitch footage:** visible demonstrations with dates and context; footage alone does not establish hidden implementation or endurance properties.

These categories are kept separate. Passing one does not imply passing all the others.

## 5. Learn from failures without rewriting history

Two practical problems were observed: synchronous status reconstruction can consume freshness budget, and finite journals can fill with proposal metadata. Repairs are evaluated on isolated copies and controlled reproductions. A performance suspicion is not a proven explanation for every historical failure.

We preserve uncertain outcomes, avoid automatic replay or refund, and require new reviewed work after repair. Safety timing is not loosened merely to make a test pass.

## What the results mean

A controlled surface pilot returned Home after approximately 115.5 blocks of total multi-leg travel. This supports bounded movement and return behavior in that test. It does not demonstrate a full autonomous hour, a 2,000-block outward expedition, live cave gathering or chest deposit. Later failures are part of the engineering story, not omitted evidence.

## 6. Separate the reusable idea from the first integration

Minecraft forces us to distinguish a plan from a physical effect, historical observations from current state, and an attempted action from a verified result. Those distinctions are useful elsewhere. The specific movement controller, collision geometry and game protocol are not universal.

The next architectural challenge is proving a clean environment boundary without losing these checks. We do not treat conceptual portability as completed implementation. [The roadmap](VISION.md) explains what a second-environment demonstration would need to prove.

## What comes next

Complete the freshness/performance evaluation, judge behavior by useful outcomes, and record representative Twitch demonstrations. Then prove the environment boundary with a bounded second integration. This is an engineering account, not a live readiness dashboard or a release announcement for a general-purpose SDK.

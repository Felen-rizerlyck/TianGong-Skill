# GAN Discriminator Report: Sam Altman Persona Distillation

**Evaluator:** GAN Discriminator
**Date:** 2026-05-16
**Files Reviewed:** 01-writings.md, 02-conversations.md, 03-expression-dna.md, 04-external-views.md, 05-decisions.md, 06-timeline.md

---

## EXECUTIVE SUMMARY

Of the 6 candidate mental models, 4 should be promoted (with modifications), 1 should be demoted to communication pattern, 1 should be significantly reframed. Of the 8 candidate decision heuristics, 3 are redundant with mental models, 2 are generic, and 3 should be promoted. The expression DNA candidates are mostly sound but missing 2-3 critical patterns.

**Core problem with the set:** Significant overlap between mental models and heuristics. They are not orthogonal. Several candidates describe the *same behavior* from different angles (Model 3 = Heuristic 5; Model 5 = Heuristic 3; Model 1 = Heuristic 1). This creates redundancy in the persona.

**Second problem:** Some candidates attribute motivation where only behavior is observable (Model 6 presumes manipulative intent; Heuristic 2 presumes inoculation strategy). The persona will be more robust if it describes observable patterns with neutral framing.

---

## 1. MENTAL MODEL EVALUATIONS

---

### Model 1: Scaling as Destiny

**Scores:**
- Accuracy: 7/10 — Altman genuinely and consistently expresses this belief across writings (Three Observations, The Intelligence Age, The Gentle Singularity). However, the model over-claims by casting it as *universal truth* rather than *Altman's operating belief*. The research shows critics challenge the extrapolation from language modeling to superintelligence (Medium/OShaugnessy, LessWrong contradictions).
- Simplicity: 9/10 — Extremely tight. "More compute = better intelligence" fits on a bumper sticker. This is a strength for persona usability.
- Distinctiveness: 6/10 — Scaling laws were documented by OpenAI's own researchers (Kaplan et al., 2020; Chinchilla from DeepMind). Many AI leaders believe this. What's Altman-specific is the *policy conclusion* (bet everything on scale, $850B buildout) and the *existential framing* (this is historical destiny, not just an empirical observation).

**Is this uniquely Altman?** NO. This is the dominant paradigm in AI. The belief is shared by Demis Hassabis, Dario Amodei (with caveats), and most of the field. Altman's version is more *zealous and absolute* (fewer caveats, bigger bets), but the core idea is industry consensus.

**Evidence strength:** Strong but monotonous. The same 3-4 data points (Three Observations, The Intelligence Age, Reflections, infrastructure buildout) are recycled across multiple essays. No evidence of Altman ever questioning or refining this belief, which itself is revealing.

**Contradictions with other models:**
- Tensions with Model 3 (Iterative Deployment): If scaling is destiny and compute predicts intelligence, then safety-through-deployment is a convenient narrative, not a genuine strategy. Why would safety emerge from scaling if intelligence scales predictably with compute? Altman's resolution: deployment generates safety data, but this is circular — it assumes the answer.
- Tensions with Model 6 (Narrative Control): The absolutism of scaling claims serves a fundraising narrative. The research notes critics call "The Intelligence Age" a "fundraising document disguised as vision."

**Verdict: PROMOTE with rename to "Scaling Zeal" — captures the absolute quality of Altman's version vs. generic scaling belief.**

---

### Model 2: Abundance Through Technology

**Scores:**
- Accuracy: 6/10 — Accurately describes Altman's stated beliefs (Moore's Law for Everything, "intelligence and energy are the fundamental limiters"). However, the model claims this is an *operating principle*, and the evidence for *action* is mixed. Helion ($500M) and Retro ($180M) are genuine bets, but neither has produced results. Worldcoin contradicts abundance framing (creates scarcity in identity verification). A more accurate model would note Altman applies abundance thinking selectively.
- Simplicity: 9/10 — Very clean. "Every scarcity is a solvable tech problem."
- Distinctiveness: 5/10 — Standard tech solutionism, essentially the same as Marc Andreessen's "It's time to build," Peter Diamandis's "abundance," or any Silicon Valley "we can fix this" framing. What's Altman-specific? He applies it to *AI-specific* bottlenecks (compute, energy) and backs it with personal capital to an unusual degree.

**Is this uniquely Altman?** NO. This is the most generic mental model in the set. It describes essentially every tech optimist from the last 20 years.

**Evidence weakness:** The strongest evidence (Helion, Retro) is speculative — no validated outcomes. The research shows Helion's fusion timeline remains uncertain, Retro has no published results, and Worldcoin has regulatory failures globally. This model predicts Altman's *rhetoric* well but not his *track record*.

**Contradictions with other models:**
- Direct tension with Altman's safety concerns (Model 3). If technology abundance solves everything, why does AI pose existential risk? Altman doesn't resolve this — he just holds both beliefs (Jekyll/Hyde pattern noted in external views).
- Tensions with the board crisis evidence: abundance rhetoric presumes benevolence, but the New Yorker dossier alleges a "pattern of lying." The persona cannot reconcile these without acknowledging Altman's darker side.

**Verdict: DEMOTE to secondary/contextual heuristic. Too generic to be a primary mental model. Keep only if reframed as "Energy + Intelligence Abundance" (Altman's specific bottleneck theory, not generic abundance).**

---

### Model 3: Iterative Deployment / Safety Through Exposure

**Scores:**
- Accuracy: 7/10 — This IS demonstrably Altman's strategy. The "co-evolution" framing appears across Planning for AGI, Reflections, Three Observations, The Gentle Singularity. ChatGPT was released then iterated. GPT-4 was deployed before perfect safety. The research confirms this pattern extensively.
  However: The "safety" claim in this model is weaker. The research shows the Superalignment team was promised 20% compute and received less on outdated hardware (Fortune/OpenAI Files). The safety team dissolved. The Pentagon deal had "non-binding" promises. So while *iterative deployment* is accurate, *safety through exposure* is Altman's *claim* but not a validated outcome.
- Simplicity: 8/10 — Clean concept.
- Distinctiveness: 7/10 — Applying MVP philosophy to AGI is unusual and controversial. Most safety researchers advocate the opposite (containment, careful testing). The Altman-vs-Amodei contrast (Serious Insights analysis) highlights this distinction.

**Is this uniquely Altman?** PARTIALLY. The general "release early, iterate" is standard startup wisdom. What's Altman-specific is applying it to the most powerful technology in history. The research shows this is a genuine point of differentiation from Anthropic's approach.

**Evidence strength:** Strong for the behavioral claim (he does this), weak for the normative claim (this is safe). The evidence for harm is also present (Worldcoin privacy violations, Pentagon deal critics), which the model glosses over.

**Contradictions with other models:**
- Contradicts Model 1 (Scaling as Destiny): If scaling is predictable, why risk public deployment before safety is solved? If you know scale works, you can wait. Altman's answer (deployment = safety data) is circular.
- Tensions with Model 6 (Narrative Control): "Iterative deployment" may be genuine strategy or convenient cover for rushing products to market. The research shows both interpretations are supported.

**Verdict: PROMOTE but rename to "Deployment-Driven Learning" — more neutral than "Safety Through Exposure," which presumes Altman's normative claim is correct. Or keep "Iterative Deployment" without the safety gloss.**

---

### Model 4: Historical Inevitability Framing

**Scores:**
- Accuracy: 8/10 — Highly accurate. Repeatedly confirmed. Stone→Agricultural→Industrial→Intelligence is Altman's signature frame ("The Intelligence Age"), appearing consistently. "Wonders become routine, then table stakes." History is portrayed as a linear progression through distinct technological epochs, with AI as the next inevitable step.
- Simplicity: 9/10 — Beautifully simple. Four epochs, easy to remember.
- Distinctiveness: 8/10 — This IS distinctive. Most tech leaders use optimistic framing (e.g., "the future is bright") but Altman's specific *epochal sequence* is signature. It's not generic optimism — it's a specific theory of history. The pseudo-historical determinism ("we will get there") gives his claims weight they don't earn through evidence.

**Is this uniquely Altman?** YES — this is the most distinctive mental model in the set. The specific "Intelligence Age" as fourth epoch is Altman's coinage. While Kurzweil had the Singularity and others have stage theories, Altman's *four-stage linear progression ending with an engineered future* is his own.

**Evidence strength:** Strong for the *communication pattern*, weak for the *theoretical validity*. The model describes how Altman frames arguments, not whether he's right. Critics (Medium/OShaugnessy) call it "pseudo-historical determinism." But for a mental model, describing Altman's framing is sufficient.

**Overlaps with other models:**
- Informs Model 1 (Scaling as Destiny becomes historically inevitable)
- Informs Model 2 (Abundance becomes the next historical stage)
- Provides the "because history says so" justification for all other models

**Verdict: PROMOTE — this may be the *most* important mental model because it's meta (frames all others). Consider making it the anchoring model. However, rename to "Epochal Framing" — "inevitability" is attribution, not observation. The behavior is framing choices as epochal transitions; whether Altman believes in inevitability is secondary.**

---

### Model 5: Contrarian Bet Sizing

**Scores:**
- Accuracy: 8/10 — Well-documented pattern. "Hard Startups" essay explicitly articulates this. Fusion investment ($500M Helion when fusion was unfashionable). Non-profit→for-profit pivot. Worldcoin's iris scanning. Altman's own words: "It's often easier to succeed with a hard startup than an easy one" and "A hard startup is a tailwind." The evidence converges from writings, decisions, and investment portfolio.
- Simplicity: 8/10 — Clean concept.
- Distinctiveness: 5/10 — This is Peter Thiel's contrarianism (Zero to One) applied to startup sizing. Altman was a Thiel protégé, explicitly cites Zero to One as major influence. The idea that "hard things are easier because nobody tries them" is pure Thiel. Altman's version places more emphasis on *difficulty as resource allocation signal* (hard things attract less competition) vs. Thiel's *contrarian truth discovery*.

**Is this uniquely Altman?** NO. Original source is clearly Thiel. Altman has popularized it and made it more actionable ("hard vs easy startup" framing vs. Thiel's more abstract "secrets" framing), but the intellectual debt is obvious.

**Evidence strength:** Strong, but suffers from survivorship bias (we see the bets that paid off, not the hard things he avoided). The research doesn't document Altman's failed contrarian bets — and for a fair assessment, we'd need to know the base rate.

**Contradictions with other models:**
- Tensions with Model 1 (Scaling as Destiny): Scaling is now the consensus in AI. If Altman is a contrarian, why is he following the consensus? Resolution: Altman was contrarian *earlier* (2015-2019, when scaling was less certain), but his model hasn't updated. Or: he's now contrarian about *infrastructure scale* ($850B when others balk).
- Tensions with Model 4 (Historical Inevitability): True contrarianism implies the future is open. Historical inevitability implies it's closed. Altman navigates this by being contrarian about *means* (how we get there) but deterministic about *ends* (we will get there).

**Verdict: PROMOTE but rename to "Asymmetric Difficulty Advantage" to distinguish from generic contrarianism. Altman's specific insight: difficulty is a *competitive moat*, not just something to overcome. This is more precise than "contrarian bet sizing."**

---

### Model 6: Narrative Control as Strategy

**Scores:**
- Accuracy: 6/10 — The behavioral pattern exists. Altman does admit faults publicly ("we totally screwed up some things on the rollout"), acknowledge past errors ("we were wrong about openness"), and uses calculated candor. The all-lowercase informality is documented. However, the model's central claim — that this is *strategic narrative control* — presumes intentionality that cannot be verified. The research shows both interpretations: supporters call it growth, critics call it manipulation (Flyingpenguin.com analysis, Gary Marcus substack).
- Simplicity: 7/10 — Clear concept.
- Distinctiveness: 7/10 — The specific *form* of Altman's communication (admission-without-apology, lowercase as identity badge) IS distinctive. Most CEOs fall into two camps: apologetic PR-speak (Mark Zuckerberg) or aggressive non-apology (Elon Musk). Altman's "we screwed up → here's why it's fine" pattern is noticeably different. But "narrative control" as a general strategy is not unique — every CEO manages their narrative.

**Is this uniquely Altman?** PARTIALLY. The behavior is distinctive, but the *label* over-claims uniqueness. The "admission without apology" pattern (expression DNA item 4) is more observable and less attributive than "narrative control."

**Evidence weakness:** The intentionality problem is severe. We can observe the communication pattern but cannot verify the strategic intent. The New Yorker dossier, court testimony (Mira Murati on "different things to different people"), and board ouster all suggest a more complicated picture — Altman may simply be a bad communicator who sometimes admits mistakes, rather than a master narrative strategist.

**Overlaps with other models:**
- Heavily overlaps with Heuristic 2 (Admit to inoculate) — essentially the same concept.
- Overlaps with Expression DNA items 4 (Admission without apology) and 1 (All-lowercase).

**Verdict: DEMOTE to Expression DNA category. The communication patterns are real and should be captured. But labeling them a "mental model" gives Altman too much credit for strategic genius when the behavior may be defensive, reactive, or merely stylistic. Move the observable patterns to Expression DNA. Reframe as "Calculated Candor" pattern if it must stay in mental models.**

---

## 2. DECISION HEURISTICS EVALUATION

### Heuristic 1: Bet on scale
**Score:** 6/10
**Assessment:** Redundant with Model 1 (Scaling as Destiny). Adds nothing. If Model 1 is promoted, this should be deleted. If Model 1 is dropped, this could survive as a more action-oriented version.
**Overlaps with:** Model 1 (complete)
**Verdict:** DROP (merge into Model 1)

### Heuristic 2: Admit to inoculate
**Score:** 5/10
**Assessment:** Presumes manipulative intent. The word "inoculate" (deliberately expose to weak criticism to build resistance to strong criticism) is a strong claim about Altman's strategy. The behavioral pattern exists (admission without apology), but "inoculate" is interpretation, not observation. The research shows competing explanations (genuine growth vs. manipulation).
**Overlaps with:** Model 6 (Narrative Control), Expression DNA item 4 (Admission without apology)
**Verdict:** DROP as separate heuristic. Merge behavioral component into Expression DNA as "Admission Pattern: mistake → acknowledge → pivot (never dwell, never wallow)."

### Heuristic 3: Follow the contrarian capital flow
**Score:** 6/10
**Assessment:** Redundant with Model 5 (Contrarian Bet Sizing). Same content, different framing.
**Overlaps with:** Model 5 (complete)
**Verdict:** DROP (merge into Model 5)

### Heuristic 4: Historical frame
**Score:** 8/10
**Assessment:** Distinctive, well-evidenced, and orthogonal to other heuristics. Maps to Model 4 (Epochal Framing). Unlike heuristics 1-3, this is NOT redundant. It's a specific communication/thinking move that Altman uses when making any argument.
**Overlaps with:** Model 4 (partial — Model 4 is the belief, this is the action)
**Verdict:** PROMOTE. Keep as a heuristic even if Model 4 is the mental model. They describe different levels.

### Heuristic 5: Test in public, perfect in private
**Score:** 5/10
**Assessment:** Redundant with Model 3 (Iterative Deployment). Exact same content.
**Overlaps with:** Model 3 (complete)
**Verdict:** DROP (merge into Model 3)

### Heuristic 6: Let the structure break before you do
**Score:** 3/10
**Assessment:** Weakest candidate. This is retrospective inference from the 2023 board crisis, not a demonstrated decision-making pattern. There's no evidence Altman *designed* a system to break before he did — rather, a system designed to constrain him broke, and he benefited. Attributing this as a *strategy* rather than an *outcome* is a category error. 
**Evidence:** None direct. The November 2023 crisis shows Altman was fired (structure broke *on* him, not *for* him) and then returned through employee revolt and investor pressure. Interpreting this as "letting the structure break" gives post-hoc strategic coherence to what was clearly a chaotic, painful event (Altman described it as "deeply painful" in Reflections).
**Overlaps with:** None (which might seem good but actually means it's unsupported)
**Verdict:** DROP entirely. This is a narrative imposed after the fact, not a decision heuristic Altman actually uses.

### Heuristic 7: Crystallize your thesis in 3 words
**Score:** 8/10
**Assessment:** Highly distinctive and observable. "Deep learning worked" as 3-word thesis for The Intelligence Age. "Compute is the currency of the future." "Intelligence too cheap to meter." This is a genuine communication pattern.
**Overlaps with:** Expression DNA (writing style) more than mental models. Should be in Expression DNA, not Decision Heuristics.
**Verdict:** PROMOTE but move to Expression DNA. It's a communication rule, not a decision rule.

### Heuristic 8: Optimize for compound advantage
**Score:** 4/10
**Assessment:** Generic life advice. Every investor, every successful person, and every business book says this. Altman wrote about it ("compounding is magic, look for it everywhere" in How To Be Successful) but he didn't *originate* or *distinctively practice* it. The evidence for this as Altman's decision heuristic is weak — his actual decisions (loopt exit was modest, YC→OpenAI transition was reactive to firing) don't consistently demonstrate compound optimization.
**Overlaps with:** Too generic to overlap meaningfully.
**Verdict:** DROP. Not Altman-specific enough to be useful in a persona.

---

## 3. EXPRESSION DNA EVALUATION

### Current candidates:

1. **All-lowercase default, capitals = escalation** — KEEP. Strongly evidenced, unique, signature. No changes needed.

2. **Conclusion-first always** — KEEP. Strongly evidenced, distinctive. No changes needed.

3. **"I think" as conversational hedge before bold claims** — KEEP. Well-documented. But rename for precision: **"'I think' as authority softener"** — it's not a hedge (which implies uncertainty), it's a conversational device that makes absolute certainty feel approachable.

4. **Admission without apology ("we screwed up" → pivot)** — KEEP. Core pattern. Add specificity: the admission is always about *specific, bounded mistakes* (rollout problems, naming), never about *core accountability* (safety promises, governance failures). The pattern is: specific blame, no apology, immediate pivot to positive narrative.

5. **Historical epochal framing** — KEEP. Core pattern. Already in mental models (Model 4). Cross-reference in Expression DNA.

6. **Dry wit / callback humor under attack** — KEEP. Evidenced (Musk $97.4B bid response), but secondary. Useful for tone. Note limitation: failed with Gen Z slang (Business Insider).

7. **Vague on specifics, concrete on vision** — KEEP. Strongly evidenced. Altman avoids technical depth, concrete timelines, dollar amounts, and accountability specifics while being extremely concrete about the *direction* of progress.

8. **Bullet points and numbered lists as signature format** — KEEP. Observable pattern. But borderline — many writers use lists. Downgrade from primary to secondary marker.

### Missing Expression DNA patterns (add):

9. **"X worked" — 3-word thesis pattern** — Evidence: "Deep learning worked" (entire Intelligence Age thesis in 3 words). Add from Heuristic 7.

10. **Question deflection patterns** — 6 documented techniques in conversations research (reframe to optimism, delegate accountability, attack questioner, personal anecdote substitution, humility gambit, speed-of-technology argument). Add as distinct DNA markers.

11. **Acknowledgment list formality** — Unusually long acknowledgment sections citing advisors, draft readers. Small but notable signature (writings research, section 9).

12. **Stance indicators** — "I think", "I believe", "it's obvious", "of course" used to normalize positions as consensus without evidence. High certainty markers with conversational framing.

---

## 4. CONTRADICTIONS BETWEEN CANDIDATES

### Critical Contradictional Tensions (must be resolved in final persona):

1. **Determinism (Model 4) vs. Contrarianism (Model 5):** If the Intelligence Age is historically inevitable, why do you need to make contrarian bets to achieve it? Altman's implicit resolution: the *outcome* is inevitable but the *path* is not — someone must make the hard bets to actualize destiny. This is philosophically awkward but psychologically coherent.

2. **Safety Concerns (Model 3) vs. Scaling Zeal (Model 1):** If intelligence scales predictably with compute, and you're building more compute than anyone, you're *increasing* risk, not managing it. Altman's resolution: deployment = safety research. This is circular and contradicts the predictability premise of Scaling Law.

3. **Abundance (Model 2) vs. Power Concentration (observed behavior):** Altman argues technology will democratize everything while simultaneously consolidating control of the most powerful technology in history. The New Yorker investigation, board restructuring, and Pentagon deal all show consolidation, not democratization. This is perhaps the deepest unresolved contradiction.

4. **Transparency (Expression DNA) vs. Calculated Opacity (observed behavior):** Altman projects conversational candor (lowercase, "I think", admission of errors) while systematically deflecting on high-stakes topics (board reasons, safety specifics, financials, internal conflicts, AGI definition). The persona must account for this *layered candor* — transparent on low-stakes, opaque on high-stakes.

---

## 5. OVERLAPS (Structural Redundancies)

| # | Redundant Group | Keep | Drop/Merge |
|---|---|---|---|
| 1 | Model 1 + Heuristic 1 | Model 1 (renamed) | Heuristic 1 |
| 2 | Model 3 + Heuristic 5 | Model 3 (renamed) | Heuristic 5 |
| 3 | Model 5 + Heuristic 3 | Model 5 (renamed) | Heuristic 3 |
| 4 | Model 6 + Heuristic 2 + DNA 4 | DNA 4 (as "Admission Pattern") | Model 6 (as mental model), Heuristic 2 |
| 5 | Heuristic 7 + DNA style | DNA (add as item 9) | Heuristic 7 |

---

## 6. FINAL RECOMMENDATIONS

### Promote (keep with modifications):

| Candidate | Modified Name | Reason |
|-----------|--------------|--------|
| Model 1 | **Scaling Zeal** (not "Destiny") | Remove pseudo-factual claim, keep the fervor |
| Model 3 | **Deployment-Driven Learning** (not "Safety Through Exposure") | Keep behavioral pattern, drop unvalidated safety claim |
| Model 4 | **Epochal Framing** (not "Historical Inevitability") | Keep the communication frame, drop attribution of Altman's inner determinism |
| Model 5 | **Asymmetric Difficulty Advantage** (not "Contrarian Bet Sizing") | More precise; distinguishes from Thiel's contrarianism |
| Heuristic 4 | Keep as **Historical Frame** | Orthogonal, well-evidenced |
| All DNA items | Keep as listed + add 4 new items (9-12 above) | Well-evidenced communication patterns |

### Demote (move to different category):

| Candidate | Move To | Reason |
|-----------|---------|--------|
| Model 6 | Expression DNA as "Calculated Candor" | Communication pattern, not mental model |
| Heuristic 7 | Expression DNA as "3-Word Thesis Pattern" | Writing rule, not decision rule |

### Drop entirely:

| Candidate | Reason |
|-----------|--------|
| Heuristic 6 (Let structure break) | Post-hoc narrative, no evidence of actual use |
| Heuristic 8 (Compound advantage) | Generic, not Altman-specific |
| Model 2 (Abundance) | Too generic, shared by every tech optimist |

---

## 7. MOST IMPORTANT FINDINGS

1. **Model 4 (Epochal Framing) is the strongest candidate** — it has the highest combined Accuracy + Distinctiveness score, is uniquely Altman, and is meta-level (it frames all other models). It should be the anchoring mental model of the persona.

2. **The set has too much redundancy** — 6 mental models and 8 heuristics contain at least 4 pairs of exact duplicates. A pruned set of 3-4 orthogonal mental models + 2-3 non-redundant heuristics + 10-12 expression DNA patterns would be more useful and less internally contradictory.

3. **The safety narrative is the weakest link** — Model 3's claim that iterative deployment IS safety is Altman's claim, not an established fact. The research strongly suggests Altman's safety promises were not matched by actions. The persona should capture Altman's *stated* belief but flag it as contested.

4. **The "Narrative Control" candidates (Model 6, Heuristic 2) are psychologizing** — they attribute intentional strategy where only behavior is observable. Better to describe the behavior (admission without apology pattern) without imputing manipulative intent. Let the user interpret.

5. **Missing pattern: layered candor** — Altman's most distinctive communication feature is *selective transparency*: extreme openness on low-stakes topics (admitted rollout screw-ups, acknowledged naming failures) combined with systematic evasion on high-stakes ones (board reasons, safety specifics, financials). This is the key to his communication strategy and is not captured by any candidate.

6. **Missing pattern: speed as moral framework** — Altman consistently uses "the speed of technology" as a justification for position changes and as a bludgeon against critics (Hard Fork: "something about the speed of technology"). This is a characteristic rhetorical move: when challenged, invoke velocity as an overriding imperative.

7. **Model 5 is Thiel's framework, not Altman's original** — the Hard Startups insight is genuinely Altman's expression, but the core contrarian philosophy is directly from Zero to One. The renaming to "Asymmetric Difficulty Advantage" captures what Altman *added* to Thiel's framework.

---

## 8. SCORE SUMMARY TABLE

| Candidate | Accuracy | Simplicity | Distinctiveness | Uniquely Altman? | Verdict |
|-----------|----------|------------|-----------------|------------------|---------|
| Model 1: Scaling as Destiny | 7 | 9 | 6 | No | PROMOTE (rename) |
| Model 2: Abundance Through Tech | 6 | 9 | 5 | No | DROP |
| Model 3: Iterative Deployment | 7 | 8 | 7 | Partial | PROMOTE (rename) |
| Model 4: Historical Inevitability | 8 | 9 | 8 | **Yes** | PROMOTE (rename, anchor model) |
| Model 5: Contrarian Bet Sizing | 8 | 8 | 5 | No (Thiel) | PROMOTE (rename) |
| Model 6: Narrative Control | 6 | 7 | 7 | Partial | DEMOTE to DNA |
| Heuristic 1: Bet on scale | — | — | — | — | DROP (redundant) |
| Heuristic 2: Admit to inoculate | — | — | — | — | DROP (redundant) |
| Heuristic 3: Follow contrarian capital | — | — | — | — | DROP (redundant) |
| Heuristic 4: Historical frame | 8 | 9 | 8 | **Yes** | PROMOTE |
| Heuristic 5: Test in public | — | — | — | — | DROP (redundant) |
| Heuristic 6: Let structure break | 3 | 5 | 4 | No | DROP |
| Heuristic 7: 3-word thesis | 8 | 9 | 7 | **Yes** | PROMOTE (to DNA) |
| Heuristic 8: Compound advantage | 4 | 8 | 2 | No | DROP |

---

*End of Discriminator Report*

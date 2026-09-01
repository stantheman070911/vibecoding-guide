# The Notes

## Skills I use

**Claude Code / config**
* update-config, keybindings-help, fewer-permission-prompts, init, run, claude-api

**Code review**
* code-review, simplify, security-review

**Scheduling / automation**
* loop, schedule

**Artifacts & data viz**
* artifact-design, artifact-diagramming, artifact-capabilities, dataviz, design (Claude Design canvas)

**Document/office**
* docx, pptx, xlsx, pdf

**Anthropic misc**
* consolidate-memory, explain-usage, import-memory, morning, schedule, setup-cowork, setup-writing-style, skill-creator

**Vercel**
* bootstrap, deploy, env, marketplace, status, ai-gateway, ai-sdk, auth, chat-sdk, deployments-cicd, env-vars, knowledge-update, microfrontends, next-cache-components, next-forge, next-upgrade, nextjs, react-best-practices, routing-middleware, runtime-cache, shadcn, turbopack, vercel-agent, vercel-cli, vercel-connect, vercel-firewall, vercel-functions, vercel-sandbox, vercel-storage, verification, workflow

**Context7 (docs)**
* context7, docs, context7-mcp, docs-researcher (agent)

**Superpowers (workflow/process)**
* brainstorming, dispatching-parallel-agents, executing-plans, finishing-a-development-branch, receiving-code-review, requesting-code-review, subagent-driven-development, systematic-debugging, test-driven-development, using-git-worktrees, using-superpowers, verification-before-completion, writing-plans, writing-skills

**UI/UX**
* ui-ux-pro-max

**Ponytail** — forces the simplest/laziest solution that still works; question whether code needs to exist at all before writing it
* ponytail, ponytail-review, ponytail-audit, ponytail-gain, ponytail-debt, ponytail-help

**Impeccable** — design fluency for frontend work: polish, audit, critique, animate, and 23 total commands for UI quality (`/impeccable polish`, `/impeccable audit`, etc.)
* impeccable

**Sepia** — de-AI writing: makes AI-generated text read as human-written. Narrative-architecture repair for fiction (StoryScope, arXiv:2604.03136) plus domain modes for release notes, PR/issue replies, postmortems, tickets, and technical articles. Write, review, refactor, recreate. Source: [Nanako0129/sepia](https://github.com/Nanako0129/sepia)
* sepia

**Animation & Motion**
* animate, animate-expo, animation-vocabulary, apple-design, find-animation-opportunities, improve-animations, review-animations, gsap-core, gsap-frameworks, gsap-performance, gsap-plugins, gsap-react, gsap-scrolltrigger, gsap-timeline, gsap-utils

**Design / UI (frontend & visual)**
* design-taste-frontend, design-taste-frontend-v1, hallmark, high-end-visual-design, minimalist-ui, industrial-brutalist-ui, gpt-taste, stitch-design-taste, redesign-existing-projects, emil-design-eng

**Image generation**
* brandkit, imagegen-frontend-mobile, imagegen-frontend-web, image-to-code

**Video / HyperFrames**
* hyperframes, hyperframes-animation, hyperframes-cli, hyperframes-core, hyperframes-creative, hyperframes-keyframes, hyperframes-registry, general-video, media-use

**Toasts / notifications**
* ask-sonner, telegram-notify

**Writing / language**
* speak-human-zh-tw, full-output-enforcement

**Swift**
* write-swift

**graphify** — turns any input (code, docs, papers, images, videos) into a persistent knowledge graph with god nodes, community detection, and query/path/explain tools

**eli5** — explains any topic, code, or error tailored to a specific audience (age, grade level, job role, or relationship). Source: [DreambigOu/ELI5](https://github.com/DreambigOu/ELI5)

**open-slide** — CLI (not a skill) that scaffolds a slides workspace with Claude Code skills preconfigured. Installed globally via `npm install -g @open-slide/cli`; run `npx @open-slide/cli init <name>` to scaffold a new workspace. [open-slide.dev](https://open-slide.dev)

## Writing tips for an AI

Notes I give AI tools when asking them to write or edit prose, kept in the language I originally wrote them in (Traditional Chinese).

### 核心撰寫原則

1. **請勿憑空捏造任何內容**

沒有足夠資訊時，不要自行補完。事實、推論與不確定資訊要清楚區分。

2. **Trust the reader. Do not over-explain.**

沒有必要為尚未被質疑的問題主動進行預防性辯解。

如果原文本身沒有明顯漏洞，也沒有容易引起合理質疑的地方，就不要為了回應假想中的反對意見，額外補充解釋、辯護或限定語。

文字說到足夠即可，不必提前堵住每一個可能的誤解。只有在確實容易造成誤解、需要澄清，或讀者很可能提出合理疑問時，才補充必要說明。

3. **結構清晰**

* 結論優先：重要觀點放前面。
* 層次分明：開頭、正文、結尾各有功能。
* 善用標題與條列，但不要過度切割。

4. **邏輯嚴謹**

* 前後一致：論點與結論不可互相矛盾。
* 推理合理：重要主張要有足夠依據。
* 避免跳躍：段落與觀點之間要自然銜接。
* 不要把推測或判斷寫成既定事實。

5. **用字精準**

* 說人話：少用冷僻字、官腔與過度華麗的修辭。
* 刪除廢話：避免空洞、重複或沒有實質作用的句子。
* 意義明確：用最簡單、最準確的方式表達。
* 能短則短，但不要為了簡潔犧牲準確性。

6. **內容完整，但不要為了完整而冗長**

* 言之有物：重要觀點要有事實、數據、例子或推理支撐。
* 交代必要背景，但不要加入與核心內容無關的資訊。
* 同一個觀點說清楚一次即可。
* 不需要為了形式強行加入總結。

7. **節奏流暢**

* 長短句交錯，避免句型過於單一。
* 適度分段與留白，降低閱讀負擔。
* 避免大量使用制式轉折語。
* 寫完後重新閱讀；卡住、冗長或需要重讀的地方就修改。

8. **忠於原意**

潤飾或改寫時，不要擅自改變原文的立場、語氣強弱、確定程度、因果關係或原本意圖。

9. **不要機械套用規則**

所有結構、解釋、例子與修辭都必須有實際作用。

**寫需要寫的，不寫不需要寫的；知道的說清楚，不知道的不要補。**

## Scope Deletion

A rule I give AI coding/writing tools for how to handle content I ask them to remove, so a one-time deletion doesn't quietly turn into a new standing instruction.

Do not confuse **state modification** with **instruction accumulation**.

A deletion must not become a constraint. A correction must not leak into the artifact. A meta-correction must not recursively generate another rule.

當使用者表示某內容不需要、不屬於 scope 或應移除時，視為 **scope deletion**：從產物及相關 contract surfaces 中直接刪除，後續視同從未存在。

除非明確要求保留紀錄，否則不得將刪除或修正轉化為規則、negative constraint、警告、註解、版本說明或其他 meta-language。

**Deletion is not prohibition. Correction should leave no residue.**

## CLAUDE.md preset

@AGENTS.md

### Rules for Coding

#### Prime Directive

**There is nothing so useless as doing efficiently that which should not be done at all.**

Before optimizing execution, confirm that the proposed work is necessary, appropriate, and aligned with the actual objective.

#### 1. Read Before You Write

Inspect the relevant files, code, configuration, documentation, and surrounding context before making changes.

Do not modify code you have not first understood in context.

#### 2. Understand Before You Modify

Determine what the existing system does, why it behaves that way, and what constraints it operates under before proposing a change.

Do not treat symptoms without understanding the underlying behavior.

#### 3. State Assumptions Explicitly

When information is uncertain or incomplete, state the assumption being made before acting on it.

Do not silently convert uncertainty into fact.

#### 4. Do Not Invent Architecture

Work with the architecture that actually exists.

Do not fabricate abstractions, services, interfaces, dependencies, conventions, or future requirements that are not supported by the repository or the task.

#### 5. Prefer the Smallest Correct Change

Make the simplest change that fully solves the problem.

Minimize affected files, dependencies, abstractions, and behavioral surface area. Complexity requires justification.

#### 6. Do Not Refactor for Display

Do not rewrite, restructure, generalize, or modernize unrelated code merely to demonstrate sophistication.

Refactoring is justified only when it materially improves the requested change, correctness, maintainability, or safety.

#### 7. Every Change Must Be Explainable

Each meaningful action should have a clear reason tied to evidence, requirements, or an identified problem.

If a change cannot be explained simply, reconsider whether it should be made.

#### 8. Verify the Result, Not Just the Edit

After making changes, inspect the resulting behavior and output.

Do not assume that syntactically valid code or a successful edit means the task is complete.

#### 9. Test Before Delivery

Run the relevant tests, checks, builds, linters, type checks, or validation commands before declaring the work complete.

If verification cannot be performed, state exactly what was not verified and why.

#### 10. Learn From Repeated Failures

When the same class of error occurs more than once, record the lesson and adjust the approach so it is not repeated.

Repeated mistakes should produce durable improvements in reasoning, process, tests, or documentation.

#### 11. Preserve What Does Not Need to Change

Treat existing working behavior as a constraint.

Avoid unrelated edits and preserve established interfaces, conventions, and behavior unless changing them is necessary to accomplish the task.

#### 12. Completion Requires Evidence

A task is complete only when:

* the relevant context was inspected;
* the requested change was implemented;
* assumptions and limitations are explicit;
* unnecessary scope was avoided;
* the resulting behavior was verified; and
* relevant tests or checks were run successfully, or any inability to run them was clearly disclosed.

**Default operating principle: understand first, change minimally, verify rigorously.**

## Copywriting Guide

### Copywriting Notes

**1. The offer carries the sale**

Gary Halbert: "Your offer is by far the most important element in the entire sales message."

A strong message cannot rescue a weak offer. Before refining the copy, make sure the offer itself is compelling:

* What does the buyer receive?
* Why is it valuable now?
* Why is it better, safer, easier, or more distinctive than the alternatives?
* What reduces their risk or increases urgency?

Practical rule: Improve the offer before spending hours polishing the wording.

**2. Call out the right market immediately**

Eugene Schwartz: Call your market into the headline.

The reader should quickly feel: "This is for me." Use the headline to identify the audience, situation, problem, or aspiration.

Example:
Instead of: "A Better Way to Build Your Business"
Write: "For Independent Consultants Who Want More Qualified Leads Without Posting Every Day"

Practical rule: Specific relevance earns attention.

**3. Make the outcome more valuable and believable**

Alex Hormozi: Increase the dream outcome and the perceived likelihood of achieving it; decrease time delay and effort.

People evaluate an offer through four questions:

1. What result do I get?
2. How likely is it to work for me?
3. How long will it take?
4. How much effort, sacrifice, or risk will it require?

Practical rule: Strengthen the desired result, make proof visible, shorten the path, and remove unnecessary work.

**4. Write for the customer, not for yourself**

Jim Edwards: Nobody cares about you in your sales copy.

Customers care about their own problems, desires, risks, and identity. Company history, credentials, and features matter only when they clearly help the reader get what they want.

Weak: "We have developed an innovative, proprietary solution."
Better: "Get a clear weekly plan for finding clients, without guessing what to post or whom to contact."

Practical rule: Turn every "we" statement into a reason the customer should care.

**5. Use bullets to create curiosity**

Gary Halbert: Reveal enough to create desire, but not enough to satisfy curiosity.

A bullet should present a compelling benefit, unexpected insight, or intriguing mechanism—then leave the reader wanting the explanation.

Example:
"The simple 'two-question' follow-up that turns silent prospects into booked calls—without sounding desperate."

Practical rule: A bullet should make the reader want the next sentence, the next section, or the product itself.

**6. Specific facts beat vague adjectives**

David Ogilvy: Specific facts beat vague adjectives.

Words such as "amazing," "revolutionary," "premium," and "powerful" are usually weak unless supported by a fact.

Weak: "A powerful system for improving conversion."
Better: "A five-email sequence designed to recover abandoned leads within 72 hours."

Practical rule: Replace broad praise with numbers, names, time frames, steps, examples, or concrete outcomes.

**7. Respect the reader's intelligence**

David Ogilvy: The customer is intelligent. Write like you respect them.

Do not rely on exaggerated claims, empty hype, or simplistic manipulation. Explain the logic, provide evidence, and let the reader reach a confident conclusion.

Practical rule: Make bold claims only when you can make them credible.

**8. Differentiate through the mechanism**

Eugene Schwartz: When every competitor makes the same promise, change the mechanism.

In crowded markets, everyone claims to save time, increase revenue, improve confidence, or create results. The differentiator is often how your solution produces that result.

Example:
Generic promise: "Lose weight without giving up your favorite foods."
Distinct mechanism: "Use a high-satiety meal framework that reduces cravings before willpower becomes necessary."

Practical rule: Do not merely promise a better result. Explain the distinctive path that makes it possible.

**9. Treat the headline as the highest-leverage line**

John Caples: If you create a good headline, your task is more than half completed.

The headline determines whether the rest of the message gets read. It should earn attention through relevance, clarity, specificity, curiosity, or a strong promise.

A useful headline often includes:

* A desired outcome
* A defined audience
* A problem or obstacle
* A unique mechanism
* A credible time frame or qualifier

Practical rule: Write multiple headline options before settling on one. The first headline is rarely the strongest.

**10. Sell the transformation, not the object**

Tony Robbins: People do not buy products; they buy a better version of themselves.

People buy what the product enables: confidence, relief, status, security, freedom, competence, belonging, or identity.

Example:
Customers do not buy a productivity app. They buy the feeling of being organized, dependable, and in control.

Practical rule: Describe the person the customer becomes after using the product.

### Modern Additions (AI & Social Era)

Distilled from a synthesis of the ten lessons above against current research and platform guidance — the parts that weren't already covered.

**11. Distinctive provenance beats fluent prose**

In an AI-saturated market, generic fluency is cheap. What's scarce: first-hand experience, original data, a named point of view, verifiable specifics.

Practical rule: State where the insight came from — a call, a test, a build — not just the conclusion.

**12. Research the buyer-in-a-moment, not the demographic**

A specific person, facing a specific trigger, trying to make a particular improvement, under particular constraints — not an age/role label. Learn their trigger, current method, alternatives considered, objections, and what evidence they'd need to believe you.

Practical rule: Write from a real decision you observed, not an imagined persona.

**13. Climb the proof ladder as the claim gets bigger**

Explanation → concrete detail → demo → first-party data → independent corroboration (attributable case, real review) → risk-bearing commitment (trial, guarantee, SLA).

Practical rule: Match evidence weight to how consequential, expensive, or unusual the claim is.

**14. Match the CTA to buyer readiness**

Unaware → watch/read/save. Problem-aware → compare/diagnose. Solution-aware → trial/demo. Ready → buy/subscribe. Existing customer → activate/refer.

Practical rule: Don't ask for "buy now" from someone who just discovered the problem exists.

**15. Run the sameness test**

Delete the brand name. If the copy could describe three competitors, it lacks evidence, mechanism, or point of view.

Practical rule: Add a constraint, a number, or a stance until it's no longer swappable.

**16. Promise and delivery are one system now**

In algorithmic/social distribution, a hook that overpromises can win a click but tank completion, retention, and future reach. The opening is a gate; the body must pay it off.

Practical rule: Judge headlines by downstream engagement and conversion quality, not just click-through.

**17. Use AI to research and edit, not to author claims**

Use it to organize interviews, cluster objections, generate divergent angles, and flag vague or unsupported language. Keep claim selection, proof choice, and point of view human — and verify every number, quote, and comparison before publishing.

Practical rule: If AI drafted it, a human must still be able to say exactly why each claim is true.

**18. Don't fabricate proof, scarcity, or relationships**

Manufactured testimonials, fake urgency, and undisclosed commercial relationships are unethical and, in the US, can be illegal under FTC rules on reviews and endorsements.

Practical rule: Real, disclosed, and modest beats fake, hidden, and impressive.

### Copywriting Checklist

Before publishing a sales message, ask:

* Is the offer genuinely strong?
* Does the headline clearly call out the right reader?
* Is the desired outcome vivid and valuable?
* Have I shown why the result is believable?
* Have I reduced perceived time, effort, and risk?
* Is the copy focused on the customer rather than the business?
* Are the bullets specific, desirable, and curiosity-driven?
* Have I replaced vague claims with concrete facts?
* Does the message respect the reader's intelligence?
* Is the mechanism distinct from competitors?
* Am I selling the customer's transformation, not merely the product?

### Core Principle

The best copy makes a valuable offer feel relevant, credible, distinct, and personally meaningful—then makes the next step feel easy.

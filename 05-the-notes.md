# The Notes

## Here are the skills I use

Grouped by where they actually come from — checked against `~/.claude/plugins/installed_plugins.json` and `~/.claude/skills/` on disk, not just guessed from the name.

### Built-in (ships with Claude Code — not installed, can't be removed)

**Claude Code / config**
- update-config, keybindings-help, fewer-permission-prompts, init, run, claude-api

**Code review**
- code-review, simplify, security-review

**Scheduling / automation**
- loop, schedule

**Artifacts & data viz**
- artifact-design, artifact-diagramming, artifact-capabilities, dataviz, design (Claude Design canvas)

**Anthropic-authored document/office skills**
- anthropic-skills:docx, anthropic-skills:pptx, anthropic-skills:xlsx, anthropic-skills:pdf

**Anthropic-authored misc**
- anthropic-skills:consolidate-memory, anthropic-skills:explain-usage, anthropic-skills:import-memory, anthropic-skills:morning, anthropic-skills:schedule, anthropic-skills:setup-cowork, anthropic-skills:setup-writing-style, anthropic-skills:skill-creator

### Installed via plugin marketplace (tracked in `~/.claude/plugins/installed_plugins.json`)

**Vercel**
- vercel:bootstrap, vercel:deploy, vercel:env, vercel:marketplace, vercel:status, vercel:ai-gateway, vercel:ai-sdk, vercel:auth, vercel:chat-sdk, vercel:deployments-cicd, vercel:env-vars, vercel:knowledge-update, vercel:microfrontends, vercel:next-cache-components, vercel:next-forge, vercel:next-upgrade, vercel:nextjs, vercel:react-best-practices, vercel:routing-middleware, vercel:runtime-cache, vercel:shadcn, vercel:turbopack, vercel:vercel-agent, vercel:vercel-cli, vercel:vercel-connect, vercel:vercel-firewall, vercel:vercel-functions, vercel:vercel-sandbox, vercel:vercel-storage, vercel:verification, vercel:workflow

**Context7 (docs)**
- context7-plugin:context7, context7-plugin:docs, context7-plugin:context7-mcp, context7-plugin:docs-researcher (agent)

**Superpowers (workflow/process)**
- superpowers:brainstorming, superpowers:dispatching-parallel-agents, superpowers:executing-plans, superpowers:finishing-a-development-branch, superpowers:receiving-code-review, superpowers:requesting-code-review, superpowers:subagent-driven-development, superpowers:systematic-debugging, superpowers:test-driven-development, superpowers:using-git-worktrees, superpowers:using-superpowers, superpowers:verification-before-completion, superpowers:writing-plans, superpowers:writing-skills

**UI/UX**
- ui-ux-pro-max:ui-ux-pro-max

**Ponytail** — forces the simplest/laziest solution that still works; question whether code needs to exist at all before writing it
- ponytail, ponytail-review, ponytail-audit, ponytail-gain, ponytail-debt, ponytail-help

**Impeccable** — design fluency for frontend work: polish, audit, critique, animate, and 23 total commands for UI quality (`/impeccable polish`, `/impeccable audit`, etc.)
- impeccable

### Installed via skills manager (symlinked or copied into `~/.claude/skills` from `~/.agents/skills`)

**Animation & Motion**
- animate, animate-expo, animation-vocabulary, apple-design, find-animation-opportunities, improve-animations, review-animations, gsap-core, gsap-frameworks, gsap-performance, gsap-plugins, gsap-react, gsap-scrolltrigger, gsap-timeline, gsap-utils

**Design / UI (frontend & visual)**
- design-taste-frontend, design-taste-frontend-v1, hallmark, high-end-visual-design, minimalist-ui, industrial-brutalist-ui, gpt-taste, stitch-design-taste, redesign-existing-projects, emil-design-eng

**Image generation**
- brandkit, imagegen-frontend-mobile, imagegen-frontend-web, image-to-code

**Video / HyperFrames**
- hyperframes, hyperframes-animation, hyperframes-cli, hyperframes-core, hyperframes-creative, hyperframes-keyframes, hyperframes-registry, general-video, media-use

**Toasts / notifications**
- ask-sonner, telegram-notify

**Writing / language**
- speak-human-zh-tw, full-output-enforcement

**Swift**
- write-swift

### Installed via dedicated tool installer (own version tracking, not the plugin system or the generic skills manager)
- graphify — turns any input (code, docs, papers, images, videos) into a persistent knowledge graph with god nodes, community detection, and query/path/explain tools. Tracked via its own `.graphify_version` file (currently 0.9.49).

### Manually installed (dropped straight into `~/.claude/skills`, no package manager tracking)
- eli5 — explains any topic, code, or error tailored to a specific audience (age, grade level, job role, or relationship). Source: [DreambigOu/ELI5](https://github.com/DreambigOu/ELI5)

## Writing tips for an AI

# 核心撰寫原則

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

Do not confuse **state modification** with **instruction accumulation**.

A deletion must not become a constraint. A correction must not leak into the artifact. A meta-correction must not recursively generate another rule.

當使用者表示某內容不需要、不屬於 scope 或應移除時，視為 **scope deletion**：從產物及相關 contract surfaces 中直接刪除，後續視同從未存在。

除非明確要求保留紀錄，否則不得將刪除或修正轉化為規則、negative constraint、警告、註解、版本說明或其他 meta-language。

**Deletion is not prohibition. Correction should leave no residue.**

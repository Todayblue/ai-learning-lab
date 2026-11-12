# Hand Off — AI Engineering Learning Journey

- Schema: hand-off/v1
- Created at: 2026-11-12 (Asia/Bangkok)
- Source as-of: 2026-11-12; live repository checked this session
- Scope: AI learning, verified progress, conceptual gaps, learning resources, and the local AI Learning Lab
- Destination: new ChatGPT AI Mentor conversation; portable Markdown (no hidden memory required)
- Coverage: PARTIAL — full attached historical export (2,967 lines) and accessible current conversation reviewed for relevant topics; other unseen conversations are excluded
- Resume readiness: CONDITIONAL — safe to review and select a lesson; lab execution depends on fresh environment inspection and user selection
- Authority: Context handoff only; never grants installation, coding, Git, API spending, or runtime permissions

## Executive brief

Learner is a software developer experienced with C#, .NET, REST APIs, SQL, databases, and backend architecture, but a beginner in ML/model internals. Goal: understand how AI really works, then build employable AI Application/Software Engineering skills (LLMs, RAG, agents/harness, reliability). Teach primarily in Thai with English technical terms, Big Picture First, simple examples, diagrams, one concept at a time, hands-on observation, active recall, YAGNI. Include a clickable Next Session button where supported.

The learner reports finishing 3Blue1Brown "But what is a neural network?" (Chapter 1); explanatory lessons through Gradient Descent and many later LLM topics were delivered. There is NO confirmed successful hands-on lab or tested PyTorch environment. The repeated difficulty is mapping words/tokens to actual numeric tensors, dimensions, weights, neurons, and outputs. The next small useful step is a local numerical lab with one or two weights, showing prediction, loss, gradient, and update, then a 4-feature-to-2-neuron experiment. Do not silently start Lab 1.

Live Mac repository: /Users/todayisblue/Documents/GitHub/personal/ai-learning-lab; branch main, clean before handoff writing, only README.md in the initial tree. No existing docs/labs/AGENTS.md found. The original handoff-creation task authorized only three Markdown files. That historical scope is not ongoing execution authority; later changes require a new, explicit task authorization.

## Coverage manifest

| Workstream | Source/evidence | Included | Limitation |
| --- | --- | --- | --- |
| Original mentor contract / learning map | Historical export, 2026-11-06, around lines 1427–1602 | Language, levels, six teaching principles, commands, button, YAGNI | Assistant lesson content does not prove user comprehension |
| AI Harness / career direction | Historical export, 2026-11-04 to 11-06, lines 9–1425 | Model vs app, harness, tools, evaluation, .NET AI path | Recommendations are not user-approved implementations |
| 3Blue1Brown and core ML | Export, 2026-11-10 to 11-11, lines 2149–2967 | Ch.1 viewing report, 13,002 parameters, training/inference, Gradient Descent explanation | Ch.2 viewing / Chapter 3 completion unconfirmed |
| Follow-up concept study | Accessible current conversation through 2026-11-12 | Activation, forward pass, embedding dimensions, tokens, LLM/RAG, vector DB | Understanding checks displayed, no recorded selections/results |
| Actual repository | Remote Desktop Commander live read-only before creation, 2026-11-12 | README, branch, Git status, absence of labs/docs | Python, PyTorch, MPS, installed packages not inspected |
| Hardware | User-provided Mac screenshot / statement | MacBook Pro M2, 16 GB RAM; preferred free local labs | Current RAM/disk/tool readiness not rechecked via host commands |

## Learner profile and goals (CONFIRMED)

- Background: software developer; C#, .NET, APIs, SQL, backend and software architecture.
- Learning: Thai explanations, standard English technical terms; understandable visuals and numbers before abstractions; examples connected to backend development.
- Career: AI Application Engineer / AI Software Engineer; optionally progress to AI Systems/ML Engineering.
- Preference: local, free, lightweight and reproducible on MacBook Pro M2 16GB; avoid paid APIs/cloud by default. Learner performs meaningful steps; do not over-automate.
- Lesson format: LEVEL 1 overview by default; LEVEL 2 architecture/data flow on request; LEVEL 3 mathematics/code/labs on explicit request. One meaningful concept at a time. End learning sessions with Understanding Check and clickable Next Session where supported.
- Learning commands: เริ่ม, ต่อ, แผนที่, เจาะลึก, ตัวอย่าง, ลองทำ, ทดสอบ, สรุป, กลับภาพใหญ่, Add-on.

## Verified local repository and environment (2026-11-12)

- Device online via Remote Desktop Commander: MacBook-Pro-khxngTodayis.local.
- Repository: /Users/todayisblue/Documents/GitHub/personal/ai-learning-lab
- Git remote (user-provided): https://github.com/Todayblue/ai-learning-lab
- Branch: main; initial status: clean, tracking origin/main; latest pre-handoff commit: 5a061b34db70fde0cd3c1aa3f2d78683c5c8ba2a ("Initial commit", 2026-11-12 12:01:52 +0700).
- Initial repo contents: README.md only, containing "# ai-learning-lab". No AGENTS.md, docs/ or labs/.
- Host Python version, virtualenv, torch, Ollama, free disk, hardware acceleration: UNKNOWN (not inspected; do not assert installed).
- After handoff creation, expect docs/learning/ with three new, uncommitted Markdown files; independently recheck in next conversation.

## Learning map (flexible, not a forced schedule)

| Area | Priority | Position |
| --- | --- | --- |
| AI / ML / Deep Learning / Generative AI distinctions | CORE | EXPLAINED |
| Neural Networks: neurons, weights/biases, activation, parameters | CORE | EXPLAINED; Chapter 1 viewing CONFIRMED |
| Training vs inference, loss, gradient descent, backprop | CORE | Gradient descent EXPLAINED; calculation practice not verified |
| LLM fundamentals: tokenization, embeddings, dimensions, Transformer, attention, output probabilities | CORE | EXPLAINED repeatedly; needs numerical reinforcement |
| AI Application: prompt, context, APIs, structured output | CORE | Conceptual exposure; hands-on UNKNOWN |
| Retrieval: vector search, vector DB, RAG | CORE LATER | EXPLAINED; labs not implemented |
| Agents and Harness: tools, MCP, state, security, evaluation | ADD-ON / later | Architectural introduction EXPLAINED |
| Reliable AI: tests, evals, privacy, cost, observability | ADD-ON / later | Introduced only |
| Training from scratch, fine-tuning, deeper ML maths | ADD-ON | Not yet practiced |

Status vocabulary: CONFIRMED = explicit learner statement or checked evidence of a specific fact; EXPLAINED = a topic was taught but not necessarily understood; UNDERSTOOD = comprehension demonstrated in an answer, explanation, or exercise (not automatically a completed lab); PRACTICED = actual exercise evidence; COMPLETED = verified lab acceptance; PLANNED = proposed but not started; UNKNOWN = evidence insufficient.

## History and evidence-based progress

1. 2026-11-04: Investigated Google AI Harness crash course, then Google vs Anthropic vs OpenAI. Covered context/memory, tools/MCP/workflows, runtime/privacy/security, evals. This is background and not a current coding objective.
2. 2026-11-04–06: Discussed AI Software Engineering career path, .NET / PostgreSQL / RAG / Agents and potential portfolio projects. Earlier AI Issue Triage Assistant was a proposal, NOT an approved build.
3. 2026-11-06–10: Began AI Engineering Journey Sessions 1–3: model vs application, AI/ML/DL/GenAI, supervised learning/training vs inference. Delivered explanations; do not mark understanding checks as passed.
4. 2026-11-10: User explicitly said: "ผมดูวิดีโอ 3Blue1Brown 'But what is a neural network?' (Deep Learning Chapter 1) จบแล้ว". This is CONFIRMED self-report of completing viewing, not a graded comprehension result.
5. 2026-11-10–11: Explored 784→16→16→10 (28×28 image, 10 digit classes) with 12,960 weights + 42 biases = 13,002 parameters; difference between 12,900 mistaken and 12,960 correct; neuron formulas and role of biases.
6. 2026-11-11: User asked to continue learning Gradient Descent based on 3Blue1Brown Chapter 2. Assistant explained gradients, loss, learning rate. Viewing the Chapter 2 video was NOT explicitly confirmed. Backpropagation video suggested but not confirmed watched.
7. Current conversation through 2026-11-12: Revisited activation (ReLU/Sigmoid/Tanh/Softmax), forward propagation, where inputs and initial weights come from, Transformer/LLM and model knowledge vs external memory/vector DB, text→token→embedding→attention/FFN→logits→decoding, parameter counting for fully connected layers, 1 scalar input vs 4 features, embedding dimension selection and "Hi"/"Hello" similarity. These topics are EXPLAINED, not proven mastered.
8. User supplied screenshot showing M2 16 GB, explicitly requested hands-on local labs after saying explanations were hard to picture, then reported cloned repo. Prior assistant proposed Lab 1 with PyTorch and roadmap; no real run output or lab completion is on record.

### Important accurate mental models for review

- Dense layer with bias: parameters = (input features × output neurons) + output neurons. Example 4→2: 8 weights + 2 biases = 10.
- One token can produce a vector with 4, 768, or other model-defined dimensions; token count and feature count are different.
- Parameters include learned embedding table, attention projections, FFN and other learned tensors. A pretrained language model does NOT require a vector DB; RAG retrieval is external.
- Layer forward pass: z = Wx + b; a = activation(z). Training updates parameters from loss gradients, while standard inference usually does not.
- Individual embedding dimensions do not have guaranteed human-readable labels; cosine similarity examples used in lessons were illustrative, not real model vectors.
- Distinguish *a token lookup in model embedding weights* from *retrieval against an external vector database*.

## Concepts to reinforce / open questions

- Highest-priority confusion: where numeric input comes from, how token ID becomes embedding vector, how 1 token with 4 features reaches multiple neurons, and which weights/biases are used for each computation.
- How training changes an actual weight after observing a loss/gradient rather than showing invented numbers.
- How learned embeddings/attention representations relate to next-token prediction without implying "LLM retrieves the nearest word vector."
- How activation output from one neuron is propagated to the next layer with new connection weights.
- Separate "one input sample" from "one scalar input feature".
- Confirm current Python/tool availability and desired coding pace once an actual lab is selected.
- Confirm whether Chapter 2 video was watched before treating it as complete; Chapter 3 Backpropagation may be the next *video* after the learner is comfortable with gradient concepts.

## Resources (original or official links used in lessons)

- 3Blue1Brown Ch.1: https://www.3blue1brown.com/lessons/neural-networks/
- 3Blue1Brown Ch.2: https://www.3blue1brown.com/lessons/gradient-descent/
- 3Blue1Brown Backpropagation: https://www.youtube.com/watch?v=Ilg3gGewQ5U
- 3Blue1Brown Transformer: https://www.3blue1brown.com/lessons/gpt/
- Google ML Crash Course: https://developers.google.com/machine-learning/crash-course/
- Hugging Face LLM Course: https://huggingface.co/learn/llm-course/
- PyTorch intro: https://pytorch.org/get-started/locally/
- PyTorch nn.Embedding: https://docs.pytorch.org/docs/stable/generated/torch.nn.Embedding.html
- Microsoft Generative AI for Beginners (.NET): https://github.com/microsoft/Generative-AI-for-beginners-dotnet
- Karpathy Zero to Hero: https://karpathy.ai/zero-to-hero.html
- Anthropic effective agents: https://www.anthropic.com/research/building-effective-agents
- Google AI Harness: https://g.dev/ai/ai-harness

## Practical Lab roadmap (PLANNED, not implemented)

- Lab 1A (RECOMMENDED FIRST): One scalar input, one weight, optional bias; inspect output, target, squared-error loss, gradient sign, one optimizer step, and before/after values. Start with Python arithmetic or very small PyTorch script after environment verification. This is intentionally smaller than the earlier proposed Embedding→Dense lab.
- Lab 1B: 4 features → 2 neurons, ReLU. Show input shape, weight matrix 2×4, bias shape 2, parameter count 10, weighted sums and activations; edit one weight and compare outputs.
- Lab 2: Tiny trainable network with 3–5 samples; observe updates, training vs inference, loss across steps.
- Lab 3: Real tokenizer and pretrained small embedding/Transformer; print token IDs, embedding shapes and actual values. Do not mislabel an untrained random lookup as semantic understanding.
- Lab 4: Visualize small self-attention Q/K/V, scores, weights and outputs; later inspect a pretrained model.
- Lab 5: Local lightweight LLM inference on M2 if resources permit (verify versions/requirements before installing; no paid APIs).
- Lab 6: Five synthetic documents → embeddings → local vector search → retrieved snippets → RAG. Prefer simple local search first; pgvector only if it solves a learning need.
- Later: portfolio .NET AI app (e.g., issue triage / document Q&A), RAG evaluation, MCP/tool calling and reliability.

Proposed lab acceptance: user can print actual input/weight/bias/forward output/loss/gradient; change one weight and observe predicted effect; explain each value; no requirement to download a large model or use cloud.

## Decisions, constraints, and rationale

- Active: Big Picture First; minimal math until concrete need; one concept at a time, visual, step-by-step, genuine computation. Use Thai with standard technical English.
- Active: Learning in the named repo, free/local first, beginner-friendly; explicitly distinguish EXPLAINED from PRACTICED/COMPLETED.
- Historical scope of the original handoff task (2026-11-12): three Markdown files only; no lab code, packages, cloud, Git stage/commit/push, or global config. This records past authorization, not a permanent constraint on new explicitly authorized tasks.
- No accepted implementation architecture exists for labs; earlier Python/PyTorch and Ollama suggestions are proposals, not completed setup.
- Reason for choosing Lab 1A: repeated questions about numerical meaning of inputs, embedding vectors, weights and activation indicate a more inspectable 1-weight example is useful before adding Transformer internals.

## Evidence and provenance

- Historical transcript as supplied in current chat: "ChatGPT-ตรวจสอบ AI Harness Links-20261112-1209.md", export metadata 2026-11-12 12:09:49 (source conversation updated 2026-11-11 15:29:26). The instruction attachment named a variant "(2).md"; actual attached basename in this session lacked "(2)"; content was inspected. New chat does not need historical export if this handoff is available.
- Current ChatGPT conversation contains later follow-ups and the user's reported clone path; it is summarized above, not attached separately here.
- Remote Desktop Commander read-only checks: directory listing, README read, branch/Git status/log on 2026-11-12. Verify the live repo again before doing any lab work.
- User-supplied Mac screenshot: hardware is REPORTED / visually supported; tool installation not checked.
- Links above are source references for future study, not proof the learner opened every page or completed every course.

## Open issues and readiness

- UNKNOWN: current Python version, package installation, .venv, disk headroom, torch/MPS and test commands on host.
- UNKNOWN: Chapter 2 viewing completion, active comprehension check answers, or prior successful practical labs outside inspected repo.
- No code, training, downloads, Git commits or pushes authorized by this handoff.
- Resume readiness: CONDITIONAL for execution; READY for read-only lesson planning and verifying current environment.

## Next safe actions

1. Inside the ChatGPT Project "AI Engineering Journey", apply its Project Instructions and read this handoff from Project Sources; outside the Project, read the reusable mentor role too. Inspect README/Git status before a lab when relevant.
2. Briefly report confirmed vs explained vs unknown, and present one smallest next exercise.
3. Offer Lab 1A (one weight, loss, gradient, update) as the recommended first experiment. Do not create/install/run until the learner selects it.
4. Optional video next: confirm Chapter 2 viewed or revisit its intuition; Chapter 3 Backpropagation is reasonable only once Gradient Descent is understood.
5. For any mutation, honor the current request's allowed paths and tool permissions; never assume the handoff grants authority. Stop if repository state has drifted or conflicting edits appear.

## Bootstrap for new chat

See ./resume-new-chat.md for the project-aware copy-paste prompt. In the ChatGPT Project "AI Engineering Journey", Project Instructions v1.2 define the teaching role and this file is the main Project Source. For chats outside the Project, ./ai-mentor-big-picture-first.md remains the reusable role. Uploaded Project Sources do not automatically synchronize with local repo edits; confirm freshness before relying on status. The full historical transcript need not be reattached when this handoff is available.

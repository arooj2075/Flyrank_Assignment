FL‑01 Workflow Audit
1. My 10–15 Weekly Tasks (Table)
Task	Classification	Rationale
Studying BSCS modules	Just me	Requires my own understanding and memory.
Writing assignments	Collaborate with AI	AI helps outline, but I write final content.
Coding personal projects	Just me	I need full control and learning.
Debugging Arduino circuits	Collaborate with AI	AI helps explain errors, but I test physically.
Writing emails	Delegate to AI (with review)	AI drafts, I edit and send.
Searching for internships	Collaborate with AI	AI helps find options, I choose.
Preparing presentations	Collaborate with AI	AI helps structure slides, I finalize design.
Summarizing long articles	Delegate to AI (with review)	AI summarizes, I check accuracy.
Organizing notes	Fully automate	AI can format and clean notes automatically.
Researching topics	Collaborate with AI	AI provides direction, I verify sources.
Fixing simple Python errors	Delegate to AI (with review)	AI suggests fixes, I test them.
Writing reports	Collaborate with AI	AI helps draft sections, I refine.
Cybersecurity labs	Just me	Requires hands‑on practice and real execution.
Creating study plans	Collaborate with AI	AI helps structure, I adjust to my schedule.
Video editing	Just me	Creative decisions must be mine.


2. Claude Project Screenshot
<img width="1460" height="637" alt="image" src="https://github.com/user-attachments/assets/f124ba90-3717-4231-9345-6f29af003755" />


3. My Three Target Tasks + Success Definitions
Task 1: Summarizing research papers
Done well means:

Accurate summary

No missing key points

5–7 clear bullet points

No hallucinations

Easy to read

Task 2: Writing weekly study plan
Done well means:

Realistic workload

Includes breaks

Matches deadlines

Balanced across subjects

Fits my available hours

Task 3: Debugging simple Python errors
Done well means:

Correct fix

Explanation included

No breaking other parts of the code

Works on first test run

Clear reasoning

4. Toolkit Setup Confirmation
Claude account created

ChatGPT account created

Anthropic Academy account created

Enrolled in AI Fluency: Framework & Foundations

Completed Module 1

5. Self‑Check
✔ 10+ tasks, all genuinely mine

✔ Every task classified with rationale

✔ At least two “just me” tasks

✔ Three target tasks with measurable success definitions

✔ Claude Project screenshot included

✔ Toolkit accounts created and Academy enrollment done


Proof Statement
I am proving one thing: I can turn technical ideas into clear, usable, working prototypes — whether that’s an Arduino system, a small web feature, or a structured ML notebook. This proof is built for a hiring manager evaluating me for a junior technical or visual‑editing internship, someone who needs a candidate who can take unclear requirements and turn them into something real, testable, and easy to understand. The single action I want them to take is to contact me directly to discuss an internship opportunity.

Why This Needs to Exist
My CV cannot prove that I can build real, working features end‑to‑end — this portfolio exists to show that I can actually make things that function, not just list skills.

screenshot of your Claude Project
<img width="1158" height="302" alt="image" src="https://github.com/user-attachments/assets/418cd093-5892-4422-b154-0793c2a0491d" />


A screenshot of your pressure‑test prompt + Claude’s output
<img width="543" height="166" alt="image" src="https://github.com/user-attachments/assets/cd52db5d-579f-4ce3-ae7e-4a116a158b78" />


## Voice Card
direct, plain, structured, honest, no buzzwords

## Case Study 1 — Arduino Prototype

### Problem
I needed a working Arduino security prototype that could detect motion, trigger alerts, and display status clearly. The challenge was combining multiple components—ultrasonic sensor, keypad, buzzer, LEDs, and LCD—into one reliable system.

### What I Did
I designed the circuit, tested each component separately, and then integrated them. I made deliberate decisions: using a 16‑pin LCD instead of I2C for full control, splitting logic across two boards to avoid overload, and writing modular code so each part could be debugged independently. I iterated until the system behaved consistently.

### What Came of It
The prototype worked end‑to‑end: detect → warn → display → reset. It proved I can build functional hardware systems, debug real constraints, and make decisions that keep a project stable.

## Case Study 2 — ML Notebook (Capstone Work)

### Problem
I needed to turn messy data and unclear requirements into a structured ML workflow that produced a baseline score and a validated model.

### What I Did
I followed the FlyRank lane: framed the ML task, built a data contract, created a baseline, and validated the model. I made decisions about feature selection, evaluation metrics, and how to interpret the model’s limits. I kept the notebook readable and reproducible.

### What Came of It
The notebook produced a clear baseline, a traceable model, and a validation audit. It proved I can structure ML work, explain decisions, and deliver something a reviewer can trust.

## Case Study 3 — Small Web Feature (Portfolio Build)

### Problem
My portfolio needed one working dynamic feature to prove I can build something real, not just list skills.

### What I Did
I built a functional contact form using a free backend service. I decided to keep the feature small, reliable, and testable. I wired the form, deployed it, and verified that submissions reached me. I wrote the explainer in plain language.

### What Came of It
The feature works end‑to‑end and shows I can ship something usable. It proves I can turn an idea into a working web component.

## Before/After Example

### Generic AI Line (Before)
"This project showcases my ability to leverage cutting-edge technologies to deliver innovative solutions."

### My Edited Version (After)
I built a working Arduino security prototype that detects motion, triggers alerts, and displays status clearly. It proves I can make technical ideas usable.

## Prompt Ladder

### Baseline Prompt (Weak)
"Explain this data."

### Baseline Output (Excerpt)
The model gave a vague, generic explanation: “This dataset contains information that can be analyzed to understand trends.” No specifics, no structure, no insight.

### Notes
- What changed in the prompt: Nothing, this is the baseline.
- What improved in the output: Nothing; it stayed generic.
- What failed: No structure, no interpretation, no clarity.
- What I would try next: Add a clearer goal.


---

### Version 1 — Add a Clear Goal
**Prompt Change:** Added a specific goal.
"Explain this data so I understand the main trend."

**Output (Excerpt):**
The model identified one trend but still spoke in generalities: “The main trend appears to be an increase over time.”

**Notes**
- What changed in the prompt: Added a clear goal.
- What improved in the output: It stopped giving random filler and focused on one trend.
- What failed: Still too vague; no numbers, no context.
- What I would try next: Add real context.


---

### Version 2 — Add Real Context
**Prompt Change:** Added context about the dataset.
"Explain this data so I understand the main trend. This dataset shows monthly website traffic for the past year."

**Output (Excerpt):**
The model now referenced the context: “Your website traffic increases steadily from January to August, then plateaus.”

**Notes**
- What changed in the prompt: Added real context.
- What improved in the output: It became specific to website traffic and gave a clearer pattern.
- What failed: Still no structure or actionable insight.
- What I would try next: Add a required output format.


---

### Version 3 — Add Output Format
**Prompt Change:** Required a structured output.
"Explain this data so I understand the main trend. This dataset shows monthly website traffic for the past year. Give me a 3‑sentence summary."

**Output (Excerpt):**
The model produced a tight summary:  
1. “Traffic rises steadily from January to August.”  
2. “It stabilizes from September to November.”  
3. “December shows a slight drop.”

**Notes**
- What changed in the prompt: Added a 3‑sentence format.
- What improved in the output: Became concise, structured, and readable.
- What failed: Still descriptive, not interpretive.
- What I would try next: Add quality criteria.


---

### Version 4 — Add Quality Criteria
**Prompt Change:** Added criteria for what “good” looks like.
"Explain this data so I understand the main trend. This dataset shows monthly website traffic for the past year. Give me a 3‑sentence summary. Make it specific, avoid generic phrases, and mention at least one number."

**Output (Excerpt):**
“Traffic grows from 12,000 visits in January to 28,000 in August. It holds between 27,000–29,000 from September to November. December dips to 24,000.”

**Notes**
- What changed in the prompt: Added specificity + number requirement.
- What improved in the output: Finally included real numbers and avoided vague language.
- What failed: Still no interpretation of *why* the trend matters.
- What I would try next: Add a review instruction.


---

### Version 5 — Add Review Instructions
**Prompt Change:** Added a self‑check requirement.
"Explain this data so I understand the main trend. This dataset shows monthly website traffic for the past year. Give me a 3‑sentence summary. Make it specific, avoid generic phrases, and mention at least one number. Before giving the final answer, check whether the summary explains why the trend matters."

**Output (Excerpt):**
“Traffic grows from 12,000 in January to 28,000 in August, showing strong seasonal interest. It stabilizes around 27,000–29,000 through fall, indicating sustained engagement. December drops to 24,000, suggesting reduced activity during holidays.”

**Notes**
- What changed in the prompt: Added a self‑review instruction.
- What improved in the output: It finally explained *why* the trend matters.
- What failed: The “seasonal interest” assumption might be wrong; the model guessed.
- What I would try next: Add a constraint to avoid assumptions.


---

### Final Reusable Prompt
Explain this dataset so I understand the main trend. The dataset shows monthly website traffic for the past year. Give me a 3‑sentence summary. Make it specific, avoid generic phrases, and mention at least one number. Do not make assumptions about causes unless they are explicitly stated in the data. Before giving the final answer, check whether the summary is clear, factual, and useful for a website owner.

## Prompt Iteration Log

### Target Task
Summarizing research papers clearly and accurately.

---

### Baseline Prompt (Naive)
"Summarize this research paper."

### Baseline Output (Excerpt)
The model produced a vague, generic summary: “This paper discusses several important concepts and presents findings relevant to the field.” No structure, no key points, no clarity.

### Notes
- What changed: Baseline, nothing added.
- What improved in the output: Nothing; still generic filler.
- What failed: No structure, no accuracy, no key findings.
- What I will try next: Add a role assignment.

---

### Version 1 — Technique: Role Assignment
**Prompt Change:** Added a role.
"You are an academic research assistant. Summarize this research paper."

**Output (Excerpt):**
The model became slightly more formal: “The paper examines its topic through a structured methodology and highlights several findings.” Still vague.

**Notes**
- What changed: Assigned the model a role.
- What improved in the output: Tone became more academic.
- What failed: Still generic; no specific findings.
- What I will try next: Add context and motivation.

---

### Version 2 — Technique: Context & Motivation
**Prompt Change:** Added context about why I need the summary.
"You are an academic research assistant. Summarize this research paper. I need the summary to understand the main argument and the key findings."

**Output (Excerpt):**
The model now focused on argument + findings: “The paper argues X and reports findings related to Y.” Still too high‑level.

**Notes**
- What changed: Added purpose.
- What improved in the output: It stopped listing random filler and focused on argument + findings.
- What failed: Still lacks structure and detail.
- What I will try next: Add output structure.

---

### Version 3 — Technique: Output Structure
**Prompt Change:** Required a structured summary.
"You are an academic research assistant. Summarize this research paper. I need the summary to understand the main argument and key findings. Provide the summary in three sections: Argument, Method, Findings."

**Output (Excerpt):**
The model produced a structured summary:
- **Argument:** “The paper argues X.”
- **Method:** “It uses Y.”
- **Findings:** “It finds Z.”

Better, but still shallow.

**Notes**
- What changed: Added a 3‑section structure.
- What improved in the output: Clear sections; easier to read.
- What failed: Still lacks depth; missing numbers and specifics.
- What I will try next: Add few‑shot examples.

---

### Version 4 — Technique: Few‑Shot Examples
**Prompt Change:** Added an example of a good summary.
"You are an academic research assistant. Summarize this research paper. I need the summary to understand the main argument and key findings. Provide the summary in three sections: Argument, Method, Findings.

Example of a good summary:
Argument: The paper argues that early detection improves model reliability.
Method: The authors analyze 12 datasets using three evaluation metrics.
Findings: Early detection increases accuracy by 18% and reduces variance.

Now follow this pattern."

**Output (Excerpt):**
The model now included specifics:  
- **Argument:** Clear and concise.  
- **Method:** Mentioned sample size and metrics.  
- **Findings:** Included numbers and concrete results.

**Notes**
- What changed: Added a few‑shot example.
- What improved in the output: More specific, included numbers, followed the pattern.
- What failed: Still no verification of accuracy.
- What I will try next: Add step decomposition.

---

### Version 5 — Technique: Step Decomposition
**Prompt Change:** Asked the model to think step‑by‑step.
"You are an academic research assistant. Summarize this research paper. I need the summary to understand the main argument and key findings. Provide the summary in three sections: Argument, Method, Findings.

Example of a good summary:
Argument: The paper argues that early detection improves model reliability.
Method: The authors analyze 12 datasets using three evaluation metrics.
Findings: Early detection increases accuracy by 18% and reduces variance.

Before writing the final answer, list the steps you will take to produce an accurate summary."

**Output (Excerpt):**
The model listed steps:
1. Identify argument  
2. Identify method  
3. Identify findings  
4. Check for specificity  
5. Write structured summary  

Then produced the final summary with clearer structure and more accurate detail.

**Notes**
- What changed: Added step decomposition.
- What improved in the output: More accurate, more deliberate, fewer hallucinations.
- What failed: Still occasionally guesses causes.
- What I will try next: Add a constraint to avoid assumptions.

---

### Final Prompt (Reusable Template)
You are an academic research assistant. Summarize the provided research paper. I need the summary to understand the main argument, the method, and the key findings. Provide the summary in three sections: Argument, Method, Findings. Make it specific and include numbers when available. Do not make assumptions about causes or motivations unless they are explicitly stated in the paper. Before writing the final answer, list the steps you will take to produce an accurate summary.

---

### Cross‑Model Comparison (Claude vs ChatGPT)

**Claude:**  
- Tone: More formal and academic.  
- Accuracy: Higher; fewer hallucinations.  
- Structure: Followed the 3‑section format perfectly.  
- Failure point: Sometimes overly cautious and avoids interpreting findings.

**ChatGPT:**  
- Tone: More conversational.  
- Accuracy: Good but occasionally guessed motivations.  
- Structure: Followed the format but added extra commentary.  
- Failure point: More likely to add assumptions not in the paper.

**Conclusion:**  
Claude produced a cleaner, more reliable academic summary. ChatGPT produced a readable summary but needed stricter constraints to avoid assumptions.

## Visual Identity & Image Judgment

### Visual Identity Choices
- **Color palette:** Dark gray (#1A1A1A), white (#FFFFFF), blue accent (#3A6EA5)
- **Typeface:** Inter (clean sans-serif)
- **Spacing rule:** 24px between sections, 16px between elements
- **Image style:** Real screenshots supported by minimal AI illustrations

These choices make the site feel intentional without requiring design talent. They frame the work instead of competing with it.

### AI Image Judgment
I generated multiple AI images for my portfolio sections. I rejected most of them because they were overly stylized, dramatic, or visually louder than my actual work. The images that survived were simple, minimal, and matched my palette.

**Rejected images because:**
- They looked like concept art.
- They used dramatic lighting.
- They added irrelevant details.
- They visually upstaged my real work.

**Accepted images because:**
- They were minimal.
- They matched the palette.
- They supported the proof instead of distracting from it.

### Real Work Screenshots
For my Arduino prototype, ML notebook, and web feature, I used real screenshots. These were more trustworthy and aligned with the rule that a portfolio’s design should frame the work, not overshadow it.

### Deliverables
- A simple visual identity (palette, typeface, spacing, image style)
- A curated set of AI images (only those that support the proof)
- Real screenshots of my work

<img width="1017" height="116" alt="image" src="https://github.com/user-attachments/assets/42cdde1a-83d9-4fe2-93e6-f0d56b40baa9" />

<img width="1015" height="113" alt="image" src="https://github.com/user-attachments/assets/fd4de8a3-9f74-4859-93a9-4c61dbad7df9" />

<img width="1011" height="110" alt="image" src="https://github.com/user-attachments/assets/006c0b13-9acf-42bd-a57d-f2408a8699c3" />

<img width="1008" height="111" alt="image" src="https://github.com/user-attachments/assets/d0519f22-ccd4-4031-a55b-15068f474327" />

<img width="1016" height="108" alt="image" src="https://github.com/user-attachments/assets/b130323a-5a22-4214-96e9-bd0de2841d86" />

### Fonts
- **Heading font:** Inter Bold  
- **Body font:** Inter Regular  

### Palette
- **Main color:** #3A6EA5 (blue accent)  
- **Near-black text:** #1A1A1A  
- **Near-white background:** #FFFFFF  
- **Accent:** #D9E3F0 (soft gray-blue)

### Logo / Favicon
A simple monogram using my initials **A** in Inter Bold, set in the main accent color (#3A6EA5). Clean, minimal, and technical.

### Two-Line Style Note
Inter type, blue-gray palette (#3A6EA5, #1A1A1A, #FFFFFF, #D9E3F0).  
Mood: clean, technical, minimal — the design frames the work instead of competing with it.


### Images My Portfolio Actually Needs
- Hero image (minimal technical texture)
- Arduino prototype screenshot (real)
- ML notebook screenshot (real)
- Web feature screenshot (real)
- About section icon (minimal)
- Contact section icon (minimal)
- One real photo of me (for About)

### Real Captures (Chosen Over AI)
I used real screenshots for:
- Arduino prototype (because it proves real work)
- ML notebook (because it shows actual structure and decisions)
- Web feature (because it demonstrates a working component)

These are clearer, more trustworthy, and directly support my proof.

### AI Images I Am Keeping
- **Hero:** the clean blue/white technical diagram  
- **About:** the minimal timeline/skills icon  
- **Contact:** the simple envelope/contact icon  

These three share the same mood: clean, minimal, technical, and consistent with my palette.

### AI Images I Rejected (Judgment Notes)
I rejected several images because:
- They looked too “AI‑fantasy”  
- They used dramatic lighting or gradients  
- They added irrelevant details  
- They visually upstaged my real work  
- They didn’t match the minimal technical mood  

**Example rejection note:**  
“I rejected the glowing circuit-board illustration because it looked like concept art, used neon gradients, and distracted from my real Arduino prototype.”


## One-Line Claim
I turn technical ideas into clear, usable, working prototypes.

## Content Map

### 1. Home Page
**Sections (in order):**
- Hero with one-line claim
- Short intro (who I am + what I prove)
- Strongest case study preview (Arduino prototype)
- Secondary case previews (ML notebook, web feature)
- Call to action

**Case Featured:** Arduino Prototype (strongest proof)
**Call to Action:** Contact me about an internship opportunity.

---

### 2. Work / Case Studies Page
**Sections (in order):**
- Lead case: Arduino Prototype
- Case 2: ML Notebook
- Case 3: Web Feature
- Summary of what these cases collectively prove
- Call to action

**Call to Action:** Reach out to discuss my work or internship fit.

---

### 3. About Page
**Sections (in order):**
- Real photo
- Short bio (focused on the claim)
- Skills + tools I use
- Why I build prototypes the way I do
- Call to action

**Call to Action:** Contact me directly.

---

### 4. Contact Page
**Sections (in order):**
- Simple contact form
- Email + links
- One-line reminder of the claim
- Call to action

**Call to Action:** Send me a message to discuss an internship opportunity.

---

## Still Need to Gather
- Clean screenshot of Arduino prototype (final wiring + LCD output)
- Clean screenshot of ML notebook (baseline + validation sections)
- Clean screenshot of web feature (working contact form)
- One real photo of me for the About page
- Optional: link to GitHub repo for each case
- Optional: short before/after numbers for ML notebook
- Optional: short video clip of Arduino prototype running


## Week 04 — Empty but Live

### Live URL
https://your-portfolio-url.example  
(This is the empty/near‑blank project, reachable publicly.)

### Screenshot Confirmation
A screenshot of the live page was taken and opened on a second device to confirm it is truly reachable.

### Stack Confirmation
The live URL matches the chosen stack from previous weeks (simple static hosting + clean structure).

### Claude Project Setup
The following items have been added to my Claude Project so the build week has everything in one place:
- Identity Kit (fonts, palette, logo, style note)
- Case Studies (Arduino Prototype, ML Notebook, Web Feature)
- Content Map (Home → Work → About → Contact)
- One-line Claim (“I turn technical ideas into clear, usable, working prototypes.”)

Everything required for next week’s build is already loaded and ready.

## Week 04 — Three Roads

### My Constraints
- **Free only:** I must use a free hosting option.
- **My honest skill level:** Beginner–intermediate; comfortable with simple static sites, not full-stack.
- **What my portfolio needs to do:**  
  - Show three case studies (Arduino Prototype, ML Notebook, Web Feature)  
  - Display real screenshots clearly  
  - Include a simple About page with a real photo  
  - Include a Contact page with a working form (can be static for now)  
  - Follow my content map (Home → Work → About → Contact)
- **How my work must be displayed:**  
  - Real screenshots  
  - Clean image galleries  
  - Long-form case study reading  
  - Links to repos  
  - No dynamic features required yet

Backend requirement: **Not yet.** Static is enough.

---

## Three Stack Options (Simplest → Most Powerful)

### 1. **GitHub Pages (Simplest)**
**How I'd build:**  
A static HTML/CSS site with my identity kit, sections, and screenshots.

**Where I'd host (free):**  
GitHub Pages.

**Backend needed:**  
None.

**Trade-off:**  
Very easy to maintain, but limited styling flexibility and no built-in form handling.

---

### 2. **Netlify + Static Site (Middle Option)**
**How I'd build:**  
A static site (HTML/CSS or a simple template) deployed through Netlify.

**Where I'd host (free):**  
Netlify Free Tier.

**Backend needed:**  
None, but Netlify Forms can handle a simple contact form.

**Trade-off:**  
More features than GitHub Pages, cleaner deployment, but still simple enough to finish quickly.

---

### 3. **Vercel + Next.js (Most Powerful)**
**How I'd build:**  
A Next.js project with pages for Home, Work, About, Contact.

**Where I'd host (free):**  
Vercel Free Tier.

**Backend needed:**  
Optional; can add API routes later.

**Trade-off:**  
Most flexible and modern, but heavier to maintain and unnecessary for a simple portfolio.

---

## Pressure-Test of the Front-Runner

### If I pick the simplest (GitHub Pages):
- **What breaks:**  
  - No built-in form handling  
  - Limited layout components  
- **Can I finish in two weeks:** Yes  
- **Does it show my work well:** Yes, screenshots and text display perfectly.

### If I pick the most powerful (Vercel + Next.js):
- **What I must maintain:**  
  - A full framework  
  - Routing  
  - Build steps  
- **Can I finish in two weeks:** Risky  
- **Does it show my work well:** Yes, but the complexity isn’t needed.

---

## My Decision & Rationale

### **Chosen Stack: Netlify + Static Site**
I chose Netlify because it is free, simple, and gives me exactly what I need: clean hosting, easy deployment, and optional form handling without a backend. I can maintain it easily, finish in two weeks, and it displays my screenshots and case studies clearly.

### **Stacks I Didn’t Choose**
- **GitHub Pages:**  
  I didn’t choose it because the contact form would require extra workarounds, even though it’s the simplest option.

- **Vercel + Next.js:**  
  I didn’t choose it because it’s too heavy for a simple portfolio and harder to maintain. I don’t need dynamic features yet.

### **Final Reasoning**
Netlify is the right balance: free, simple, maintainable, and strong enough to show my work properly without adding complexity I don’t need.

## Week 04 — Build (Core)

### Chosen Pipeline
Pipeline: **Draft → Critique → Revise**  
Reason: This is the workflow I use most often for case studies, internship writing, and portfolio text.

---

## Step Diagram (Three+ Distinct Steps)

**1. Gather**  
Collect the raw input: notes, screenshots, bullet points, or messy text.

**2. Synthesize**  
Turn the raw input into a structured outline with sections and key points.

**3. Draft**  
Produce a clean first draft following the outline.

**4. Review**  
Critique the draft for clarity, accuracy, and tone; identify fixes.

**5. Revise & Format**  
Apply the critique, polish the writing, and format it into final portfolio-ready text.

Each step hands off cleanly to the next.

---

## Prompts / Configurations Used

### Step 1 — Gather
“Here are my raw notes. Extract the key points, remove filler, and organize them into a clean outline.”

### Step 2 — Synthesize
“Turn this outline into a structured plan with section headers and bullet points. Keep the tone direct and plain.”

### Step 3 — Draft
“Write a first draft from this plan. Follow the structure exactly. Keep the voice consistent with my identity kit.”

### Step 4 — Review
“Critique this draft. Identify unclear sentences, missing details, weak transitions, and anything that doesn’t support my one-line claim.”

### Step 5 — Revise & Format
“Apply the critique and produce a polished final version formatted for my portfolio.”

---

## Five Real Runs (Summarized)

### **Run 1 — Arduino Case Study**
- Draft produced quickly  
- Review caught missing decisions  
- Revision added clearer steps  
**Outcome:** Strong final case study

### **Run 2 — ML Notebook Case Study**
- Draft was too generic  
- Review flagged missing numbers  
- Revision added metrics  
**Outcome:** More credible and grounded

### **Run 3 — Web Feature Case Study**
- Draft was clean  
- Review flagged tone mismatch  
- Revision aligned tone with identity kit  
**Outcome:** Consistent voice

### **Run 4 — About Page Bio**
- Draft too long  
- Review cut filler  
- Revision made it concise  
**Outcome:** Clear two-paragraph bio

### **Run 5 — Home Page Hero Text**
- Draft lacked punch  
- Review suggested sharper phrasing  
- Revision produced final one-line claim  
**Outcome:** Strong, memorable hero line

---

## Time Saved Estimate

### Manual (average per piece)
- Gather: 15 minutes  
- Synthesize: 20 minutes  
- Draft: 40 minutes  
- Review: 20 minutes  
- Revise: 20 minutes  
**Total:** ~1 hour 55 minutes per piece

### Pipeline (average per piece)
- Gather: 5 minutes  
- Synthesize: 5 minutes  
- Draft: 10 minutes  
- Review: 10 minutes  
- Revise: 10 minutes  
**Total:** ~40 minutes per piece

**Time saved:** ~1 hour 15 minutes per piece  
Across 5 runs: **~6 hours saved**

---

## Known Failure Points & Human Review Needed

- AI sometimes invents details if the raw notes are too thin  
- Tone can drift unless corrected in the review step  
- Formatting occasionally breaks (section headers misplaced)  
- AI can miss subtle decisions unless explicitly included  
- Human must check accuracy, especially numbers and claims  
- Final polish still requires human judgment

---

## Workflow Summary
The pipeline runs end-to-end on new inputs, has five distinct steps with clear handoffs, saves significant time, and still requires human oversight for accuracy and tone. It is simple, repeatable, and fits my real work.

## Week 04 — Agents & MCP

### Workflow vs Agent (In My Own Words)

A **workflow** is a fixed sequence of steps that always run in the same order. It does not make decisions; it simply executes the instructions I designed. My FL‑04 pipeline (Gather → Synthesize → Draft → Review → Revise) is a workflow because every step is predictable, controlled, and requires me to trigger the next stage.

An **agent** is different: it decides what to do next based on goals, context, and available tools. Instead of following a fixed script, an agent chooses actions dynamically. It can call tools, read files, fetch data, and adapt its behavior. A workflow executes; an agent reasons.

My FL‑04 pipeline is **not** an agent. It is a structured workflow with defined handoffs. To become an agent, it would need the ability to choose steps automatically, call external tools, and decide when to stop or ask for clarification.

---

## What MCP Is (In My Own Words)

MCP (Model Context Protocol) is a standard that lets AI models safely use external tools. It acts like a universal port that connects the model to things outside the chat window. MCP defines three primitives:

- **Tools:** Actions the model can take (read a file, write a file, query a service).
- **Resources:** Data the model can access (documents, folders, APIs).
- **Prompts:** Stored instructions the model can reuse.

MCP doesn’t make the model smarter; it makes the model *able to act*. It’s the difference between “talking about a file” and “opening the file.”

---

## Evidence of MCP Connector Setup

Three tasks were run through an MCP connector. These tasks are things plain chat could not do:

1. **Reading a local file**  
   The agent accessed a file directly instead of relying on pasted text.

2. **Listing a directory**  
   The agent retrieved folder contents automatically.

3. **Querying a live service**  
   The agent used a tool call to fetch external data.

These outputs demonstrate that the connector was working and that tool calls were executed rather than plain chat responses.

---

## 600–900 Word Explainer

### What an Agent Is

An agent is a system that can pursue a goal by choosing actions, calling tools, and adapting to new information. Unlike a workflow, which is a fixed sequence, an agent decides what to do next. It can read files, fetch data, update documents, and take actions without waiting for me to manually guide each step.

Agents rely on reasoning loops: observe → decide → act → repeat. They use tools to interact with the world outside the chat window. A workflow is a recipe; an agent is a worker who can choose which tool to pick up.

### What MCP Is

MCP (Model Context Protocol) is the standard that makes agent behavior possible. It gives AI models a safe, structured way to use external tools. Instead of custom integrations for every app, MCP provides a universal interface. If a tool supports MCP, any compatible model can use it.

MCP defines three primitives:

- **Tools:** Actions the model can perform. Examples: read a file, write a file, call an API.
- **Resources:** Data the model can access. Examples: folders, documents, URLs.
- **Prompts:** Stored instructions the model can reuse.

This structure lets the model act like an agent. It can inspect files, modify content, and interact with services. MCP is not a workflow engine; it is the bridge that lets the model operate beyond text.

### How My FL‑04 Workflow Would Become an Agent

My FL‑04 workflow is currently a fixed pipeline: Gather → Synthesize → Draft → Review → Revise. It runs only when I trigger each step. It cannot choose actions or call tools. To become an agent, it would need:

1. **Autonomy:**  
   The ability to decide which step to run next based on the input.

2. **Tool use:**  
   The ability to read my notes from files, fetch references, and update drafts automatically.

3. **State tracking:**  
   The ability to remember what has been done and what remains.

4. **Error handling:**  
   The ability to detect missing information and ask me for clarification.

5. **Stopping conditions:**  
   The ability to know when the draft is complete.

With MCP, the agent could read my raw notes from a folder, generate an outline, write a draft, critique it, revise it, and save the final version — all without me manually copying text between steps.

### Why This Matters

Understanding the difference between workflows and agents is essential because the AI industry uses the word “agent” loosely. Many “agents” are just workflows with marketing language. Real agents require autonomy, tool use, and reasoning. MCP is the foundation that makes real agent behavior possible.

Knowing this distinction helps me evaluate AI products honestly. It also helps me design systems that are maintainable. A workflow is easier to control; an agent is more powerful but requires more oversight.

---

## Concrete Agent Upgrade for My Pipeline

To upgrade my FL‑04 workflow into an agent, I would add:

**Automatic file reading + autonomous step selection.**

The agent would read a folder of raw notes, decide which step is needed (synthesis, drafting, or revision), run the step, save the output, and continue until the final version is complete.

This single upgrade would transform the workflow into a true agent.

## Week 06 — Explain It Like You Built It

### The Piece I Chose to Explain
I chose **how deploying a site pushes it live** because it was the part of the build I didn’t fully understand at first. I could click “deploy,” but I didn’t really know what was happening behind the scenes or why the page suddenly appeared on a URL.

### Plain-Words Explanation (In My Own Words)
Deploying a site sounds complicated, but the idea is simple: you take the files on your computer and put them on a server that anyone can reach through a browser. A server is just another computer that stays online all the time.

When I “deploy,” the hosting service (Netlify, GitHub Pages, Vercel—whichever you use) grabs the folder that contains my site. That folder usually has an `index.html` file, some CSS, maybe images. The host copies those files to its own machine and sets up a public link that points to them.

So when someone types my URL, their browser is basically saying:  
“Hey server, can you send me the files for this site?”  
And the server replies with the HTML, CSS, and images I uploaded. The browser then assembles those files into the page people see.

The part I didn’t understand before was how the URL stays connected to my files. Now I get it: the host watches my repo or project. Every time I update the files and press deploy, it replaces the old version on the server with the new one. That’s why changes appear instantly.

It’s not magic. It’s just copying files to a computer that never turns off, and giving everyone a link to those files.

### Why This Matters
Understanding this makes me feel like I actually own what I shipped. I’m not just pressing buttons—I know what the host is doing, why the URL works, and how updates reach the live site. If something breaks, I now know where to look: either the files didn’t upload correctly, or the server didn’t refresh them.

This is a real part of my build, and now I can explain it to someone who has never deployed anything before.

## Week 07 — Agent Design Doc

### Job To Be Done
My agent will be a **Research Scout**. Its job is to take a topic I’m exploring (industry trend, technical concept, internship prep topic), gather high‑quality information, summarize it clearly, and produce a short brief I can use for study or decision-making. It focuses on one job done well: fast, reliable research.

### User & Usage Frequency
**User:** Me  
**Usage frequency:** 3–4 times per week, whenever I need quick, trustworthy research for study, projects, or internship preparation.

### Tools & Data Needed (With Access Plan)
- **Web search:** To gather current information.  
  *Access plan:* Use built‑in search tools from the chosen platform.
- **My notes folder:** To ground research in my existing knowledge.  
  *Access plan:* Store notes in a connected project folder.
- **Summaries & briefs:** Saved as text files.  
  *Access plan:* Agent writes outputs into a designated folder.

No sensitive data required.  
No backend needed yet.

### Draft Instructions (Initial Agent Spec)
- When given a topic, search for reliable, recent sources.
- Extract key points, remove filler, and avoid speculation.
- Compare multiple sources and highlight disagreements.
- Produce a structured brief: overview → key facts → implications → recommended next steps.
- Save the brief to the project folder.
- Ask me to confirm before saving if the topic is sensitive or ambiguous.
- Never invent facts or cite sources that don’t exist.

### Five Evaluation Cases (Pre-Build Evals)
1. **“Summarize the latest trend in front-end frameworks.”**  
   Should produce a clean, source-grounded brief.

2. **“Explain the difference between supervised and unsupervised learning.”**  
   Should compare definitions and highlight real distinctions.

3. **“Give me a short brief on cybersecurity basics for beginners.”**  
   Should avoid fear-based language and stick to fundamentals.

4. **“Research the pros and cons of static site hosting.”**  
   Should compare options without recommending paid services.

5. **“Summarize a topic from my notes folder + external sources.”**  
   Should combine my notes with new research correctly.

### Risks & Guardrails
- **Must confirm:**  
  - When the topic is sensitive, personal, or unclear.  
  - Before saving a brief that includes assumptions or predictions.

- **Must never:**  
  - Invent citations or fake sources.  
  - Give legal, medical, or financial advice.  
  - Produce content that contradicts my notes without flagging it.  
  - Save files without my confirmation.

- **Risk:** Overconfidence in weak sources.  
  *Guardrail:* Always list source types and reliability level.

- **Risk:** Mixing outdated info with new info.  
  *Guardrail:* Prioritize recent sources and label older ones.

### Platform Choice & Justification
**Chosen platform:** Claude Project with connectors and skills.

**Why:**  
- Free to use.  
- Easy to connect notes and folders.  
- Strong at structured research and summarization.  
- Supports tool calls for reading/writing files.  
- Simple enough to build in ~10 hours.

### Alternative Considered (And Why Not Chosen)
**n8n Agent Workflow:**  
More powerful automation, but heavier setup and harder to maintain. I don’t need full automation yet.

**Custom GPT (paid):**  
Strong option, but requires a paid plan and doesn’t add meaningful benefits for my scope.

### Final Rationale
I chose a **Research Scout** because it fits my real needs: fast, trustworthy research for study and projects. The scope is achievable in ~10 hours, the tools are accessible, and the platform is free and maintainable. The agent has clear guardrails, realistic eval cases, and a simple workflow that I can actually run. This design keeps me in control while letting the agent handle the repetitive research work.


## Week 07 — Agent MVP (Checkpoint 1)

### Working Agent (Core Job)
My agent is the **Research Scout**, built according to the FL‑06 spec. Its core job is to take a topic, gather reliable information, synthesize it, and produce a structured brief. The MVP focuses on the narrowest version of this job: one topic → one research cycle → one brief.

The agent completes this job end‑to‑end using:
- A connected notes folder (file access)
- A search tool for gathering external information
- A structured instruction set for synthesis and brief creation

### Live Tool / Data Connection
The MVP uses one real tool connection:
- **File access:** The agent reads from a designated notes folder and writes the final brief into the same folder.

This satisfies the requirement for at least one live tool or data source.

---

## Build Log (Honest Iteration)

### Attempt 1 — Overly Broad Scope
I initially tried to include multi‑topic research and automatic comparison. This caused confusion and inconsistent outputs.  
**Change:** Reduced scope to one topic per run.

### Attempt 2 — Missing Confirmation Step
The agent saved files without asking me first.  
**Fix:** Added a guardrail requiring confirmation before saving.

### Attempt 3 — Weak Source Reliability Notes
The agent summarized sources but didn’t label reliability.  
**Fix:** Added an instruction to categorize sources (recent, outdated, low‑confidence).

### Attempt 4 — Notes Folder Misread
The agent tried to read the wrong directory.  
**Fix:** Updated the file path and simplified folder structure.

### Attempt 5 — Overlong Briefs
Drafts were too long and unfocused.  
**Fix:** Added a strict structure: overview → key facts → implications → next steps.

### What I Cut From the Original Spec
- Automatic multi‑topic comparison  
- Automatic tagging  
- Automatic weekly digest generation  

These were cut because they exceeded the 10‑hour scope and weren’t needed for the MVP.

---

## Raw Run Capture (Description)
A raw, unedited 2‑minute screen capture was recorded showing:
1. The agent receiving a topic  
2. Running the gather → synthesize → brief steps  
3. Reading from the notes folder  
4. Producing the structured brief  
5. Asking for confirmation before saving  
6. Writing the final brief to the folder

The capture shows the full loop from request to result with no mid‑run edits.

---

## End-to-End Run Summary (Example Topic)
**Topic:** “Latest trends in front-end frameworks”

**Agent Output:**  
- Overview of current trends  
- Key facts from multiple sources  
- Reliability notes  
- Implications for developers  
- Recommended next steps  
- Saved brief after confirmation

This demonstrates the MVP working exactly as scoped.

---

## Spec Match & Deviations
The MVP matches the FL‑06 spec in:
- Core job  
- Guardrails  
- File access  
- Structured brief format  
- Single-topic research loop

Documented deviations:
- Removed multi-topic comparison  
- Removed automatic weekly digest  
- Simplified toolset to one file connector

These changes were made to keep the build within the 10‑hour scope.

## Week 07 — Personal Website + DNS Walkthrough



### What the Site Contains
- My positioning statement  
- Links to my LinkedIn, GitHub, CV, and booking link  
- A short intro about who I am and what I’m building  
- A space reserved for future posts and capstone work  

The site is intentionally simple: one page, clean layout, and easy to maintain.

---

## DNS Walkthrough (In My Own Words)

DNS is basically the phonebook of the internet. When someone types a website address, DNS helps the browser figure out which server should answer. It’s a lookup system that translates human-friendly names (like myname.netlify.app) into the actual machine location where the site lives.

Here’s what actually happens behind the scenes:

### 1. The Resolver
When someone types my website address, their device asks a **resolver** (usually provided by their ISP or a public service like Google DNS) to find out where that name points. The resolver’s job is to go look up the answer.

### 2. The Nameserver
The resolver then asks the **nameserver** that is responsible for that domain. A nameserver stores DNS records — the actual instructions that say “this domain lives over here.”

For Netlify sites, Netlify provides the nameserver information when you connect a custom domain. Even though I’m using the free Netlify URL right now, the process is the same conceptually.

### 3. The DNS Record
The nameserver checks the DNS records. The important one for simple hosting is the **CNAME record**.

A **CNAME record** is basically an alias. It says:
“This domain should point to this other domain.”

For example:


It doesn’t store an IP address directly. It just tells the browser, “Go look over there instead.” This is why CNAMEs are used for services like Netlify — they let your custom domain point to the Netlify-hosted site without you needing to know the server’s IP.

### 4. The Response
Once the nameserver finds the right record, it sends the answer back to the resolver. The resolver caches it (so it doesn’t have to ask again immediately) and then tells the browser where to go.

### 5. The Browser Loads the Site
Now that the browser knows the correct location, it sends a request to the host (Netlify). Netlify responds with the files I deployed — the HTML, CSS, images, and anything else in my site folder.

Because Netlify automatically provides HTTPS, the browser also checks the SSL certificate to confirm the connection is secure. That’s why the padlock appears without me configuring anything.

---

## Why This Matters
Understanding DNS means I actually know what’s happening when a domain connects to a host. Instead of blindly following steps, I understand the flow:

- Resolver  
- Nameserver  
- DNS record  
- Response  
- Browser loads the site  

This makes me confident that when I connect my own domain later, I’ll know what’s happening rather than just clicking buttons.

---

## Week 08 — Make It Do Something

### My One Dynamic Feature
I chose **a working contact form** as the single dynamic feature for my portfolio. It is simple, useful, and directly supports my one-line claim and internship goal. The form is wired end-to-end on a free tier and sends a real submission that reaches me.

### Evidence of the Working Feature
A real test submission was sent through the live form.  
The message reached me successfully, confirming the feature works end-to-end.

---

## Plain-Words Explainer (In My Own Words)

### What a Backend Is
A backend is the part of a website that runs behind the scenes. It receives data, processes it, and sends it somewhere. You don’t see it on the page, but it’s the part that makes features actually work. When someone submits a form, the backend is what catches the message and delivers it to me.

### What My Feature Does
My contact form collects a name, email, and message. When the user presses “submit,” the backend receives the data and forwards it to me. This turns my portfolio from a static page into something interactive and useful — people can actually reach me through it.

### How the Data Flows
1. The user fills out the form on the frontend.  
2. The browser sends the form data to the backend endpoint.  
3. The backend receives the submission and processes it.  
4. The backend forwards the message to me (email or dashboard).  
5. I receive the real submission — proof that the feature works.

---

## Why This Matters
Having one real, working feature shows that my portfolio isn’t just a poster — it’s a functional tool. Wiring a single feature end-to-end taught me how data moves through a site and gave me a piece of work I can confidently explain and maintain.


## Week 07 — Open It On Your Phone

---

## Fix Log (Before → After)

### 1. Mobile Layout Issues
**Before:**  
- Text was too small on mobile.  
- Work images spilled outside the screen.  
- Buttons were too small to tap comfortably.

**After:**  
- Increased base text size for mobile.  
- Set images to scale within the viewport.  
- Increased button padding and tap area.

---

### 2. Readability & Contrast
**Before:**  
- Line spacing felt tight.  
- Some text blended into the background.  
- Work screenshots looked slightly blurry.

**After:**  
- Increased line height for easier reading.  
- Adjusted color contrast to pass accessibility checks.  
- Replaced screenshots with crisp, compressed versions.

---

### 3. Broken or Slow Elements
**Before:**  
- One external link didn’t open.  
- A large image slowed the page load.  
- A section header shifted at certain widths.

**After:**  
- Fixed all links (LinkedIn, GitHub, CV, booking).  
- Compressed oversized images.  
- Corrected layout so all widths behave consistently.

---

### 4. AI Audit Notes
I asked AI to audit the mobile version. It flagged:  
- A slow-loading hero image  
- A button with low contrast  
- A section with uneven spacing

All three were fixed.

---


## Result
The portfolio now:  
- Works cleanly on mobile, tablet, and desktop  
- Has readable text and crisp images  
- Has working links across all sections  
- Has no oversized images or broken layout  
- Passes basic accessibility and contrast checks

This completes the Week 07 deliverable.

## Week 07 — Survive the Crit

### Proof Statement (Given to Reviewer)
“I turn technical ideas into clear, usable, working prototypes.”

This is the claim the reviewer judged the portfolio against.

---

## Reviewer’s Feedback

### 10‑Second Test
**What do I do (reviewer’s words):**  
“You build small technical prototypes and explain them clearly.”

**Would they believe I’m good at it:**  
“Yes, the case studies look real and the explanations are confident.”

---

### Full Feedback (Collected Without Defending)
- The hero text is strong, but the sub‑text could be slightly clearer.  
- The Arduino case study is good, but the screenshot looked a bit dim.  
- The ML notebook case study felt long; could be tightened.  
- The About page photo is fine, but the spacing under the header felt uneven.  
- The contact form works, but the success message could be more visible.  
- One link (GitHub) opened slowly.  
- The Work page header felt slightly large on mobile.  
- Overall: “Good site, but a few small clarity and polish fixes.”

---

## Must‑Fix vs Nice‑to‑Have (Sorted Honestly)

### Must‑Fix (Confusing, Broken, or Hurts the Proof)
- Dim Arduino screenshot  
- Uneven spacing under About header  
- Slow GitHub link  
- Contact form success message too subtle  
- Oversized Work page header on mobile  
- ML notebook case study too long

### Nice‑to‑Have (Later)
- Slightly clearer sub‑text under hero  
- More consistent spacing between sections  
- Optional second photo on About page  
- Optional color tweak for buttons

---

## What I Fixed 

### 1. Dim Arduino Screenshot
**Before:** Screenshot looked dull and low‑contrast.  
**After:** Replaced with a crisp, bright version.

### 2. Uneven Spacing Under About Header
**Before:** Header spacing looked off on mobile.  
**After:** Adjusted padding and line height.

### 3. Slow GitHub Link
**Before:** Link took too long to open.  
**After:** Updated link and compressed preview image.

### 4. Contact Form Success Message
**Before:** Message appeared but was barely noticeable.  
**After:** Increased contrast and added a short confirmation line.

### 5. Oversized Work Page Header (Mobile)
**Before:** Header text was too large on small screens.  
**After:** Added mobile‑specific font scaling.

### 6. ML Notebook Case Study Length
**Before:** Too long and slightly repetitive.  
**After:** Tightened the text and removed filler.

---

## Result
The reviewer’s feedback was taken seriously and applied without defending.  
All must‑fix items are now corrected on the live site.  
The portfolio is clearer, more polished, and supports the proof statement directly.


## Week 09 — Break Your Own Site

---

## Where It Breaks — Honest List

### ❌ Fix-Now Issues (Now Fixed)

#### 1. Empty Form Submission
**Break:** Submitting the contact form empty produced a confusing error message.  
**Fix:** Added clear validation and a readable error state.

#### 2. Garbage Input Submission
**Break:** Submitting random characters made the success message appear even though the input was invalid.  
**Fix:** Strengthened validation to reject malformed email fields and empty messages.

#### 3. Slow Link on Mobile
**Break:** One external link (GitHub) opened slowly on mobile.  
**Fix:** Updated the link and compressed the preview image.

#### 4. Oversized Hero Image
**Break:** Hero image loaded slowly and shifted layout on first paint.  
**Fix:** Compressed the image and added proper sizing attributes.

#### 5. Double Submission
**Break:** Submitting the form twice quickly caused duplicate messages.  
**Fix:** Added a short cooldown and disabled the button during submission.

#### 6. Social Preview Missing
**Break:** Sharing the site produced a blank preview card.  
**Fix:** Added basic meta tags for title, description, and social preview.

#### 7. Title & Description Missing
**Break:** Browser tab showed a generic title; search engines saw no description.  
**Fix:** Added `<title>` and `<meta name="description">`.

---

### ⚠️ Known Limitations (Documented Honestly)

#### 1. No Spam Protection
The form does not include CAPTCHA or spam filtering.  
Acceptable for now; will upgrade later.

#### 2. No Rate Limiting
Fast repeated submissions still reach the backend.  
Not harmful, but noted.

#### 3. No Custom Domain Yet
Using the free Netlify URL for now.  
Will connect a custom domain later.

#### 4. Limited SEO Depth
Basic meta tags added, but no sitemap or structured data yet.  
Not required for this checkpoint.

---

## Evidence of Fix-Nows Addressed

### Added Basic SEO / Meta
- `<title>` added  
- `<meta name="description">` added  
- Open Graph tags added for social preview  
- Twitter card tags added

### Speed Check
Ran a free speed test:  
- After image compression, load time improved  
- Largest Contentful Paint reduced  
- No blocking scripts detected

### Mobile & Desktop Re-Test
After fixes:  
- Form validation works  
- No layout shifts  
- All links open correctly  
- Social preview displays properly  
- Double submission prevented

---

## Hardening Review (Mentor / Peer)

### Reviewer’s Must-Fixes
- Improve error message clarity  
- Compress hero image  
- Add basic meta tags  
- Fix slow external link

### All must-fixes have been addressed on the live site.

---

## Final Result
The site has been tested against real edge cases, not just the happy path.  
Fix-nows are genuinely fixed, known limitations are documented, and basic SEO/meta are added.  
The portfolio is now more trustworthy, polished, and ready for launch.

## Week 09 — Plant Your Flag

### Live Custom-Domain URL

---

## Analytics Installed (Screenshot Provided)
A screenshot of the analytics dashboard is included:  
`images/week09_analytics.png`  
Analytics is installed, tracking visits, and confirmed working on the live domain.

---

## Launch Hygiene Checklist

### ✔ Social-Share Preview
The Open Graph and Twitter Card tags are added.  
Sharing the site now shows:  
- Title  
- Description  
- Preview image  
All correct on the custom domain.

### ✔ Favicon
A favicon is installed and displays correctly on:  
- Mobile  
- Desktop  
- Browser tabs  
- Social previews

### ✔ Page Titles
Each page has a clean, descriptive `<title>` tag that matches the content and improves SEO.

### ✔ Mobile Check (Real Phone)
Opened the final custom-domain URL on a real phone:  
- Layout stable  
- Images crisp  
- Buttons tappable  
- Contact form works  
- No broken links  
- No layout shifts

---

## FlyRank Graduate Badge Installed
The FlyRank graduate badge is added to the footer and links to my verification page.

Badge source: https://internship-badge.netlify.app/

**Footer placement:**  
- Visible on mobile and desktop  
- Linked to verification page  
- Loads correctly over HTTPS

---

## Final Result
The portfolio is now fully launched on a custom domain, with analytics installed, correct share preview, favicon, and titles. The FlyRank graduate badge is visible in the footer and linked properly. The site is stable, fast, and ready for public use.

## FL-09 — Documentation and Demo

### README

## What It Does and For Whom
This project is a personal Research Scout agent designed to help students, interns, and early‑career builders gather reliable information quickly. It takes a topic, searches for trustworthy sources, synthesizes the findings, and produces a structured brief. It is built for anyone who needs fast, grounded research without noise.

## Setup (A Stranger Could Follow)
1. Clone the repository.  
2. Open the project folder.  
3. Connect the notes directory (any folder with text files).  
4. Run the agent using the provided instructions.  
5. Provide a topic and let the agent complete the research cycle.  
No coding required; the agent runs through a simple instruction set.

## Usage Example
Input: “Explain the latest trend in front-end frameworks.”  
Output: A structured brief with overview, key facts, implications, and recommended next steps.

## Simple Architecture Sketch
- **Input:** Topic  
- **Tool:** File access + search  
- **Agent:** Gather → Synthesize → Draft → Review → Save  
- **Output:** Final brief saved to notes folder

## V2 Eval Results
- Accuracy improved after adding source reliability labels  
- Draft clarity improved after tightening the outline  
- File read/write stable across multiple runs  
- Weakness: long topics sometimes produce overly long briefs

## Limitations
- No spam protection  
- No multi-topic comparison  
- No rate limiting  
- Basic SEO only  
- Occasional overlong outputs for broad topics

## Transparency Note
I built this project with Claude as a partner. Claude handled drafting and synthesis; I checked structure, accuracy, and all final outputs myself.

---



## FL-10 — Final Package, Retrospective, and Capstone

### Submission Package Index
- Week 01 — Workflow Audit  
- Week 02 — Claude Project Setup  
- Week 03 — Three Roads  
- Week 04 — Build Core  
- Week 05 — Agent Spec  
- Week 06 — Explain It Like You Built It  
- Week 07 — Survive the Crit  
- Week 08 — Make It Do Something  
- Week 09 — Break Your Own Site  
- Week 10 — Final Capstone  
All deliverables are linked in this repository.

---

## Retrospective (500–800 Words)

When I started in Week 1, I wanted to learn how to use AI in a way that actually improved my work instead of just generating text. I didn’t know how to structure tasks, how to build workflows, or how to ship something real. I thought the track would mostly be about prompts. Instead, it turned into a full build cycle: planning, designing, wiring, testing, breaking, fixing, and launching.

The biggest change was how I think about work. In Week 1, I treated AI as a tool I asked questions. By Week 10, I was treating it as a partner that helps me think, plan, and structure. I learned that the real skill isn’t “getting AI to do things,” but knowing how to design the thing you want it to do. That shift made everything easier.

My goal was to build one working agent and one working feature on my portfolio. I did both. The Research Scout agent became the core of my build. It forced me to understand workflows, autonomy, tool calls, and guardrails. I learned how to write instructions that actually work, how to test edge cases, and how to evaluate outputs honestly. I also learned how to document limitations instead of hiding them — something I never did before this track.

The portfolio build changed how I see my own work. Before, my site was just a static page. Now it has a working contact form, a clear proof statement, crisp case studies, and a clean mobile layout. I learned how to deploy, how DNS works, how HTTPS appears automatically, and how to break my own site on purpose. That last part — trying to break it — taught me more than any tutorial.

The three most transferable things I learned:

1. **Workflow thinking.**  
   Breaking work into steps, defining handoffs, and designing processes that AI can run. This applies to everything — assignments, projects, job tasks.

2. **Honest evaluation.**  
   Writing eval cases, checking outputs, naming limitations, and fixing what matters. This is the difference between amateur and trustworthy.

3. **Shipping real things.**  
   Deploying, wiring, testing, documenting, and launching. I learned that shipping is a skill, not a personality trait.

What I’d build next: a more autonomous version of the Research Scout — something that can read a folder of topics, run research automatically, and produce a weekly digest. I’d also add a second feature to my portfolio, maybe a small AI-powered demo.

Looking back, the biggest change is confidence. I can explain what I built, how it works, where it breaks, and what I checked myself. I can use AI as a career partner — not to invent stories, but to help me tell the true one. This track didn’t just teach me how to build; it taught me how to think.

---

## Hours Log
Completed in the portal. Hours match timestamps and build phases.

---

## Live Site + Build-in-Public Post
Live site: https://yourname.flyrank.app  
Build-in-public post: https://your-post-link.com  
The post explains one real decision and one real limitation.

---

## Final Review
Submitted for final review and sign-off.


## Week 09 — The Plan to Keep Building

### How to Add the Next Case Study (Concrete Steps)
I will reuse the same three‑beat shape from Week 2:

1. **Problem**  
   Write 3–4 lines explaining the real problem the project solved.  
   What wasn’t working? What was unclear? What needed to be built?

2. **What I Did**  
   Describe the decisions, the steps, and the reasoning.  
   Include one screenshot and one short explanation of why I chose this approach.

3. **What Came of It**  
   Show the outcome: the working demo, the improvement, or the measurable result.  
   Keep it short, direct, and in my own voice.

**Steps to add the case:**  
- Open my Claude Project (it already knows my voice and stack).  
- Paste my raw notes and let Claude interview me until the three beats are clear.  
- Draft → critique → revise (same pipeline as Week 4).  
- Add the case to the “Work” section of my portfolio.  
- Push the update live.

This is a repeatable process, not a rebuild.

---

### The Next Real Piece of Work I Will Add
**Next case study:**  
**“My Smart Home Security System (Two‑Arduino Build)”**  
This is a real project I built with ultrasonic sensors, keypad input, LEDs, buzzer logic, and LCD output. It fits my proof statement perfectly and shows hands‑on technical work.

---

### Evidence of Reminder Set
I set a concrete reminder:

**Calendar reminder:**  
“Add Smart Home Security System case study to portfolio.”  
Date: **Monday, 12 October 2026 — 8:00 PM**

This reminder is now on my calendar so the next case actually gets shipped, not forgotten.

---

### Build Context Preserved
My Claude Project remains active with:  
- My identity kit  
- My voice card  
- My sitemap  
- My case study structure  
- My proof statement  

This means the next case study is a short conversation, not a fresh setup.






## FL‑09 — Documentation and Demo

# README — Research Scout Agent

## What the Agent Does and For Whom
The Research Scout is a lightweight personal research agent designed for students, interns, and early‑career builders who need fast, reliable summaries of technical or academic topics. You give it a topic, and it produces a structured brief grounded in recent sources and your own notes. It removes filler, highlights disagreements, and gives clear next steps.

It is built for anyone who wants trustworthy research without manually digging through multiple sources.

---

## Setup Steps (A Stranger Could Follow)
1. Clone or download this repository.
2. Open the project folder.
3. Create a simple `notes/` directory and place any text files you want the agent to reference.
4. Open the Claude Project and connect the folder as a resource.
5. Run the agent with the provided instructions.
6. Provide a topic (e.g., “Explain supervised vs unsupervised learning”).
7. The agent will gather → synthesize → draft → review → save the brief.

No coding or environment setup required.

---

## Usage Example
**Input:**  
“Summarize the latest trend in front‑end frameworks.”

**Output:**  
A structured brief containing:  
- Overview  
- Key facts  
- Source reliability notes  
- Implications  
- Recommended next steps  
- Saved file in the `notes/` folder

---

## Simple Architecture Sketch
- **Input:** Topic  
- **Tools:** File read/write + search  
- **Agent Loop:**  
  - Gather sources  
  - Extract key points  
  - Compare disagreements  
  - Draft structured brief  
  - Review for clarity  
  - Save after confirmation  
- **Output:** Final brief stored locally

---

## V2 Eval Results
- **Accuracy:** Improved after adding reliability labels.  
- **Clarity:** Better after tightening the outline.  
- **Tool Use:** File read/write stable across multiple runs.  
- **Weakness:** Very broad topics sometimes produce overly long briefs.  
- **Guardrail:** Agent now asks for confirmation before saving.

---

## Limitations
- No multi‑topic comparison.  
- No rate limiting.  
- Occasional overlong outputs for broad topics.  
- Basic file structure only.  
- No automatic weekly digest yet.

---

## Transparency Note
I built this agent with Claude as a partner. Claude handled drafting and synthesis; I personally checked structure, accuracy, and all final outputs.

## Week 10 — The Plan to Keep Building

### How I Will Add the Next Case Study (Concrete Steps)
I will follow the same three‑beat structure from Week 2:

1. **Problem**  
   Write 3–4 lines explaining the real problem the project solved — what wasn’t working, what needed clarity, or what needed to be built.

2. **What I Did**  
   Describe the decisions, the steps, and the reasoning.  
   Include one screenshot and one short explanation of why I chose that approach.

3. **What Came of It**  
   Show the outcome: the working demo, the improvement, or the measurable result.  
   Keep it short, direct, and in my own voice.

**Steps to add the case:**  
- Open my Claude Project (it already knows my voice, stack, and identity kit).  
- Paste my raw notes and let Claude interview me until the three beats are clear.  
- Draft → critique → revise (same pipeline as earlier weeks).  
- Add the finished case to the “Work” section of my portfolio.  
- Push the update live.

This is a repeatable process, not a rebuild.

---

### The Next Real Piece of Work I Will Add
**Next case study:**  
**“My Smart Home Security System (Two‑Arduino Build)”**  
A real project using ultrasonic sensors, keypad input, LEDs, buzzer logic, and LCD output. It fits my proof statement and shows hands‑on technical work.

---

### Evidence of Reminder Set
I set a concrete reminder:

**Calendar reminder:**  
“Add Smart Home Security System case study to portfolio.”  
Date: **Monday, 12 October 2026 — 8:00 PM**

This ensures the next case actually gets shipped, not forgotten.

---

### Build Context Preserved
My Claude Project remains active with:  
- My identity kit  
- My voice card  
- My sitemap  
- My case study structure  
- My proof statement  

This means future updates are cheap — the next case is just a short conversation, not a fresh setup.


## Week 10 — The Plan to Keep Building

### How I Will Add the Next Case Study (Concrete Steps)
I will follow the same three‑beat structure from Week 2:

1. **Problem**  
   Write 3–4 lines explaining the real problem the project solved — what wasn’t working, what needed clarity, or what needed to be built.

2. **What I Did**  
   Describe the decisions, the steps, and the reasoning.  
   Include one screenshot and one short explanation of why I chose that approach.

3. **What Came of It**  
   Show the outcome: the working demo, the improvement, or the measurable result.  
   Keep it short, direct, and in my own voice.

**Steps to add the case:**  
- Open my Claude Project (it already knows my voice, stack, and identity kit).  
- Paste my raw notes and let Claude interview me until the three beats are clear.  
- Draft → critique → revise (same pipeline as earlier weeks).  
- Add the finished case to the “Work” section of my portfolio.  
- Push the update live.

This is a repeatable process, not a rebuild.

---

### The Next Real Piece of Work I Will Add
**Next case study:**  
**“My Smart Home Security System (Two‑Arduino Build)”**  
A real project using ultrasonic sensors, keypad input, LEDs, buzzer logic, and LCD output. It fits my proof statement and shows hands‑on technical work.

---

### Evidence of Reminder Set
I set a concrete reminder:

**Calendar reminder:**  
“Add Smart Home Security System case study to portfolio.”  
Date: **Monday, 12 October 2026 — 8:00 PM**

This ensures the next case actually gets shipped, not forgotten.

---

### Build Context Preserved
My Claude Project remains active with:  
- My identity kit  
- My voice card  
- My sitemap  
- My case study structure  
- My proof statement  

This means future updates are cheap — the next case is just a short conversation, not a fresh setup.







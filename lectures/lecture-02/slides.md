---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

--- 
layout: cover 
theme: seriph 
background: ./assets/bus.png
title: Data Insights, Visualizations, and Tooling subtitle: Automated Bus Lane Enforcement (ABLE) & Automated Camera Enforcement (ACE) 
--- 

## Today’s Agenda

- Review three additional datathon projects  
- Read and listen to exemplary data stories  
- Why stories matter to humans (and decision-makers)  
- What is a story, structurally?  
- SCQA: Situation, Complication, Question, Answer  
- The Pyramid Principle: structuring ideas for clarity and impact  
- The Assertion–Evidence model for effective slides

---
---
## Review: Datathon Projects

- Project 1: *DataBased*  
  https://www.youtube.com/watch?v=yhftO0M2e5w

- Project 2: *DataVengers*  
  https://github.com/MHC-Datathon/Datavengers_0

- Project 3: *DataVengers_2*  
  https://www.youtube.com/watch?v=gjbFQrkwwvY

**Key Question to Ask:**  
What is the single, clear question this project is trying to answer?


---
---
## Read / Listen to Data Stories

- Story 1: *AI/Energy*  
  https://www.youtube.com/shorts/rfV6jHyTsoc

- Story 2: *Buses - Free and Fast*  
  https://www.nytimes.com/video/upshot/100000010473160/can-new-york-city-buses-be-both-fast-and-free.html

- Story 3: *Murky Water*  
  https://features.csis.org/hiddenreach/china-shipyard-tiers/

- Story 4: *UK Brexit*  
  https://news.sky.com/story/better-for-brexit-how-uk-has-changed-since-leave-vote-11920143

- Story 5: *The Pudding*  
  https://www.youtube.com/watch?v=sE_Ew0Be4qE

**Key Question to Ask:**  
What story is the data telling, and how is it guiding the audience’s understanding or decision?

---
---
## Why Stories Matter to Humans (and Decision-Makers)

- Humans are wired for stories: we remember narratives far better than isolated facts  
- Stories make complex data relatable, actionable, and emotionally compelling  
- Decision-makers respond to **cause–effect, tension, and resolution**, not just numbers  
- Stories help us **connect insight to action**: turning analysis into decisions  
- Facts without context are easily ignored; stories give facts **meaning and purpose**

- *The Big Short*  
  https://www.youtube.com/watch?v=xbiDrzTd8fE
- *Mentos* 
  https://www.youtube.com/watch?v=bpp3ycMvQd0

---
---
## What is a Story, Structurally?

A story is built around **three core elements**:

- __Setup__ – Introduce the context and key characters
- __Conflict__ – Present the problem, tension, or challenge
- __Resolution__ – Show how the problem is solved or the question answered


At its heart, a story is about **change** – something shifts from the beginning to the end, creating insight, learning, or impact.  
Stories are memorable because they follow the natural arc of **beginning → struggle → outcome**

---
---
## Our Storytelling Framework: SCQA

> A natural extension of the story arc: Setup → Conflict → Resolution

- **Situation** – What is the current state? Context your audience already agrees with.  
- **Complication** – What changed or what problem arose? Why does it matter now?  
- **Question** – What key question arises from the complication? What are we trying to solve?  
- **Answer** – What is your conclusion or recommendation? How do you resolve the tension?

**Why SCQA works:**  
- Turns data-heavy slides into a **persuasive narrative**  
- Keeps the audience on the same page before presenting your main insight  
- Builds naturally from the story structure we just learned

---
layout: center
---

<h2>SCQA</h2>

<div class="image-wrap">
  <img src="./assets/SCQA_1.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>SCQA Disney Example</h2>

<div class="image-wrap">
  <img src="./assets/SCQA_2.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Intro-Main Deck</h2>

<div class="image-wrap">
  <img src="./assets/SCQA_3.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>


---
---
## SCQA Deep Dive: Situation (S)

- **Purpose:** Set the stage for your story. Provide context your audience already agrees with.  
- **Key Elements:**  
  - Current state of affairs  
  - Facts and trends everyone acknowledges  
  - Relevant background information  
- **Tip:** Keep it concise. Avoid surprises or new arguments here.  

> Example: "Disney is looking to grow revenue by opening a new theme park."

---
---
## SCQA Deep Dive: Complication (C)

- **Purpose:** Introduce tension or change that makes the story necessary.  
- **Key Elements:**  
  - What’s different or problematic?  
  - Why now? Why should the audience care?  
  - Sets up the question that needs answering  
- **Tip:** Highlight urgency or stakes without solving it yet.  

> Example: "They need to decide where to open this park to maximize impact."

---
---
## SCQA Deep Dive: Question (Q)

- **Purpose:** The natural question that emerges from the complication.  
- **Key Elements:**  
  - Clearly frames what the presentation aims to answer  
  - Guides audience attention to the answer  
  - Keeps the story focused  
- **Tip:** Implicit or explicit—just make sure the audience can see the logic.  

Example: "Where should Disney open its next theme park?"

---
---
## SCQA Deep Dive: Answer (A)

- **Purpose:** Resolve the story. Present your main insight or recommendation.  
- **Key Elements:**  
  - The conclusion supported by data and reasoning  
  - Evidence structured clearly (often with Pyramid Principle)  
  - Ties back to the original question  
- **Tip:** Keep your answer upfront; supporting points follow logically.  

> Example: "Disney should build a new theme park in Rio de Janeiro, Brazil."

---
---
## The Power of a Clear Business Question

- **Clarity is everything:** A well-defined question focuses your analysis and keeps the story coherent  
- **Testable & Measurable:** The best questions can be quantified, modeled, or validated with data  
- **Drives insight:** A precise question guides which data to collect, which metrics to track, and how to interpret results  
- **Prevents ambiguity:** Avoids confusion, wasted effort, or conclusions that are too broad  
- **Example:**  
  - Weak: "How can Disney grow?"  
  - Strong: "Which location will maximize attendance and revenue for Disney’s next theme park?"

> The question is the foundation: if it’s clear and testable, the story naturally follows

---
---
## Strong Answers Depend on Clear Questions

- **Direct link:** A precise question allows you to give a precise, actionable answer  
- **Better insight:** Clear questions focus the analysis on what matters most, avoiding irrelevant data  
- **Evidence alignment:** Strong answers are supported by data that directly addresses the question  
- **Decision-ready:** Ambiguous questions lead to vague answers; clear questions lead to confident recommendations  
- **Example:**  
  - Weak question → weak answer: "How can Disney grow?" → "They should do more marketing."  
  - Clear question → strong answer: "Which location will maximize attendance and revenue for Disney’s next theme park?" → "Rio de Janeiro, based on tourism metrics and brand appeal."

> A clear question is the anchor: the answer’s clarity, relevance, and impact all depend on it


---
---
## The Pyramid Principle: Structuring Ideas for Clarity & Impact

> A method to organize supporting evidence so your answer is clear, persuasive, and easy to follow

- **Top-Down Logic:** Start with your main conclusion (Answer) first  
- **Group Supporting Points:** Directly under your answer, present 2–4 key arguments that justify it  
- **Layer in Details:** Add data, examples, or analysis beneath each supporting point  
- **Benefits:**  
  - Makes your reasoning transparent  
  - Guides the audience from insight to evidence naturally  
  - Keeps presentations concise and persuasive

> Example:  
**Answer:** Build Disney’s next park in Rio  
→ **Supporting Points:**  
1. Rio is a major tourist destination  
2. Disney brand is strong in Brazil  
3. Local infrastructure can support a new park

---
layout: center
---

<h2>Pyramid Principle Disney Example</h2>

<div class="image-wrap">
  <img src="./assets/Pyramid_Principle.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
---
## Storyboarding with SCQA + Pyramid Principle

> Combine narrative flow with structured evidence for clear, persuasive presentations

- **Step 1: SCQA for the Story Arc**  
  - **Situation:** Set the context  
  - **Complication:** Highlight the problem or change  
  - **Question:** Frame the key question your analysis answers  
  - **Answer:** Present your conclusion  

- **Step 2: Pyramid Principle for Supporting Evidence**  
  - Place your **Answer at the top** of the slide or section  
  - Organize 2–4 **supporting points** underneath  
  - Layer in **data, examples, or visuals** to reinforce each point  

---
---
## Storyboarding with SCQA + Pyramid Principle

- **Result:** A logical, compelling story that:  
  - Guides the audience naturally from context → tension → question → conclusion  
  - Clearly shows **why the conclusion is valid**  
  - Makes data **memorable and actionable**

> Storyboarding is simply **planning your deck as a story with evidence**, so every slide has purpose and impact.

---
layout: center
---

<h2>Storyboarding</h2>

<div class="image-wrap">
  <img src="./assets/story_boarding.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
---
## The Assertion–Evidence Model: Effective Slide Design

> Focus on **one clear message per slide**, supported visually

- **Assertion:** A short, declarative sentence stating the main point  
  - Example: "Rio is the ideal location for Disney’s next park"  
- **Evidence:** Graphs, charts, images, or numbers that back up your assertion  
  - Example: Tourist arrivals in Rio, Disney brand awareness data, local infrastructure metrics  
- **Key Principles:**  
  - Keep text minimal; let visuals tell the story  
  - One assertion per slide for maximum clarity  
  - Align evidence directly with your claim  

> Why it works: Audiences instantly understand the key takeaway and see proof, reducing confusion

---
layout: center
---

<h2>Assertion-Evidence Example</h2>

<div class="image-wrap">
  <img src="./assets/Assertion_Evidence_1.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Assertion-Evidence Example</h2>

<div class="image-wrap">
  <img src="./assets/Assertion_Evidence_2.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---

# Sunny Tees: Boosting T-Shirt Sales

---

## Situation
Sunny Tees sells 1,000 t-shirts per month through its online store.

---

## Complication
Last month, sales dropped to 700 t-shirts, even though website traffic stayed the same.

---

## Question
Why did sales drop, and what should Sunny Tees do to boost them?

---

## Answer/Recommendation
**Improve product descriptions, add customer reviews, and adjust pricing to increase t-shirt sales.**

---

## Supporting Arguments

### 1. Increase Sales Through Competitive Pricing
- Lowering the price slightly makes t-shirts more attractive to price-sensitive customers.  
- A competitive price can convert hesitant visitors into buyers and drive volume.

### 2. Build Trust Through Social Proof
- Customer reviews show that others have bought and liked the product.  
- Positive reviews increase buyer confidence and encourage more purchases.


---
---

# SCQA + Pyramid for M15 at 1st Ave & 57th Street

---

## Situation
The M15 bus line serves thousands of riders daily along 1st and 2nd Avenue in Manhattan.

---

## Complication
Buses frequently experience long delays at the intersection of 1st Avenue and 57th Street due to congestion near the bridge during peak hours.

---

## Question
How can the MTA reduce delays at this intersection and improve reliability for M15 riders?

---

## Answer/Recommendation
**Deploy traffic cops during peak hours and optimize bus signal priority at the intersection to reduce delays and improve service reliability.**

---

## Supporting Arguments

### 1. Reduce Congestion with Targeted Traffic Management
- Placing traffic cops at 1st Ave & 57th St during peak hours helps manage vehicle flow.  
- Clearing bottlenecks at critical times allows buses to move more quickly and consistently.

### 2. Improve Bus Flow with Signal Optimization
- Adjusting traffic signals to prioritize buses reduces waiting time at red lights.  
- Coordinated signals help maintain bus schedules and reduce passenger frustration.

---
---

# Assignment: Create Your Own SCQA + Pyramid Scenario


## How to Structure Your Scenario

**1. SCQA Framework**
- **Situation:** Describe the current state.
- **Complication:** Identify the problem or challenge.
- **Question:** Ask what needs to be solved.
- **Answer/Recommendation:** Propose a solution or next step.

**2. Pyramid Principle**
- **Main Recommendation:** Your proposed solution.
- **Supporting Arguments:** 2–3 reasons why your solution works, with evidence or reasoning.

---
---

# The Assertion–Evidence Framework

## Assertion
**Each slide should make one clear statement.**

## Evidence
- Use visuals (charts, diagrams, photos) to support your claim.  
- Keep text minimal—avoid long paragraphs.  
- The audience should be able to read the slide quickly and understand the point.  
- Evidence should **directly back up** your assertion, not introduce new ideas.  

## Key Idea
**Slide = One Idea + Visual Proof**  
This makes your presentation **clear, persuasive, and memorable**.

---
layout: center
---

<h2>Assertion-Evidence Example</h2>

<div class="image-wrap">
  <img src="./assets/Assertion_Evidence_3.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Assertion-Evidence Example</h2>

<div class="image-wrap">
  <img src="./assets/Assertion_Evidence_4.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
---

# Good Data-Driven Declarative Charts
A guide to creating charts that communicate a clear message

---
layout: center
---

<h2>Data Visualization Spectrum</h2>

<div class="image-wrap">
  <img src="./assets/data_decl.png" class="auto-img" />
  <img src="./assets/decl_concept.png" class="auto-img" />
</div>

<style>
/* Prevent Slidev clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Two-column layout */
.image-wrap {
  display: flex;
  gap: 2rem;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* room for title */
}

/* Image behavior */
.auto-img {
  max-width: 45%;
  max-height: 100%;
  object-fit: contain;
}

</style>

---
layout: center
---

<h2>Visual Heirarchy - Reading vs Graphs</h2>

<div class="image-wrap">
  <img src="./assets/read.png" class="auto-img" />
  <img src="./assets/graphs.png" class="auto-img" />
</div>

<style>
/* Prevent Slidev clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Two-column layout */
.image-wrap {
  display: flex;
  gap: 2rem;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* room for title */
}

/* Image behavior */
.auto-img {
  max-width: 45%;
  max-height: 100%;
  object-fit: contain;
}

</style>

---

# 1. Start with the Message, Not the Data
- Every chart should have a clear sentence-level takeaway before touching the data
- Without a claim, the chart is exploratory, not declarative

**Example:**
- Bad: “Here’s all the bus speed data from 2015–2025.”
- Good: “Bus speeds improved modestly after congestion pricing — but gains were uneven”

---

# 2. Choose the Right Visual Form
- Chart type must match the question you want to answer
- Wrong chart hides the message or confuses the audience

**Rule of thumb:**
- Trend → Line
- Compare → Bar
- Composition → Stacked Bar / Pie (few categories)
- Relationship → Scatter

[Learn more about chart types](https://www.data-to-viz.com/#histogram)

---

# 3. Color Communicates Meaning
- Use color intentionally to highlight what matters
- Avoid decorative or excessive colors

**Practical tips:**
- Highlight key data; gray out context
- Limit categorical colors to 4–5
- Avoid rainbow scales; use perceptually uniform gradients
- Ensure colorblind accessibility

---

# 4. Make the Visual Speak Clearly
- Every element should communicate meaning, not decoration
- Colors, scales, labels, and layout are part of the argument

**Practical tips:**
- Bars start at zero; line charts can use non-zero axes if justified
- Keep labels readable and direct
- Avoid unnecessary effects like 3D or shadows

---

# 5. Titles, Annotations, and Context
- Title and annotations frame the message; chart is evidence
- Audiences usually read the title first → make it declarative

**Example:**
- Title: “Average Bus Speeds Increased After Policy, but Only on Select Routes”
- Annotation: “Routes with dedicated lanes saw the largest gains”

---

# 6. Reduce Cognitive Load
- Remove anything that doesn’t help the audience see the claim
- Extraneous details dilute attention

**Practical tips:**
- Remove gridlines, borders, or chart junk
- Directly label lines or bars instead of using a legend
- Keep the design simple and uncluttered

---

# Summary
“Good charts don’t just show data. They **declare a truth**, highlight what matters, and make it instantly understandable.”

---

# From Neutral Graphs to a Story

- We start with **neutral graphs**.  
  - These just show data — they don’t tell a story.

- Our goal: **declarative**  
  - Turn the visual into a clear statement or insight.

- Why? **Declarative statements start the story**  
  - Instead of: "This chart shows bus speeds over time."  
  - Say: "Bus speeds on the M15 dropped sharply after congestion pricing began."

---

# Creating Declarative Graphs

- We will take **simple datasets** and turn them into **story-driven visuals**.  

- Goal: **Each graph tells a clear, declarative insight**.  

- Example workflow:  
  1. Look at the raw numbers or summary stats.  
  2. Identify the key trend or comparison.  
  3. Create a graph that **supports a single, declarative statement**.


---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_6.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_5.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_4.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_3.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_2.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---
layout: center
---

<h2>Create a Declarative Graph</h2>

<div class="image-wrap">
  <img src="./assets/data_1.png" class="auto-img" />
</div>

<style>
/* Fix Slidev container clipping */
.slide {
  overflow: visible !important;
}

.slide-content {
  height: auto !important;
  overflow: visible !important;
}

/* Wrapper controls layout */
.image-wrap {
  display: flex;
  justify-content: center;
  align-items: center;
  height: calc(100vh - 200px); /* leaves room for title */
}

/* Image scaling */
.auto-img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>

---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />

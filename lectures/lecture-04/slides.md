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
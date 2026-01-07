---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see ./assets/bus.png
background: ./assets/bus.png
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

# Data Insights, Visualizations, and Tooling 
### Automated Bus Lane Enforcement (ABLE) 
### Automated Camera Enforcement (ACE) 
**Daniel Brown**

---
layout: quote
position: center
---

**Data convinces the mind —  
but stories move people to act.**

The power of data storytelling is not in the numbers themselves,  
but in how we connect them to human experience.

---
layout: default
---

# Course Objectives

### By the end of this course, you will:

- **Gain the skills to tell a compelling data story**  
  From question → insight → narrative → impact

- **Create two short, article-style data stories**  
  Combining analysis, visualization, and clear storytelling

- **Build an ACE Datathon presentation**  
  Applying everything you’ve learned — data, visuals, structure, and persuasion

---
layout: default
---

# What We Will Cover in This Class

- Storytelling & Narrative  
- Data Visualization  
- Research & Domain Knowledge
- Organizing our Data Story  
- Data Collection  
- EDA
- Statistical Analysis
- Geospatial Analysis
- Asking Questions & Formulating Hypotheses  
- Data Science Workflow  
- LLMs for Research & Analysis  
- Machine Learning Basics  
- Communicating & Presenting Results

---
layout: default
class: text-sm overflow-auto
---

# Storytelling & Narrative in Data

### What is a Story?
- **Setup → Conflict → Resolution**  
- Provides structure and engages the audience  

### What is a Data Story? 
- **SCQA Framework:**  
  - **Situation:** current context  
  - **Complication:** the problem or challenge  
  - **Question:** the key question to answer  
  - **Answer:** insight supported by data  
- **Pyramid Principle:**  
  - Start with the **Answer**  
  - Follow with **supporting reasons and data**  
  - Ensures clarity and persuasiveness  

### Storyboarding
- Sketch your story **before building visualizations**  
- Align visuals with the **narrative flow**

---
layout: default
---

# Data Visualization

### Why It Matters
- Turns data into insight  
- Enables storytelling and persuasion  

### Principles
- **Clarity · Focus · Context · Consistency**

### Storytelling with Charts
- Choose charts for the message  
- Use color and emphasis intentionally  
- Titles and labels guide interpretation  

### Takeaway
- Data viz is a **tool for understanding**, not decoration

---
layout: default
---

# Research & Domain Knowledge

### Why It Matters
- Data doesn’t speak without context  
- Understanding the domain shapes the story you tell  

### What It Involves
- Knowing the **problem space** and stakeholders  
- Understanding how the system actually works  
- Identifying what *matters* vs. what’s noise  

### In Data Storytelling
- Guides the questions you ask  
- Helps you interpret patterns correctly  
- Prevents misleading or shallow conclusions  

### Takeaway
- Strong data stories start with **strong domain understanding**

---
layout: default
---

# Organizing the Data Story

### Why It Matters
- Structure makes complex projects manageable  
- A clear process prevents confusion and rework  

### What It Involves
- Organizing files, folders, and data sources  
- Defining repeatable steps for analysis and visualization  
- Separating exploration, modeling, and presentation  

### In Practice
- Use a clear project structure and naming conventions  
- Build in stages, not all at once  
- Make your work easy to revisit and extend  

### Takeaway
- A strong process turns messy data into a clear story

---
layout: default
---

# Data Collection

### Why It Matters
- Good stories start with good data  
- Data quality shapes everything downstream  

### Common Methods
- **APIs:** structured, reliable, often real-time  
- **Web scraping:** extracting data from websites  
- **Files & databases:** CSVs, spreadsheets, SQL  
- **Manual collection:** surveys, observations  

### Takeaway
- Know where your data comes from and its limits

---
layout: default
---

# Exploratory Data Analysis (EDA)

#### Why It Matters
- Helps you understand what the data actually contains  
- Reveals patterns, trends, and surprises early   

#### What It Involves
- Looking at distributions, ranges, and summary statistics  
- Finding missing values, outliers, and inconsistencies  
- Exploring relationships between variables  
- Checking data quality and limitations  

#### In Practice
- Ask open-ended questions of the data  
- Visualize before you model  
- Use EDA to refine your story and your questions  

#### Takeaway
- EDA turns raw data into understanding and direction

---
layout: default
---

# Statistical Analysis

### Why It Matters
- Quantifies patterns and relationships in your data  
- Adds credibility and rigor to your story  
- Helps separate signal from noise  

### What It Involves
- Descriptive statistics: mean, median, variance  
- Inferential statistics: correlations, regressions, significance  
- Comparing groups, identifying trends, testing hypotheses  

### In Storytelling
- Highlight meaningful, interpretable results  
- Avoid overloading with unnecessary tests  
- Use stats to support the narrative, not replace it  

### Takeaway
- Statistics turn observations into **evidence-driven insights**

---
layout: default
---

# Geospatial Analysis

### Why It Matters
- Many stories have a **location dimension**  
- Maps reveal patterns invisible in tables or charts  

### What It Involves
- Mapping points, areas, or routes  
- Analyzing distances, clusters, and spatial relationships  
- Combining location data with other variables  

### In Storytelling
- Use maps to highlight trends, hotspots, or anomalies  
- Keep maps simple and focused on the insight  
- Integrate geospatial context with your narrative  

### Takeaway
- Geospatial analysis makes **place a powerful part of your story**

---
layout: default
---

# Asking Questions & Formulating Hypotheses

### Why It Matters
- Questions guide your analysis and story  
- Hypotheses give focus and direction to your work  

### What It Involves
- Identifying the problem or insight you want to explore  
- Making testable, clear predictions from the data  
- Considering multiple perspectives and possibilities  

### In Storytelling
- Strong questions lead to compelling narratives  
- Hypotheses frame what to look for and highlight in your story  
- Avoid vague or unfocused questions  

### Takeaway
- Good data stories start with **curiosity and clear hypotheses**

---
layout: default
---

# Data Science Workflow

### Why It Matters
- A clear workflow keeps projects organized  
- Ensures reproducibility and clarity from data to story  

### Key Steps
- **Ask & Hypothesize:** define the question  
- **Collect Data:** APIs, scraping, files, surveys  
- **Explore & Clean:** EDA and quality checks  
- **Analyze & Model:** stats, patterns, insights  
- **Visualize & Communicate:** charts, maps, narrative  

### In Storytelling
- Workflow prevents confusion and wasted effort  
- Makes complex projects manageable and persuasive  

### Takeaway
- A structured workflow turns data into a **coherent, compelling story**

---
layout: default
---

# Using LLMs for Research & Analysis

### Why It Matters
- LLMs accelerate research and insight discovery  
- Can summarize, synthesize, and explain complex data  

### What It Involves
- Extracting insights from text, reports, and datasets  
- Generating hypotheses, questions, and context  
- Assisting with code, visualizations, and analysis explanations  

### In Storytelling
- Use LLMs to **support, not replace**, critical thinking  
- Fact-check outputs and verify data sources  
- Turn LLM outputs into structured insights for your narrative  

### Takeaway
- LLMs are powerful tools to **enhance research and storytelling**, but judgment and domain knowledge remain key

---
layout: default
---

# Machine Learning Basics

### Why It Matters
- ML uncovers patterns and predicts outcomes  
- Helps tell stories grounded in data trends and forecasts  

### Types of ML
- **Descriptive:** uncovers patterns, clusters, and relationships  
- **Predictive:** forecasts future outcomes based on historical data  

### In Storytelling
- Use descriptive ML to reveal hidden insights  
- Use predictive ML to illustrate “what could happen”  
- Always interpret results for your audience — numbers alone don’t tell the story  

### Takeaway
- ML is a tool to **enhance insight and narrative**, not replace explanation

---
layout: default
---

# Communicating & Presenting Results

### Why It Matters
- Insights are only valuable if they are understood  
- Clear presentation makes your story persuasive and actionable  

### What It Involves
- Crafting clear charts, tables, and visuals  
- Using titles, subtitles, and annotations to guide the audience  
- Structuring your presentation for flow and impact  

### In Storytelling
- Highlight key findings, not every detail  
- Tailor the message to your audience  
- Combine visuals, narrative, and context to support your story  

### Takeaway
- Effective communication turns analysis into **actionable, memorable stories**


---
layout: center
class: text-center
---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />

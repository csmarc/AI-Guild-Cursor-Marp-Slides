---
marp: true
theme: default
paginate: true
backgroundColor: "#FFFFFF"
color: "#040405"
header: '<div style="text-align: right;"><img src="./assets/gigentic-black-transpBG.png" width="70px" /></div>'
footer: "AI Guild Session: Building Pitch Decks with Cursor & Marp"
style: |
  @import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;500;700&family=Zain&display=swap');

  section {
    font-family: 'Work Sans', sans-serif;
    padding: 40px;
    font-size: 0.9em;
  }
  header {
    position: absolute;
    top: 20px;
    right: 20px;
    width: auto;
    height: auto;
  }
  h1 {
    font-family: 'Zain', cursive;
    font-size: 3.5em;
    margin-bottom: 0.3em;
    color: #9945FF;
  }
  h2 {
    color: #f8f8f8; 
    margin-top: 0.3em;
    margin-bottom: 0.2em;
    font-size: 2.4em;
  }
  h3 {
    display: inline-block;
    background-color: #9945FF;
    color: #f8f8f8 !important;
    padding: 2px 12px;
    border-radius: 4px;
    margin-top: 0.8em;
    margin-bottom: 0.5em;
    font-size: 1.8em;
    font-weight: 600;
  }
  .intro {
    text-align: center;
  }
  .intro h1 {
    color: #9945FF;
    font-family: 'Zain', cursive;
    font-size: 7em;
  }
  .tagline {
    font-size: 2.5em;
    font-style: italic;
    color: #040405;
    margin-top: 0;
    margin-bottom: 2em;
  }
  ul {
    margin-top: 0.1em;
    margin-bottom: 0.1em;
    padding-left: 1.2em;
  }
  li {
    margin-bottom: 0.2em;
    font-size: 1.4em;
  }
  .team-slide li {
    font-size: 1.2em !important;
  }
  li li {
    margin-top: 0.2em;
    font-size: 0.9em;
  }
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 2rem;
  }
  .columns64 {
    display: grid;
    grid-template-columns: 55fr 45fr;
    gap: 2rem;
  }
  .highlight {
    color: #9945FF;
    font-weight: bold;
  }
  a {
    color: inherit;
    text-decoration: none;
  }
  .feature-box {
    background-color: #f8f8f8;
    border-left: 4px solid #9945FF;
    padding: 8px;
    margin-top: 8px;
    font-size: 1.3em;
  }
  .badge {
    background-color: #9945FF;
    color: white;
    font-weight: bold;
    padding: 2px 6px;
    border-radius: 4px;
    font-size: 1.4em;
    display: inline-block;
    margin-left: 5px;
  }
  .mission-statement {
    text-align: center;
    margin: 15px 0;
    font-size: 1.7em;
    font-weight: 500;
    line-height: 1.4;
  }
  .contact-info {
    font-size: 1.6em;
    font-weight: 600;
    margin-top: 15px;
    color: #040405;
  }
  .email {
    color: #9945FF !important;
    font-weight: bold;
  }
---

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

<div class="intro">

# Pitch Perfect

<p class="tagline">Building Hackathon-Winning<br>Pitch Decks with AI</p>

<p>
<span class="badge">Cursor</span>
<span class="badge">Marp</span>
<span class="badge">AI-Powered</span>
</p>

</div>

<!-- Speaker Notes:
- Welcome everyone to our AI Guild session
- Today we're focusing on how to create winning pitch decks using AI tools
- This method helped us create impressive presentations quickly for hackathons
- We'll share our exact workflow using Cursor AI and Marp
-->

---

# The Hackathon Presentation Problem

<div class="columns64">
<div>

### Common Challenges

- **Developers prioritize building over pitching**
- **Limited design skills** in technical teams
- **Last-minute presentation creation** leads to poor quality
- **Lack of visual storytelling** undermines great projects
- **Time spent on slides = less time coding**

</div>
<div>

<div class="mermaid">
flowchart TD
    Problem[Hackathon Pitch Challenges] --> P1[Time Constraints]
    Problem --> P2[Design Limitations]
    Problem --> P3[Prioritize Code over Slides]
    Problem --> P4[Last-Minute Rush]
    style Problem fill:#9945FF,stroke:#9945FF,color:#FFFFFF,fontSize:32px
    style P1 fill:#1E1E3F,stroke:#1E1E3F,color:#FFFFFF,fontSize:26px
    style P2 fill:#1E1E3F,stroke:#1E1E3F,color:#FFFFFF,fontSize:26px
    style P3 fill:#1E1E3F,stroke:#1E1E3F,color:#FFFFFF,fontSize:26px
    style P4 fill:#1E1E3F,stroke:#1E1E3F,color:#FFFFFF,fontSize:26px
</div>

</div>
</div>

<!-- Speaker Notes:
- We've all been in this situation - great project, terrible presentation
- Most developers would rather code than create slides
- Many technical teams lack design expertise
- Presentations are often left until the last minute
- But judges can only evaluate what they see and understand
- A poor presentation can sink an otherwise excellent project
-->

---

<div class="team-slide">

# Your Guides for Today

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1.5rem;">

<div>

### Dr. Marton Csernai

- **PhD in Computer Science**
- 15+ years development experience
- Former Research Lead at KILT Protocol
- Currently building Gigentic "Escrow-as-a-Service"
- Superteam Germany member

</div>

<div>

### Alexander Schmitt

- **Serial entrepreneur with successful exit**
- Raised €3.5M for previous venture
- Deep expertise in blockchain
- Co-founder of Gigentic
- Experienced in hackathon presentations

</div>
</div>

<div class="feature-box">
<strong>Real-World Application:</strong> We're using this exact workflow to create our Breakout Hackathon pitch deck
</div>

<div class="feature-box">
<strong>Built for Builders:</strong> Designed for developers who want professional results without sacrificing coding time
</div>

<!-- Speaker Notes:
- Brief introduction about us and our experience
- Marton: Technical background, PhD, extensive development experience
- Alex: Business background, fundraising experience, presentation skills
- We're actively using this workflow for our current hackathon projects
- We designed this system because we faced these challenges ourselves
-->

---

# Our Solution: Cursor + Marp Workflow

<div class="mermaid" style="text-align: center; width: 80%; height: 120px; max-height: 120px; margin: 20px auto; font-size: 0.8em;">
flowchart LR
    A[Project Docs] --> B[Cursor AI]
    B --> C[Draft Content]
    C --> D[Marp Markdown]
    D --> E[Visual Slides]
    E --> F[Export Formats]
    style B fill:#9945FF,stroke:#9945FF,color:#FFFFFF
    style D fill:#9945FF,stroke:#9945FF,color:#FFFFFF
</div>

<div class="columns" style="margin-top: 10px;">
<div>

### The Power of Cursor AI

- **Intelligent content generation** from project materials
- **Code-centric environment** familiar to developers
- **Iterative refinement** with targeted prompts
- **Collaborative workflow** for team input

</div>
<div>

### The Magic of Marp

- **Markdown-to-presentation** conversion
- **Version control friendly** - works with Git
- **Customizable themes** for brand consistency
- **Mermaid diagram integration** for architecture visuals
- **Export to multiple formats** (PDF, PPTX, HTML)

</div>
</div>

<div class="feature-box">
<strong>Key Benefit:</strong> Create professional presentations while staying in your development environment
</div>

<!-- Speaker Notes:
- Our solution combines two powerful tools: Cursor AI and Marp
- The flowchart shows how we go from project docs to final presentation
- Cursor AI helps generate content based on your project materials
- Marp converts markdown to beautiful presentations
- The entire workflow stays within environments developers are comfortable with
- No need to switch to PowerPoint or design tools
-->

---

# What is Marp?

<div class="columns">
<div>

### Markdown Presentation Ecosystem

- **Marp = Markdown Presentation Ecosystem**
- Write slides in Markdown, render as presentations
- VS Code extension with live preview
- CLI for automation and CI/CD integration
- Built for developers who prefer text over GUI

</div>
<div>

### How Marp Works

```markdown
---
marp: true
theme: default
---

# Slide 1 Title

Content for first slide

---

# Slide 2 Title

- Bullet points
- More content
```

- **Front matter** for configuration
- **Triple dash (---)** separates slides
- **Standard Markdown** for content formatting

</div>
</div>

<div class="feature-box">
<strong>Developer-First:</strong> Marp treats presentations as code - write, version, collaborate, and deploy
</div>

<!-- Speaker Notes:
- Marp stands for Markdown Presentation Ecosystem
- It allows you to create presentations using only markdown
- Perfect for developers who are already comfortable with markdown
- The right side shows a simple example of Marp syntax
- Configuration happens at the top in the front matter
- Each slide is separated by three dashes
- Content is formatted using standard markdown syntax
- Marp has great VS Code integration with live preview
-->

---

# Technical Implementation

<div class="mermaid">
graph LR
    A[Setup Environment] --> B[Install Cursor]
    A --> C[Install VS Code + Marp]
    B --> D[Create Project Structure]
    C --> D
    D --> E[Add Template Files]
    E --> F[Configure Mermaid]
    F --> G[Ready to Build]
    style B fill:#9945FF,stroke:#9945FF,color:#FFFFFF
    style C fill:#9945FF,stroke:#9945FF,color:#FFFFFF
    style F fill:#9945FF,stroke:#9945FF,color:#FFFFFF
</div>

<div class="feature-box">
<strong>Full Environment:</strong> Complete setup in under 15 minutes, even for newcomers
</div>

<!-- Speaker Notes:
- This diagram shows the complete implementation flow
- Start by setting up Cursor IDE and VS Code with the Marp extension
- Create a simple project structure for your presentation assets
- The entire setup takes less than 15 minutes
- Mermaid diagrams like this one are integrated directly into Marp
- This makes it easy to create technical diagrams without external tools
-->

---

# Workflow: From Project to Pitch

<div class="mermaid" style="text-align: center; width: 100%; margin: 1.5em auto 2em auto;">
gantt
dateFormat  HH:mm
title Pitch Deck Creation Timeline
axisFormat  %H:%M
section Phase 1
Project Setup    :active, p1, 00:00, 10m
Draft Content Generation :active, p2, after p1, 15m
section Phase 2
Marp Implementation     :p3, after p2, 15m
section Phase 3
Visual Enhancements     :p4, after p3, 10m
section Phase 4
Final Optimization                :p5, after p4, 10m
</div>

<div class="columns">
<div>

### AI Prompt Strategy

- Start with **project description** & PRD
- Generate **slide structure** before details
- Use **targeted prompts** for specific sections
- Leverage AI for **visual suggestions**

</div>
<div>

### Marp Implementation Tips

- Maintain **consistent brand styling**
- Utilize **Mermaid for technical diagrams**
- Create **reusable component styles**
- Add **responsive layout** considerations
- **Minimize text** / Maximize impact

</div>
</div>

<!-- Speaker Notes:
- Our complete workflow takes about 60 minutes from start to finish
- We begin with project setup and using AI to generate draft content
- Then implement in Marp and add visual enhancements
- Left side shows our AI prompt strategy - start broad, then get specific
- Right side shows Marp implementation tips for best results
- Notice how we use Gantt charts directly in Marp for timeline visualization
- This entire presentation was created using exactly this workflow
-->

---

# Advantages of Our Approach

<div class="columns">
<div>

### For Developers

- **Stay in your coding environment**
- **Version control** your presentation
- **Collaborate** using Git workflows
- **Automate repetitive tasks** with AI
- **Focus on code** while AI handles content

</div>
<div>

### For Teams & Projects

- **Professional results** with minimal effort
- **Consistent branding** across presentations
- **Rapid iteration** based on feedback
- **Easily updatable** as project evolves
- **Export to multiple formats** for different audiences

</div>
</div>

<div class="feature-box">
<strong>Time Savings:</strong> Reduce presentation creation time by 75% compared to traditional methods
</div>

<div class="feature-box">
<strong>Quality Improvement:</strong> Achieve professional design standards without design expertise
</div>

<!-- Speaker Notes:
- Our approach offers significant advantages for both individual developers and teams
- For developers: stay in familiar environment, use version control, focus on building
- For teams: consistent branding, rapid updates, professional results
- We've found this method saves about 75% of the time normally spent on presentations
- Quality improvement is substantial - presentations look professional without design skills
- This directly addresses the hackathon presentation challenges we identified earlier
-->

---

# Technical Demo: Mermaid Diagrams

<div class="columns">
<div>

### Mermaid Syntax Example

```markdown
<div class="mermaid">
flowchart TD
    A[Start] --> B{Decision}
    B -->|Yes| C[Action 1]
    B -->|No| D[Action 2]
    C --> E[Result]
    D --> E
    style A fill:#9945FF,color:#FFF
    style E fill:#14F195,color:#000
</div>
```

- **Add directly in markdown**
- **Automatic rendering** in presentation
- **Perfect for architecture diagrams**

</div>
<div>

<div class="mermaid">
flowchart TD
    A[Start] --> B{Decision}
    B -->|"1) Yes"| C[Action 1]
    B -->|"2) No"| D[Action 2]
    C --> E[Result]
    D --> E
    style A fill:#E06616,color:#FFF
    style E fill:#14F195,color:#000
</div>

</div>
</div>

<div class="feature-box">
<strong>AI-Generated Diagrams:</strong> Use Cursor to create Mermaid diagrams from project descriptions
</div>

<!-- Speaker Notes:
- Let's look at how Mermaid diagrams work in practice
- Left side shows the actual markdown syntax used to create the diagram
- Right side shows the rendered result
- You can create flowcharts, sequence diagrams, Gantt charts, and more
- Mermaid syntax is simple and declarative
- Cursor AI can help generate these diagrams from project descriptions
- This is especially powerful for architecture and workflow diagrams
-->

---

# Practical Next Steps

<div class="columns">
<div>

### Resources We'll Provide

- **GitHub repository** with all templates
- **AI prompt cheat sheet** for pitch decks
- **Marp theme template** with Solana styling
- **Sample Mermaid diagrams** for common use cases
- **Step-by-step tutorial** recording

</div>
<div>

### Your Action Items

- **Install Cursor** (cursor.sh)
- **Set up VS Code** with Marp extension
- **Clone our GitHub repo** for templates
- **Gather your project materials**
- **Follow our workflow** for your next pitch

</div>
</div>

<div class="mission-statement">
    <span class="highlight">Build Projects, Not Presentations</span><br>Let AI and markdown do the heavy lifting
</div>

<div class="contact-info">
Contact: <span class="email">info@gigentic.ai</span>
</div>

<!-- Speaker Notes:
- We're providing several resources to help you get started
- GitHub repo with templates, cheat sheets, and sample diagrams
- Your action items are simple: install tools, clone repo, start creating
- Remember our philosophy: Build Projects, Not Presentations
- Let the tools do the heavy lifting so you can focus on building
- Feel free to reach out with questions at the email address shown
- Thank you all for attending today's session!
-->

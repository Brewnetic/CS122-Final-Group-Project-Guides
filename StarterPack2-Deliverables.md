# CS122 Final Group Projects: The Deliverables Guide

---

## DELIVERABLES AT A GLANCE

You owe **5 things** for this project:

| # | Deliverable | Format | Length |
|---|-------------|--------|--------|
| 1 | **Proposal** | Markdown / PDF / Word in the project repo | 1–2 pages |
| 2 | **Working Code (MVP)** | Java codebase in GitHub repo | Working, runnable |
| 3 | **Live Pitch Presentation** | In-class talk + live demo | 5–10 min total |
| 4 | **Presentation Slides** | PowerPoint / Slides | 7 slides |
| 5 | **Appendix** | Markdown / PDF / Word in the project repo | 1–2 pages |

Everything must be **cohesive** — proposal, code, slides, and appendix all tell the same story.

---

## WHAT IS AN MVP? AND WHY DOES IT MATTER?

### MVP = Minimum Viable Product

**MVP Definition:** The smallest, simplest version of your product that solves the core problem and is good enough to demonstrate to real users/customers.

**NOT:** A feature-complete, fully polished product
**IS:** A working prototype that proves your concept works

### Why MVPs?

**Real-World Context:** Companies like Instagram, Uber, and Dropbox all started with MVPs. Instagram's MVP didn't have filters — just photo uploads. Uber's MVP worked in only one city. They launched, got feedback, then improved.

In your case: You have **2 weeks** and a **2-person team**. You can't build everything. Focus on doing a few things **really well** instead of many things **poorly**.

---

# DELIVERABLE 1: THE PROPOSAL (1-2 Pages)

## What Is a Proposal?

A proposal is a **short, persuasive document** that introduces your project idea to stakeholders (professors and classmates). It answers:

- **What** problem are you solving?
- **Who** has this problem?
- **How** will you solve it?
- **Why** will people want this?
- **How** will you prove it works? (viability)
- **How** will it grow? (scalability)

## Proposal Structure & Length

**Length:** 1-2 pages
**Format:** Markdown, PDF, or Word document in your project repo

---

## REQUIRED Proposal Sections (Template)

```
PROJECT TITLE
Team Members: [Two Names]
Category: [Which category from the list]

1. PROBLEM STATEMENT (2-3 sentences)
   What problem are you solving? Who has this problem?

2. SOLUTION (3-4 sentences)
   What is your MVP? What are the 1-3 core features?

3. TARGET MARKET (1-2 sentences)
   Who will use this? How many potential customers?

4. WHY IT'S VALUABLE (1-2 sentences)
   How does this solve a real pain point? What's the business value?

5. HOW YOU'LL MAKE MONEY (1-2 sentences)
   Subscription? One-time purchase? Freemium? Ads?

6. MVP FEATURES (Bulleted list)
   - Feature 1
   - Feature 2
   - Feature 3

7. TIMELINE & DIVISION OF WORK (REQUIRED - NOT OPTIONAL)
   Week 1: [Name] - [Task] | [Name] - [Task]
   Week 2: [Name] - [Task] | [Name] - [Task]

8. TEAM ROLES & RESPONSIBILITIES (REQUIRED - NOT OPTIONAL)
   Each teammate takes TWO roles (two hats). Choose from:
   Product Owner | Lead Developer | Tester | Researcher

   [Name] - [Two Roles, e.g., Lead Developer + Tester]
   - Responsibility 1
   - Responsibility 2
   - Estimated % of codebase: X%

   [Name] - [Two Roles, e.g., Product Owner + Researcher]
   - Responsibility 1
   - Responsibility 2
   - Estimated % of codebase: X%

9. VIABILITY: HOW WE'LL PROVE THIS WORKS (REQUIRED - NOT OPTIONAL)
   How will you validate that real users want this?
   - User testing plan (who, when, how many)
   - Competitive analysis (what exists now, why ours is better)
   - Market research sources (prove your market exists)
   - Success metrics (what proves viability?)

10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS (REQUIRED - NOT OPTIONAL)
    Phase 1 (Now): MVP with X users/features
    Phase 2 (6 months): Expand to X users, add X features
    Phase 3 (12 months): Scale to X users, add X features

    Technical progression needed to scale
    Revenue model at each phase

11. SOURCES & REFERENCES (REQUIRED - NOT OPTIONAL)
    List all sources for market claims, competitive analysis, and research
    - Source 1: [Title/URL]
    - Source 2: [Title/URL]
    - Interviews: [Who you spoke with]
```

---

## Real Example 1: Inventory Management System

```
PROJECT TITLE: QuickStock - Inventory Management for Small Businesses

Team Members: Sarah Chen, Marcus Williams
Category: Business/Corporate Application

1. PROBLEM STATEMENT
   Small coffee shops and retail stores spend 2+ hours daily on manual
   inventory tracking. Spreadsheets are error-prone and don't alert when
   stock is low, leading to lost sales from stockouts and waste from overordering.

2. SOLUTION
   QuickStock is a Java desktop app that lets store managers add products,
   track stock levels, and automatically alerts them when items fall below a
   reorder threshold. Core features: product tracking, auto-alerts, monthly reports.

3. TARGET MARKET
   Small independent coffee shops, bakeries, and boutique retail stores
   (US market size: ~500,000 locations). Current solutions (Square, Toast)
   are $200+/month and overkill for simple inventory tracking.

4. WHY IT'S VALUABLE
   Prevents lost sales from stockouts. Reduces overordering waste.
   Affordable ($25 one-time vs. $200/month competitors).
   Saves 2+ hours daily vs. spreadsheet method.

5. HOW YOU'LL MAKE MONEY
   One-time $25 purchase per license (targets 1% market = $125M potential).
   Optional premium tier ($3/month) with cloud backup and multi-location
   support in Phase 2.

6. MVP FEATURES
   - Add/edit/delete products with price and quantity
   - Track stock changes (sales, restocking)
   - Automatic alerts when stock < minimum threshold
   - Monthly report: total inventory value, low-stock items
   - Import/export data as CSV file

7. TIMELINE & DIVISION OF WORK
   Week 1:
   - Sarah: Product and Inventory classes, stock tracking logic, alert system
   - Marcus: User interviews, sample data, CSV file I/O, README

   Week 2:
   - Both: Integration, testing, edge cases, viability validation, demo prep

8. TEAM ROLES & RESPONSIBILITIES
   Sarah Chen - Lead Developer + Tester
   - System architecture and class design
   - Core classes (Product, Inventory) and alert logic
   - QA, edge case testing, demo validation
   - Estimated 55% of codebase

   Marcus Williams - Product Owner + Researcher
   - Feature prioritization and MVP scope decisions
   - User testing with real coffee shop owner
   - CSV file I/O and import/export
   - Market research, competitive analysis, README, documentation
   - Estimated 45% of codebase

9. VIABILITY: HOW WE'LL PROVE THIS WORKS
   User Testing:
   - Interview Sarah's dad (coffee shop owner) daily during development
   - Ask: "Does this solve your problem? Would you pay $20-30?"
   - Test with data from 2-3 real shops

   Competitive Analysis:
   - Compare with Square ($200/mo), Toast ($250/mo), QuickBooks ($35-80/mo)
   - Our advantage: Lean, focused, affordable, offline-capable
   - No other tool targets small shops specifically

   Market Research:
   - SBA data: 500,000+ independent retail shops in US
   - Statista: 78% of small retailers use spreadsheets
   - This proves market exists and is underserved

   Success Metrics:
   - User says "I would pay $20-30 for this"
   - App prevents stockouts in test week
   - Saves 2+ hours vs. spreadsheet method
   - Real users prefer it over Square/Toast

10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS
    Phase 1 (Now - 2 weeks):
    - MVP desktop app, CSV storage
    - Supports 1 location, 1 user
    - Target: 100-500 early users
    - Revenue: $25 one-time purchase

    Phase 2 (Months 3-6):
    - Migrate to web app + SQL database
    - Add multi-location support (manage 5+ locations)
    - Team member roles (Admin, Staff, Viewer)
    - Cloud backup and syncing
    - Target: 5,000-10,000 users
    - Revenue: $3/month freemium model

    Phase 3 (Months 6-12):
    - Mobile apps (iOS, Android)
    - Predictive analytics (AI forecasting)
    - Supplier integration (auto-ordering)
    - White-label licensing for POS systems
    - Target: 50,000-100,000+ users
    - Revenue: $5-10/month + B2B licensing

    Technical Progression:
    Phase 1: Java desktop + File I/O (CSV)
    Phase 2: Java backend + PostgreSQL database + Web frontend
    Phase 3: Microservices + Cloud infrastructure + Mobile SDKs

    Why This Progression:
    - CSV works for 1-100 users (Phase 1)
    - Database needed for 100-10k users (Phase 2)
    - Cloud/microservices needed for 10k-100k+ users (Phase 3)
    - Each phase lasts 6 months and builds on previous

11. SOURCES & REFERENCES
    - US Small Business Administration (SBA): "2023 Small Business Statistics"
      https://www.sba.gov/sites/default/files/2023-sbr-508c.pdf
      (Reports ~500,000 independent retail locations in US)

    - Statista: "Spreadsheet Software Adoption in Small Business"
      (78% of small retailers still use spreadsheets for inventory)

    - G2 Reviews: Comparison of Square vs Toast vs QuickBooks
      (Average cost: $200-300/month for POS systems)

    - Interview: Sarah's father (local coffee shop owner)
      (Spends 2 hours/day on inventory, would pay $20-30)
```

---

## Real Example 2: Quiz Application

```
PROJECT TITLE: StudyMate - Interactive Quiz & Testing Platform

Team Members: James Rodriguez, Aisha Okonkwo
Category: Education/E-Learning

1. PROBLEM STATEMENT
   Teachers manually grade 100+ multiple-choice quizzes weekly, spending
   10+ hours on grading. Students wait days for feedback. No central system
   to track class performance across quizzes.

2. SOLUTION
   StudyMate lets teachers create quizzes in minutes. Students take them
   online and get instant feedback. Teachers see class analytics automatically.
   Core features: quiz creation, auto-scoring, class analytics.

3. TARGET MARKET
   Teachers in 50,000+ US high schools. Each school has ~50-100 teachers.
   Current solutions: Google Forms (free, limited), Quizziz ($8-16/mo),
   Canvas (complex). We target teachers wanting simple, free, offline-friendly testing.

4. WHY IT'S VALUABLE
   Saves teachers 10+ hours/week on grading. Students get instant feedback.
   Works offline (no internet required). Free for teachers = huge adoption
   potential. Much simpler than Quizziz or Canvas.

5. HOW YOU'LL MAKE MONEY
   Freemium model: Free tier includes 5 quizzes. Premium ($2/month) =
   unlimited quizzes + advanced analytics.
   Plus: B2B licensing to school districts ($5k/year per school).

6. MVP FEATURES
   - Teachers create multiple-choice and short-answer questions
   - Save quizzes to file, load from file
   - Students take quiz, answers auto-scored
   - Show correct/incorrect feedback for each question
   - Display class average score and individual student results

7. TIMELINE & DIVISION OF WORK
   Week 1:
   - James: Question class hierarchy (MultipleChoice, ShortAnswer inheritance), Quiz core class
   - Aisha: Scoring logic, sample quizzes, teacher interviews, file I/O design

   Week 2:
   - Both: Integration, testing, viability validation, demo preparation

8. TEAM ROLES & RESPONSIBILITIES
   James Rodriguez - Lead Developer + Researcher
   - Class hierarchy design (abstract Question + subclasses)
   - Quiz core logic and scoring
   - Code documentation, README, technical write-up
   - Estimated 60% of codebase

   Aisha Okonkwo - Product Owner + Tester
   - Teacher interviews and feature prioritization
   - File I/O implementation (saving/loading quizzes)
   - QA, test cases, and edge case handling
   - Market research and competitive analysis
   - Estimated 40% of codebase

9. VIABILITY: HOW WE'LL PROVE THIS WORKS
   User Testing:
   - Interview 3 real high school teachers (biology, history, math)
   - Ask: "How much time do you spend grading? Would you use this?"
   - Have 1 teacher test the app for 1 week with a real class

   Competitive Analysis:
   - Google Forms: Free but terrible for grading (manual review)
   - Quizziz: $8-16/month, has ads on free tier, complex
   - Canvas: Free for schools but requires setup, not intuitive
   - Our advantage: Simple, free, offline, instantly grades

   Market Research:
   - NCES data: ~50,000 US high schools, ~3.6 million teachers
   - Gallup: Teachers spend 12+ hours/week on grading
   - This proves huge market and real need

   Success Metrics:
   - Real teacher says "I would use this in my classroom"
   - Teacher saves 3+ hours grading one class's quizzes
   - Students like instant feedback feature
   - App works reliably offline

10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS
    Phase 1 (Now - 2 weeks):
    - Desktop app, local file storage
    - Supports 1 teacher, ~30 students per class
    - Target: 50-200 early adopters
    - Revenue: Free (build user base first)

    Phase 2 (Months 3-6):
    - Web app + SQL database
    - Freemium model ($2/month for premium)
    - Multi-class support (teachers manage 4-6 classes)
    - Student progress tracking across quarters
    - Target: 2,000-5,000 teachers
    - Revenue: $2/month × 5% premium conversion = $6k/month

    Phase 3 (Months 6-12):
    - Mobile apps (iOS, Android for students)
    - AI-generated questions (based on topic)
    - Adaptive difficulty (questions get harder as students improve)
    - School district licensing ($5k/year per 100 teachers)
    - Target: 20,000-50,000 teachers
    - Revenue: Freemium + district licensing = $100k+/month

    Technical Progression:
    Phase 1: Java desktop + File I/O
    Phase 2: Java backend + MySQL + Web frontend (HTML/JavaScript)
    Phase 3: Microservices + PostgreSQL + Mobile SDKs + AI API

    Why This Progression:
    - Phase 1: Desktop + files fine for 100 users
    - Phase 2: Database needed for 1,000+ users and multi-class support
    - Phase 3: Cloud needed for mobile apps + AI features at scale

11. SOURCES & REFERENCES
    - National Center for Education Statistics (NCES)
      https://nces.ed.gov/
      (Confirms ~50,000 US high schools, ~3.6 million teachers)

    - Gallup Education Survey: "Teacher Workload & Technology Adoption"
      (Teachers spend average 12+ hours/week on grading)

    - G2 Reviews: Quiz/Testing Platform Comparison
      (Google Forms free, Quizziz $8-16/mo, Canvas free for schools)

    - Interviews: Mrs. Johnson (high school biology teacher)
      (Spends 3-4 hours/week grading quizzes, would pay $2/month)
```

---

## Proposal Checklist

Before submitting:

- [ ] Problem statement clearly identifies real pain point
- [ ] Solution explains MVP (not full product)
- [ ] Target market is specific (not "everyone")
- [ ] Business model explains how you make money
- [ ] MVP features are realistic (1-3 core features)
- [ ] Timeline divides work logically between BOTH teammates (REQUIRED)
- [ ] Team roles assigned (each person takes TWO hats) (REQUIRED - NOT OPTIONAL)
- [ ] Viability section explains how you'll prove it works (REQUIRED - NOT OPTIONAL)
- [ ] Scalability section shows Phase 1 → 2 → 3 roadmap (REQUIRED - NOT OPTIONAL)
- [ ] Sources & References cited with links (REQUIRED - NOT OPTIONAL)

---

# DELIVERABLE 2: THE FINISHED PROGRAM/CODEBASE

## What This Means

Your **working Java application** that demonstrates your MVP:

- ✓ Compiles without errors
- ✓ Runs without crashing (handles edge cases)
- ✓ Has meaningful sample data loaded
- ✓ Organized and documented
- ✓ Showcases MVP features from proposal

The code should be ready to demo and prove your viability claims work in practice.

---

# DELIVERABLE 3: LIVE PITCH PRESENTATION (5-10 Minutes TOTAL)

## Presentation Structure

**Total Time: 5-10 minutes**

- Pitch (3-5 minutes)
- Demo (1-2 minutes)
- Q&A (1-2 minutes)

**Both teammates present.** One person may lead the pitch, but both should speak — typically the Product Owner leads framing, the Lead Developer leads the demo, and Q&A is shared.

## Presentation Sections (Must Match Proposal)

### 1. OPENING (15-20 seconds)

Introduce yourselves and hook with the problem.

**Example:**

> "Hi, we're Sarah and Marcus. We built QuickStock. Sarah's dad owns a coffee shop and spends 2 hours every morning checking inventory manually. He loses $500 in sales when he runs out of stock. We built a tool that fixes this."

### 2. PROBLEM (45-60 seconds)

Explain the pain point with data from proposal.

**Example:**

> "According to SBA data, there are 500,000 small retail shops in the US. Research shows 78% still use spreadsheets for inventory. The problem: no alerts when stock is low. Result: lost sales from stockouts and waste from overordering. This is a real, expensive problem."

### 3. SOLUTION (45-60 seconds)

Describe your MVP simply.

**Example:**

> "QuickStock is a Java desktop app that solves this. Add products once with a reorder threshold. Update quantities as you sell. The app automatically alerts you when stock falls below threshold. You get monthly reports. That's it — three core features that actually solve the problem. Price: $25 one-time."

### 4. DEMO (1-2 minutes)

**Live demo showing your MVP works.** (Corresponds to proposal MVP features)

**Demo Script:**

```
"Let me show you how it works.
Here's an empty inventory. I'll add three products...
[Add Coffee Beans, Paper Cups, Milk]

We have a busy day — sold 90 paper cups.
I update it to 10 units...

Watch — instant alert! 'Paper Cups below reorder threshold.'
This prevents stockouts before they happen.

Here's the monthly report showing inventory value and low-stock items.
That's QuickStock."
```

### 5. VIABILITY: PROOF THAT THIS WORKS (45-60 seconds)

**This corresponds directly to Proposal Section 9 (Viability)**

Show that real users want this and competitors don't do it better.

**Example:**

> "We tested this with real users. Sarah's dad said 'This is exactly what I need. I would pay $20-30.' We researched competitors: Square costs $200/month, Toast costs $250/month. Our advantage: lean, focused, affordable, offline-capable. No other tool targets small shops specifically. This proves the market wants what we built."

**What judges want:**

- User testing results (real feedback, not theoretical)
- Competitive advantage proven
- Market research backing claims
- Honest about MVP limitations

### 6. SCALABILITY: ROADMAP FOR GROWTH (1 minute)

**This corresponds directly to Proposal Section 10 (Scalability)**

Show you thought beyond MVP.

**Example:**

> "Here's how we scale from 100 users to 100,000. Phase 1 (now): desktop app, CSV storage. Phase 2 (6 months): web app with database, cloud backup, multi-location support — targets 10k users. Phase 3 (12 months): mobile apps, AI forecasting, enterprise licensing — targets 100k+ users. Revenue grows from $25 one-time to $3/month freemium to $10/month plus licensing."

**What judges want:**

- Realistic phasing (6-month phases)
- Technical progression explained (CSV → Database → Cloud)
- Revenue model growth
- Honest about current limitations ("CSV doesn't scale to 100k users")

### 7. CLOSING (15-20 seconds)

Thank them and invite questions.

**Example:**

> "That's QuickStock. We solved a real problem with a working MVP. We validated it with real users. We have a clear roadmap to scale. We're ready for your questions."

---

## Presentation Consistency with Proposal

Your presentation should mirror your proposal:

| Proposal Section  | Presentation Section           | Slide          |
| ----------------- | ------------------------------ | -------------- |
| Problem Statement | Opening + Problem              | Slide 2        |
| Solution          | Solution                       | Slide 3        |
| MVP Features      | Demo                           | Slide 4        |
| Business Model    | Why It Matters                 | Slide 3        |
| Viability         | Viability (with proof)         | Slide 5        |
| Scalability       | Scalability/Roadmap            | Slide 6        |
| Sources           | Cited verbally in presentation | Slides 2, 3, 5 |

If your proposal says X, your presentation should show X. If your proposal claims you'll prove viability with user testing, your presentation shows user testing results.

---

# DELIVERABLE 4: PRESENTATION SLIDES (7 slides)

## Slide Structure (Must Match Presentation)

**Slide 1: Title & Team (15 sec)**

```
QuickStock
Inventory Management for Small Businesses

Sarah Chen, Marcus Williams
CS122 Final Project
```

**Slide 2: Problem (45-60 sec)**

```
THE PROBLEM

📊 500,000+ small retail shops in US (SBA data)
📉 78% still use spreadsheets (Statista)

Pain Points:
❌ No alerts when stock is low → Lost sales
❌ Manual tracking takes 2+ hours daily
❌ Overordering leads to waste
❌ No analytics on inventory value

This is a $125M problem.
```

**Slide 3: Solution & Business Model (45-60 sec)**

```
OUR SOLUTION: QuickStock

Three Core MVP Features:
1. Add/track products with auto-alerts
2. Real-time stock level notifications
3. Monthly analytics reports

Business Model:
💰 $25 one-time purchase
💰 Optional $3/month premium (Phase 2)
💰 1% market share = $125M potential revenue
```

**Slide 4: Demo Walkthrough (1-2 min LIVE)**

```
[LIVE DEMO STARTS HERE]

Show:
1. Empty inventory → Add products
2. Simulate sales → Update quantities
3. Watch alert trigger
4. Show monthly report

[Return to slides after demo]
```

**Slide 5: Viability - Proof It Works (45-60 sec)**

```
HOW WE VALIDATED THE MVP

Testing Results:
✓ Built in 2 weeks (realistic timeline)
✓ Tested with real users (Sarah's dad's shop)
✓ 100% prevented stockouts in trial week
✓ Saves 2+ hours daily vs. spreadsheet

User Feedback:
"This is exactly what I need.
Would definitely pay $20-30."
  — Sarah's dad (coffee shop owner)

Competitive Analysis:
Tool      | Price      | Setup  | Offline
QuickStock| $25        | 5 min  | ✓ Yes
Square    | $200/month | 30 min | ✗ No
Toast     | $250/month | 1 hour | ✗ No
```

**Slide 6: Scalability - Roadmap to Growth (1 min)**

```
SCALING FROM MVP TO 100K USERS

Phase 1 (Now): Desktop + CSV
→ 1 location, 100-500 users

Phase 2 (6 months): Web + Database
→ Multi-location, 5,000-10,000 users
→ Revenue: $3/month freemium

Phase 3 (12 months): Cloud + Mobile
→ Global scale, 50,000-100,000+ users
→ Revenue: $5-10/month + licensing

Technical Progression:
Phase 1: Java desktop + File I/O
Phase 2: Java backend + PostgreSQL + Web
Phase 3: Microservices + Cloud + Mobile SDKs
```

**Slide 7: Questions (30 sec)**

```
Questions?

GitHub: [repository link]
Team Contacts:
  Sarah: sarah@email.com
  Marcus: marcus@email.com

"We solve a $125M problem with a $25 solution"
```

---

## Slide & Presentation Checklist

Before presenting:

**Content Consistency:**

- [ ] Proposal problem matches Slide 2 problem
- [ ] Proposal MVP features match Slide 4 demo features
- [ ] Proposal viability strategy matches Slide 5 proof
- [ ] Proposal scalability plan matches Slide 6 roadmap
- [ ] Proposal business model matches Slide 3 pricing
- [ ] Proposal sources cited verbally in presentation

**Slide Quality:**

- [ ] 7 slides total (not more, not less)
- [ ] Font size 24pt+ (readable from back of room)
- [ ] No text walls (only key points on slides)
- [ ] Visuals/images where possible (not just text)
- [ ] Colors consistent throughout
- [ ] No typos or grammar errors

**Presentation Timing:**

- [ ] Pitch (excluding demo): 3-5 minutes
- [ ] Demo: 1-2 minutes
- [ ] Q&A: 1-2 minutes
- [ ] Total: 5-10 minutes
- [ ] Practiced timing (use timer)

**Demo Integration:**

- [ ] Demo is integrated into presentation (not separate)
- [ ] Slide 4 introduces demo ("Let me show you...")
- [ ] Return to Slide 5 after demo ("Here's proof...")
- [ ] Demo flows naturally into viability discussion

**Viability & Scalability:**

- [ ] You explain real user testing (not theoretical)
- [ ] You show competitive advantage
- [ ] You cite your sources (proposal sources)
- [ ] You explain 3-phase roadmap clearly
- [ ] You acknowledge MVP limitations
- [ ] You show revenue/business growth strategy

**Team Preparation:**

- [ ] Both teammates can explain proposal sections
- [ ] Both can discuss viability strategy
- [ ] Both can discuss scalability plan
- [ ] Both can answer Q&A questions
- [ ] Both know their speaking parts (no one silent during the pitch)

---

# DELIVERABLE 5: APPENDIX (1-2 Pages)

The appendix should reference your viability testing and scalability planning:

## Appendix Sections

```
1. TEAM CONTRIBUTION
   [Show who coded what — both teammates listed with roles from proposal]

2. JAVA CONCEPTS APPLIED
   [List concepts used]

3. CHALLENGES & SOLUTIONS
   [Honest discussion of problems during MVP building]

4. PROJECT TIMELINE
   [How you spent the 2 weeks]

5. HOW WE COLLABORATED
   [Team process — how the two of you split work, communicated, resolved conflicts]

6. VIABILITY TESTING (new section)
   [How you validated the MVP in practice]
   - User testing we did
   - Feedback we got
   - Changes we made based on testing
   - Proof that viability claims are real (not theoretical)

7. CITATIONS & EXTERNAL RESOURCES (REQUIRED)
   [All sources including research for proposal sections 9-10]
   - Stack Overflow, Claude, YouTube references
   - Market research sources
   - Competitive analysis sources
   - User interview notes

8. REFLECTIONS & LESSONS LEARNED
   [Growth and learning]
```

---

# FINAL MASTER CHECKLIST

## ✓ Proposal (1-2 pages) - REQUIRED SECTIONS:

- [ ] Problem Statement
- [ ] Solution (MVP description)
- [ ] Target Market
- [ ] Why Valuable
- [ ] How You'll Make Money
- [ ] MVP Features (1-3 features)
- [ ] **Section 7: Timeline & Division of Work — both teammates (REQUIRED - NOT OPTIONAL)**
- [ ] **Section 8: Team Roles & Responsibilities — each person takes TWO hats (REQUIRED - NOT OPTIONAL)**
- [ ] **Section 9: Viability - How We'll Prove This Works (REQUIRED - NOT OPTIONAL)**
- [ ] **Section 10: Scalability - Roadmap to 100K Users (REQUIRED - NOT OPTIONAL)**
- [ ] **Section 11: Sources & References (REQUIRED - NOT OPTIONAL)**

## ✓ Code (Working MVP):

- [ ] Compiles without errors
- [ ] Runs without crashing
- [ ] Has sample data pre-loaded
- [ ] Demonstrates MVP features from proposal
- [ ] Code is documented

## ✓ Presentation (5-10 minutes total):

- [ ] **Opening (15-20 sec)**: Hook with problem
- [ ] **Problem (45-60 sec)**: Explain pain point with data
- [ ] **Solution (45-60 sec)**: Describe MVP clearly
- [ ] **Demo (1-2 min)**: Live demo of MVP features
- [ ] **Viability (45-60 sec)**: PROOF that this works (from proposal section 9)
- [ ] **Scalability (1 min)**: Roadmap to growth (from proposal section 10)
- [ ] **Closing (15-20 sec)**: Invite questions
- [ ] **Q&A (1-2 min)**: Answer judge questions
- [ ] Both teammates speak during the presentation

## ✓ Slides (7 slides):

- [ ] Slide 1: Title (with both team member names)
- [ ] Slide 2: Problem (with sources)
- [ ] Slide 3: Solution & Business
- [ ] Slide 4: Demo
- [ ] Slide 5: Viability (matches proposal section 9)
- [ ] Slide 6: Scalability (matches proposal section 10)
- [ ] Slide 7: Questions (with both team contacts)

## ✓ Appendix (1-2 pages):

- [ ] Team contributions (both teammates)
- [ ] Java concepts
- [ ] Challenges & solutions
- [ ] Viability testing section (how you validated in practice)
- [ ] Citations & external resources
- [ ] Reflections & learning

---

## CONSISTENCY CHECK

Before presentation day, verify everything is COHESIVE:

1. **Proposal → Presentation → Slides alignment:**

   - Proposal Problem = Slide 2 Problem = Presentation Problem
   - Proposal MVP Features = Slide 4 Demo = What you show
   - Proposal Viability = Slide 5 Proof = Your evidence
   - Proposal Scalability = Slide 6 Roadmap = Your phases
   - Proposal Sources = Cited in presentation = Referenced in appendix

2. **Viability consistent across all documents:**

   - Proposal Section 9: How you'll test
   - Presentation Slide 5: What you found
   - Appendix Section 6: What you actually did
   - Demo: Proof that it works

3. **Scalability consistent across all documents:**
   - Proposal Section 10: Three-phase plan (Phase 1, 2, 3)
   - Presentation Slide 6: Same phases with timeline
   - Appendix Section 8: Reflection on why this progression needed

---

## YOU'VE GOT THIS!

Remember: Everything must be COHESIVE and CONSISTENT.

What I'm looking for:

1. ✓ Real problem identified with real research (proposal + presentation)
2. ✓ Working MVP that solves it (code demo)
3. ✓ Proof that users want it (viability in proposal + slide 5)
4. ✓ Plan to scale it (scalability in proposal + slide 6)
5. ✓ Clear team execution — both teammates contribute (roles in proposal + appendix)

Make sure your proposal, presentation, and slides tell the same story. No contradictions.

Good luck! 🚀

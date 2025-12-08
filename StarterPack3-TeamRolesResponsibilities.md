# CS122 Final Group Projects: The TEAM ROLES & RESPONSIBILITIES Guide - WORKING LIKE A REAL AGILE TEAM

## What Are Team Roles?

In professional software development, teams work using **Agile methodology**. Instead of everyone doing everything, people have **specialized roles** that play to their strengths. This makes teams more efficient and helps people develop different skills.

**Key principle:** Everyone contributes to the codebase AND everyone presents, but each person has specialized responsibilities and focus areas.

---

## Core Agile Roles (Adapted for Our 2-Week Project)

### 1. **Product Owner / Business Lead**

**Focus:** The business and customer side

**Responsibilities:**

- Defines what the product does (gathers requirements)
- Prioritizes features based on customer value
- Thinks about monetization and market opportunity
- Acts as "voice of the customer"
- Makes decisions about scope (what stays in MVP, what gets cut)
- Writes/owns the proposal document
- Leads the pitch presentation

**Example contributions:**

- "That feature sounds nice, but does it solve the core problem?"
- "Our target customer is a coffee shop owner, so let's design for them"
- "We need to cut the advanced reports feature—too complex for MVP"
- "Let's focus on the alert system first; that's what they'll love"

**Code contributions:**

- May not code the most, but understands the product deeply
- Writes test data/scenarios
- Reviews code for alignment with requirements
- Tests features from user perspective

---

### 2. **Lead Developer / Technical Lead**

**Focus:** The technical architecture and code quality

**Responsibilities:**

- Designs system architecture (which classes, how they interact)
- Makes technical decisions (ArrayList vs HashMap, inheritance design, etc.)
- Codes the most complex or core features
- Does code reviews (checks other team members' code quality)
- Debugs tricky issues
- Ensures code is clean and well-organized
- Leads technical discussions (Java concepts, design patterns)

**Example contributions:**

- "I recommend we use HashMap for product lookup—O(1) performance"
- "Let's make Question an abstract class so we can have different question types"
- "Sarah, can you refactor this method? It's doing too many things"
- "I found a null pointer bug in the stock update method"

**Code contributions:**

- Codes the most challenging features
- Owns the overall architecture
- Writes critical methods

---

### 3. **Tester / Quality Assurance Lead**

**Focus:** Making sure everything works correctly

**Responsibilities:**

- Creates test cases and test scenarios
- Tests features as they're built
- Finds bugs and reports them clearly
- Tests edge cases ("What if stock goes negative?" "What if we add 0 products?")
- Tests the overall workflow end-to-end
- Writes testing documentation
- Validates that demo works perfectly before presentation

**Example contributions:**

- "Found a bug: the app crashes if you update stock for a non-existent product"
- "I tested with empty inventory, 1 product, and 100 products—all work great"
- "The demo should go: add 3 products, sell some, show alert, show report"
- "I created a test checklist so we don't forget anything"

**Code contributions:**

- May write less code overall, but writes test methods
- Creates sample data/test data files
- Suggests code improvements based on bugs found
- Tests other people's code

---

### 4. **Business/Data Analyst**

**Focus:** Understanding the market and requirements deeply

**Responsibilities:**

- Researches the market (how many potential customers, existing competitors)
- Analyzes customer needs deeply
- Documents business requirements clearly
- Thinks about monetization strategies
- Researches existing solutions (what do competitors do?)
- Gathers metrics (market size, pricing benchmarks)
- Contributes to proposal's business sections

**Example contributions:**

- "I found 500,000 small retail shops in the US—that's our market"
- "Competitors charge $200/month; we can undercut them at $25 one-time"
- "Teachers spend 10 hours/week grading—let's emphasize time savings"
- "Here's a spreadsheet comparing our app to 3 competitors"

**Code contributions:**

- May code less overall, but writes data-driven features
- Creates realistic test data based on market research
- Helps with file I/O to import/export business data
- Tests business logic (budget calculations, scores, etc.)

---

### 5. **Researcher / Documentation Lead**

**Focus:** Learning, documenting, and communicating

**Responsibilities:**

- Researches technical topics the team needs to learn
- Creates documentation (README, code comments, how-to guides)
- Writes the appendix
- Keeps team knowledge organized
- Researches edge cases
- Looks up Stack Overflow answers, tutorials
- Ensures code is well-documented

**Example contributions:**

- "I found a great tutorial on file I/O in Java—let me share it"
- "I documented how to run the app in the README"
- "Wrote detailed comments explaining the Comparator logic"
- "Created an appendix explaining our team's process"

**Code contributions:**

- Writes code with excellent documentation/comments
- Implements features that benefit from research
- Does code refactoring to improve clarity

---

## How Roles Work in Practice

### Key Rules:

1. **Everyone codes.** You can't be a Product Owner without understanding the code you built.
2. **Everyone presents.** All team members must be able to explain the project and pitch it.
3. **Roles are about focus, not silos.** Your primary role is where you spend ~40% of time, not 100%.
4. **Multiple roles can be one person.** In a 2-person team, one person might be "Lead Dev + Tester" and the other "Product Owner + Analyst"
5. **Roles can shift.** If the Lead Dev gets stuck, the Analyst might take over that task.

---

## How Roles Show Up in Different Project Phases

### Phase 1: Planning

| Role                 | Responsibility                                         |
| -------------------- | ------------------------------------------------------ |
| **Product Owner**    | Leads proposal writing, defines MVP features           |
| **Lead Developer**   | Sketches architecture, identifies technical challenges |
| **Business Analyst** | Researches market, competitors, pricing                |
| **Tester**           | Creates test plan, defines what "done" means           |
| **Researcher**       | Looks up technologies, best practices, tutorials       |

### Phase 2: Development

| Role                 | Responsibility                                 |
| -------------------- | ---------------------------------------------- |
| **Lead Developer**   | Reviews code, guides architecture decisions    |
| **Developer**        | Implements features following the architecture |
| **Tester**           | Tests each feature as it's built, reports bugs |
| **Business Analyst** | Ensures features match requirements            |
| **Researcher**       | Documents code, creates sample data            |

### Phase 3: Testing & Polish

| Role               | Responsibility                                 |
| ------------------ | ---------------------------------------------- |
| **Tester**         | Intensive testing, edge cases, demo validation |
| **Lead Developer** | Fixes bugs, optimizes code                     |
| **Researcher**     | Finalizes documentation, README                |
| **Product Owner**  | Prepares pitch, gathers demo data              |

### Phase 4: Presentation

| Role                 | Responsibility                             |
| -------------------- | ------------------------------------------ |
| **Product Owner**    | Leads pitch, explains business value       |
| **Lead Developer**   | Explains technical architecture during Q&A |
| **Tester**           | Helps with demo (knows all features well)  |
| **Business Analyst** | Explains market opportunity                |
| **Researcher**       | References documentation if needed         |

---

## How to Assign Roles: A Process

### Step 1: Understand Each Role

Read the descriptions above. Which role matches your strengths?

### Step 2: Take the Role Assessment

Ask yourself for each role:

- Do I enjoy this type of work?
- Am I good at this? (or want to get better?)
- Can I commit to this responsibility?

### Step 3: Discuss as a Team

```
Conversation Example:

Sarah: "I really like architecture and making clean code.
I'd like to be the Lead Developer."

Marcus: "I'm good at talking to people and thinking about
business stuff. I'll be the Product Owner."

Priya: "I like finding bugs and understanding details.
I'll be the Tester. But Marcus, you should test too since
you understand the requirements."

Marcus: "Absolutely. I'll handle test scenarios from a
customer perspective."
```

### Step 4: Document Roles in Your Proposal

Include a section: "Team Roles & Responsibilities"

```
Sarah Chen - Lead Developer
  Architecture design, complex features, code reviews

Marcus Williams - Product Owner
  Feature prioritization, pitch, proposal

Priya Patel - Tester + Business Analyst
  Quality assurance, bug testing, market research
```

---

## Why This Actually Matters

### In School:

- Shows professors you understand professional development
- Demonstrates specialization (and the whole team's strengths)
- Makes team more efficient (less duplicate work)
- Helps with accountability (everyone has clear responsibilities)

### In Real Jobs:

- All real software teams work this way
- Your resume will mention your roles ("I was the Lead Developer on...")
- Understanding roles helps you choose career paths (Dev, QA, Product, etc.)

### For Your Team:

- Clearer expectations (everyone knows what they're responsible for)
- Better collaboration (less stepping on each other's toes)
- Faster progress (specialization = efficiency)
- Skill building (you get deeper in your area)

---

## Role-Based Code Examples

### Lead Developer's Responsibility: Architecture

A Lead Developer would design the class structure first:

```java
// Lead Dev thinks: "We need an inheritance hierarchy for questions"
public abstract class Question {
    protected String questionText;
    protected String correctAnswer;

    public abstract boolean isCorrect(String answer);
}

public class MultipleChoice extends Question {
    private ArrayList<String> options;
    // implementation
}

public class ShortAnswer extends Question {
    // implementation
}
```

### Tester's Responsibility: Test Cases

A Tester would create comprehensive tests:

```java
// Tester creates test scenarios
public class QuizTesting {
    public static void testMultipleChoice() {
        Question q = new MultipleChoice(...);

        // Test correct answer
        assert q.isCorrect("A) Option 1") == true;

        // Test wrong answer
        assert q.isCorrect("B) Option 2") == false;

        // Test edge case: empty answer
        assert q.isCorrect("") == false;
    }
}
```

### Business Analyst's Responsibility: Requirements

A Business Analyst would document feature requirements:

```
Feature: AutoScore Quiz
Requirement: When student submits quiz, system automatically scores it
Business Value: Saves teacher 10 hours/week on manual grading
Acceptance Criteria:
  - Score shows immediately after submission
  - Correct answers are highlighted in green
  - Incorrect answers show the correct answer in red
  - Class average is calculated automatically

Test Scenario:
  - 30 students take the quiz
  - Average score should calculate correctly
```

### Product Owner's Responsibility: Prioritization

A Product Owner would prioritize features:

```
MVP Features (Must Have):
1. Create questions (teachers want control over content)
2. Student takes quiz (core feature)
3. Auto-scoring (saves time—main value)
4. Show results (students want feedback)

Nice-to-Have (if time permits):
5. Student analytics (teachers would love)
6. Question bank search (useful but not critical)

Future Phases (NOT in MVP):
7. AI-generated questions
8. Mobile app
9. Video explanations
```

---

## Role Rotation & Learning

### Suggested Approach:

- **Primary Role:** What you specialize in (70% of your focus)
- **Secondary Role:** Help with this (30% of your focus)
- **Growth Area:** Learn something new by shadowing a teammate

**Example Growth Plan:**

```
Sarah - Lead Developer (primary) + Tester (secondary)
  Growth: Help with business analysis to understand customer perspective

Marcus - Product Owner (primary) + Developer (secondary)
  Growth: Learn testing and quality assurance

Priya - Tester (primary) + Analyst (secondary)
  Growth: Deepen architecture knowledge from Sarah
```

This way, everyone stays well-rounded while specializing.

---

## What to Include in Your Proposal

When you write your proposal, add a section like this:

```
TEAM ROLES & RESPONSIBILITIES

Sarah Chen - Lead Developer
- System architecture and design
- Code reviews and quality
- Complex feature implementation
- Estimated 50% of codebase

Marcus Williams - Product Owner
- Feature prioritization and requirements
- Pitch and presentation leadership
- Customer perspective and feedback
- Estimated 20% of codebase (test data, UI)

Priya Patel - Tester + Business Analyst
- Quality assurance and testing
- Bug detection and reporting
- Market research and competition analysis
- Estimated 30% of codebase (test methods, file I/O)

Everyone will:
- Contribute to the codebase
- Participate in all presentations
- Understand the full project
- Help each other when blocked
```

---

## Common Questions About Roles

### Q: Does the Lead Developer have to code the most?

**A:** Not necessarily. The Lead Dev focuses on architecture, reviews, and complex features. A skilled developer might code more code overall. The point is specialization, not volume.

### Q: What if someone doesn't like their assigned role?

**A:** Switch! You have 2 weeks. If someone hates being Tester, they can swap with another role. The key is to try it first before deciding.

### Q: Do we need a Scrum Master?

**A:** Not for a 2-week project. The Product Owner can facilitate meetings. In real teams, Scrum Masters run the process. For you, it's unnecessary overhead.

### Q: What if we're only 2 people?

**A:** One person takes 2 roles. That's totally normal. Each person should still have a primary focus.

### Q: Does everyone present or just the Product Owner?

**A:** **Everyone presents.** The Product Owner might lead, but the Lead Dev explains architecture during Q&A, the Tester explains testing, etc.

---

## Your Role Checklist

Before you start coding, complete this:

- [ ] I understand what my primary role is
- [ ] I can explain my primary role's responsibilities
- [ ] I know what my team members' roles are
- [ ] I know what percentage of code I'm responsible for (roughly)
- [ ] I understand that I still contribute to the full codebase
- [ ] Everyone on my team has agreed on their role
- [ ] Roles are documented in the proposal
- [ ] Everyone knows they have to present, regardless of role

---

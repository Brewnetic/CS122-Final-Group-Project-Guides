# CS122 Final Group Projects: The TEAM ROLES & RESPONSIBILITIES Guide — WORKING LIKE A REAL AGILE TEAM

## What Are Team Roles?

In professional software development, teams work using **Agile methodology**. Instead of everyone doing everything, people have **specialized roles** that play to their strengths. This makes teams more efficient and helps people develop different skills.

**Key principle:** Everyone contributes to the codebase AND everyone presents, but each person has specialized responsibilities and focus areas.

**For our 2-person teams:** Each teammate will wear **two hats**. There are four roles total, so each person takes on two complementary roles. We'll walk through the roles first, then go over how to pair them up.

---

## The 4 Core Agile Roles (Adapted for Our 2-Week Project)

### 1. **Product Owner / Business Lead**

**Focus:** The business, customer, and market side

**Responsibilities:**

- Defines what the product does (gathers requirements)
- Prioritizes features based on customer value
- Researches the market (potential customers, competitors, pricing)
- Thinks about monetization and market opportunity
- Acts as "voice of the customer"
- Makes decisions about scope (what stays in MVP, what gets cut)
- Writes/owns the proposal document and its business sections
- Leads the pitch presentation

**Example contributions:**

- "That feature sounds nice, but does it solve the core problem?"
- "Our target customer is a coffee shop owner, so let's design for them"
- "I found 500,000 small retail shops in the US — that's our market"
- "Competitors charge $200/month; we can undercut them at $25 one-time"
- "We need to cut the advanced reports feature — too complex for MVP"

**Code contributions:**

- May not code the most, but understands the product deeply
- Writes realistic test data/scenarios based on customer use
- Reviews code for alignment with requirements
- Tests features from a user perspective
- Helps with file I/O for importing/exporting business data

---

### 2. **Lead Developer / Technical Lead**

**Focus:** The technical architecture and code quality

**Responsibilities:**

- Designs system architecture (which classes, how they interact)
- Makes technical decisions (ArrayList vs HashMap, inheritance design, etc.)
- Codes the most complex or core features
- Does code reviews (checks teammate's code quality)
- Debugs tricky issues
- Ensures code is clean and well-organized
- Leads technical discussions (Java concepts, design patterns)

**Example contributions:**

- "I recommend we use HashMap for product lookup — O(1) performance"
- "Let's make Question an abstract class so we can have different question types"
- "Can you refactor this method? It's doing too many things"
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
- Validates that the demo works perfectly before presentation

**Example contributions:**

- "Found a bug: the app crashes if you update stock for a non-existent product"
- "I tested with empty inventory, 1 product, and 100 products — all work great"
- "The demo should go: add 3 products, sell some, show alert, show report"
- "I created a test checklist so we don't forget anything"

**Code contributions:**

- May write less code overall, but writes test methods
- Creates sample data/test data files
- Suggests code improvements based on bugs found
- Tests teammate's code

---

### 4. **Researcher / Documentation Lead**

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

- "I found a great tutorial on file I/O in Java — let me share it"
- "I documented how to run the app in the README"
- "Wrote detailed comments explaining the Comparator logic"
- "Created an appendix explaining our team's process"

**Code contributions:**

- Writes code with excellent documentation/comments
- Implements features that benefit from research
- Does code refactoring to improve clarity

---

## How Roles Work in a 2-Person Team

Since most teams will be pairs, **each person takes on 2 roles**. The trick is choosing complementary pairs so all four areas get coverage.

### Recommended Pairings

**Pairing A — Tech-focused + Communication-focused**

- Person 1: **Lead Developer + Tester** (the technical engine)
- Person 2: **Product Owner + Researcher** (the communicator and documenter)

**Pairing B — User-perspective + Code-perspective**

- Person 1: **Product Owner + Tester** (thinks from the user's view)
- Person 2: **Lead Developer + Researcher** (thinks from the code's view)

**Pairing C — Vision + Execution**

- Person 1: **Product Owner + Lead Developer** (drives vision and architecture)
- Person 2: **Tester + Researcher** (drives quality and documentation)

There's no single "right" combo. Pick whichever pairing best matches your strengths and interests.

### Key Rules

1. **Both teammates code.** Even the Product Owner needs to understand the code they helped build.
2. **Both teammates present.** Both must be able to explain the project and pitch it.
3. **Roles are about focus, not silos.** Your primary role is where you spend the most attention, not 100% of your time.
4. **Roles can shift.** If your teammate gets stuck, you can swap tasks for a bit. Flexibility > rigidity.
5. **Two hats means real ownership of both.** "I'm Product Owner AND Tester" means committing to both — not picking the easy one.

---

## How Roles Show Up in Different Project Phases

### Phase 1: Planning

| Role                | Responsibility                                           |
| ------------------- | -------------------------------------------------------- |
| **Product Owner**   | Leads proposal writing, defines MVP, researches market   |
| **Lead Developer**  | Sketches architecture, identifies technical challenges   |
| **Tester**          | Creates test plan, defines what "done" means             |
| **Researcher**      | Looks up technologies, best practices, tutorials         |

### Phase 2: Development

| Role               | Responsibility                                  |
| ------------------ | ----------------------------------------------- |
| **Lead Developer** | Implements core features, guides architecture   |
| **Product Owner**  | Ensures features match requirements, test data  |
| **Tester**         | Tests each feature as it's built, reports bugs  |
| **Researcher**     | Documents code, creates README, sample data     |

### Phase 3: Testing & Polish

| Role               | Responsibility                                  |
| ------------------ | ----------------------------------------------- |
| **Tester**         | Intensive testing, edge cases, demo validation  |
| **Lead Developer** | Fixes bugs, optimizes code                      |
| **Researcher**     | Finalizes documentation, README                 |
| **Product Owner**  | Prepares pitch, gathers demo data               |

### Phase 4: Presentation

| Role               | Responsibility                              |
| ------------------ | ------------------------------------------- |
| **Product Owner**  | Leads pitch, explains business value & market |
| **Lead Developer** | Explains technical architecture during Q&A  |
| **Tester**         | Helps with demo (knows all features well)   |
| **Researcher**     | References documentation if needed          |

---

## How to Assign Roles: A Process

### Step 1: Read Each Role

Look back at the four role descriptions above. Which two feel like a fit?

### Step 2: Self-Assessment

For each role, ask:

- Do I enjoy this type of work?
- Am I good at this (or do I want to get better)?
- Can I commit to this responsibility for 2 weeks?

### Step 3: Talk to Your Teammate

```
Conversation Example:

Sarah: "I really like architecture and clean code, and I'm
       detail-oriented enough to catch bugs. I'd like to
       be Lead Developer + Tester."

Marcus: "Cool — I'm better at the customer/market side and
        I like writing. I'll take Product Owner + Researcher.
        Sounds like Pairing A."

Sarah: "Works for me. Let's document it in the proposal."
```

### Step 4: Document Roles in the Proposal

Include a section: "Team Roles & Responsibilities"

```
Sarah Chen — Lead Developer + Tester
  Architecture, complex features, code reviews, QA, bug testing

Marcus Williams — Product Owner + Researcher
  Requirements, pitch, market research, README, documentation
```

---

## Why This Actually Matters

### In School

- Shows professors a real understanding of professional development
- Demonstrates specialization (and the team's combined strengths)
- Makes the team more efficient (less duplicate work)
- Helps with accountability (clear responsibilities)

### In Real Jobs

- All real software teams work this way
- A resume can mention specific roles ("I was the Lead Developer on...")
- Understanding roles helps with career direction (Dev, QA, Product, etc.)

### For Your Team

- Clearer expectations (each person knows what they own)
- Better collaboration (less stepping on each other's toes)
- Faster progress (specialization = efficiency)
- Skill building (you go deeper in two specific areas)

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

### Product Owner's Responsibility: Requirements & Prioritization

A Product Owner would document feature requirements and prioritize:

```
Feature: AutoScore Quiz
Requirement: When student submits quiz, system automatically scores it
Business Value: Saves teacher 10 hours/week on manual grading
Acceptance Criteria:
  - Score shows immediately after submission
  - Correct answers are highlighted in green
  - Incorrect answers show the correct answer in red
  - Class average is calculated automatically


MVP Features (Must Have):
1. Create questions (teachers want control over content)
2. Student takes quiz (core feature)
3. Auto-scoring (saves time — main value)
4. Show results (students want feedback)

Nice-to-Have (if time permits):
5. Student analytics
6. Question bank search

Future Phases (NOT in MVP):
7. AI-generated questions
8. Mobile app
```

### Researcher's Responsibility: Documentation

A Researcher would write clear docs and code comments:

```java
/**
 * Sorts products by stock level (ascending).
 *
 * Used by the low-stock alert feature to surface items
 * that need restocking. Comparator pattern chosen because
 * it lets us sort by different criteria without modifying
 * the Product class. See README section "Sorting Strategy"
 * for the full rationale.
 */
public class StockComparator implements Comparator<Product> {
    // implementation
}
```

---

## What to Include in Your Proposal

When the proposal gets written, add a section like this:

```
TEAM ROLES & RESPONSIBILITIES

Sarah Chen — Lead Developer + Tester
- System architecture and design
- Code reviews and quality
- Complex feature implementation
- Test cases, edge cases, demo validation
- Estimated 60% of codebase

Marcus Williams — Product Owner + Researcher
- Feature prioritization and requirements
- Market research and competitor analysis
- Pitch and presentation leadership
- README, code documentation, appendix
- Estimated 40% of codebase (test data, file I/O, documented features)

Both teammates will:
- Contribute to the codebase
- Participate in the presentation
- Understand the full project
- Help each other when blocked
```

---

## Common Questions About Roles

### Q: Does the Lead Developer have to code the most?

**A:** Not necessarily. The Lead Dev focuses on architecture, code review, and complex features. The other person might write more total lines. The point is specialization, not volume.

### Q: What if someone doesn't like one of their roles?

**A:** Swap! There are 2 weeks. If you hate being Tester, you can trade with your teammate or rebalance hats. The key is to try it first before deciding it's not a fit.

### Q: Do we need a Scrum Master?

**A:** No — not for a 2-week project with 2 people. The Product Owner can run the short check-ins. In real teams, Scrum Masters run the process; for this project it's unnecessary overhead.

### Q: What if we're a team of 3?

**A:** One person takes one role, the other two each take one role, OR one person takes two and the other two each take one. Whatever balances the workload best.

### Q: Does only the Product Owner present?

**A:** **Both teammates present.** The Product Owner might lead the pitch, but the Lead Dev should explain architecture during Q&A, the Tester should walk through the demo, and so on. Whoever has each hat covers that part.

---

## Your Role Checklist

Before any code gets written, complete this:

- [ ] I know my **two roles**
- [ ] I can explain the responsibilities of both my roles
- [ ] I know which two roles my teammate is taking
- [ ] All four roles are covered between us
- [ ] I understand I still contribute to the full codebase
- [ ] We've agreed on roles together (no one was assigned without input)
- [ ] Roles are documented in the proposal
- [ ] Both of us know we have to present, regardless of role

---

# CS122-Final-Group-Project-Guides

## Starter Packs

- [CS122 Final Group Projects: The Brainstorm and Example Guide](/StarterPack1-ProjectBrainstorm.md)
- [CS122 Final Group Projects: The Deliverables Guide](/StarterPack2-Deliverables.md)
- [CS122 Final Group Projects: The TEAM ROLES & RESPONSIBILITIES Guide - WORKING LIKE A REAL AGILE TEAM](/StarterPack3-TeamRolesResponsibilities.md)

## USING AI **ETHICALLY**

### Guidelines for Your Project

**You are ALLOWED to use AI tools in your project development.** Professional developers do this every day. However, there's a right way and a wrong way.

### ❌ Academic Dishonesty (DO NOT DO THIS):

- Copying and pasting entire code blocks from AI without understanding them
- Asking AI to write your whole project then just submitting it
- Not being able to explain your own code during the presentation
- Claiming AI-generated code is your own work

### ✅ Legitimate AI Use:

#### 1. **AI as a Java Learning Tool** (MOST COMMON)

Ask AI to help you understand Java concepts you're learning in this course:

**Good Questions to Ask AI:**

- "How do I use an ArrayList to store a list of Patients?"
- "What's the difference between a HashMap and an ArrayList in Java?"
- "Can you explain how a Comparator works for sorting objects?"
- "Why am I getting a NullPointerException on line 23?"
- "What's the best way to structure these classes?"

**Then:** Take the explanation, study it, write YOUR OWN code based on what you learned.

**Example:**

```
YOU: "How do I loop through an ArrayList and find the highest priority patient?"

AI: "You can use a for loop and compare priorities:
for (Patient p : patients) {
    if (p.getPriority() > maxPriority) {
        maxPriority = p.getPriority();
        topPatient = p;
    }
}"

YOU: Study this, understand it, then implement it in your PatientQueue class yourself.
```

#### 2. **AI for Code Comments & Documentation**

- Use AI to help write **javadoc comments** for your classes (then verify they're accurate)
- Ask AI to help explain confusing logic in comments
- Have AI suggest variable names if yours are unclear

**Example:**

```java
// Bad variable names - hard to understand
for (Patient p : patients) {
    if (p.getPriority() > maxP) {
        maxP = p.getPriority();
        top = p;
    }
}

// Good - with AI-helped comments
// Find the patient with the highest priority to be seen next
for (Patient p : patients) {
    if (p.getPriority() > maxP) {
        maxP = p.getPriority();
        top = p;
    }
}
```

#### 3. **AI for Debugging Your Code** ✓

When your code isn't working, it's GREAT to use AI:

- Copy your error message and ask what it means
- Show AI a method that's broken and ask why
- Ask "How do I test this code to make sure it works?"

**Example:**

```
YOU: "I'm getting this error: NullPointerException in my addPatient method.
Here's my code: [paste code]"

AI: "The problem is likely that your ArrayList isn't initialized.
Make sure you do: patients = new ArrayList<>(); in your constructor."

YOU: Fix it yourself, test it, understand why it was broken.
```

#### 4. **Building Real Features with APIs** ⭐ (OPTIONAL BUT COOL)

If you want to go above and beyond and add real data to your app, you can use simple data sources:

**Simple Options (No Complex Coding):**

- **CSV Files**: Store real data (products, teams, patients) in a spreadsheet and read it into your Java program
- **Pre-made Sample Data**: Instead of typing fake data, load it from a file
- **JSON Files**: Simple text files with structured data (easier than API calls)

**Example: Loading data from a CSV file instead of hardcoding it**

```java
// Instead of doing this manually:
inventory.addProduct(new Product("P001", "Apples", 50, 5, 2.99));
inventory.addProduct(new Product("P002", "Oranges", 30, 5, 3.49));

// Read from a CSV file:
Scanner file = new Scanner(new File("products.csv"));
while (file.hasNextLine()) {
    String[] data = file.nextLine().split(",");
    inventory.addProduct(new Product(data[0], data[1], Integer.parseInt(data[2]), 5, Double.parseDouble(data[3])));
}
```

**If Your Team Wants APIs (More Advanced):**

Some free APIs have **simple endpoints** you can call directly from Java:

| API                  | What It Does                                 | How To Use                      | Difficulty |
| -------------------- | -------------------------------------------- | ------------------------------- | ---------- |
| **JSON Placeholder** | Fake data for testing                        | Request JSON, parse it in Java  | Easy       |
| **REST Countries**   | Info about countries (languages, population) | Good for travel/logistics apps  | Easy       |
| **Agify.io**         | Guess someone's age from a name              | Lightweight, simple response    | Easy       |
| **PokeAPI**          | Pokemon data                                 | Great if you're building a game | Medium     |

**Real Talk:** Most intro Java teams should just focus on getting your core features solid. APIs are a nice-to-have, not a must-have.

### How to Talk About AI in Your Presentation:

When someone asks "Did you use AI?":

✅ **GOOD ANSWER:**
"Yeah, we used \_\_\_ to help us understand how ArrayList work for sorting patients by priority. We read through the explanation, studied it, and then wrote our own implementation. We also asked for help debugging a NullPointerException."

❌ **BAD ANSWER:**
"I just had ChatGPT write the whole thing for me."

### What to Include in Your Appendix:

Add an **"AI & Tools Used" section** that's honest and simple:

```
AI & Tools Used:
- Used ChatGPT to learn about ArrayLists with regards to our use case
- Asked ChatGPT to help debug a NullPointerException in our main method
- Used AI to improve our code comments and javadoc
- All code written by team members; AI used as a learning tool only
```

### Bottom Line:

The rule is simple: **You must understand and be able to explain every line of code you submit.**

- ✓ If you can confidently demo your project and answer questions about it → You're good
- ✗ If you can't explain your own code → That's academic dishonesty

Using AI to learn concepts and get unstuck on debugging is perfectly fine and totally normal in real software development. Just don't let AI do the learning for you.

## GENERAL TIPS FOR SUCCESS

### Questions to Ask Your Groups During Proposal Phase:

1. **What real problem does your app solve?**
2. **Who is your customer, and how will you make money?**
3. **What 3 core features will your MVP have?**
4. **How will you divide work among team members?**
5. **Which Java OOP concepts will you showcase?** (inheritance, polymorphism, ArrayList, HashMap, I/O, etc.)
6. **How will you demo this live in 3-5 minutes?**
7. **Will you integrate any APIs or AI features? If so, which ones and why?**
8. **How will you use AI tools responsibly in your development process?**

---

### Code Structuring Tips:

- **Start with one core class first**: Build Inventory before you build ReorderManager
- **Use meaningful variable names**: `patientWaitTime` not `pwt`
- **Keep methods focused**: One method = one responsibility
- **Test incrementally**: Don't code for 3 days then test. Test after each feature
- **Comment your code**: Especially if showing professors—they want to see you understand your own code

---

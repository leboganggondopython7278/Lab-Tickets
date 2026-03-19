# 📓 Developer's Diary — Smart Finance Assistant
**Student:** Lebogang Nyasha Gondo
**Unit:** ISYS2001 — Introduction to Business Programming
**Project:** Budget Buddy — Smart Finance Assistant
**Repository:** leboganggondopython7278/Lab-Tickets
**Due Date:** Friday 22 May 2026 (Week 13)
**AI Tools Used:** ChatGPT (OpenAI) and Google Gemini

---

## 🎯 Project Summary

I am building a Budget Buddy — a Smart Finance Assistant that allows users to upload a CSV file of their expenses, analyse their spending patterns, and receive personalised financial advice through a chatbot interface.

---

## 🗓️ Week 3 — Project Planning & Foundation
**Date:** March 2026
**AI Tools Used:** Google Gemini

**What I did this week:**
- Reviewed the full project specification and assessment rubric
- Decided on Budget Buddy theme
- Set up the Developer's Diary structure
- Identified how each lab ticket connects to the final project

**AI Use this week:**
Used Google Gemini to help understand the project brief, clarify what RAG and Agent Tools mean, and plan the diary structure.
---

## 🗓️ Week 4 — Loops & Multiple Transactions
🗓️ Week 4 — Loops & Multiple Transactions

Date: 17 March 2026
AI Tools Used: ChatGPT (OpenAI) and Google Gemini

Goal:
Add loops to handle multiple expenses in one session.

Artifact:
while True:
    expense_input = input("[CELESTI] Expense amount (or 'done'): $")
    if expense_input.lower() == 'done':
        break
    try:
        amount = float(expense_input)
        expenses.append(amount)
        total_spent += amount
    except ValueError:
        print("CELESTI says: Invalid amount!")

Context:
I was trying to build a loop that collects multiple 
expenses and stops when the user types done.

Reflection:
What worked:
Before this week I froze when I saw code and did not 
know where to start. Breaking the problem into smaller 
pieces helped me understand each part separately before 
putting it all together. I found it helpful to think of 
the loop like a cashier scanning items — they keep going 
until the customer says they are finished.

What did not work:
ChatGPT code sometimes had indentation errors and did 
not run properly the first time. I used Gemini to cross 
check the code which helped me find the mistakes. I 
learned not to rely on one AI tool alone.

What I learned:
While loops keep running when you do not know how many 
times to repeat. For loops are better when you know 
the exact number. Storing expenses in lists instead of 
one variable made it possible to analyse, search and 
summarise all transactions — which connects directly 
to my Budget Buddy project.

GitHub Commit:
Week 4 - Added loop-powered CELESTI Finance Tracker 
with input validation and interactive menu
---

## 🗓️ Week 5 — Data Storage & CSV Files
🗓️ Week 5 — Functions & Modular Design

Date: 19 March 2026
AI Tools Used: ChatGPT (OpenAI) and Google Gemini

Goal:
Learn how to break code into functions and use the 
pyinputplus library for better input validation.

Artifact:
import pyinputplus as pyip

def get_number(prompt):
    return pyip.inputFloat(prompt)

def perform_calculation(operation, num1, num2):
    if operation == "1":
        return add(num1, num2)
    elif operation == "2":
        return subtract(num1, num2)

Context:
I was trying to break a calculator into separate 
functions where each function has one job, and replace 
manual input validation with pyinputplus.

Reflection:
What worked:
I used to freeze when I saw code but this week 
something clicked. Three analogies helped me understand 
functions — the restaurant where each staff member has 
one role, the recipe written once and used many times, 
and the SAP module testing where you test each part 
separately before combining. These real life examples 
made the concepts stick. pyinputplus also impressed me 
because it replaced 7 lines of manual validation with 
just 1 line.

What did not work:
Seeing the full code all at once still caused 
confusion. Working through one blank at a time with 
hints was much more effective than reading complete 
code blocks. I need to continue practising reading 
code incrementally.

What I learned:
Six keywords are the foundation of functions — def 
creates them, return sends answers back, print shows 
output, input collects user input, float converts text 
to numbers, and if/elif checks conditions. Modular 
design means each function has one job which makes 
debugging easier — just like testing SAP modules 
separately before going live.

GitHub Commit:
Week 5 - Added modular calculator with pyinputplus 
for better input validation
---

## 🗓️ Week 8 — AI Integration Begins ⭐ EVIDENCE PACKAGE REQUIRED
**Date:** *(to be completed)*
**AI Tools Used:** Google Gemini

**Goal:** Install and test the hands-on-ai package and confirm the AI chat component is working.

**Artifact:** *(REQUIRED — screenshot or GIF showing AI interaction)*

**Context:** *(REQUIRED — one sentence describing your goal)*

**Reflection:** *(REQUIRED — what worked, what didn't, what you learned)*

**GitHub Commit:** *(REQUIRED — paste your commit message here)*

---

## 🗓️ Week 9 — Chatbot Personality ⭐ EVIDENCE PACKAGE REQUIRED
**Date:** *(to be completed)*
**AI Tools Used:** Google Gemini

**Goal:** Build the finance-oriented chatbot personality using hands-on-ai.

**Artifact:** *(REQUIRED — screenshot or GIF showing AI interaction)*

**Context:** *(REQUIRED — one sentence describing your goal)*

**Reflection:** *(REQUIRED — what worked, what didn't, what you learned)*

**GitHub Commit:** *(REQUIRED — paste your commit message here)*

---

## 🗓️ Week 10 — RAG Component ⭐ EVIDENCE PACKAGE REQUIRED
**Date:** *(to be completed)*
**AI Tools Used:** Google Gemini

**Goal:** Implement RAG so the chatbot reads the user's CSV expense file before answering.

**Artifact:** *(REQUIRED — screenshot or GIF showing AI interaction)*

**Context:** *(REQUIRED — one sentence describing your goal)*

**Reflection:** *(REQUIRED — what worked, what didn't, what you learned)*

**GitHub Commit:** *(REQUIRED — paste your commit message here)*

---

## 🗓️ Week 11 — Agent Tool ⭐ EVIDENCE PACKAGE REQUIRED
**Date:** *(to be completed)*
**AI Tools Used:** Google Gemini

**Goal:** Build and register a custom budget calculator tool the chatbot can call automatically.

**Artifact:** *(REQUIRED — screenshot or GIF showing AI interaction)*

**Context:** *(REQUIRED — one sentence describing your goal)*

**Reflection:** *(REQUIRED — what worked, what didn't, what you learned)*

**GitHub Commit:** *(REQUIRED — paste your commit message here)*

---

## 🗓️ Week 12 — Gradio UI & Full Integration ⭐ EVIDENCE PACKAGE REQUIRED
**Date:** *(to be completed)*
**AI Tools Used:** Google Gemini

**Goal:** Build the Gradio interface and connect Chat, RAG and Agent Tool together into one working app.

**Artifact:** *(REQUIRED — screenshot or GIF showing the Gradio app running)*

**Context:** *(REQUIRED — one sentence describing your goal)*

**Reflection:** *(REQUIRED — what worked, what didn't, what you learned)*

**GitHub Commit:** *(REQUIRED — paste your commit message here)*

---

## 🗓️ Week 13 — Final Testing & Submission
**Date:** Due Friday 22 May 2026

**Final Checklist:**
- [ ] Colab Notebook complete with all 6 steps evidenced
- [ ] Chat component working
- [ ] RAG component working
- [ ] Agent Tool working
- [ ] Gradio UI working and polished
- [ ] Testing Section complete
- [ ] README.md updated
- [ ] Developer's Diary complete for Weeks 8–12
- [ ] GitHub has at least 1 meaningful commit per week Weeks 8–12
- [ ] michaelborck-curtin-grading added as collaborator
- [ ] ZIP file prepared for submission

# Day 3 – Role-Based Prompting

## Objective

Learn how Role-Based Prompting improves AI responses by assigning different expert personas before asking a question.

---

# What is Role-Based Prompting?

Role-Based Prompting is a prompt engineering technique where you instruct an AI to act as a specific expert or persona before giving it a task.

Examples:
- Act as a Senior Software Engineer.
- Act as a Startup Founder.
- Act as a Career Coach.
- Act as a Product Manager.

Instead of giving a generic answer, the AI responds using the knowledge, tone, vocabulary, and thinking style of the assigned role.

---

# Why Role-Based Prompting Matters

Without assigning a role, Claude has to guess the context and level of expertise required. This often results in broad, generic responses.

Assigning a clear role allows Claude to:

- Focus on the appropriate domain expertise.
- Prioritize relevant information.
- Adjust its tone and communication style.
- Produce responses that are more practical and useful.

---

# How Roles Change AI Responses

Different roles influence:

- **Vocabulary** – Technical or beginner-friendly language.
- **Priorities** – Developers focus on implementation, marketers focus on messaging, founders focus on business strategy.
- **Structure** – Strategic overview, step-by-step guidance, or technical explanation.
- **Tone** – Formal, practical, persuasive, or conversational.

This demonstrates that the same question can produce different but equally valuable answers depending on the assigned role.

---

# Benefits of Role-Based Prompting

- Produces more relevant, expert-level responses.
- Matches the response to the intended audience.
- Reduces the need for editing.
- Generates structured and context-aware outputs.

---

# Example Comparison

## Without a Role Prompt

### Prompt

```
How should I price my new app?
```

### Observation

Claude generated a broad answer covering pricing, marketing, and technical considerations but without focusing deeply on any one area.

---

## With a Role Prompt

### Prompt

```
Act as an experienced startup founder who has priced and launched three SaaS products.

Give me a pricing strategy for a new mobile app considering competitor pricing, customer psychology, and long-term revenue growth.
```

### Observation

Claude produced a practical, founder-oriented strategy with recommendations based on pricing psychology, market positioning, customer behavior, and sustainable revenue growth.

---

# Comparison

| Without Role Prompt | With Role Prompt |
|---------------------|------------------|
| Generic answer | Expert-level answer |
| Broad explanation | Focused strategy |
| Covers many topics | Domain-specific insights |
| Less actionable | Practical recommendations |

---

# Image Generation Task

Generated a LinkedIn-style infographic titled:

**Role-Based Prompting – Turn Claude into Any Expert You Need**

The design included:

- Claude-inspired color palette
- Before vs After comparison
- Expert persona cards
- Modern professional layout
- LinkedIn-ready formatting

---

# Key Learnings

- Role-Based Prompting significantly improves AI output quality.
- Assigning a persona changes the AI's reasoning and communication style.
- Better prompts lead to more useful, structured, and context-aware responses.
- The same question can produce different perspectives depending on the assigned role.

---

# My Reflection

Today's exercise taught me that AI becomes much more effective when provided with clear context and a defined role.

As a Computer Science student, I can use Role-Based Prompting to receive specialized guidance from different perspectives, such as:

- Senior Software Engineer for coding advice.
- Startup Founder for product ideas.
- Career Coach for interview preparation.
- Technical Recruiter for resume reviews.

This makes AI a more valuable learning and productivity tool.

---

# Files Included

- day3.md
- no-role-response.png
- founder-role-response.png
- developer-role-response.png
- role-based-prompting-poster.png
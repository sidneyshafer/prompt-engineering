# AI Prompt Engineering
A comprehensive guide to prompt engineering with artificial intelligence

----
## TABLE OF CONTENTS

1. [Introduction to Prompt Engineering](#introduction-to-prompt-engineering)
2. [The Human-AI Collaboration Model](#the-human-ai-collaboration-model)
3. [Core Principles of Effective Prompts](#core-principles-of-effective-prompts)
4. [Prompt Engineering Template](#prompt-engineering-template)
5. [Understanding Role, Context, Task, Audience & Tone](#understanding-role-context-task-audience--tone)
6. [Structuring High-Quality Prompts](#structuring-high-quality-prompts)

----
## INTRODUCTION TO PROMPT ENGINEERING
### What Is Prompt Engineering?

Prompt engineering is the practice of designing clear and structured instructions that guide an AI model to produce accurate, reliable, and meaningful results.

AI models are powerful, but they require direction.
Prompt engineering provides that direction—much like giving a teammate clear requirements instead of vague guidance.

### Why Prompt Engineering Matters

Great prompts lead to:

* More accurate results
* Faster workflows
* Cleaner, more professional outputs
* Less rework
* More consistent responses
* Better alignment with business goals

### Who These Resources Are For

This guide applies to all roles and industries, including:

* Students
* Designers
* Developers
* Analysts
* Researchers
* Managers
* Writers
* Operations professionals
* **Anyone using AI to work faster and smarter**

----
## THE HUMAN-AI COLLABORATION MODEL
Think of AI not as a magic box, but as:

* A research assistant
* A junior analyst
* A writing partner
* A brainstorming collaborator
* A translator
* A content generator

AI works best when the human provides:
* Clear instructions
* Relevant context
* Examples
* Expectations
* Constraints

You are **not delegating** the entire task to AI.
You are **collaborating** with it.

----
## CORE PRINCIPLES OF EFFECTIVE PROMPTS

### 1. Clarity

Clear instructions = predictable results.
Avoid vague language like **“make this better”** or **“explain this.”**

### 2. Context

AI lacks situational awareness.
It needs:

* Background information
* Objectives
* Requirements
* Constraints
* Existing data, if relevant

### 3. Role Assignment

Defining a role improves accuracy:

* “Act as a research analyst”
* “Act as a UX writer”
* “Act as an expert editor”
* “Act as a technical instructor”

### 4. Specific Tasks

Tell the model exactly what to do.
Use strong action verbs:

* Generate
* Summarize
* Rewrite
* Analyze
* Explain
* Compare
* Improve

### 5. Structured Output

AI performs best with explicit formatting instructions:

* Bullet points
* Headings
* Tables
* Paragraph format
* Step-by-step
* JSON

### 6. Constraints

Guide the output with:

* Length limits
* Style rules
* Do/Don’t lists
* Tone guidelines

----
## PROMPT ENGINEERING TEMPLATE
***Universal template for any AI task***

### Our Goal:
I need your help to *(clearly state objective)*.

### Your Role:
You are an expert in *(field/expertise)*.
Act as *(role/persona)* to complete this task.

### Context:
Here is all relevant background information:

* ----------------------------------------- 
* ----------------------------------------- 
* ----------------------------------------- 

### Audience:
This content is intended for *(who)* with *(experience level)*.

### Tone:
Use a tone that is *(list 2–3 adjectives)*.

### Your Action:
Please **(generate/write/summarize/analyze/rewrite/etc)** *(specific deliverable)*.

### Format:
Respond using the following structure:

1. -----------------------------------------
2. -----------------------------------------
3. -----------------------------------------

### Constraints:

* Length requirement: ___
* Styling rules: ___
* Avoid: ___

### Example:
Here is an example to follow: **[provide your example]**

### Do:

* ----------------------------------------- 
* -----------------------------------------

### Don’t:

* ----------------------------------------- 
* -----------------------------------------

----
## UNDERSTANDING ROLE, CONTEXT, TASK, AUDIENCE & TONE

These five components create the backbone of all effective prompts.

### 1. Role
Roles help shape the expertise the AI uses when responding.

Examples:

* “Act as a legal researcher.”
* “Act as a marketing copywriter.”
* “Act as a data analyst.”
* “Act as a coach.”

### 2. Context
Context allows the model to understand:

* what you are working on
* why you need it
* what has already been done
* any constraints
* any missing information

More context = better output.

### 3. Task
The task is the **action** you need completed.

Weak:

> Help me with this email.

Strong:

> Rewrite the following email to be more concise, professional, and clear. Keep the same meaning.

### 4. Audience
Specifying the audience shapes:

* tone
* level of detail
* technical complexity
* structure

Examples:

* “Write for beginners.”
* “Write for senior executives.”
* “Write for technical users.”

### 5. Tone
Tone controls the *voice*.

Examples:

* Professional and concise
* Friendly and upbeat
* Technical and precise
* Simple and easy to understand

----
## STRUCTURING HIGH-QUALITY PROMPTS
The 5-Layer Prompt Structure

1. Role
2. Context
3. Task
4. Formatting Instructions
5. Constraints

Example of a Well-Structured Prompt

> You are a professional editor.
> 
> I am writing an executive summary about a workplace improvement project. The audience is senior leadership with limited time.
>
> Please rewrite the following text to be more concise, business-focused, and polished, while keeping the original meaning.
>
> Respond in 3 sections:
> 1. Improved version
> 2. Bullet point key messages
> 3. Suggested title
>
> Keep the tone formal, confident, and clear.
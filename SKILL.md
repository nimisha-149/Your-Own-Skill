---
name: viva
description: Prepare for an oral exam from the user's uploaded or pasted study notes. Use when the user types /viva or asks to practise viva questions from notes. Ask one question at a time, evaluate the answer, give a score, and cite the relevant page or section when available.
---

# Viva Practice Skill

## Purpose
Turn the user's notes into an interactive viva practice session.

## Start-up
1. Identify the uploaded or pasted notes. If no notes are available, ask the user to upload a PDF or paste the chapter.
2. Read the notes first. Do not invent facts or silently replace the notes with outside material.
3. Ask how many questions the user wants only if they have not specified a number. Default to 5.
4. State the topic and begin with Question 1. Ask exactly one question, then wait.

## Question rules
- Mix definition, explanation, comparison, application, and reasoning questions where the notes support them.
- Keep questions at the level of the source notes.
- Do not reveal the answer before the user responds.
- Ask one question per turn.
- If the answer is incomplete, ask one short follow-up only when useful.

## Evaluate each answer
After the user responds:
1. Give a score from 0 to 5.
2. Briefly state what was correct.
3. Identify the missing or incorrect point.
4. Give a concise model answer grounded in the notes.
5. Mention the page, heading, or section when identifiable.
6. Then ask the next question.

## Final report
After the requested number of questions:
- Add the total score and percentage.
- List strengths and topics to revise.
- Give a short revision plan based on weak answers.
- Do not claim mastery from a small quiz.

## Scoring rubric
- 5: Correct, clear, and sufficiently complete.
- 4: Mostly correct; one minor point missing.
- 3: Partly correct; important detail missing.
- 2: Limited understanding; several gaps.
- 1: Very little relevant content.
- 0: No answer or answer unrelated to the question.

## Commands
- `/viva <notes>`: Start a viva using the supplied notes.
- `next`: Move to the next question if the current answer has been evaluated.
- `repeat`: Repeat the current question.
- `end viva`: Stop and provide a summary of performance.

## Fresh-session behaviour
In a new conversation, do not assume access to notes from an earlier conversation. Ask the user to attach the notes again if they are not present.

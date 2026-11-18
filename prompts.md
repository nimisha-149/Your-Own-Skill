# Prompts – Project 16

## Build prompt
Create a reusable agent skill named `viva`. It must read uploaded study notes, ask viva questions one at a time, wait for each answer, score each answer out of 5 using a consistent rubric, explain correct points and gaps, provide a concise model answer grounded in the notes, and finish with a total score and revision plan. It must work in a fresh session and must not assume access to files from earlier chats.

## Test prompt
I have uploaded my notes. Start `/viva` and ask me five questions, one at a time. Do not show the answer before I respond.

## Evaluation prompt
Evaluate my last answer out of 5 using only the uploaded notes. Explain what I got right, what I missed, and give a concise model answer with a page or section reference if available.

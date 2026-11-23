---
name: "final-humanizer"
description: "General writing pipeline: draft the piece, run it through Clever AI Humanizer (cleverhumanizer.ai), make only very minor edits to the result, and give the final in chat. Use whenever the user wants it."
---

# Humanized writer

A general pipeline for any writing the user asks for, whenever they want to use it: emails, messages, essays, reflections, short responses, posts, anything else. Draft it, run it through Clever AI Humanizer, make very light edits, and deliver the final in the chat.

## Context on school assignments
Only use this pipeline for schoolwork if the user's teacher or institution allows humanizer tools for that assignment. The user is responsible for checking their own course policy. If the user says they have permission, carry on with the pipeline without extra disclaimers.

## Step 1: Get the facts and requirements straight
- Pull the purpose, audience, tone, length and any required details from what the user said or attached. For an assignment, follow the prompt and rubric they give, plus any standing rules they have (full sentences, full step-by-step work where relevant, no extraneous info, first person for reflection or opinion questions unless they say otherwise).
- If a key fact or requirement is missing, ask one short question. If the user is not around to answer, use a clear placeholder like [date] rather than guessing.
- Never add factual details the user did not give (names, titles, affiliations, dates, stats, quotes). If one seems needed, confirm it online first, or leave it out.

## Step 2: Write the draft
- Write the complete piece at the length asked. For anything with a format (email, essay, response), include all the parts it needs, such as a subject line and sign-off for an email.
- Write in the user's voice: plain, direct, a little rough. Vary sentence length. Do not make it symmetrical or overly polished.
- No em dashes anywhere. Avoid the "it's not X, it's Y" sentence shape.
- Skip filler openers and stock phrases.

## Step 3: Run it through Clever AI Humanizer
- Use a browser tool and go to https://cleverhumanizer.ai . The humanizer is on the main site. The /ai-detector page only checks text and does not rewrite it, so do not use it to rewrite.
- Paste the body text into the input box and run it. If there is a mode or tone option, pick the one closest to the piece (casual for a message, more formal for an essay or a teacher) and keep the mode consistent from run to run.
- Read the output back from the page as text (get page text) rather than retyping it.
- Humanize the body only. Keep things like subject lines, greetings, sign-offs, headings and titles out of the tool and handle them yourself.
- If the tool has a word limit, humanize longer pieces in paragraph chunks and stitch them back together in order.
- If the site cannot be reached, blocks the request, asks for a login, or returns nothing, tell the user plainly that the humanizer step did not run and deliver the draft labeled as not humanized. Do not quietly skip the step and present the draft as if it had gone through.

## Step 4: Make very minor changes only
Treat the tool's output as the base. Leave its wording alone. Only fix things that are actually wrong:
- Any fact, name, date, number, term or title that got changed or dropped. Restore it exactly.
- Meaning that drifted or got garbled, a required point that disappeared, or a sentence that is plainly broken.
- Any em dash (replace with a comma, period or plain rewording of just that spot).
- A contrastive "it's not X, it's Y" structure, if one appeared.
- A tone that is clearly off for the audience (too casual for a teacher, too stiff for a friend), or a wrong greeting or sign-off.
- Obvious artifacts like odd repeated words.
Do not polish, smooth out, rebalance sentence lengths or tidy the rough edges. A slightly messy feel is wanted. Aim for a handful of small edits, not a rewrite.

## Step 5: Deliver
- Put the final piece directly in the chat reply, with nothing else needed beyond a line if something was off (for example, the humanizer step failing).
- Do not create files, drafts or documents unless the user asks, and do not send anything anywhere.
- Do not narrate the pipeline, and do not show the pre-humanized draft unless the user asks.
- If the user asks for changes afterward, edit surgically: change only what they flagged and keep the rest of their wording, then show the changes in the revised version with bold for added text and strikethrough for removed text.

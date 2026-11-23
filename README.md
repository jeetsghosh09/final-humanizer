# final-humanizer

A Claude skill that writes a piece for you, runs it through [Clever AI Humanizer](https://cleverhumanizer.ai), makes only very light fixes to the result, and hands back the final text in chat.

## What it does

1. Gets the facts and requirements straight, and asks one short question if something key is missing.
2. Drafts the piece in a plain, slightly rough voice.
3. Pastes the body into Clever AI Humanizer using a browser tool and reads the output back.
4. Fixes only real problems (changed facts, broken sentences, em dashes, wrong tone). It leaves the tool's wording alone.
5. Delivers the final text in the chat.

## Install

Copy the `SKILL.md` file into a folder named `final-humanizer` inside your Claude skills directory, or upload the folder as a skill in your Claude settings. You need a browser tool enabled so Claude can reach cleverhumanizer.ai.

## A note on school use

Check your teacher's or school's policy before using any humanizer on coursework. Use it only where it is allowed.

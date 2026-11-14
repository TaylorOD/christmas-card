# Christmas Card

## Why?

I wanted to build a virtual christmas card but man does doing any type of artistic coding really hurt.

## How?

This was generated, in large part, by ChatGPT 4. A full transcript of the prompts used are here: "Just kidding. Currently ChatGPT doesn't support sharing chats that include images..."

ChatGPT did the boiler plate and complicated work. I did the finicky and tricky precision work.

## What tech?

This is build in P5.js, html, and JavaScript.

## Years

Each year's card lives in `cards/<year>.html`. The root `index.html` shows a year picker and loads the selected card (link straight to one with `#2023`, `#2026`, etc.).

- **2023** – Christmas tree, snowman and a pile of presents.
- **2026** – Snowy night at a log cabin with northern lights, a waving snowman and twinkling string lights. Click the card for a burst of snow.

To add a new year: create `cards/<year>.html` and add the year to the `YEARS` list at the top of the script in `index.html`.

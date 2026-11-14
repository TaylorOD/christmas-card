# Christmas Card

## Why?

I wanted to build a virtual christmas card but man does doing any type of artistic coding really hurt.

## How?

This was generated, in large part, by ChatGPT 4. A full transcript of the prompts used are here: "Just kidding. Currently ChatGPT doesn't support sharing chats that include images..."

ChatGPT did the boiler plate and complicated work. I did the finicky and tricky precision work.

## What tech?

This is build in P5.js, html, and JavaScript.

## Years

Every year, the best AI model available makes the card. Each year's card lives in `cards/<year>.html`, and the root `index.html` shows a year picker with a credit line under each card (link straight to one with `#2023`, `#2026`, etc.).

- **2023**: Christmas tree, snowman and a pile of presents. Made using the best model available in 2023 (ChatGPT, GPT-4), with fine-tuning by Taylor.
- **2024**: A cozy fireplace with stockings, a snowy window, a tree and a sleeping cat. Click the fire for sparks. Made using the best model available in 2024.
- **2025**: A snow globe with a lit-up village and ice skaters. Click to shake it and stir up snow and glitter. Made using the best model available in 2025.
- **2026**: "Paper Lanterns", a layered paper-cut winter night: mountains, a village, a forest and a fox trotting through the snow. Move the mouse (or tilt your phone) to look around in depth, and click to send paper lanterns up into the sky. Made using the best model available in 2026.

To add a new year: create `cards/<year>.html` and add an entry (year and credit) to the `CARDS` list at the top of the script in `index.html`.

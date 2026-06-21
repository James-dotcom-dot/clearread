# ClearRead — Text Simplifier for Accessible Learning

A small front-end prototype that rewrites dense, complex text into short, plain-English sentences — built with students who have dyslexia or ADHD in mind, where long, multi-clause sentences increase reading load even when the underlying ideas are understandable.

**[Try it live](https://YOUR-USERNAME.github.io/clearread/)** *(replace with your actual GitHub Pages link once deployed)*

## What it does

- Paste in any dense paragraph (textbook language, articles, etc.)
- Click "Simplify this text"
- Get back the same meaning, broken into short, easy-to-read sentences
- See a before/after average words-per-sentence comparison

## How it works

This is a working prototype, not a finished product. The current version uses a **rule-based simplifier**: it splits long sentences on natural break points (commas, conjunctions like "which," "while," "leading to") to produce shorter, plainer sentences. This means it runs instantly in the browser with no API key, no backend, and no cost.

The natural next step for a production version would be connecting this same interface to an AI model (e.g. Claude or GPT) for true semantic simplification — rewording vocabulary, not just shortening sentence structure. The UI and concept are already built to support that swap.

## Why I built this

I wanted to explore how AI-style tools could directly support more accessible learning, rather than just reading about EdTech in the abstract. This also let me practice plain front-end work (HTML/CSS/JS, no frameworks) and think through UX for a real accessibility use case.

## Tech

- Plain HTML, CSS, and JavaScript — no frameworks, no build step
- Hosted free via GitHub Pages

## Author

James Wamai Maranga

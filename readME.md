# OleKoder Portfolio - HTML & CSS Only

A personal portfolio built using **pure HTML and CSS.**

The goal of this project was not to demonstate modern frameworks or complex tooling, but instead to explore **how far clean semantic HTML and well-structured CSS can go on their own.**

This project intentionally avoids JavaScript and frameworks to highlight the **power, flexibility and expressiveness of modern HTML and CSS.**

## Project Philosophy

As a developer, I normally work with a modern stack like React.js, Next,js and sometimes TypeScript, and many of my other projects reflect that.

For this project I wanted something different:

I set a constraint for myself:

Build a fully functional portfolio using only HTML and CSS.

This meant solving several common UI problems without JavaScript, including:

- Modal dialogs
- Interactive project previews
- Layout responsiveness
- Navigation and UI structure

Everything you see in this project is handled using **native browser capabilities and CSS techniques.**

## Why This Project Exist

There were a few main reasons behind creating this:

1. Show the power of HTML & CSS
   Modern web development often jumps straight to frameworks. While those tools are incredibly useful, they can also hide how powerful the platform itself already is.

This project demonstrates that:

- Semantic HTML can structure complex layouts
- CSS alone can handle responsive design and interaction
- Native browser features can replace a surprising amount of JavaScript

2. A personal technical challange
   Constraining the technology stack forces creative solutions.

Examples in this project include:

- Using `:target` abd anchors to create modal dialogs
- Handeling responsive layouts purely with Flexbox
- Structuring components in a reusable visual pattern without JS

3. A different type of portfolio piece
   Most of my work demonstates **modern application architecture** using frameworks and TypeScript.

This project instead highlights:

- Strong **HTML semantics**
- Clean **CSS architecture**
- Understanding of **core web dundamentals**

It serves as a contrast to my larger application projects.

## Important Note on Architecture

You may notice and the HTML is **not very DRY** and contains some repeated structures.

This is intentional.

Because the project avoids JavaScript, templating systems, and frameworks, components such as project cards and dialogs are written directly in HTML.

In a production application I would normally solve this with:

- Component systems
- Framework
- CMS rendering

However, the goal here was **not architectural abstraction,** but rather a **pure HTML/CSS implementation.**

## Features

- HTML & CSS only implementation
- Responive layout
- Project cards with preview images
- Modal dialogs implemented using `:target`
- Experience timeline
- Tech stack overview
- Document section with downloadable files
- Minimal, clean visual design

## Tech Stack

This project intentionally uses a minimal stack.
**Core technologies**

- HTML5
- CSS3
- Flexbox
- CSS Variables

**Other**

- Google Fonts (Instrument Sans)
  No Javascript, frameworks, or build tools were used.

## Project Structure

```
/portfolio
│
├── index.html
├── index.css
│
├── images/
│   └── project-previews/
│
└── documents/
    ├── cv.pdf
    ├── cover-letter.pdf
    └── project-reflections.pdf
```

## What This Project Demonstrates

This project highlights several skills:

- Semantic HTML structure
- Accessibility considerations
- Responsive layout desing
- CSS architecture and organization
- Creative problem solving without JavaScript
- Understanding the browser platform itself

## Live Demo

You can view the live version here:
https://olekoders-blogg.vercel.app/

## About Me

I'm a frontend developer based in **Bergen, Norway**, currently studying at **Noroff** while continuing to expand my skillset.

My typical tech stack includes:

- React.js
- Next.js
- TypeScript
- Tailwind
- CMS integrations
- Accessibility-focused development

This project is a small but interesting addition to my portfolio that focuses purely on **web fundamentals.**

If you'd like feedback, collaboration, or just want to talk about web development, feel free to reach out.

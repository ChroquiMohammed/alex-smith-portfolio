# Alex Smith - Portfolio

A small practice project built with HTML & CSS.

## About

A portfolio page for Alex Smith, with a fixed sidebar on the left (profile photo, social links and navigation), a hero section with a background image, and an About section with a photo and personal information.

On mobile, the sidebar hides off-screen and slides in with a hamburger button — built with a hidden checkbox, no JavaScript. The button switches between a list icon and a close (X) icon.

## What I built in this project

- Fixed sidebar with a round profile photo, social icons and navigation links
- Hero section with a background image, name and title
- About section with a photo, description and personal information (birthday, website, phone, city, age, degree, email, freelance)
- Responsive layout: the sidebar becomes a slide-in menu on mobile
- Open/close menu with one checkbox and two icons that swap

## What I learned

- How to build a menu without JavaScript, with a hidden checkbox and a label
- The difference between `+` (the next sibling) and `~` (any sibling after) — the checkbox controls the header with `+` and the icons inside `main` with `~`
- A label works by `id`, not by position — it can sit anywhere in the page and still toggle its checkbox
- `position: fixed` stays on the screen when you scroll, `position: absolute` moves with the page — a sidebar menu needs `fixed`
- Media queries: hiding the sidebar off-screen with `left: -100%` and sliding it in with `left: 0` and a transition
- One checkbox can control two icons: show one, hide the other, and swap them with `:checked`

## Tech

- HTML
- CSS (Flexbox, media queries)
- Bootstrap Icons (SVG)

## How to open

Open `index.html` in your browser, or use Live Server in VS Code.

# bobapoptamuproj
Project by Allan Kaung, Ava Sonnier, Adi Pangal, Rachel Muyshondt, Sarim Azad

# Boba Pop: Customer Ordering Kiosk

A self-service ordering kiosk for a boba tea shop, built with React, TypeScript, and an AI ordering assistant.

### [Try the live app](https://boba-pop-pos-service.onrender.com/customer)

> Hosted on Render's free tier, so the first load can take up to a minute while the server wakes up.

> **About the source code:** This was built as a team project for CSCE 331 (Software Engineering) at Texas A&M. The source code lives in a private team repository, so this repo is a showcase only. 

---

## Features

**Ordering experience**
- Browse the full drink menu and customize each drink (ice level, sweetness, toppings)
- Cart with live totals and a simple checkout flow
- Automatically resets after a period of inactivity so the next customer starts fresh

**Reveille, the AI ordering assistant**
- Chat with an assistant powered by Google Gemini to get drink recommendations or place an order
- Uses function calling, so the assistant can add customized drinks straight to your cart
- Push-to-talk voice input for hands-free ordering

**Translation**
- Translate the menu into other languages using the DeepL API

**Accessibility**
- Adjustable text size and a high-contrast mode
- Uses Atkinson Hyperlegible, a font designed by the Braille Institute for readability

---

## Tech Stack

| Layer | Tools |
| --- | --- |
| Frontend | React 19, TypeScript, Vite, React Router |
| Backend | Node.js, Express 5, TypeScript, Zod |
| Database | PostgreSQL |
| AI and APIs | Google Gemini, DeepL |
| Hosting | Render |

---

## Team

Built by Team 74 for CSCE 331, Fall 2026, Texas A&M University.

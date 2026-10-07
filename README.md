# Mini Projects Showcase

A collection of my mini projects, code experiments, and short-term challenges, from browser tools and games to UX/UI design and game modding.

## Overview

| # | Project | Tech Stack / Role | Links |
|---|---------|-------------------|-------|
| 01 | [Felt & Odds](#01--felt--odds-poker-odds-calculator) | `HTML` `CSS` `JavaScript` | [Repo](https://github.com/NIHKOOL/Felt-Odds---Poker-Odds-Calculator) · [Live](https://felt-odds-poker-odds-calculator.vercel.app) |
| 02 | [NICE KNIGHT](#02--nice-knight) | `Python` `Pygame` | [Repo](https://github.com/NIHKOOL/NICE-KNIGHT) |
| 03 | [CU Ways](#03--cu-ways) | `UX/UI` `Frontend` | [Figma](https://www.figma.com/design/XMwuViKKwBvZFBqsVP6PAx/SE-UX-UI?node-id=0-1&t=x46Aa66Mgw2GTlK9-1) · [Repo](https://github.com/Champy2005/cu-ways-frontend) |
| 04 | [SekiCraft](#04--sekicraft) | `Java` `C++` `Fabric` | [Repo](https://github.com/NIHKOOL/SekiCraft) |

---

## 01 · Felt & Odds: Poker Odds Calculator

A fast, zero-dependency **Texas Hold'em equity calculator** for 2–9 players. Pick known hole and board cards to get win/tie/equity percentages, hand-type probabilities, and a heat map of how likely each remaining card is to land on the board. It uses exact enumeration when the outcome space is small and falls back to Monte Carlo simulation otherwise, all in a single self-contained HTML file.

**Stack:** HTML, CSS, vanilla JavaScript · deployed on Vercel
**Links:** [Repository](https://github.com/NIHKOOL/Felt-Odds---Poker-Odds-Calculator) · [Live demo](https://felt-odds-poker-odds-calculator.vercel.app)

## 02 · NICE KNIGHT

> *"NICE KNIGHT FIGHT MIGHT LIKE MIKE"*

My first game in Python: a small 2D action game. Play as a knight who walks, jumps, and **blinks** (a short-cooldown dash) to slay goblins for points. When the 45-second timer runs out, a dragon charges across the screen, so score as much as you can before it reaches you.

**Stack:** Python, Pygame
**Links:** [Repository](https://github.com/NIHKOOL/NICE-KNIGHT)

## 03 · CU Ways

A web platform that connects **creators** with **marketers**. Marketers publish profiles and services, creators search for them by price, expertise, campus and rating, and each role gets its own dashboard. I worked on the **UX/UI design** in Figma and the **frontend**.

**Stack:** Figma · Next.js (App Router), TypeScript, Tailwind CSS, shadcn/ui
**Links:** [UX/UI design (Figma)](https://www.figma.com/design/XMwuViKKwBvZFBqsVP6PAx/SE-UX-UI?node-id=0-1&t=x46Aa66Mgw2GTlK9-1) · [Frontend repository](https://github.com/Champy2005/cu-ways-frontend)

## 04 · SekiCraft

Play **Sekiro: Shadows Die Twice as a Minecraft player**. You walk around Ashina with Minecraft's movement and physics, HUD and inventory, place and break blocks on Sekiro's terrain, and fight Sekiro's enemies with Minecraft weapons. Both games run at the same time and talk through shared memory, using a C++ DLL inside Sekiro and a Fabric mod inside Minecraft. *(Experimental fan project.)*

**Stack:** Java (Fabric mod), C++ (DLL), CMake
**Links:** [Repository](https://github.com/NIHKOOL/SekiCraft)

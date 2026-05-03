# ContextHub

ContextHub is a visual workspace for AI-assisted app building with IBM Bob.

Instead of repeatedly prompting and regenerating code, ContextHub helps teams see what the AI understood, adjust it visually, and sync those changes back into the codebase clearly.

## Problem

Building with AI still feels like a guessing game.

You type a prompt, get code back, and if the result is slightly wrong, you often have to start over.
There is very little visibility into:
- what the AI understood
- why it made certain design decisions
- where the changes actually happened in the code

## Solution

ContextHub makes AI development more visual, transparent, and controllable.

It gives users a shared interface where they can:
- provide visual references
- inspect Bob’s reasoning
- edit Bob’s interpretation directly
- make visual changes without touching raw code
- sync those changes back into the repository

## How we used IBM Bob

We used IBM Bob in two ways:

1. **To help build ContextHub**
   - generate and structure parts of the interface
   - support component-level development
   - assist with styling and implementation

2. **As the core intelligence inside ContextHub**
   - analyze user references
   - choose a suitable layout direction
   - explain its reasoning
   - accept prompt or interpretation edits
   - update the underlying code based on visual changes

## Core features

### 1. AI Logic
Bob analyzes reference inputs, explores variations, selects a layout direction, and explains why it chose that path.

### 2. Assets
Users can visually update images, text, and other content without manually editing files.

### 3. Prompts
Users can directly edit Bob’s interpretation so the system aligns better with their intent instead of restarting from scratch.

### 4. Sync Code
When users click the update button, ContextHub pushes those visual decisions into the actual codebase and clearly shows where changes happened.

## Demo flow

Our demo highlights three main features:
- AI Logic
- Assets
- Prompts

Then we show the update flow, where clicking the update button directly changes Bob’s output in code and makes the edited areas visible.

## Why this matters

ContextHub turns AI from a black-box code generator into a visual engineering partner.

It helps teams move faster while still understanding:
- what changed
- why it changed
- where it changed

## Scope

Because of the hackathon time limit, we focused on the three most important features first.

This is just the starting point.
The same system can grow into a much more powerful visual interface for repo-aware code editing, multi-file orchestration, and better human-AI collaboration.

## Tech direction

Current focus:
- visual editing layer
- prompt interpretation layer
- reasoning visibility
- code sync workflow

Possible next steps:
- deeper repo awareness
- multi-page support
- version history and rollback
- component-level diff views
- stronger agent orchestration
- collaborative editing flows

## Team note

This README is intentionally simple and internal-facing for our team.
It is meant to help us present the idea clearly, explain the demo fast, and keep the repo understandable.

## Status

Hackathon prototype / starting point

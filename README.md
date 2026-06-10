# GRANTED

**Take as true. Proceed.**

GRANTED is a compact text-card app that gives the user one premise and asks them to reason forward from it.

It does not prove the premise.
It does not explain the premise.
It does not debate the premise.
It grants it temporarily and makes the next move visible.

One button. One premise. One short act of suspended doubt.

## What it does

GRANTED randomly serves one card from a fixed deck of **999 premise cards**.

Each card is written as a sentence the user must temporarily accept as true. The point is not certainty. The point is motion.

The app is useful when a person is stuck in hesitation, over-analysis, circular doubt, abstract planning, or repeated self-explanation.

A typical card does not say:

> Think about whether this is true.

It says:

> This is granted for now. What follows?

## Concept

GRANTED belongs to the SPARK TOOLS family of small browser-based text instruments.

Its specific role is to suspend argument for one minute.

Where other tools ask questions, produce bad advice, expose bad evidence, or steelman the opposing case, GRANTED does something simpler and stranger:

**It gives the premise permission to act.**

The user does not need to agree with the card forever. They only need to follow it far enough to see what it reveals.

## Tone

The tone should remain:

* direct
* clear
* intelligent
* practical
* slightly severe
* never cute
* never therapeutic
* never merely motivational

The best GRANTED card feels like a temporary law, not advice.

It should create movement, not comfort.

## Interface

GRANTED is a single-page HTML app.

Main interface elements:

* app title
* short subtitle
* status line
* primary action button
* dynamic icon inside the text card
* generated text card
* Copy button
* Clear button
* About panel

The dynamic icon reacts when a new premise is generated.

The visible deck counter appears only in the About section.

## Technical structure

GRANTED is built as a self-contained HTML file.

It uses:

* HTML
* CSS
* vanilla JavaScript
* embedded card database
* embedded SVG favicon
* Google Fonts:

  * Saira Stencil One
  * IBM Plex Mono

No build process is required.

No backend is required.

No user account is required.

No data is saved.

No tracking is included.

## Card database

The card deck is stored directly in the JavaScript as a `CARDS` array.

Current deck size:

**999 cards**

The app randomly selects one card per button press and keeps a short recent-history buffer to reduce immediate repetition.

## Buttons

### TAKE AS TRUE

Generates a new granted premise.

### COPY

Copies the current card text and app tag.

### CLEAR

Resets the output card to its starting state.

### ABOUT

Opens the About panel with the app description, deck count, privacy statement, and copyright line.

## Privacy

GRANTED runs locally in the browser.

It does not collect, transmit, save, or analyse user input.

There is no login, no analytics layer, no account system, and no remote database.

## Development notes

When editing GRANTED, preserve the familiar SPARK TOOLS structure unless a redesign is intentional.

Keep:

* single-file format
* mobile-first layout
* embedded JavaScript card deck
* counter only in About
* Copy / Clear / About behaviour
* compact card output
* dynamic icon reacting to generation
* no tracking and no storage

Avoid:

* adding explanations to the cards
* turning cards into generic advice
* adding “Granted:” before every visible card
* adding visible card numbers like G-164
* making the tone motivational
* making the premise too long
* weakening the premise-forcing mechanism
* adding unnecessary interface elements

## SPARK TOOLS context

GRANTED is part of **SPARK TOOLS**, a suite of small text-based browser instruments for thinking, writing, reframing, and creative pressure.

Related tools include:

* IDK MACHINE
* BADVICE
* SAID IT
* TILT
* BAD EVIDENCE
* THE WRONG QUESTION
* COUNTERWEIGHT
* GRANTED

Each tool has its own voice, but the suite shares a compact, retro-terminal, text-first design philosophy.

## Copyright

© HRF 2026. All rights reserved.

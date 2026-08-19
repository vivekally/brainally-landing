# BrainAlly Landing

Landing page for BrainAlly, the consent-first company brain.

**Live:** https://vivekally.github.io/brainally-landing/

**Market thesis:** https://vivekally.github.io/brainally-thesis/ ([repo](https://github.com/vivekally/brainally-thesis))

## What it says

A company brain is not search. It is a living model of how a company works,
built from the people who do the work.

The architecture is four rings, each earning the next:

    Digital Twin -> Personal Brain -> Company Brain -> Self-Learning AI

The wedge is consent. The brain belongs to the company. The twin belongs to
the person.

## Stack

Single static `index.html`. No build step, no dependencies. SVG ring animation
in CSS, scroll reveals via IntersectionObserver, Inter from Google Fonts.

Served by GitHub Pages from `main` at root. `.nojekyll` keeps Jekyll out of it.

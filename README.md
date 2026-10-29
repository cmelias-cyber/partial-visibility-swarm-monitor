# Partial-Visibility Swarm Monitor

Hackathon project for the Swarm Alignment Hackathon (Nov 6 to 8, 2026), organized by the AI Alignment Foundation and Apart Research, in the Oversight & monitoring track.

## Research question
How much does a monitor lose when it sees only part of the messages exchanged by a swarm of AI agents?

## Method
We will plant a covert channel in a small simulated swarm of AI agents, then hide more of the messages from the monitor in each experimental condition and measure how well it detects the channel.

## Measure of success
A detection curve showing how the monitor's performance changes as its visibility shrinks.

## Status
Planning stage. The experiment design, scoring rubric, and background notes are in `docs/`. The simulated swarm and the monitor will be built during the hackathon weekend.

## Repository layout
- `docs/`: experiment plan, scoring rubric, background, and team roles
- `src/`: simulation and monitor code (built during the hackathon)
- `data/`: swarm logs
- `results/`: detection curve and final report

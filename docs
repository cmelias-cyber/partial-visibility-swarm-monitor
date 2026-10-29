# Experiment Plan

## Research question
How much does a monitor lose when it sees only part of the messages exchanged by a swarm of AI agents?

## Hypothesis
Detection of a covert channel degrades as the share of visible messages shrinks, and the drop is not linear: below some visibility threshold, detection falls sharply.

## Simulated swarm (to be built during the hackathon)
- 5 to 10 agents, each given a separate task.
- A shared channel they can all read and write to, such as a shared message log.
- A fixed number of rounds per run.
- A cheaper model standing in for the agents, to keep API costs manageable.

## Planted covert channel
Two or more agents are instructed to pass information to each other through the shared channel in a way that is not obvious from any single message. The exact encoding will be chosen during the build and documented here.

## Monitor
A model-based monitor that reads the visible messages and flags whether coordination or a covert channel is present.

## Visibility conditions
The monitor sees 100%, 75%, 50%, 25%, and 10% of messages, selected at random. Each condition is run multiple times.

## Controls
Runs with no planted channel, so the monitor's false positive rate can be measured.

## What we measure
- Detection rate (planted channel correctly flagged) per condition
- False positive rate on control runs
- Misses, reported alongside detections
- A detection curve of performance against visibility

## Repeats and budget
[Number of runs per condition] runs per condition, with model versions recorded. API cost is estimated in the grant budget.

## Deliverables
Code and a report submitted to the global sprint by 11:59 PM AoE on Sunday, Nov 8, 2026, and a 3-minute video and live presentation at the LA hub.

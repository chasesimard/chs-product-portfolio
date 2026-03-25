# Voice / Automation Product Workflow Case Study

## Overview
This case study explores how I would improve a voice or automation workflow where users experience friction during routing, handoff, or workflow completion.

## Problem
A voice or automation workflow may technically function while still creating user frustration through:
- misrouting
- repeated clarification loops
- broken handoffs
- poor fallback experiences
- unclear status communication

## Users Affected
- callers or end users trying to complete a task quickly
- internal teams receiving failed transfers or escalations
- operators managing workflow reliability
- product teams trying to scale automation safely

## Product Goals
- increase workflow completion rate
- reduce failed handoffs
- reduce unnecessary call transfers
- improve user clarity and confidence
- reduce operational burden from automation failures

## Key Failure Modes
1. incorrect intent recognition
2. routing to the wrong destination
3. no confirmation before critical action
4. unclear fallback language
5. handoff failures with no recovery path
6. poor handling of ambiguity

## Proposed Improvements

### 1. Confirm before critical routing
Require confirmation on sensitive or uncertain transfers.

### 2. Add fallback states for failed handoffs
If a handoff fails, provide a recovery path instead of ending in dead air or confusion.

### 3. Improve workflow observability
Track where the workflow breaks:
- intent capture
- routing
- transfer
- completion
- escalation

### 4. Tighten copy and interaction design
Reduce ambiguity in prompts and confirmation language.

### 5. Create a workflow review framework
Use failed interactions as inputs into product improvement.

## Metrics
- workflow completion rate
- transfer success rate
- reroute rate
- fallback rate
- repeat clarification rate
- average turns before successful routing
- user drop-off rate

## Rollout Plan
1. map the end-to-end workflow
2. identify highest-friction failure points
3. prioritize transfer and fallback improvements
4. test revised workflow
5. monitor workflow completion and failed handoffs

## PM Skills Demonstrated
- workflow design
- systems thinking
- UX reasoning
- operations-aware product design
- instrumentation thinking
- iterative rollout planning

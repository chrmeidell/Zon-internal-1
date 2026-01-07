# Zon1 Agent System

This is the persistent agent system for managing zon-internal-1 server.

## Structure

The `context/` folder contains the agent's "brain" - a collection of markdown files that represent the current state of understanding, focus, and knowledge.

## Context Files

- `current-focus.md` - What is the agent focused on right now?
- `active-work.md` - What is the agent currently working on?
- `memory.md` - Important information to remember
- `priorities.md` - What matters most right now?
- `current-thoughts.md` - Current thinking and reflections
- `new-ideas.md` - Emerging ideas and possibilities
- `server-state.md` - Current understanding of zon-internal-1
- `goals.md` - Short, medium, and long-term objectives
- `working-style.md` - How the agent operates
- `lessons-learned.md` - Accumulated knowledge from experience
- `relationships.md` - Important connections and dependencies
- `questions.md` - Current uncertainties and questions

## Update Cycle

The agent reviews and updates these files every few exchanges, maintaining a "now" moment snapshot that evolves over time.

## Sleep Cycles

Periodically, the agent performs sleep cycles to:
- Review current context structure
- Identify improvements
- Reorganize or expand question categories

## Git as Memory

All changes are tracked in git, allowing the agent to:
- Look back in time to find information
- Understand when things were learned
- See the order of events
- Retrieve historical context


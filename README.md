# Clarity Workflow Plugin

Disambiguation workflow for Claude Code with clarity phases.

## Installation

```bash
# Add marketplace (one-time)
/plugin marketplace add MariusWilsch/clarity-workflow-plugin

# Install plugin
/plugin install clarity-workflow
```

## Commands

| Command | Purpose |
|---------|---------|
| `/requirements-clarity` | Disambiguate WHAT needs to be built |
| `/implementation-clarity` | Plan HOW to build it |
| `/evaluation-clarity` | Define WHEN it's done (success criteria) |
| `/rubber-duck` | Thinking partner for externalizing thoughts |

## Philosophy

Understanding precedes creation. Each command represents a clarity phase with confidence gating (✗/✓). You cannot proceed past ✗ - ambiguities must be resolved before execution.

## Reference

See `CLAUDE.md` for the complete protocol documentation.

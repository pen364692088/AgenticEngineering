# Agentic Engineering Framework

**⚠️ This project has been merged into [LongRunKit](https://github.com/pen364692088/LongRunKit).**

## What happened?

The Agentic Engineering framework is now an **extension** of LongRunKit, providing a unified CLI for long-running task management with multi-agent workflow support.

## How to use

```bash
# Install LongRunKit
git clone https://github.com/pen364692088/LongRunKit.git
cd LongRunKit
./bin/longrun init --project .

# Initialize a project with Agentic Engineering
longrun init --project /path/to/your/project --with-agentic
```

## Available commands

```bash
longrun init --with-agentic    # Initialize with full framework
longrun test-smoke             # 10-30s quick validation
longrun test-fast              # 1-3min pre-commit tests
longrun test-full              # Full test suite
longrun checkpoint "note"      # Save progress
longrun status                 # Show current state
longrun report "cmd"           # Run and generate reports
```

## Features

- ✅ Test layering (smoke/fast/full)
- ✅ Context memory (STATUS/TODO/DECISIONS/HANDOFF)
- ✅ Parallel work (worktree + oracle diff)
- ✅ Agent roles (planner/implementer/verifier/scribe/merger)
- ✅ Reproducibility (seed + structured reports)

## Documentation

See [LongRunKit README](https://github.com/pen364692088/LongRunKit) for full documentation.

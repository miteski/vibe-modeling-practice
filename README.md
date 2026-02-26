# Vibe Modeling

Vibe modeling is the practice of visually exploring domain events, system boundaries, and user flows with AI before writing code.

It gives developers structured context and shared understanding, so vibe coding starts from a clear model instead of a vague prompt.

## Vibe modeling vs vibe coding

Vibe coding is the vehicle. Vibe modeling is knowing where you're going before you start driving.

| | Vibe modeling | Vibe coding |
|---|---|---|
| **Goal** | Understand the system shape | Generate working code |
| **Medium** | Visual board + AI conversation | Prompts + code editor |
| **Output** | Shared domain model, structured context | Code changes, features |
| **Best time** | Before implementation, during refactors | During implementation |
| **Risk if skipped** | Hidden boundaries, rework, misaligned teams | Slower implementation, less feedback velocity |

## What vibe modeling is not

- Not a compliance-heavy architecture review
- Not UML diagrams for the sake of documentation
- Not replacing coding — it makes coding better
- Not delegating design decisions to AI — you drive, AI consults

## Your first vibe modeling session

1. **Open the board.** Start with a blank canvas at [VibeModeling.app](https://www.vibemodeling.app/board.html).
2. **Name your domain events.** What happens in your system? User registered, order placed, payment processed — get them onto sticky notes.
3. **Let AI consult you.** The AI sees your board and asks the questions you forgot. It surfaces patterns. It catches gaps.
4. **Draw boundaries.** Group events that belong together. Name the bounded contexts. Connect the flows.
5. **Take it into implementation.** Bring your model into Claude Code, Cursor, or any AI coding tool. Start coding with confidence.

## Learn more

- [What is vibe modeling?](https://www.vibemodeling.app/what-is-vibe-modeling/) — the full definition and FAQ
- [Open the board](https://www.vibemodeling.app/board.html) — try it now, free in your browser
- [Blog](https://www.vibemodeling.app/blog/) — articles on vibe modeling, domain-driven design, and AI-assisted development

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

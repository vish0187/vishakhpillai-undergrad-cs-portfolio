<div align="center">

# Token Toolkit

### Growing a CS160 Java concept into a usable text-processing tool

**Java · OOP · Text Processing**

🟡 **In Development**

[Course Home](../../README.md) · [Coursework Origin](../../coursework/token-class/README.md)

</div>

---

## Project Idea

My CS160 coursework introduced a `Token` object that stores a string value. Token Toolkit is an independent extension exploring what happens when Token objects become the basic units of a small text-processing program.

The original assignment remains documented separately. Features listed here are only marked complete once they actually exist.

## From Coursework to Engineering

| CS160 foundation | Independent direction |
|---|---|
| Java class | Reusable Token model |
| Private field | Encapsulated token state |
| Constructors | Controlled object creation |
| Getter / setter | Public object interface |
| `toString()` | Readable token output |

## Planned Architecture

```text
┌────────────┐     ┌────────────┐     ┌──────────────┐     ┌────────────┐
│ Text Input │ ──→ │ Tokenizer  │ ──→ │ List<Token>  │ ──→ │  Analyzer  │
└────────────┘     └────────────┘     └──────────────┘     └─────┬──────┘
                                                                  │
                                                                  ▼
                                                            ┌────────────┐
                                                            │ CLI Result │
                                                            └────────────┘
```

## Target v1.0

- accept text input
- split input into Token objects
- report useful basic statistics
- provide a simple command-line experience
- include automated tests
- provide examples that make the project easy to try

## Build Progress

- [ ] **v0.1** · Preserve and clean up the Token model
- [ ] **v0.2** · Implement tokenization
- [ ] **v0.3** · Add basic analysis
- [ ] **v0.4** · Add automated tests
- [ ] **v0.5** · Build the CLI experience
- [ ] **v1.0** · Polish documentation and add a real demo

## Demo

> 🚧 A demo will be added when a meaningful runnable version exists.

## Why this project matters

The value is in the progression: learning an abstraction in class, understanding it, and then applying it as one component of a larger program.

[**See the coursework foundation →**](../../coursework/token-class/README.md)

---

<div align="center">

Built incrementally as I progress through CS160.

</div>

# Study Buddy

A Claude Code plugin for studying with four learning modes:

- **Tutor** explains a topic, finds gaps in your understanding, and works through problems with you.
- **Classmate** turns your notes or a topic into active-recall flashcards.
- **Teacher** creates practice quizzes with answer keys and explanations.
- **Little Brother** asks you to teach the material back in plain language, one question at a time.

## Install

Run Claude Code with this plugin directory:

```sh
claude --plugin-dir /path/to/study-buddy
```

Replace the path with the directory where you cloned this repository. Then ask Claude to use the Study Buddy skill, or start a request with a mode name, for example:

- “Tutor me on quadratic equations.”
- “Classmate: make flashcards from these notes: …”
- “Teacher: quiz me on cellular respiration.”
- “Little Brother: ask me about the French Revolution.”

You can provide notes, a subject, a specific question, or a mix. The skill will ask a short clarifying question only when it needs information such as your level or desired quiz length.

## What to expect

Study Buddy prioritizes understanding and active recall over simply giving answers. It distinguishes information from your notes from additional background knowledge, flags uncertainty, and adapts explanations to your level. For quizzes, answers are separated so you can try first.

## Plugin structure

```text
.claude-plugin/plugin.json
skills/study-coach/SKILL.md
```

## License

MIT

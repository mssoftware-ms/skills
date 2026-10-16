# Skills

Agent skills for Claude Code, Codex and other agents supporting the [Agent Skills](https://agentskills.io) standard.

## prompt-optimizer (Prompt Pro)

Verwandelt eine Anfrage, Rohidee oder einen bestehenden Prompt in einen optimierten, wiederverwendbaren Prompt für andere KI-Chats (ChatGPT, Gemini, Claude, Midjourney) – im Format **#Prompt Pro / Mögliche Zusätze / Fragen**. Der Skill löst die Aufgabe nicht selbst, sondern liefert nur den Prompt.

Turns a request, rough idea or existing prompt into an optimized, reusable prompt for other AI chats (German by default, answers in the language of the request).

### Installation

```bash
npx skills add mssoftware-ms/skills --skill prompt-optimizer -g
```

Manuell: den Ordner `skills/prompt-optimizer` nach `~/.claude/skills/` (Claude Code) bzw. `~/.agents/skills/` (Codex) kopieren.

## License

[MIT](LICENSE)

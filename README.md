# Language Learning Skill

A Codex skill for learning German and English with clear Chinese explanations and lightweight vocabulary practice.

## What it does

- Translates German or English words, phrases, sentences, and passages into natural Chinese.
- Selects useful vocabulary and fixed expressions from the source, explaining their meaning in context, pronunciation, grammar, and common usage.
- Adds an individual click-to-play audio player to each selected vocabulary item, using local system speech synthesis.
- Adds user-selected words with the `add` command and continues the numbering from the latest vocabulary explanation.
- Saves selected vocabulary to a dated, language-separated learning log on the Desktop with the `record` command.
- Generates date-based MP3 pronunciation practice from the learning log with the `mp3` command. Each entry is spoken three times with pauses for repetition.

## Use

Invoke the skill with `$xulin-languagelearning` and provide German or English text to study.

Common follow-up commands:

- `add informieren` — explain an additional word from the latest passage.
- `record 1,3` — save selected numbered entries to the learning log.
- `mp3 11.10.2026` — create pronunciation practice for that date's saved entries.

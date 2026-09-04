# Source

This skill is vendored from [AgriciDaniel/banana-claude](https://github.com/AgriciDaniel/banana-claude)
(version 3.0.0), MIT licensed — see `LICENSE` in this directory.

## Requirements

- Claude Code 2.1.199 or newer
- Python 3.11 or newer with `python3` on `PATH`
- A Gemini API key for a billing-enabled Google AI project, exported as
  `GEMINI_API_KEY` in the environment before running any paid generation
  command. The skill never reads or stores the key itself.

## Usage

Ask Claude to generate, edit, compare, or review images and it will route to
`/banana` per `SKILL.md`. Every paid Gemini request is planned and shown for
approval before execution — see `SKILL.md` for the full workflow.

## Upstream docs

- [User guide](https://github.com/AgriciDaniel/banana-claude/blob/main/docs/guide.md)
- [Security and privacy](https://github.com/AgriciDaniel/banana-claude/blob/main/SECURITY.md)
- [Changelog](https://github.com/AgriciDaniel/banana-claude/blob/main/CHANGELOG.md)

# Summarize-this-TLDR Claude Code Skill
Provides an a brief or summary for any uploaded or shared document for executive audiences using Claude Code

**How it works:**
It's an executive document summarizer that:
  - Triggers on: file uploads, paths, or phrases like "summarize this", "TL;DR", "brief me on this"
  - Reads: PDFs, Word docs, PowerPoints, spreadsheets, plain text, pathway to the file location
  - Output: structured exec briefing — Overview, Top Takeaways, Issues/Blockers, Next Steps
  - Audience: C-suite/VP level, 90-second read, under 300 words

**Suggested invoking skillstarters:**
   "summarize this", "give me a summary", "what is this about", "summarize for execs", "TL;DR", "brief me on
   this", "what are the key points", or when a file is uploaded or a path is provided without a specific instruction.

----------------
**Installation**

**Recommended (clone directly into Claude Code skills directory)**
```
mkdir -p ~/.claude/skills
git clone https://github.com/gdiwanaipm-stack/exec-summarizer.git ~/.claude/skills/exec-summarizer
```
**Manual install/update (only the skill file)**
If you already have this repo cloned (or you downloaded SKILL.md), copy the skill file into Claude Code’s skills directory:

```
mkdir -p ~/.claude/skills/exec-summarizer
cp SKILL.md ~/.claude/skills/exec-summarizer/
```
-----------------
**Usage**
In Claude Code, invoke the skill:
```/exec-summarizer [paste your text here]```

Or ask Claude to ```exec-summarizer this text [paste your text here]```

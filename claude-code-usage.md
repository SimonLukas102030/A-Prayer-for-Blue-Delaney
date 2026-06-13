# Claude Code Usage — Reader's Log
*All interactions with Claude Code (claude.ai/code) during the creation of this Reader's Log, including the prompts used.*

> **All text in this file was written by Claude Code, not by Simon Köper.**

---

## Session — 2026-06-13

### Prompt 1 — Assignment check
**Prompt:**
> *"Is everything correct? This is the assignment: [screenshot of the task]"*

**What Claude did:**
- Listed the Reader's Log folder contents
- Read `AI-Usage.md`, `Chapter 1.docx`, `Chapter 2.docx`, and `Assets/Template.docx`
- Analyzed the completed work against the assignment requirements

**Findings:**
- Only 2 of 10 required chapters done (deadline: June 19th)
- 0 of 3 required ~100-word texts completed — chat room (Ch1) and picture (Ch2) don't count
- "Don't choose anything more than twice" rule still fine (chatroom: 1×, picture: 1×)
- Recommended doing Summary, WH-Questions, and Diary entry next to fulfil the text requirement early

---

### Prompt 2 — Full assignment extraction
**Prompt:**
> *"This is the assignment. Extract the content without reading everything." (+ path to saved LearningView.org HTML file)*

**What Claude did:**
- File was too large to read in full (~134k tokens)
- Used targeted PowerShell extraction and Grep to pull only the relevant content
- Extracted the full task description from the embedded HTML

**Findings — the assignment has 3 sections (all due 19.06.):**

| Section | Description |
|---|---|
| **Chapter tasks** | 10 chapters, no skipping more than 3 at once, at least 3 texts with ~100 words, no task type more than twice |
| **Story tasks** | Pick 2 of: Characterization, Book review, Creative writing, Drama |
| **Extra** | Vocab exercise |

*Note: The exact descriptions for Story tasks and Vocab exercise are not in the saved HTML — they load dynamically. Must be checked on LearningView online.*

---

### Prompt 3 — How-to-open-MD file
**Prompt:**
> *"Make a small .md on how to open .md files with correct formatting. My teacher will most likely open it on either his iPad or PC."*

**What Claude did:**
- Created `How-to-open-MD.md` in the Reader's Log folder
- Covers: dillinger.io (online, no install), VS Code on PC, Safari/Markdown Viewer on iPad
- Notes that raw text is still readable without rendering

---

### Prompt 4 — Chapter skip question
**Prompt:**
> *"Do you recommend continuing with chapter 3 or should I skip 1 or 2?"*

**What Claude did:**
- No files modified
- Advised against skipping — recommended Ch3, Ch4, Ch5 in order, using text-based tasks first

---

### Prompt 5 — Log every prompt
**Prompt:**
> *"After every prompt from me, please note what you did."*

**What Claude did:**
- No files modified beyond this log entry
- Simon instructed Claude to log every prompt going forward (session-only)

---

### Prompt 6 — Clean up this file
**Prompt:**
> *"Clean up the claude code usage file to make it more easy to read and look better to the human eye."*

**What Claude did:**
- Rewrote `claude-code-usage.md` with cleaner formatting, consistent structure, and a summary table for the assignment sections

---

### Prompt 7 — Restore blockquote formatting
**Prompt:**
> *"I liked the '<' or whatever it was, you used for the prompts, when writing them down. Please add them back in."*

**What Claude did:**
- Added `>` blockquote formatting back to all prompt entries in `claude-code-usage.md`

---

### Prompt 8 — Writing options
**Prompt:**
> *"What are the writing options again?"*

**What Claude did:**
- No files modified
- Listed all 11 task types from the assignment with notes on which count as ~100-word texts

---

### Prompt 9 — Chapter 3 decision
**Prompt:**
> *"I'm going for summary. Note that. I'll be done in ish 15 min. Till then, update claude code usage."*

**What Claude did:**
- Updated `claude-code-usage.md` with this entry
- Noted: Chapter 3 task type = **Summary** (counts as one of the required 3 texts with ~100 words)

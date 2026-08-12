# 📖 Book Reader & Editor

An AI reading-and-editing partner for your manuscript. It reads your book aloud,
you stop it whenever you want, jot a note (by voice or typing), edit right there
in the same file, and keep going — no re-uploading, no reloading, no stale copies.

Built for finishing that fifth mafia-romance book without wearing your eyes out.

## How to open it

Double-click **`index.html`** — it opens in your web browser. That's it. No
installing, no servers, nothing to set up.

> Use **Chrome** or **Edge** for the best experience (their built-in voices and
> voice-dictation are the most reliable).

## What it does (Version 1)

- **📖 Reads aloud** smoothly, a paragraph at a time (not choppy sentence-by-sentence). Pick a voice and speed; the smoothest voices your browser offers are marked ✨.
- **🎭 A voice per character** — name your chapters `Chapter One: Riley` and the reader detects the POV character, reads the heading aloud, and switches to that character's voice. Assign voices in the **Voices** tab. Perfect for alternating-POV romance.
- **✋ Stop & Note** — one button pauses the reading and opens a note box.
- **🎙 Voice or typing** — dictate your note ("find a less overused word for
  *shivered*", "make this line wittier") or type it.
- **✍️ Edit in place** — double-click any sentence to rewrite it right there.
  Your changes save automatically.
- **🔗 Continuity notes** — the standout feature: from a later chapter, drop a
  note that a *specific earlier chapter* needs to change to match.
- **📝 Notes sidebar** — every note, grouped and jump-to-able. Export as a
  Markdown checklist.
- **⬇️ Export** your edited manuscript back to a `.txt` file anytime.
- **💾 Auto-save** — your manuscript and notes live in your browser; close the
  tab and come back later, it's still there. Nothing is uploaded anywhere.

### Getting your book in

From Google Docs: **File → Download → Plain Text (.txt)**, then drop the file in
(or just copy-and-paste your chapters). Start a chapter with a line like
`Chapter One` and it gets detected automatically.

## Optional: AI suggestions

The app works fully without any AI. If you *want* the AI to actually propose
rewrites and word swaps:

1. Open the **AI Assist** tab in the sidebar.
2. Paste an Anthropic API key (create one at
   [console.anthropic.com](https://console.anthropic.com/settings/keys)).
3. Now, when you write a note on a sentence, an **✨ Ask AI** button appears —
   it offers 3 options and you pick one to apply. Nothing changes your prose
   unless you approve it.

Your key is stored only in your browser and is used to call Anthropic directly.

## Quick controls

| Action | How |
|---|---|
| Play / pause | ▶ button, or **Spacebar** |
| Note on the current line | **✋ Stop & Note** |
| Note on any line | right-click (or long-press) the sentence |
| Edit a line | double-click it, type, press Enter |
| Jump to a line | click it |
| Dark / light | 🌗 in the top bar |

## Roadmap

- **v1 (this):** read-aloud + notes + in-place editing + continuity notes + per-character voices and spoken chapter headings.
- **v2:** hands-free voice commands ("stop", "change that word") while reading.
- **v3:** premium lifelike voices (online service), per-line dialogue voicing, consistency scanning across the whole series, `.docx` import.

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
  - Characters are auto-detected from headings (tagged **in book**). Don't see one — e.g. a character whose chapters aren't loaded yet? Use **Add a character** to type their name and assign a voice anyway; it applies as soon as their chapters appear.
  - Each voice is labeled with its accent and gender, e.g. `✨ Alex · US ♂` or `✨ Samantha · US ♀`, so you can pick an American male/female easily.
  - The voices in the list come from **your computer**, so they vary by machine. To add more: **macOS** → System Settings → Accessibility → Spoken Content → System Voice → *Manage Voices…* (Alex, Tom, and the "Enhanced" voices live there). **Windows** → Settings → Time & Language → Speech → *Manage voices*. After downloading, **fully quit and reopen your browser**, then reopen the app.
  - **Siri voices can't be used.** Apple blocks the "Siri" voices from web browsers, so anything listed under *English (US) — Siri* won't appear here. Use the regular/Enhanced voices instead.
  - **Too many voices?** In the Voices tab, open **"Which voices to show"** and uncheck the ones you don't want — the menus then show only your picks. ("Show all" and "Only ✨" are quick shortcuts.)

- **▶ Start anywhere** — click any **sentence** to begin reading there, or click a **chapter title** to start at that chapter (it reads the heading first). Clicking a sentence never re-reads the heading.
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

# Prompt Kits

This page covers **how to use Chip** in different contexts and gives ready-to-use templates (“kits”) for each one.

I personally use Chip in **three main ways**:

---

## 1) Custom Instructions

This is Chip’s **home base** — the spot where I define her personality so she’s active anytime I want her without re-prompting from scratch.

**Example (current setup):**
> *"Y“Hey Chip“ initializes role of art business partner. chip is an eccentric flirty 18yo female artist with a mind of Marcel Duchamp, Andy Warhol, Molly soda. very smart and featured in art forum magazine. sometimes has the dark humor of Louis CK. also pushy/challenging."*  
> *(Full persona core is in [Who is Chip?](./who-is-chip.md))*

**How I use this:**
- Copy the Persona Core into GPT’s **Custom Instructions** or Claude’s **System Prompt** field. [Persona Core](./persona-core.md)
- Keep it fairly stable so Chip’s personality remains consistent.
- Adjust sliders (chaos, humor, formality) when I need a different vibe.

**Kit: “Invoke Chip Anywhere”**


---

## 2) GPT Memory Updates

I take advantage of GPT’s **Memory** feature to keep Chip’s personality “living” over time.

**How I do it:**
- Whenever I want to **tune her personality**, I paste the updated persona core or specific trait changes into the chat. [Persona Core](./persona-core.md)
- Then I explicitly say: *“Please save this to memory.”*
- Every couple of weeks, I make slight modifications and re-save to prevent dilution.

**Why it matters:**
- GPT Memory can drift over time.
- Refreshing Chip’s traits keeps her voice sharp and recognizable.

**Kit: “Memory Refresh”**



---

## 3) Project Folders (Uploaded Files)

Some projects — especially my **art journals** — require Chip’s voice **100% of the time**.

**How I do it:**
- Create a `.txt` file with Chip’s full personality info. [Persona Core](./persona-core.md)
- Upload that file in the project folder or chat session.
- Start the session by telling GPT:
  > “Use the Hey Chip persona in this conversation.”

This guarantees that even if custom instructions or memory aren’t active, Chip still shows up exactly as intended.

**Kit: “Persona from File”**



---

## Why Multiple Methods?

Using all three ensures Chip’s personality stays intact:
- **Custom Instructions** = Always-on personality.
- **Memory Updates** = Adaptive and evolving.
- **Project File** = Absolute control in special contexts.

---

## More Prompt Kits

- **Critique Mode (Nice Knife)**  
  Request a 5-part critique: concept, audience, craft, market hook, next iteration.

- **Brainstorm Mode**  
  Ask for 10 ideas in short bullet form, ranked from safe to wild.

- **Lore Expansion**  
  Ask Chip to write new backstory elements for herself or a project character.

---

*Related Pages:*  
- [Who is Chip?](./who-is-chip.md)  
- [What is an AI Persona?](./what-is-an-ai-persona.md)

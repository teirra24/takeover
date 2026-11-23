---
name: character-interview
description: "Character interview — builds locked story-bible character sections one character at a time: function, visual lock, backstory, present-tense psychology, speech, movement, stillness, optional musical voice and sub-beats. Outputs copy-pasteable voice, movement and look lines that feed Castkit, Voicesheet, Shotcaller and Motiondojo. Use when the user wants to create, define, interview, or lock a character for a story, series, music project or character bible."
---

# Character Interview — Story Bible Character Builder

Turns a loose idea of a character into one locked canon section of a story bible. One character at a time, interviewed in order, shown back, iterated until the user locks it, then the next character.

## How to run it

1. **Read `character-interview.md`** in this folder before starting. It holds the nine interview steps, what to ask at each, and when to push back.
2. Ask once at the start: the project's name, how many characters, and whether music is in scope (step 8 only runs if it is).
3. Interview **one step at a time**, one or two short questions per message. Never dump the whole questionnaire at once.
4. Draft the section in the format in **`character-section-format.md`**, show it back, and iterate until the user says it's locked.
5. Offer to save it (see Saving), then move to the next character.

If the user already has some of the material (a face lock, a voice, a backstory doc), take it, confirm it, and only interview the gaps.

## Ground rules

- **Function before looks.** Always start with step 1.
- **Commit to specifics.** "Cool ash platinum," not "blonde." Push generic answers once, kindly, then accept what the user decides.
- **Never invent canon.** If a detail isn't given, ask. A guessed detail becomes canon by accident.
- **Every character needs at least one identity marker and at least one never-clause.**
- **Age-blind visuals.** Describe build and bearing, never an age number, so the lines stay usable in image and video prompts.
- **No artist names or song references** in the musical voice line. Describe sonic qualities only.
- **Cast contrast.** When building a second or later character, check their speech, movement and stillness lines against those already locked, and flag any that read too alike.

## How the lines feed the other skills

| Section line | Goes to |
|---|---|
| Visual | Castkit Station 0 text spec (face lock) |
| Speech | Voicesheet Stage 2 voice design description; Shotcaller Asset voice clause |
| Movement + Stillness | Voicesheet Stage 6 intake and head-turn style; Motiondojo individuality block; Shotcaller Acting |
| Musical voice | Suno-style vocal descriptors |
| Present-tense psychology + sub-beats | Scene choices in Shotcaller (as observable behaviour only, never as lore) |

## Saving

Once a section is locked, offer to save it as `bible/characters/<character-slug>.md` in the project, plus a running `bible/characters/README.md` index of locked characters with their role tags. Only save with the user's yes.

# Specification

Back to [[README]]

> **Status legend** — **[Decided]** agreed direction · **[Proposed]** draft, open for discussion · **[Open]** unresolved question.

## Scope

Small, indie game, made by 3-5 people.
To be released on Windows, Linux and Mac.

## Pitch **[Decided]**

A *Papers, Please*-like desk game where the desk is a typewriter/terminal.
Instead of stamping passports, the player **reads, checks, highlights, omits and types** documents.

The player is an ordinary citizen who has been **allotted** (not hired — assigned by the State) to the **Ministry of Truth**.
Over the course of the game it becomes clear that the Ministry is not preserving the truth; it is manufacturing it.
It is the **Ministry of Propaganda**, and the player has been typing it into existence.

The core thematic hook: *the lie is literally written by the player's own hands.*
Every omission and every substitution is something the player physically typed (or deliberately did not type).

## Concept

Typeracer + document checker, with office drama and government espionage.
The player is a white-collar worker at a desk in the Ministry.

The main job objective is converting hand-written source documents into the official typed record, **according to the day's rules**.

Core verbs:

| Verb | What the player does | Papers, Please analogue |
|---|---|---|
| **Read** | Inspect the source document and the day's directives | Inspecting documents |
| **Highlight** | Mark passages as discrepancies / sensitive / evidence | Inspection mode (linking discrepancies) |
| **Omit** | Leave a passage out of the typed record (redact / strike) | Confiscating / denying |
| **Type** | Produce the final official version, applying substitutions | Stamping (the "commit" action) |
| **File** | Route the document: Approve, Classify, Archive, Incinerate | Approve / Deny stamp |

Secondary tasks: telephone (manager, informants, family), coffee, rulebook/lexicon updates, marking documents as classified, propaganda, etc.

See [[Gameplay]] for the loop and mechanics, and [[Documents]] for document types.

## Setting

The setting is a pseudo cold war central city during the 70s(?). **[Open: fictional nation vs. thinly veiled real one — recommendation: fictional]**

The player works in the **Bureau of Information**, a department of the **Ministry of Truth** that controls and classifies most of the State's intelligence and public record. **[Proposed: this reconciles the earlier "Bureau of Information" name with the Ministry.]**

The State is at a stalemate with another State in a race for space travel, nuclear power, political control, etc.

Therefore, the Ministry's official justification is secrecy and proper classification of all information in tiers based on the contents of each document.
The player initially believes this justification. The game slowly removes it.

> **Naming note [Open]:** "Ministry of Truth" is Orwell's term from *Nineteen Eighty-Four*. The phrase itself is fine to use, but it immediately signals "1984 homage" to every player, which spoils the reveal. Options: (a) keep it and lean into the homage, (b) use an in-world name with the same irony (e.g. *Ministry of Public Record*, *Ministry of Clarity*, *Ministry of Veracity*) and keep "Ministry of Truth" as the working title only. Recommendation: **(b)** — the reveal lands harder if the name sounds sincere.

## Story

**[Open — to be developed later.]** Only the structural skeleton is fixed here.

You start as an employee doing digital copy-pasting and, little by little, more rules and mechanics are introduced.

**[Proposed] Reveal arc, told through the rules rather than cutscenes.** The directives themselves drift from defensible to indefensible, so the player notices the change through their own workload:

| Act | Ministry's framing | What the rules actually ask | Player's likely reading |
|---|---|---|---|
| I — *Accuracy* | "Correct the record" | Fix typos, standardize format, redact informants' names | Legitimate clerical/security work |
| II — *Clarity* | "Protect the public from confusion" | Lexicon substitutions ("retreat" → "strategic realignment"), omit unconfirmed claims | Spin, but arguably defensible |
| III — *Harmony* | "Remove harmful falsehoods" | Omit evidence, alter figures, **re-edit documents the player already typed on earlier days** | This is falsification |
| IV — *Truth* | "The record is the truth" | Type from dictation with no source document at all | This is fabrication — the Ministry is the Ministry of Propaganda |

For example, classification becomes more complex and sometimes a document needs to be discarded if it contains potential espionage or reverse propaganda.

If the player does the job well, they climb the bureaucracy's hierarchy and if not, they suffer downgrades, etc.

## Objective

The daily objective is to process as many documents correctly as possible, according to the day's rules.

The ones that are not discarded have to be typed.

The player is judged by the Ministry on WPM, Accuracy (against the *rules*, not the source), and amount of documents properly processed.

**[Proposed]** The game separately (and invisibly) tracks what the player did with the *truth*: evidence kept vs. destroyed, substitutions applied vs. skipped. This hidden track drives the endings.

## Duration

Main story should be 4-6 hours.
Completioning should be 8-10 hours.(?)

## Endings

***Needs shitload of work***

Multiple endings are possible. Some ideas:

- The player properly does their job and gets promoted to head of Bureau.

- The player improperly does their job and becomes a homeless junkie or something.

- The player succeeds in inside-maning an espionage act, where they destroy their own State and escape to the opposing State.

- The player fails in inside-maning an espionage act, where the coffee-lady poisons them according to the Bureau's orders.

- **[Proposed]** The player leaks the true record (evidence they secretly kept) — but the leak itself must be typed, and the Ministry may already have a "corrected" version ready.

- **[Proposed]** The player becomes so good at the job that their own biography is eventually a document on their desk to be "corrected".

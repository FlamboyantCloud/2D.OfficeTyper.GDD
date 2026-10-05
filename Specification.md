# Specification

Back to [[README]]

> **Status legend** — **[Canon]** from the [[Story]] bible · **[Decided]** agreed direction · **[Proposed]** draft, open for discussion · **[Open]** unresolved question.
>
> **Precedence:** [[Story]] is the canonical source for world, plot and characters. This page holds the game-level spec and the reconciliation between the story canon and the earlier GDD drafts.

## Scope

Small, indie game, made by 3-5 people.
To be released on Windows, Linux and Mac.

**[Open]** Title: repo/working name is *2D.OfficeTyper*; the story bible uses *TypeSomethingGame*. Both are working titles.

## Pitch **[Decided]**

A *Papers, Please*-like desk game where the desk is a typewriter.
Instead of stamping passports, the player **reads, checks, highlights, omits and types** the documents of the State.

**[Canon]** The player, a law graduate from a low-income family, is appointed to the **Ministry of Documentation** of the **Republic of Vlastok**, in the year of the ruling Purple Party's centennial. Rising through the Ministry, he uncovers the Truth behind each of the Party's celebrated reforms, and learns that the Ministry of Documentation is, in reality, the **Ministry of Propaganda**.

The core thematic hook: *the lie is literally written by the player's own hands.*
Every omission and every substitution is something the player physically typed (or deliberately did not type).

## Concept

Typeracer + document checker, with office drama and a slowly revealed state conspiracy.

Core verbs:

| Verb | What the player does | Papers, Please analogue |
|---|---|---|
| **Read** | Inspect the source document against the day's rules | Inspecting documents |
| **Highlight** | Mark discrepancies / sensitive passages / evidence | Inspection mode (linking discrepancies) |
| **Omit** | Leave a passage out of the typed record | Confiscating / denying |
| **Type** | Produce the final official version, applying substitutions | Stamping (the "commit" action) |
| **File** | Route the document: Certify, Return, Archive, Incinerate | Approve / Deny stamp |

**[Proposed]** The verbs are unlocked by rank (see *Progression* below), so the career ladder in [[Story]] *is* the mechanical progression.

See [[Gameplay]] for the loop and mechanics, and [[Documents]] for document types.

## Setting **[Canon]**

Full detail in [[Story]]. Summary:

- **Republic of Vlastok**, governed by a single party (the **Purple Party / PP**) for a century. Two neighbouring nations are de facto puppet states.
- **1960s–1970s**, Soviet-style monumental architecture, wide streets built for parades and military vehicles.
- **The Centennial**: the PP turns 100 and is renamed the **Grand Public Party**. The Ministry hires new staff for it — this is why the player is there.
- **Ministry of Documentation**: authenticates and certifies every national document (IDs, wills, Party decisions). Secretly the Ministry of Propaganda.
- **The Supervisor**: one per ministry, nameless, masked, lives in a segregated sector.

## Story

**[Canon]** Structure: each of the PP's five reforms has a public **Propaganda** version and a hidden **Truth**, and each reform doubles as a gameplay chapter with its own document types:

1. Abolition of physical currency
2. Universal healthcare
3. Peace and foreign relations
4. The free press
5. Religion

**[Open]** Chapter order. The bible lists them in this order but does not fix the play order. Recommendation: put **Free Press** early (newspapers are the most readable/teachable documents) and **Healthcare** or **Peace** last (heaviest Truths), with the PP founding / Blue Party leader's death as the final Truth tied to the Centennial.

### Progression: ranks × verbs × reveal **[Proposed]**

Maps the canon ranks onto the earlier "reveal through the rules" idea:

| Rank **[Canon]** | Canon power | Verbs unlocked **[Proposed]** | What the rules ask **[Proposed]** | Player's likely reading |
|---|---|---|---|---|
| **Validity Officer** | May only note discrepancies | Read, Highlight, File, Type (verbatim) | Spot errors, mismatched dates, forged stamps | Legitimate clerical / legal work |
| **Correction Officer** | Edits documents on paper, on demand | + Omit, + Lexicon substitutions, Revisions | Apply the Supervisor's requested corrections; re-edit documents the player already certified | Spin → falsification |
| **Ministry Accolade** | Free to correct, alter or edit any discrepancy "to the correct and truthful depiction" | + Free edit (no instruction given), Dictation | Decide *yourself* what the truth is | Fabrication — and the only rank where the player could restore the real truth instead |

**[Proposed]** The Accolade rank is where player agency peaks: the Ministry trusts the player to write the "truthful depiction" unsupervised. The player can comply, or quietly restore the original facts. This choice feeds the hidden complicity score (see [[Story]] EXPAND under *Career Progression*) and the ending conditions.

## Objective

The daily objective is to process as many documents correctly as possible, according to the day's rules.

The player is judged by the Ministry on WPM, Accuracy (against the *rules*, not the source), and documents properly processed.

**[Proposed]** The game separately and invisibly tracks what the player did with the truth (evidence kept vs. destroyed, corrections applied vs. quietly skipped). This is the "hidden morality or complicity score" the bible asks for.

## Duration

Main story should be 4-6 hours.
Completioning should be 8-10 hours.(?)

## Endings

**[Canon]** After all Truths are revealed, the player chooses:

1. **Escape** — flee the country toward a better future.
2. **Atonement** — end his life for all the harm he has caused.
3. **Succession** — become the next Supervisor.

**[Proposed]** Earlier GDD ending ideas, re-cast as conditions/variants of the canon endings instead of separate endings:

| Earlier idea | Becomes |
|---|---|
| Promoted to head of Bureau | **Succession** (Supervisor is the canon equivalent) |
| Fails at the job → destitute | A **game-over** before the final choice (run out of money / demoted), not an ending |
| Succeeds at espionage, escapes to the enemy State | **Escape**, good variant — requires evidence secretly kept |
| Caught; poisoned by the coffee lady on orders | **Escape**, failed variant |
| Leaks the true record | **[Open]** candidate 4th ending the bible's EXPAND asks for |

**[Open]** Atonement: suicide as an explicit ending choice is a legitimate theme but needs deliberate, non-gratuitous handling and will affect age ratings and store content descriptors. Decide early how it is presented (implied vs. shown).

## Reconciliation with earlier drafts

Items in the earlier GDD that the [[Story]] canon supersedes or conflicts with:

| Earlier GDD | Story canon | Resolution |
|---|---|---|
| *Ministry of Truth* / *Bureau of Information* | **Ministry of Documentation** | **Resolved** — use canon. (Also fixes the earlier concern that "Ministry of Truth" telegraphs the reveal.) |
| Cold-war stalemate with a rival superpower (space race, nukes, espionage — see [[Notes]]) | Vlastok's only neighbours are its own puppet states; no rival superpower | **[Open]** The Escape ending and espionage ideas need *somewhere* to escape to/spy for. Options: (a) add a distant rival bloc beyond the puppet states, (b) Escape goes into a puppet state's underground, (c) Escape is to "abroad", deliberately undefined. |
| Player is an "ordinary citizen allotted" to the Ministry | Law graduate *offered* the position | Use canon. The Ministry's approach can still feel like an offer that cannot be refused. |
| Four acts: Accuracy → Clarity → Harmony → Truth | Three ranks + five reform chapters | Ranks replace acts (table above); reforms are the chapter content. |
| Coffee lady, manager phone | The Supervisor (communication method is an EXPAND) | **[Proposed]** the "offkey manager phone" in [[Sound]] becomes the Supervisor's line. |
| Bible: *EXPAND core gameplay loop* | — | Answered by [[Gameplay]] (proposed). |

# Gameplay

Back to [[README]]

> Status legend: **[Decided]** · **[Proposed]** · **[Open]** — see [[Specification]].

## Control

- **[Proposed]** Keyboard-first. Typing is the core action, so everything that can be done by keyboard should be.
- Mouse: pick up / move documents on the desk, drag the highlighter, click the phone, stamps.
- **[Open]** Should highlighting/omitting also be keyboard-driven (select passage with arrows + hotkey) for speed-typist players?

## Game Loop

### Day loop **[Proposed]**

1. **Morning** — nation's theme (see [[Sound]]), commute screen, newspaper headline (written from documents the player typed yesterday).
2. **Briefing** — new *Directives* and *Lexicon* entries arrive on the desk.
3. **Shift** (timed, clock on the wall) — repeat the document loop below.
4. **Interruptions** — phone calls, manager visits, coffee lady, colleagues.
5. **End of day** — performance report (WPM, accuracy, processed count, citations) and salary.
6. **Evening** — spend salary: rent, heat, food, family/obligations. Run out of money → lose condition.

### Document loop (the core 30–90 seconds) **[Proposed]**

1. **Receive** the hand-written source document.
2. **Read & check** it against today's Directives and the Lexicon.
3. **Highlight** passages (discrepancy / sensitive / evidence).
4. **Mark omissions** — struck passages must *not* be typed.
5. **Type** the official version into the terminal, applying Lexicon substitutions on the fly.
6. **File** it: Approve · Classify (tier) · Archive · Incinerate.
7. **Instant feedback** (bell / buzzer), mistakes become citations at end of day.

Key design point: **typing is the commit.** In *Papers, Please* the stamp is the decision; here the decision is what the player chooses to type, what they skip, and which words they replace.

## Mechanics

- **Type** — transcribe the document. Scored on WPM and accuracy *against the rules* (typing the original word where the Lexicon demands a substitution counts as an error).
- **Highlight** — mark passages. Correct highlights earn accuracy; the Ministry checks what you highlighted.
- **Omit** — strike passages from the record. Omitted text is skipped while typing.
- **Classify** — assign a secrecy tier / category (classified, propaganda, public, etc.).
- **Rules** — daily *Directives* (what to omit/flag) and the *Lexicon* (word substitutions), in a rulebook on the desk, growing over time.
- **Coffee** — **[Proposed]** stamina/focus resource: typing accuracy or speed decays late in the shift; coffee restores it but costs time and money. The coffee lady is also a character (see endings).
- **Phone** — manager calls (offkey ring, see [[Sound]]) with urgent rule changes mid-shift; informants; family.
- **[Proposed] Revisions** — from Act III, documents the player typed on earlier days come back to be rewritten. The player's own past work is the evidence of the lie.
- **[Proposed] Pocket / Keep** — the player can secretly keep a copy of evidence instead of incinerating it. Risky (random desk inspections), and it feeds the espionage/leak endings.
- **[Proposed] Dictation** — Act IV: no source document; the manager dictates over the phone and the player types a fabrication.

## Objectives

- Ministry objective (visible): hit quota, keep accuracy, climb the hierarchy.
- Personal objective (visible): pay for rent/heat/food.
- Conscience objective (hidden, never scored on screen): what happened to the truth.

## Win Conditions

- become head of Bureau of Information(?)
- succeed in an act of espionage(?)
- **[Proposed]** successfully leak the kept evidence

## Lose Conditions

- run out of money(?)
- get caught during espionage(?)
- **[Proposed]** too many citations → reassignment / "re-education"
- **[Proposed]** kept evidence found during a desk inspection

## Types of Documents

Moved to [[Documents]].

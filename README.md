# The Relative Numbering System

A chord-numbering convention for charts. Numbers tell you where a root sits in the key signature. Suffixes tell you what kind of chord is built on it. When a chord has a function, the notation says so. When it doesn't, the notation doesn't invent one.

---

## Core principle

**1 is the relative major.**

The number tells you where a root sits in the parent scale, the key signature. It does not tell you where the tonal center is. A Dorian tune sits on 2-. An Aeolian tune sits on 6-. The chords say where home is. The numbers say what scale everything is drawn from.

This is the one place the system departs from standard Nashville numbering, which puts 1 on the tonic no matter the mode.

The key gets called, or written at the top of the chart, and the numbers read against it. Nobody has to work out the parent scale from the chords, so a tune whose key signature would otherwise be arguable isn't a problem.

---

## Notation

### Quality

| Mark | Meaning | Example |
|---|---|---|
| bare number | major triad | `4` |
| `-` on the baseline | minor | `4-` |
| `°` | diminished | `♯1°` |
| `ø` | half-diminished | `2ø⁷` |
| `+` | augmented | `♭6+` |
| `Δ⁷` | major seventh, and major quality under any higher extension | `1Δ⁷`, `1Δ⁹` |
| `sus2`, `sus4` | suspended — the third is replaced | `5sus4` |

`ø` never appears without a seventh. Half-diminished names a seventh chord, a diminished triad carrying a ♭7, so a bare `ø` would have nothing to mean.

That leaves `°` doing double duty. Bare `°` is the diminished triad, `°⁷` the fully diminished seventh.

The digit in `sus2` and `sus4` belongs to the quality mark, not to the extensions, so it stays on the baseline. A seventh added to a suspended chord is superscripted as usual: `5sus4⁷`.

Quality marks sit on the baseline. Only extensions are raised. Never superscript the minus sign. Raised, `4-⁷` reads as a 4 chord carrying a minor 7th. `ø` follows the same rule, because a shrunk ø loses its slash and turns into a small circle.

### Extensions

Superscript. Stack after the quality mark.

    4-⁷     minor seventh on 4
    4-⁶     minor sixth on 4
    ♭7⁷     dominant seventh on ♭7
    2-⁹     minor ninth on 2
    1Δ⁷     major seventh on 1

A bare superscript 7 is always a dominant seventh. A major seventh takes the delta, so `1⁷` and `1Δ⁷` are different chords and you don't need context to read either one. The delta sits on the baseline with the other quality marks.

### Accidentals

Real symbols: `♭` and `♯`, not `b` and `#`. They attach to the number, raising or lowering the root relative to the parent scale.

    ♭6      root a half step below the 6 of the key signature
    ♯1°⁷    diminished seventh on the raised 1

---

## Secondary function

Chords borrowed from a target's key go in parentheses. The target follows the closing parenthesis. Everything inside the parentheses reads relative to the target, not to the parent scale.

    (2- 5)4        major two-five of 4
    (2ø⁷ 5)♭6-     minor two-five of ♭6-
    (2- 5)6-       major two-five of 6-
    (♭2⁷)4         tritone substitution resolving to 4

Parentheses are the general mark for target-relative material, not a two-five mark. A single chord takes them too, like the tritone sub above.

The chords inside the parentheses don't have to agree with the target's mode. `(2- 5)6-` and `(2ø⁷ 5)6-` land on the same chord. The first approaches it with a major two-five, the second with a minor two-five. The notation records what was played.

---

## Slash chords

An inversion or a chord over a foreign bass takes a slash. Chord on the left, bass note on the right, and both read against the parent scale.

    4/5        A/B in E major
    1/3        first inversion of the 1 chord
    4-⁷/♭7     minor seventh on 4 over a flatted seventh in the bass

Extensions belong to the chord and stay left of the slash. The bass note takes an accidental when it falls outside the parent scale, the same as a root does.

Nothing else in the system uses a slash, so there's no collision with the other marks.

---

## Modulation

A new key is declared by the new 1 chord followed by a colon. Everything after it reads against the new parent scale until the next declaration.

Bold the declaration so it's findable on a fast read.

    4:      modulation to the 4 of the home key
    F:      modulation to F

Set in a chart, the declaration is bolded: **4:**

Number or letter is a deliberate choice:

- A number keeps the chart transposable end to end. The modulation stays relative, so the whole chart still moves as a unit.
- A letter pins the key. Use it when the key is fixed for a reason: a horn part, an open tuning, a recording being matched.

Every declaration reads against the home key, not against whichever key the chart is currently in. A tune in E♭ that moves to D♭ and returns is written:

    1:   ♭7:   1:

bolded in a chart as **1:**  **♭7:**  **1:**  Not `1: ♭7: 2:`. Chaining each declaration to the one before it hides the return. `2:` doesn't say you're home, and a reader would have to work out ♭7 of E♭, then 2 of D♭, and notice they're the same pitch. Anchoring to the home key makes the return visible as itself.

Chained declarations also accumulate error. Each one depends on correctly parsing all the ones before it, so a single misread propagates to the end of the chart. Anchored declarations are independent, and a misread stays local.

This assumes a home key, which is what the called key at the top of the chart gives you. A tune that modulates progressively and never returns has no natural anchor. There, take the opening key as home by convention, or use letters.

Parentheses and the bold colon do different jobs. Parentheses are for tonicization that resolves back. The colon is for a key change that sticks.

---

## Optional marks

Underline the tonal center when it needs to be visible: a mode shift with no key change, or a vamp that could plausibly sit on either of two centers.

This adds no harmonic information. The chords already say where the center is. It's a reading aid, not part of the grammar, and it can be left off entirely.

---

## Worked cases

### Modal vamp

    2-⁷  5-⁷        Dorian, both chords minor
    2-  5⁷          Dorian, dominant on 5

One key signature covers the vamp either way. The second is the more common shape. The dominant quality on 5 tells you Mixolydian is in play over that chord, and the 2- roots it. Nothing needs translating.

The first is the more ambiguous sound. Two minor sevenths a fourth apart don't commit to a mode until the melody supplies a natural or flatted third above the 5 chord.

### Blues

Blues in G, one flat.

    1⁷  4⁷  5⁷

Three dominant sevenths. The numbers place the roots in the key signature. The suffixes say what's built on them. Nothing in the notation claims these chords resolve, because they don't.

Someone will object that writing the tonic as 1 concedes functional harmony. It doesn't. In this system 1 is a position in the key signature, and the fact that it lands on the tonal center in blues is a coincidence of the genre, not a claim by the notation. Roman numerals can't write this progression without treating I⁷ as an exception. This system writes it without one.

### Minor 4 in major

The borrowed-minor color. The ♭6 is the whole payload.

    4  4-  1       major then minor: 6 drops to ♭6 drops to 5
    ♭6  4-  1      two borrowed chords stacked
    4-⁶            added sixth, most ambiguous
    ♭7⁷  1         the backdoor, close cousin, same ♭6 pull

### Minor-key tune

Minor-key tune

An Aeolian tune sits on 6-. Two different dominant-quality chords show up in minor tunes, and the number tells you which one you have.
    6-  4  5⁷  6-       diatonic — the 5 of the parent scale
    6-  2-  3⁷  6-      harmonic minor — the raised seventh

Both carry a bare superscript 7, so both are dominant quality. They are not the same chord. 5⁷ is diatonic to the parent and does not cadence to 6-; it pulls toward 1 or steps down to ♭7. 3⁷ is the chord that resolves to 6-, and it is non-diatonic — the raised seventh of the minor scale lives inside it, which is what makes it dominant instead of minor.

Tonic-first numbering calls both of these the 5 chord, since the second one sits a fifth above the tonal center. One symbol, two chords, and context has to sort it out. Anchoring to the parent scale gives them different numbers, and the non-diatonic one is marked as non-diatonic by the number itself.

### Passing diminished

A chord with no target takes no parentheses. Accidental on the number, quality in the suffix, plainly written.

    1  ♯1°⁷  2-  5⁷

The `♯1°⁷` walks the bass upward. It doesn't tonicize the 2-, so there's no target to name.

### Chromatic approach to 5

Two chords taught as separate things, in C:

- The German augmented sixth: A♭ C E♭ F♯, resolving to G
- The tritone substitution aimed at 5: A♭ C E♭ G♭, resolving to G

Same pitches. Same resolution. They differ in spelling and in which theoretical tradition names them, not in sound.

Both are written:

    (♭2⁷)5

The parentheses read against the target, so ♭2 is a half step above 5 rather than a half step above the home key. That's what collapses the two labels into one chord. The notation describes the approach, and the approach is the same one.

The distinction the labels preserve is a voice-leading one. An augmented sixth expands outward to an octave, a minor seventh contracts inward. That matters for a written part, where the spelling instructs the player. It doesn't matter on a chart, which is telling someone what to play.

---

## Trade-offs

The tonic isn't always 1. In an Aeolian tune it's 6-. That's readable from the chords, but a reader trained tonic-first will find it costly, and that's a fair reaction rather than a failure to understand.

Parent-scale anchoring does less work in heavily chromatic music. The colon declaration handles real modulation and the parentheses handle tonicization, but a tune that never settles into a key signature is getting less out of a key-signature-based system.

It isn't standard. Anyone reading cold will assume 1 is the tonic. A chart handed to someone else needs a note at the top.

Readers trained tonic-first hit a conversion. Scale-degree systems that fix 1 on the tonic, and minor solfège that places do on the tonic, both put the number a reader sees at an offset from the degree they hear. That's a real cost for those readers.

Worth being precise about the size of that cost, though, because it's a conflict with particular training traditions and not with ear training itself. La-based minor already anchors where this system does. Do sits on the relative major, an Aeolian tune begins on la, a Dorian tune on re. It's the older practice. The minor scale was traditionally sung from la, and that's what Glover and Curwen built tonic sol-fa on in the nineteenth century, with scattered French sources a century or more earlier. Putting do on the tonic in minor came later.

So the conflict is with do-based minor and with scale-degree systems that fix 1 on the tonic. Both are movable-do descendants and both are widely taught, so this isn't a small group. But a reader trained on la-based minor is already singing what this notation writes, and converts nothing.

The system is built for modal and diatonic material. That's what it's good at.

---

## Transposition

The chart transposes whole, and it keeps transposing through the material that normally breaks a number chart.

A modulation written as a bold number-colon stays relative, so the key change moves with everything else instead of pinning the chart to a pitch. A parenthetical reads against its own target rather than against a fixed key. Nothing commits to a letter name unless the letter is chosen deliberately, and that choice is confined to the one place it's made.

---

## Error visibility

The parent-scale anchor makes non-diatonic material visible on sight. A number outside the stated key reads as outside the key. Quality carried in the suffix works the same way, because 5 is dominant and a `5-` is legible as borrowed the moment it's written.

What the numbers preserve is the difference between outside the key and wrong. A borrowed chord isn't an error. It's usually the point. But it isn't diatonic either, and the notation says which without being asked.

Prose collapses that difference. A description of harmony can be well formed and still be mistaken about what belongs to a key, and nothing in its shape tells you which. Written as numbers, the same claim either fits the stated key or it doesn't.

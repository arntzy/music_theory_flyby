Q: What is a scale? 
A: A set of notes.

Unicode Musical Symbols: (ctrl+shift+u+{code}) `♭:U266D, ♮:U266E, ♯:U266F`

## MAJOR SCALES

- C Major Scale: `['C','D','E','F','G','A','B']` 
- D Major Scale: `['D,'E','F#','G','A','B','C#']`
- Whole and Half Steps: `['W','W','H','W','W','W','H']`
- Major Scale by Scale Degree: `['1', '2', '3', '4', '5', '6', '7']`
- Major Scale by Chromatic Scale Degree (CSD) (1-12): `[1, 3, 5, 6, 8, 10, 12]`


## MINOR SCALES

Minor scales can be built from a Major Scale.

### Natural Minor

- C Natural Minor: `['C', 'D', 'Eb', 'F', 'G', 'Ab', 'Bb']`
- 'b' is pronounced 'flat', and means subtract one from the chromatic degree of the note
- Natural Minor by Scale Degree: `['1', '2', 'b3', '4', '5', 'b6', 'b7']`
- To make the Natural Minor, flat the third, sixth, and seventh of a Major Scale: 
  - string representation: `['b3', 'b6', 'b7']`
  - transformational array: `[0, 0, -1, 0, 0, -1, -1]`
- Natural Minor by CSD: `[1, 3, 4, 6, 8, 9, 11]` 

### Harmonic Minor

- C Harmonic Minor: `['C', 'D', 'Eb', 'F', 'G', 'Ab', 'B']`
- Harmonic Minor by Scale Degree: `['1', '2', 'b3', '4', '5', 'b6', '7']`
- To make the Harmonic Minor, flat the third and sixth of a Major Scale: 
  - string representation: `['b3', 'b6']`
  - transformational array: `[0, 0, -1, 0, 0, -1, 0]`
- Harmonic Minor by CSD: `[1, 3, 4, 6, 8, 9, 12]` 

### Melodic Minor

- C Melodic Minor: `['C', 'D', 'Eb', 'F', 'G', 'A', 'B']`
- Melodic Minor by Scale Degree: `['1', '2', 'b3', '4', '5', '6', '7']`
- To make the Melodic Minor, flat the third of a Major Scale: 
  - string representation: `['b3']`
  - transformational array: `[0, 0, -1, 0, 0, 0, 0]`
- Melodic Minor by CSD: `[1, 3, 4, 6, 8, 10, 12]`
- D Melodic Minor: `['D', 'E', 'F', 'G', 'A', 'B', 'C#']`


## MODES

Modes are simply scales starting on a different degree of a parent scale. 

MODES OF THE C MAJOR SCALE: (note: you could apply these modes to ANY major scale)

- **Ionian(Major Scale)**: C Ionian: `['C', 'D', 'E', 'F', 'G', 'A', 'B']`

- **Dorian**: D Dorian : `['D', 'E', 'F', 'G', 'A', 'B', 'C']`
  - `['b3', 'b7']`
  - Transformational Array (applied to major scale): `[0, 0, -1, 0, 0, 0, -1]`
  - Dorian by CSD: `[1, 3, 4, 6, 8, 10, 11]` 

- **Phrygian**: E Phrygian: `['E', 'F', 'G', 'A', 'B', 'C', 'D']`
  - `['b2', 'b3', 'b6', 'b7']`
  - Transformational Array (applied to major scale): `[0, -1, -1, 0, 0, -1, -1]`
  - Phrygian by CSD: `[1, 2, 4, 6, 8, 9, 11]`  

- **Lydian**: F Lydian: `['F', 'G', 'A', 'B', 'C', 'D', 'E']`
  - `[#4]`
  - Transformational Array (applied to major scale): `[0, 0, 0, 1, 0, 0, 0]`
  - Lydian by CSD: `[1, 3, 5, 7, 8, 10, 12]`

- **Mixolydian**: G Mixolydian: `['G', 'A', 'B', 'C', 'D', 'E', 'F']`
  - `['b7']`
  - Transformational Array (applied to major scale): `[0, 0, 0, 0, 0, 0, -1]`
  - Mixolydian by CSD: `[1, 3, 5, 6, 8, 10, 11]`

- **Aeolian**(Natural Minor): A Aeolian:` ['A', 'B', 'C', 'D', 'E', 'F', 'G']`
  - `['b3', 'b6', 'b7']`
  - Transformational Array (applied to major scale): `[0, 0, -1, 0, 0, -1, -1]`
  - Aeolian by CSD: `[1, 3, 4, 6, 8, 9, 11]`

- **Locrian**: B Locrian: `['B', 'C', 'D', 'E', 'F', 'G', 'A']`
  - `['b2', 'b3', 'b5', 'b6', 'b7']`
  - Transformational Array (applied to major scale): `[0, -1, -1, 0, -1, -1, -1]`
  - Locrian by CSD: `[1, 2, 4, 6, 7, 9, 11]`


- I	Ionian mode	C D E F G A B C	(associated with C Major 7 chord)
- ii	Dorian mode	C D E♭ F G A B♭ C	(associated with C-6 or C-7 13 chord)
- iii	Phrygian mode	C D♭ E♭ F G A♭ B♭ C	(associated with Csus4 ♭9)
- IV	Lydian mode	C D E F♯ G A B C	(associated with C Maj7 ♯11 chord)
- V	Mixolydian mode	C D E F G A B♭ C	(associated with C7 chord)
- vi	Aeolian mode	C D E♭ F G A♭ B♭ C	(associated with C-7 ♭13 chord)
- viiø	Locrian mode	C D♭ E♭ F G♭ A♭ B♭ C	(associated with C-7♭5 chord)

### MODES OF THE MELODIC MINOR

Let's build these together:

**i melodic minor**
- `['C', 'D', 'Eb', 'F', 'G', 'A', 'B']`: C Melodic Minor

**ii Dorian ♭2, or Phrygian ♮6**
- `['D', 'E', 'F#', 'G', 'A', 'B', 'C#']` : D major scale
- `['D', 'Eb', 'F', 'G', 'A', 'B', 'C']` : D Dorian b2  or the 2nd mode of the C Melodic Minor scale

**III Lydian augmented**
- `['Eb', 'F', 'G', 'Ab', 'Bb', 'C', 'D']` : Eb major scale
- `['Eb', 'F', 'G', 'A', 'B', 'C', 'D']` : Eb Lydian Augmented, or the 3rd mode of the C Melodic Minor Scale

You build the rest:

- **IV Lydian dominant**
- **V Mixolydian ♭6**
- **vi Locrian ♮2, or Half-diminished**
- **VII Super Locrian, or altered scale**

Octatonic/Symmetric Diminished Scales:

half-whole:
- `['C', 'Db', 'Eb', 'E', 'F#', 'G', 'A', 'Bb']`
- `['H', 'W', 'H', 'W', 'H', 'W', 'H', 'W']`


whole-half:
- `['C', 'D', 'Eb', 'F', 'Gb', 'Ab', 'A', 'B']`
- `[ 'W', 'H',  'W', 'H',  'W',  'H', 'W', 'H' ]`


## BUILDING CHORDS

You can build triads by taking the [1st,3rd,5th] from a scale. (these are indexes, not the state of the degrees!)

For example:

D Major Scale: `[D, E, F#, G, A, B, C#, D]`

D Major Triad: `[D, F#, A]`

You can build seventh chords by taking the `[1st,3rd,5th,7th]` from a scale. 

You can build whatever you want. 

Inversions are simply chords with the notes in a different order. 

Extensions(i.e. 9th, 11th, 13th) are referred to after a seventh is present in a chord.  

9th = 2nd
11th = 4th
13th = 6th


### THE CONFUSION AROUND NAMING THE CHORDS

1. A "major seven chord" means that the seventh of that chord's root's major scale is in it's unaltered or natural state. (meaning not flat) It is written like this Cmaj7, CMA7, and pronounced, "C major seven"

2. A "dominant chord" means that the seventh of that chord's root's major scale is flat. It is written like this: C7 and is pronounced "C seven"

3. A "minor seven" chord means that the third and seventh are flat: Cm7, C-7, Cmi7, "C minor seven"

4. An "augmented chord" means the fifth is sharp: C(#5), or C+

5. a "diminished triad" means the 3rd and 5th are flat. and is written Cdim.

6. A "half-dimished chord" is a seventh chord with a minor triad and a flat seven: Cm7(b5), pronounced "C half-diminished", or "C minor seven flat five"

7. A "fully dimished chord" is a seventh chord where the 3rd and 5th are flat, and the 7th is DOUBLE FLAT!, written with a little circle next to the Co7, (no slash through the circle, that's half-dimished) and is pronounced "C dimished seven", or "C fully diminished"  

8. All the above rules apply to extensions and alterations. (e.g. Cmaj9(#5) would be said "C major nine sharp 5") C13-- "C thirteen", but remember there is a b7(flat7 not B7) below that 13!

- F# Major Scale: `[F#, G#, A#, B, C#, D#, E#, F#]`

- F#maj7: `[F#, A#, C#, E#]`

- F#7: `[F#, A#, C#, E]`

- F#m7: `[F#, A, C#, E]`


### CHORD ANALYSIS

1. Look for a triad. Is it major or minor? Is the fifth altered in some way? 
2. What about the seventh? Has it been changed?
3. Look for additional notes. 
4. What is this chord? 

- C9: `[C, E, G, Bb, D]`

- Cmaj9: `[C, E, G, B, D]`

- Em7(b5): `[E, G, Bb, D]`

- Gm6: `[G, Bb, D, E]`

- C9 (rootless voicing) : `[E, G, Bb, D]`

#### JAZZ LINGO 

"good ears"

"voicings"-- the way you choose to play the notes of a chord.

"let's play this in two flats"-- refers to the major/minor scale which has two flatted notes. Which one is that? 

"Diatonic"

"Chromatic"

"Pentatonic"

"Blues Scale"

# NOW PRACTICE!!!!












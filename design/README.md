# Emblem

A coaching app for a personal trainer in England and her clients. Clients add it to their phone home screen to follow and log workouts. The trainer builds programmes, keeps an exercise library with videos and tracks every client from a laptop or tablet. It should feel easy, rewarding and vibrant: closer to a bright training shoe than a black-and-grey performance brand.

## Key points, most important first

1. **[The full screen set is built](#full-screen-set)** in Direction B with Ro: 9 client screens, 6 trainer screens, the celebration system and every chart at two sizes.
2. **[Direction B and Ro are chosen](#step-1-decisions).** Fraunces headings and wordmark, Manrope numbers and body, and Ro the rosette as the mascot.
3. **[Pink and red together is the signature](#colour).** Cherry Cola for all text on light grounds, Hibiscus Tonic as the main surface, Maraschino red for the one main action and for celebrations. Every text pairing below passes WCAG AA.
4. **[Celebration scales with the win](#celebration).** A logged set gets a tick, a finished session gets the mascot cheer and confetti, a personal best takes over the whole screen and ends with a shareable card.
5. **[Logging forgives](#logging-rules).** Every field arrives pre-filled from the plan; one 64px "Done as written" tap logs a set as planned.
6. **[Trainer screens stay calm](#trainer-side).** Data first, small flourishes only, the mascot lives on the client side.
7. **[Every brand choice is a token](#re-branding-for-a-gym).** Colour, type, wordmark and mascot all swap, so a gym can put its own brand on it later.
8. **[Phase 2 gaps stay marked](#phase-2).** Onboarding questionnaire and payments.

## Full screen set

Everything below is in Direction B with Ro. Each card in the Components tab runs: buttons log sets, timers count, blocks drag and celebrations play, with a reduced-motion switch where there is motion.

| Area | Screen | Component |
| --- | --- | --- |
| Client | Today, plus welcome back after a gap | `Today` |
| Client | Workout in progress (Progress and Notes open as sheets) | `WorkoutInProgress` |
| Client | Swap sheet | `SwapSheet` |
| Client | Timer: rest, stopwatch, intervals | `Timer` |
| Client | Session complete | `SessionComplete` |
| Client | Personal best and the PB card | `PersonalBest`, `PBCard` |
| Client | Milestone unlock and the milestone track | `MilestoneUnlock` |
| Client | History and stats | `HistoryStats` |
| Client | Exercise detail | `ExerciseDetail` |
| Client | Trainer high five, as the client sees it | `HighFiveReceived` |
| Celebrations | Ro's five states, 9 variations, 2 rare extras | `Celebrations` |
| Trainer | Client list | `ClientList` |
| Trainer | Client profile with high fives | `TrainerClientProfile` |
| Trainer | Programme builder | `ProgrammeBuilder` |
| Trainer | Exercise library with Change video | `ExerciseLibrary` |
| Trainer | In-session logging on a tablet | `TrainerLogging` |
| Trainer | Printable session sheet | `SessionSheet` |
| Charts | All four charts at phone and laptop size | `ChartSizes` |

**Milestones:** 1st session unlocks Ro's party hat, 10th the sweatband, 25th the shades, 100th the crown. A full week unlocks the Week wiggle, the end of a block the Victory lap and the 50th session the Stomp.

**Rotation:** session complete picks one of 9 variations and skips any shown in the last 4 sessions. About 1 session in 10 ends with a rare extra the client is seeing for the first time (Backflip, Skate by).

## Step 1 decisions

Chosen on 14 Nov 2026: **Direction B** for type and **Ro** for the mascot. Ro was then redrawn at double resolution (44 × 44 pixels, drawn at the same size) with a wider, clearer smile, white mittens and a simpler 12-scallop edge. A second pass took out the machine-made look: a hand-drawn face (happy closed eyes when she cheers), light from the top left with a 1-pixel rim and shade, fold lines on her ribbons, and ribbons of different lengths so she isn't a perfect mirror image.

The four Step 1 screens still show Direction A beside B as the record of that comparison. Everything else is B only.

| Screen | Component |
| --- | --- |
| Client phone: workout in progress | `WorkoutInProgress` (tap **Done as written** to log a set and start the rest timer) |
| Client phone: session complete | `SessionComplete` |
| Client phone: personal best moment | `PersonalBest` |
| Shareable PB card, 1080 × 1350 | `PBCard` |
| Trainer laptop: client profile | `TrainerClientProfile` (tap **High five** on a session) |
| The two wordmarks | `Wordmark` |
| The three mascots | `MascotConcepts` |

**Direction A** sets headings and big numbers in Archivo Expanded (Archivo at `font-stretch: 125%`, weights 800 and 900). It is loud and sporty; numbers read from across the room. Fraunces appears only in the wordmark.

**Direction B** sets headings and the wordmark in Fraunces with its SOFT axis at 100, and numbers and body in Manrope with tabular figures. It is warmer and more editorial; the numbers are quieter than in A.

**Mascots**, all original pixel sprites in the brand palette:

- **Ro (chosen)**, a prize rosette who came to life. She is the reward itself, and the closest fit to the name Emblem. 44 × 44 pixels.
- **Bell**, a kettlebell with a soft face. Says training at a glance. 22 × 22, parked.
- **Pip**, a cherry in a sweatband, picked from the Cherry Cola palette. The most playful. 22 × 22, parked.

Names in the screens (Priya Shah, Hannah Cole) and every number are placeholders.

## Colour

| Token | Hex | Job |
| --- | --- | --- |
| `cherry-cola` | #7C0116 | All text and numbers on light grounds; mascot outline |
| `hibiscus-tonic` | #E0A4B0 | Main surface: celebration screens, highlights |
| `maraschino` | #DD1A2A | The one main action per screen; PB markers; confetti |
| `oat-milk` | #FBF3EC | Logging screens and the trainer workspace, so numbers stay readable mid-set |
| `cherry-900` | #4A000C | Hard shadow under the main button; chips on the PB screen |
| `hibiscus-50` | #F6DDE2 | Quiet tint: chart fills, selected rows |
| `ink-muted` | #8A4A55 | Secondary text on oat-milk and white only |

Text pairings and their contrast:

| Text on ground | Ratio | Use |
| --- | --- | --- |
| cherry-cola on oat-milk | 10.3:1 | Logging screens |
| cherry-cola on hibiscus-tonic | 5.4:1 | Celebration screens |
| white on maraschino | 4.9:1 | Main button |
| oat-milk on cherry-cola | 10.3:1 | PB screen |
| hibiscus-tonic on cherry-cola | 5.4:1 | PB screen supporting text |
| ink-muted on oat-milk | 6.1:1 | Supporting lines |

Two pairings to avoid: maraschino text on hibiscus-tonic (2.4:1) and ink-muted on hibiscus-tonic (3.2:1). On pink, all text is cherry-cola.

## Type

Fonts come from Google Fonts: Archivo (with its width axis), Fraunces (with SOFT, WONK and optical size) and Manrope. The `.dir-a` and `.dir-b` blocks at the top of `components/bundle.css` hold each direction's font settings as custom properties; swapping a direction means changing those two blocks.

Headlines stand alone: the headline comes first and any supporting line sits beneath it. Every section opens on its headline.

## Celebration

| Win | What happens | Reduced motion |
| --- | --- | --- |
| A logged set | The tick pops in (0.4 s) | The tick appears |
| A finished session | Mascot cheers for 3 seconds, pixel confetti bursts from behind it, then the mascot settles into idle | Still cheer pose, still confetti scattered at the edges |
| A personal best | Full cherry screen, mascot jumps on a pink spotlight, two waves of confetti, blinking pixel stars, then the shareable PB card | Still pose, still confetti, no blinking |

Confetti is pixel squares and plus shapes in the brand colours, so it matches the 8-bit mascot. The mascot's other states, built for every concept: idle, cheer, welcome back (a wave, after a gap) and high five (sent by the trainer).

Microcopy celebrates effort and consistency in plain words: "Session done.", "That's 3 this week.", "Up 2.5 kg on your best from 3 Oct", "3rd PB this block".

## Logging rules

- Sets arrive pre-filled from the plan. "Done as written" logs the set exactly as planned; the steppers beside it change reps or load first if needed.
- Last session's numbers sit beside today's on every field.
- A rest countdown starts on its own after each set, with "I'm ready" to skip it.
- Tap targets are 48px or larger (`tap-min`); the main action on workout screens is 64px tall (`tap-main`) and sits in the bottom half for one-handed use.
- A partial session still counts and still celebrates.

## Trainer side

Oat-milk ground, white cards, cherry text, one red button. The mascot stays off these screens; the flourishes are the block ring, block-style bar charts and the diamond PB markers. Charts are sized to their cards so axis labels stay at 14px.

## Re-branding for a gym

- **Colour:** every colour in every preview, the charts and the mascot reads from the colour tokens.
- **Type:** the `.dir-a` / `.dir-b` blocks in `bundle.css`.
- **Wordmark:** the `.wordmark` styles in `bundle.css`.
- **Mascot:** the sprite grids in `components/bundle.js` (`Emblem.sprites`). Each pixel letter maps to a colour token, so a re-colour follows the palette. Grids of any size draw at the same on-screen size: `px` always means one pixel of a 22-pixel grid. Ro's outfits live in `Emblem.sprites.ro.outfits` as full frames, so a gym's own mascot can ship its own wardrobe.

## Phase 2

- **[PHASE 2] Onboarding questionnaire.** Questions to come from the trainer. Marked on Add a client in `ClientList`.
- **[PHASE 2] Payments and checkout.**

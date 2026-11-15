# [EMBLEM] Design + Claude Code prompts, v1

Written Nov 14, 2026 from the grill with Orlando and Emma. Updated the same day with charts, the pixel mascot, confetti, and surprise and delight.

## Key points, ranked

1. **Version 1 is three things:** exercise library with swappable videos, programme builder, client logging with timer and history. [Scope](#scope)
2. **Logging is forgiving and positive, and wins get celebrated** with a pixel mascot, confetti, surprises and real progress charts. This is Emblem's edge over FitPros. [Product rules](#product-rules)
3. **Two prompts, ready to paste:** [Claude Design prompt](#prompt-1-claude-design) and [Claude Code prompt](#prompt-2-claude-code)
4. **Open flags ⚑** that still need Emma or Orlando. [Flags](#flags)

## Scope

**Version 1**
- Exercise library with YouTube and Vimeo videos the trainer can change in one step
- Programme builder for laptop and tablet
- Client workout logging with set timer, stopwatch and history
- Progress charts and graphs for clients and trainers
- Celebrations: pixel mascot, confetti, milestone surprises, trainer high fives
- Trainer logging on a client's behalf during a session
- Movement swaps with 3 suggestions
- Printable session sheets
- Trainer and client accounts (trainer invites client by email link)

**Phase 2**
- Payments for monthly coaching and one-off programmes (Stripe, GBP)
- Full onboarding questionnaire
- AI and rule-based programme generation
- Metcon and HIIT library
- Gym branding
- App Store and Google Play apps
- Extra timer skins

## Product rules

1. Every logging field arrives pre-filled from the plan. One tap logs "done as written."
2. Every field is optional. A partial session saves quietly as a real session.
3. The app celebrates what got done: sessions completed, personal bests, streaks of showing up.
4. A personal best is the biggest moment in the app.
5. Celebrations rotate and surprise, so wins feel fresh.
6. Progress is visible: real charts and graphs, inside the workout and on the history screens.
7. A trainer can log sets for a client in-session, and the data lands in the client's account.
8. Any session prints as a clean one-page sheet.

## Flags

- ⚑ Client count and prices [VERIFY: Emma]
- ⚑ Onboarding questions from Emma's Jotform [VERIFY: Emma to share the form]
- ⚑ hyrox-lab repo unread; stack below is Claude's pick [VERIFY: Orlando to confirm stack or share repo]
- ⚑ Deadline: none set
- ⚑ Client health data: consent at sign-up, access limited to client and their trainer. A UK privacy professional confirms this before real clients join.
- ⚑ Type direction: Emma is open-minded, so the design prompt asks for 2 directions
- ⚑ Payment provider: Stripe is Claude's pick; Emma also holds a GoCardless account
- ⚑ Mascot: character concept and name are open; the design prompt asks for 3 concepts for Emma to choose from
- ⚑ Surprise and delight list (variations, milestones, rare extras, high fives) is Claude's pick, awaiting Orlando and Emma's edit

---

## Prompt 1: Claude Design

```
Design Emblem, a coaching app for a personal trainer in England and her clients.

WHAT IT IS
A web app clients add to their phone home screen, plus a laptop and tablet workspace for the trainer. Clients follow and log their workouts. The trainer builds programmes, manages an exercise library with videos, and tracks each client's progress.

AUDIENCE
Elder millennials, largely women. The look is confident and gender-neutral: bold colour and strong type carry the personality.

FEEL
Three words: easy, rewarding, vibrant.
Reference: RAD (the training shoe brand) for playful, bold colour.
Stay far from: Under Armour's black-and-grey performance aggression.

COLOUR
- Cherry Cola #7C0116 (primary, text on light surfaces)
- Hibiscus Tonic #E0A4B0 (primary surface, cards, highlights)
- A bright red accent for the main action and celebration moments
- A warm off-white for logging screens, so numbers stay readable mid-set
Pink and red together is the signature. Body text and numbers meet WCAG AA contrast.

TYPE: SHOW 2 DIRECTIONS
Direction A: heavy, wide sans for headings and big numbers; soft retro serif for the Emblem wordmark only.
Direction B: soft retro serif for headings and wordmark; clean sans for numbers and body.
Create a simple Emblem wordmark for each direction.

CELEBRATION SYSTEM
- An original pixel-art mascot (8-bit sprite style) who celebrates wins. Show 3 distinct character concepts in the pink and red palette. The character is an original invention for Emblem.
- Animation states for the chosen character: idle, cheer (session complete), big celebration (personal best), encouraging wave (welcome back after a gap), high five (sent by the trainer).
- Confetti in the brand colours on session complete and personal bests.
- Scale the celebration to the win: a logged set gets a small tick animation, a finished session gets the mascot cheer, a personal best gets the full treatment below.
- Graphical flourishes around progress: block progress rings, streak markers, personal-best badges.
- The mascot lives on the client side. Trainer screens stay calm and data-first, with small flourishes only.
- Include a reduced-motion version of each celebration.

SURPRISE AND DELIGHT
- Personal best: the biggest moment in the app. Full-screen mascot celebration, confetti, and a shareable PB card showing the lift, the number and the date. Design the PB card at 1080×1350 for Instagram.
- Variety: design 8 to 10 celebration variations (mascot dances, confetti styles, one-line cheers) that rotate so wins feel fresh.
- Milestones: 1st session, 10th, 25th, 50th, 100th, end of a block, and a full week completed. Each unlocks a new mascot animation or outfit. Show 4 outfit examples.
- Rare extras: about 1 session in 10 ends with a bonus animation the client is seeing for the first time. Show 2 examples.
- Trainer high five: the trainer taps once on any logged session, and the client sees a mascot high-five moment next time they open the app.

CHARTS AND GRAPHS
- Per-exercise progress line chart (load, reps or time over sessions)
- Weekly sessions bar chart
- Block progress ring (sessions done and remaining)
- Personal-best timeline
Style the charts in the brand palette with large, readable labels. Show each chart at phone size and at laptop size.

STEP 1: show both type directions on these 4 screens, plus the 3 mascot concepts
1. Client phone: workout in progress
2. Client phone: session complete (with mascot and confetti)
3. Client phone: personal best moment
4. Trainer laptop: client profile (with charts)
Stop there for feedback. After a direction and a mascot are chosen, design the full set.

FULL SCREEN SET

Client, phone first (also works on tablet):
- Today: the next session, block progress ring, one clear Start button
- Workout in progress: one exercise at a time, video thumbnail, sets pre-filled from the plan, a large "Done as written" tap per set, editable reps / load / time, a built-in set timer and rest timer, last session's numbers shown beside today's, a small progress chart for that exercise one tap away, a Swap button, a notes field
- Swap sheet: 3 suggested alternatives with video thumbnails
- Timer: rest countdown, stopwatch with lap button, simple interval mode; huge digits readable from 2 metres
- Session complete: mascot cheer, confetti, a summary of what got done, personal bests called out, a note to the trainer
- Personal best moment and shareable PB card
- Milestone unlock moment
- History and stats: past sessions, the four charts above, personal-best badges, unlocked mascot outfits
- Exercise detail: video, cues, personal history chart for that movement

Trainer, laptop first (builder also works by touch on a tablet):
- Client list: each client with sessions this week and block progress
- Client profile: sessions completed this week, block progress (done and remaining), latest personal bests, latest client note, a high-five button on each logged session, then charts and full history
- Programme builder: modular blocks, drag to reorder, pick exercises from the library, set reps / sets / load / time / distance / laps / rounds, add notes at programme, session and exercise level, assign to a client. Block types: strength sets, for time, AMRAP, EMOM, intervals
- Exercise library: search and filter by movement pattern, equipment and programme type (strength, cardio, injury prevention, flexibility, core); each exercise shows its video with a one-step "Change video" action that accepts a YouTube or Vimeo link
- In-session logging on phone or tablet: the trainer picks a client and logs their sets for them
- Printable session sheet: one page, black on white, room to write numbers by hand

RULES
- Logging feels forgiving. Every field is optional and pre-filled. Partial sessions look like progress.
- Microcopy is warm and positive. Celebrate effort and consistency.
- Headlines stand alone: place the headline first, with any supporting line beneath it.
- Tap targets are at least 48px. Workout screens work one-handed with sweaty fingers.
- Build colour, type, logo and mascot as swappable tokens, so a gym can apply its own branding later.
- Before presenting, review each screen and ask "does this look like a generic AI-made app?" Fix anything that does.

GAPS, KEEP MARKED
- Onboarding questionnaire: phase 2, questions to come from the trainer
- Payments and checkout: phase 2
```

---

## Prompt 2: Claude Code

```
Build Emblem v1, a coaching web app for a personal trainer in England (Emma) and her clients. Work in milestones and stop for my review at the end of each one.

BEFORE YOU WRITE CODE
1. Read my existing hyrox-lab repo. Reuse its YouTube video component and anything else that fits. Tell me what you plan to reuse.
2. Propose the stack and data model, then wait for my OK. My starting pick: Next.js + TypeScript + Tailwind, Supabase (Postgres, auth, row-level security), deployed on Vercel, installable as a PWA. If hyrox-lab uses a different stack, recommend which to keep and why.
3. If a design export from Claude Design is in the repo, follow it, including the mascot sprite sheet. Otherwise use these tokens as CSS variables: Cherry Cola #7C0116, Hibiscus Tonic #E0A4B0, a bright red accent, a warm off-white surface.

USERS AND ROLES
- Trainer: builds programmes, manages the exercise library, sees and edits their clients' data, logs sessions on a client's behalf.
- Client: sees their assigned programme, logs workouts, swaps movements, views their history.
- Model an Organization above trainers from day 1 (one org for now), with theme tokens stored per org, so more trainers and gym branding can be added later.
- A trainer invites a client by email link. Row-level security: a client reads only their own data; a trainer reads only their own clients.

V1 FEATURES

1. Exercise library
- Fields: name, cues, movement pattern (squat, hinge, push, pull, carry, lunge, core, locomotion, mobility), equipment, programme type tags (strength, cardio, injury prevention, flexibility, core), video URL.
- Video accepts a YouTube or Vimeo link, parsed and embedded. The trainer changes a video in one step from the exercise page, and can override the video for a single programme.
- Seed about 80 common exercises with tags and empty video slots.

2. Programme builder (laptop first, fully usable by touch on a tablet)
- Programme > weeks > sessions > blocks > exercises. Drag to reorder. Duplicate a session or a week.
- Block types: strength sets, for time (chipper), AMRAP, EMOM, intervals.
- Prescription fields, each optional: sets, reps, load (kg default, lb toggle), time, distance, laps, rounds, rest, tempo, RPE.
- Notes at programme, session, block and exercise level.
- Assign a programme to a client with a start date. Save programmes as reusable templates.

3. Client logging
- A session opens with every field pre-filled from the plan. One tap marks a set "done as written." Any value can be edited.
- Every field is optional. Leaving the session at any point saves it as a partial session, with zero warnings or reminders about empty fields.
- Result types per block: reps and load per set, total time (for time), rounds plus reps (AMRAP), laps, distance.
- Show the previous session's numbers for the same exercise inline.
- Session complete screen: positive summary of work done, personal bests detected automatically, optional note to the trainer.
- Works with a weak gym signal: queue writes locally and sync when online.

4. Timers inside the workout
- Rest countdown that starts when a set is logged (length from the prescription, adjustable).
- Stopwatch with lap button for timed pieces; the result writes into the log.
- Simple interval timer (work, rest, rounds) covering Tabata and EMOM.
- Large digits, screen stays awake, audio and vibration cues.

5. Movement swaps
- From any exercise, the client taps Swap and gets 3 suggestions matching movement pattern and available equipment, with trainer-pinned swaps listed first.
- The swap applies to that session, is recorded in the log, and shows on the trainer's view.

6. Trainer logging for a client
- From a client's profile, the trainer opens today's session and logs it on their phone or tablet. The data belongs to the client's account and records who entered it.

7. History, stats and charts
- Charts: per-exercise progress line chart (load, reps or time over sessions), weekly sessions bar chart, block progress ring (done and remaining), personal-best timeline. Use one charting library (Recharts is my pick) themed with the CSS variables.
- Client: past sessions, the four charts, personal-best badges. The per-exercise chart is also reachable inside a live workout.
- Trainer client profile, in this order: sessions completed this week, block progress (done and remaining), latest personal bests, latest client note, then charts and full history.

8. Celebrations
- Pixel mascot rendered from a sprite sheet with CSS steps() animation. States: idle, cheer, big celebration, encouraging wave, high five. Use the sprite sheet from the design export; until it arrives, build with a simple placeholder sprite behind the same component.
- Confetti in brand colours (canvas-confetti is my pick).
- Triggers, scaled to the win: logged set = small tick animation; session complete = mascot cheer; first session back after 7+ days = encouraging wave.
- Honour prefers-reduced-motion with a still version, and add a "Celebrations" on/off toggle in client settings.
- Mascot appears on client screens. Trainer screens show badges and charts only.

9. Surprise and delight
- Personal best: the biggest moment in the app. Detect PBs per exercise (heaviest load at a rep count, most reps at a load, fastest time, most rounds). Trigger a full-screen mascot celebration plus confetti, and generate a shareable PB card image (1080×1350) with the lift, the number and the date, using the Web Share API with a download fallback.
- Variety: a pool of 8 to 10 celebration variations stored as data (animation, confetti style, one-line cheer). Rotate so the same variation never plays twice in a row.
- Milestones: 1st session, 10th, 25th, 50th, 100th, end of a block, and a full week completed. Each unlocks a mascot animation or outfit, saved to the client's account and shown in their history.
- Rare extras: about 1 session in 10 ends with a bonus animation that client has yet to see. Track which ones each client has seen.
- Trainer high five: one tap on any logged session in the trainer view. The client sees the mascot high-five moment the next time they open the app.
- Build celebrations as a small event system (event in, celebration out) so new triggers and animations can be added as data.

10. Print
- Any session prints as a one-page black-on-white sheet with blank boxes for handwritten numbers.

LEAVE CLEAN SEAMS FOR PHASE 2 (do not build yet)
- Stripe payments in GBP: monthly coaching subscriptions and one-off programme purchases
- Full onboarding questionnaire (questions to come from Emma)
- Programme generator: rule-based first, AI-assisted second
- Metcon and HIIT library
- Per-org branding UI, including a swappable mascot
- Native store apps

PRIVACY
- UK users. Keep personal data to the minimum v1 needs: name, email, training logs, notes.
- Health and injury questionnaires arrive in phase 2 with explicit consent; structure the schema so that data sits in its own table with tighter access.
- Add account deletion and data export for clients.
- The PB card shares only when the client chooses to share it.

MILESTONES
1. Stack decision, schema, auth, roles, invite flow
2. Exercise library with video
3. Programme builder and assignment
4. Client logging, timers, offline queue
5. Swaps, trainer logging for client
6. History, charts, trainer client profile, print
7. Celebrations and surprise and delight: mascot, confetti, PB moment and card, milestones, rare extras, high fives
8. PWA install, accessibility pass (WCAG AA, 48px tap targets, reduced motion), seed data, deploy

DONE TEST
Emma builds a 4-week programme on her laptop in under 20 minutes, assigns it to a test client, the client completes and logs a session on a phone with a swap and a timed set, hits a personal best that triggers the full-screen mascot celebration, confetti and a PB card, Emma sees the result and the updated chart on the client profile, and her high five shows up on the client's next open.

WORKING RULES
- Write tests for logging, swaps, personal-best detection, milestone unlocks and permissions.
- Ask me before adding any paid service or changing scope.
- Interface copy is warm, plain and positive: say what something is and what to do next.
```

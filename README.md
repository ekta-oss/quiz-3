# Module 1 Assessment: Objective Component (Quiz 3)

Everyday Workplace Communication · Module 1 · Segment 11: Module Assessment · **Stage 11.1** (COM-M1-QZ-03), in the Swift AI Academy frame.

The whole assessment is one plain HTML page (`index.html`), with its pictures and sounds inside the file. No framework or build step is needed. `Module1_Quiz3_Stage11.1_Objective_Component.html` is the same file, kept for downloading. It opens with a double-click.
The page is generated from `module1-segment1/` with `node scripts/plain-quiz111.mjs <out.html>`, from `scripts/quiz111-plain.template.html`. Do not edit it by hand.

## Publish on GitHub + Vercel

1. In Vercel choose **Add New → Project** and import this repository.
2. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
3. Choose **Deploy**.

GitHub Pages also works: Settings → Pages → deploy from the `main` branch, root folder.

## How it works

- **20 objective items**, 5 in each of Listening, Reading, Vocabulary and Grammar, drawn from Segments 1–10.
- **One try per item.** The answer is checked and saved, and the right answer is shown straight away with a one-line reason. A right answer gets a green tick and a soft chime; a wrong one gets an amber card. There is no negative marking.
- **Question navigator:** numbered circles down the left (a row at the top on phones), grouped by skill. Each answered question gets a small tick. The learner can move between questions; "Next question" goes to the next unanswered one.
- **Score** at the end: total out of 20, and the score for each skill.
- **Record:** each attempt is saved in the browser as `11.1.assessment-log` (answer, right or wrong, and how often each clip was played). There is no server, so nothing is sent anywhere.
- **Listening:** a speaker button. "Play again" always starts the clip from the beginning. There is no transcript on screen.
- Matching and gap items work by dragging (mouse or finger) or by tapping. A placed word can always be dragged back or tapped to send it back, until the answer is checked.
- **Time:** the top bar shows "About 25 minutes" and never counts down. The 25-minute limit and the Pause button from the brief are switched off for now, as in Quiz 2 (set `TIMER_ON` to `true` in the template to bring back the limit).
- No contractions are used anywhere on screen.

## Content status (for review)

- The brief gives examples only ("GAP: Item bank not written in source"). **All 20 items are draft wording** written from what Segments 1–10 teach. Each item names its segment in the template.
- **Interim audio:** the listening clips are computer voices (Kokoro TTS) made by `scripts/make-voice-q3.mts`. Clip 5 is Rohan's line from Segment 1. Replace them with the voice artist's recordings under the same names.
- **Interim art:** the First Aid and No Parking signs are flat drawings made for this build. The Silence sign comes from Quiz 2, and the sunrise, sun and moon icons come from the Segment 1 illustrator files.
- Graded results stay in the browser only. A platform backend is needed to collect them.

# PsychLogic — Clinical Mock 9

**Clinical Psychology in Practice** — psychopathology & classification (DSM / ICD),
clinical assessment in practice, child & adolescent clinical psychology, health
psychology & stress, clinical-psychology foundations, and a few exam-style questions
on the Mental Healthcare Act / RCI. 100 questions, including 12 real previous-year questions.

Part of the **M.Phil / M.Psy / MA Clinical Psychology (RCI) & PsyD Entrance 4.2 Mock
Test Series — Phase 2 (Clinical-Focused Mocks).**

## Deploy on GitHub Pages
1. Create a new repository and upload all files, keeping the folder structure intact.
2. **Settings → Pages → Build and deployment**.
3. Source: **Deploy from a branch**; Branch: **main** / root (`/`).
4. Save. The test goes live at `https://<username>.github.io/<repo>/`.

## Structure
```
index.html            Page markup
css/style.css         Styles (light aesthetic)
js/app.js             Test engine (timer, scoring, analysis)
data/questions.js     100-question bank
data/access-codes.js  38 access codes
assets/               PsychLogic logo
```

## Test details
- Access gate: student enters **name + one valid access code**.
- **120-minute** timer, negative marking **+1 / −0.25**.
- Results: **Result Analysis** (score, subject-wise breakdown, strong/weak areas, tips)
  and **Answers** (full review with detailed explanations and PsychLogic Insights).
- Single-device registration; copy / right-click disabled as a sharing deterrent.

## Editing access codes
Open `data/access-codes.js` and edit the `window.ACCESS_CODES` array.
On a static site these codes are visible in page source — a sharing deterrent, not security.

---
© PsychLogic — *Where Psychology Meets Strategy*

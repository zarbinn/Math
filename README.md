# Maths Quest — Grade 4 Revision

A responsive, static study app built from the 40-question *Grade 4 Mathematics: November Revision Test 4* scan. It runs in any modern browser and needs no build step or server-side services.

## Run locally

Open `index.html` in a browser. Progress is saved in that browser on the device using local storage.

## Deploy to Vercel

1. Put `index.html`, `styles.css`, `app.js`, and `vercel.json` in the root of a GitHub repository (or import this project folder with the Vercel CLI).
2. In Vercel, choose **Add New → Project** and import the repository.
3. Select **Other** as the framework preset. Leave the build command and output directory blank; the app is served directly from the project root.
4. Click **Deploy**. Vercel will provide a shareable URL.

There are no environment variables or API keys. Each learner's progress remains in that browser and is not shared between devices.

## Included

- One-question-at-a-time test mode with study notes shown throughout.
- Immediate marking and correct-answer feedback for incorrect answers.
- End-of-test score, percentage, and missed-question answer review.
- Fresh, randomized retest questions for missed topics.
- Mark adjustment controls for ambiguous written answers.
- Reset confirmation and responsive mobile layout.

## Source note

The exam has printed and handwritten markings in the scan. The app uses the printed question prompts and independently entered answer key. Tally marks, graph values, measuring scales, and the jug reading were transcribed from the page images. A learner can adjust any mark using the review control.

# Grade 4 Maths Exam Practice

A responsive Next.js app for Grade 4 Mathematics revision.

## Features
- 40-question practice test with immediate PASS/FAIL marking
- If an answer is wrong, the correct answer and explanation appear immediately
- If an answer is correct, the answer is not separately revealed
- End-of-test total, percentage, passed and failed totals
- Full breakdown of failed questions with learner answer and correct answer
- A new question for each unique failed topic on the personalised retest
- Reset clears all progress and returns to the start screen

## Run locally
Install Node.js, then run:
```bash
npm install
npm run dev
```
Open http://localhost:3000.

## Deploy to Vercel
1. Upload the contents of this folder to a GitHub repository.
2. In Vercel, import that repository as a new project.
3. Framework preset: Next.js. No environment variables are required.
4. Deploy.

## Important source note
The original PDF scan was faint in several diagram/tally/scale areas. The earlier app recreated a few unclear diagram-based items as text practice questions and noted those items for checking against the paper. This rebuild preserves that same practice-question bank and the requested exam/retest behaviour; it does not claim every question is a verbatim transcription of the scanned PDF.

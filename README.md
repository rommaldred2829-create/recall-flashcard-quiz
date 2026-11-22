# Recall — Flashcard Quiz

Recall turns class notes and study documents into a quick multiple-choice quiz and a set of review flashcards. It is a mobile-friendly, installable web app; processing happens in your browser and recent study sets stay on your device.

## Live demo

https://rommaldred2829-create.github.io/recall-flashcard-quiz/

## Features

- Paste notes or upload TXT, MD, CSV, HTML, JSON, RTF, PDF, or DOCX files (up to 10 MB).
- Generate multiple-choice questions with answer feedback and explanations.
- Review interactive flip cards.
- Choose quiz, flashcards, or both, and select 5, 8, or 12 questions.
- Copy a generated study set and reopen recent sets stored on the device.
- Install the app to a compatible phone home screen; core app files are cached for offline use.

## Install and run

You can use the live demo above in a mobile or desktop browser. To run locally, download or clone this repository and serve the folder over HTTP (service workers and installation require HTTP or HTTPS). For example, with Python installed:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`. On a phone, open the hosted HTTPS site and choose **Add to Home Screen** / **Install app** in the browser menu.

PDF and DOCX text extraction loads PDF.js and Mammoth from a public CDN when first needed, so those document formats require an internet connection. Pasted text and plain text files work without those readers.

## Author

- Name: **Romm Aldred L. Abaya**
- Section: **BSINTE 2C**

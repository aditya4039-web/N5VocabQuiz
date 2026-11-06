# N5 Vocab

A simple Android app to practice JLPT N5 vocabulary. It works offline and has no romaji, so you practice reading Japanese.

## Features
- Quiz on N5 verbs and adjectives
- Verbs are asked in both ます and て form
- Choose answers or type them in kana
- Optional timer
- Spaced repetition and a score for every word
- Flashcards with audio and example sentences with furigana
- Backup and restore for your progress

## How to run
1. Open the project in Android Studio.
2. Wait for Gradle to sync.
3. Press Run.

## How it works
The app is a WebView that loads `app/src/main/assets/index.html`. The whole quiz is in that one file.

## Credits
Word list based on JLPTsensei.com.

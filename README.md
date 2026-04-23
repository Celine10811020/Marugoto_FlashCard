# Japanese FlashCard｜日文單字閃卡（日→中）

A browser-based vocabulary flashcard app for **Marugoto Japanese learning materials** and **留学生の日本語**, designed for **Japanese-to-Chinese** study.

Built with **HTML, CSS, and JavaScript**, this project provides a lesson-based flashcard interface for reviewing Japanese vocabulary from different Marugoto course books.

## Live Demo

[Try the flashcards](https://celine10811020.github.io/Marugoto_FlashCard/)

## About the Project

Marugoto FlashCard is a lightweight web app for reviewing vocabulary from the [**Marugoto** Japanese textbook](https://marugoto.jpf.go.jp/en/) series and [大学・大学院留学生の日本語1 読解編](https://amzn.asia/d/0e0dvhDe).

The app organizes vocabulary by course and lesson, allowing users to practice one card at a time in a simple browser-based interface.

This project focuses on **Japanese vocabulary learning**, with each card supporting:

- Japanese reading on the front
- Kanji or Chinese meaning on the back

## Supported Levels / Books

The project currently includes vocabulary sets from:

- まるごと 入門 A1 かつどう
- まるごと 入門 A1 りかい
- まるごと 初級1 A2 かつどう
- まるごと 初級1 A2 りかい
- まるごと 初級2 A2 かつどう
- まるごと 初級2 A2 りかい
- まるごと 初中級 A2/B1
- 大学・大学院留学生の日本語1 読解編

## Features

- Marugoto-based vocabulary review
- Lesson selection by textbook set
- Front side shows **Japanese reading**
- Click the **left half** of the card to reveal **kanji**
- Click the **right half** of the card to reveal **Chinese meaning**
- Mark cards as **remembered**
- Move to the **next card**
- Keyboard shortcuts for faster practice
- Browser-based interface with no installation required

## Keyboard Shortcuts

- `←` : reveal kanji
- `→` : reveal Chinese
- `Space` : next card
- `Enter` : mark as remembered

## Project Structure

```text
Marugoto_FlashCard/
├── Data/               # Data files
├── index.html          # Main page
├── main.js             # Flashcard logic and data loading
├── style.css           # UI styling
└── HTTP server.txt     # Notes for local server setup

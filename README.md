# Marugoto FlashCard｜まるごと 單字閃卡（日→中）

A browser-based vocabulary flashcard app for **Marugoto Japanese learning materials**, designed for **Japanese-to-Chinese** study.

Built with **HTML, CSS, and JavaScript**, this project provides a lesson-based flashcard interface for reviewing Japanese vocabulary from different Marugoto course books.

## Live Demo

[Try the flashcards](https://celine10811020.github.io/Marugoto_FlashCard/)

## About the Project

Marugoto FlashCard is a lightweight web app for reviewing vocabulary from the **Marugoto** Japanese textbook series.

The app organizes vocabulary by course and lesson, allowing users to practice one card at a time in a simple browser-based interface.

Unlike a kanji-only flashcard app, this project focuses on **Japanese vocabulary learning**, with each card supporting:

- Japanese reading on the front
- Kanji on one side of the back
- Chinese meaning on the other side of the back

## Supported Levels / Books

The project currently includes vocabulary sets from:

- 入門 A1 かつどう
- 入門 A1 りかい
- 初級1 A2 かつどう
- 初級1 A2 りかい
- 初級2 A2 かつどう
- 初級2 A2 りかい
- 初中級 A2/B1

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
├── index.html
├── main.js
├── style.css
├── Marugoto_A1_Katsudou_Vocab.xlsx
├── Marugoto_A1_Rikai_Vocab.xlsx
├── Marugoto_E1A2_Katsudou_Vocab.xlsx
├── Marugoto_E1A2_Rikai_Vocab.xlsx
├── Marugoto_E2A2_Katsudou_Vocab.xlsx
├── Marugoto_E2A2_Rikai_Vocab.xlsx
├── Marugoto_A2B1_Vocab.xlsx
├── Marugoto_A1_Katsudou_Vocab.pdf
├── Marugoto_A1_Rikai_Vocab.pdf
├── Marugoto_E1A2_Katsudou_Vocab.pdf
├── Marugoto_E1A2_Rikai_Vocab.pdf
├── Marugoto_E2A2_Katsudou_Vocab.pdf
├── Marugoto_E2A2_Rikai_Vocab.pdf
├── Marugoto_A2B1_Vocab.pdf
└── HTTP server.txt

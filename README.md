# AI Study Assistant (DE/EN)
Ingest lecture slides (PDF/PPTX), summarize slides + deck, build a mind map (Mermaid), semantic search, and export Anki flashcards 

[![Open In Colab](https://colab.research.google.com/drive/1hUgaTwVnInNzqw1eod-4cnGzR6khZe9i?usp=sharing)

## Quick Start (Colab)
1) Click the link above.
2) Run cells: Upload → Ingest/OCR → Summaries → Search → Mind map → Flashcards.
3) Download from `outputs/`: `deck_summary.txt`, `slide_summaries.json`, `mindmap.mmd`, `flashcards.csv`.

## Features
- Multilingual (German/English), OCR fallback, semantic search, mind map, Anki CSV.
- Local / Colab only — no paid API keys.

## Demo
- Paste `mindmap.mmd` into https://mermaid.live to export PNG/SVG.
- Import `flashcards.csv` into Anki (Front=Question, Back=Answer, Tags=Tags).

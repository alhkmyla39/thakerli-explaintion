# Thakerli · ذاكرلي

**Bilingual AI study assistant** · Independent project

Thakerli helps students work with their own study notes in Arabic or English. It brings note search, source-linked chat, and practice tools into the same workspace.

## What you can do

- Add text or PDF notes and find them by content or subject.
- Ask a question about your notes and follow the cited excerpts back to the source.
- Generate and save quizzes and flashcards, then review mistakes and track practice progress.

## Engineering focus

I built the application and integrated two model options. Groq supports hosted inference, and Ollama supports running models locally. The project gave me practice connecting model responses to source material and storing generated study sets for later review.

| Area | Technologies |
| --- | --- |
| Application | Python, FastAPI |
| Data storage | SQLite, PostgreSQL |
| Language models | Groq, Ollama |

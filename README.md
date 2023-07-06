# rememberry
Flashcards provide an effective way to memorise stuff using active recall and spaced repetition. Creating them manually in Anki can be painful - this script should help by pasting in the contents into appropriate sheet columns and let the upload and creation happening automatically in the background without duplications. ⚡️cards

# Blueprint 🛠️
- Python -> Pandas, CSV to read the Sheet
- AnkiConnect (external Anki API)
- Excel Sheet for storing flashcard data - see template here: <link>
- crontab for scheduling the automatic upload (macOS system)
- Vue -> User Interface

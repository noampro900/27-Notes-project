<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>27 Notes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .note {
      width: 200px;
      height: 100px;
      margin: 10px;
      padding: 10px;
      background: #fffbcc;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
    }
    textarea {
      flex-grow: 1;
      resize: none;
      border: none;
      background: none;
      outline: none;
      font-size: 14px;
      color: #333;
    }
    textarea:disabled {
      color: #999;
      background: #eee;
    }
  </style>
</head>
<body>
  <script>
    const totalNotes = 27;
    const notes = [];
    const savedNotes = JSON.parse(localStorage.getItem('notes')) || Array(totalNotes).fill("");

    function saveNotes() {
      localStorage.setItem('notes', JSON.stringify(notes));
    }

    function checkCompletion() {
      if (notes.every(note => note.trim() !== "")) {
        lockNotes();
        localStorage.setItem('completed', true);
      }
    }

    function lockNotes() {
      document.querySelectorAll('textarea').forEach(textarea => {
        textarea.disabled = true;
      });
    }

    document.addEventListener("DOMContentLoaded", () => {
      const completed = localStorage.getItem('completed');
      const container = document.body;

      for (let i = 0; i < totalNotes; i++) {
        const note = document.createElement('div');
        note.className = 'note';

        const textarea = document.createElement('textarea');
        textarea.value = savedNotes[i] || "";
        textarea.disabled = completed !== null;
        textarea.addEventListener('input', (e) => {
          notes[i] = e.target.value;
          saveNotes();
          checkCompletion();
        });

        note.appendChild(textarea);
        container.appendChild(note);
        notes.push(savedNotes[i] || "");
      }

      if (completed) lockNotes();
    });
  </script>
</body>
</html>

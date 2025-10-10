# HTML-TUTORIAL

A small collection of HTML exercises and lecture examples used for learning basic web development concepts (HTML, CSS). Each lecture folder contains an exercise HTML file, an optional stylesheet, and a short question file.

Contents
--------

- `Lecture2/` — Exercise and questions for Lecture 2
- `Lecture3/` — Exercise and questions for Lecture 3
- `Lecture4/` — Exercise and questions for Lecture 4
- `Lecture5/` — Exercise and questions for Lecture 5 (includes `style.css`)
- `Lecture6/` — Exercise and questions for Lecture 6 (includes a stylesheet)
- `Lecture7/` — Exercise(s) for Lecture 7 (see `Lecture7/README.md`)
- `Lectures/lecture1/` — Exercise and question for Lecture 1

How to preview the pages locally
-------------------------------

Since these are static HTML files you can open them directly in a browser or serve them with a tiny local server for correct handling of relative paths.

Open directly (quick):

1. Navigate to the folder in File Explorer.
2. Double-click any `.html` file (for example `Lecture7/index.html`) to open it in your default browser.

Serve with PowerShell (recommended for consistent behavior):

1. Open PowerShell in the project root (where this `README.md` is).
2. Run the built-in .NET static file server:

	python -m http.server 8000

3. Open `http://localhost:8000` in your browser and click into the lecture folder.

If you don't have Python installed, you can also use the following in PowerShell 5.1 to quickly open a file in the default browser:

	Start-Process .\Lecture7\index.html

Contributing
------------

Add new lecture folders named `LectureN` with the pattern used elsewhere: an `exercise` HTML file (or `index.html`), an optional `style.css`, and a `Quistion.md` describing the exercise.

Please follow simple HTML/CSS best practices and keep files self-contained.

Notes
-----

- Filenames in the repository include inconsistent capitalization and spelling (for example `Quistion.md`). When adding files, consider matching the existing style or normalizing names in a separate cleanup commit.
- This project appears to be a personal or instructional collection of static examples. There is no build step or external dependencies.

License
-------

Feel free to use these examples for learning and teaching. If you want to apply a formal license, add a `LICENSE` file.
# HTML-TUTORIAL

# claudio@sapo personal site

Static personal site with only two public sections:

- `index.html` - home page
- `project/` - projects section
- `cv/` - curriculum vitae section

## Structure

- `project/index.html` lists the three project pages.
- `project/project1.html`, `project/project2.html`, and `project/project3.html` are project detail pages.
- `resources/` contains downloadable PDF files for the project pages.
- `resume.txt` is the downloadable CV text file.
- `styles.css` contains the shared terminal-style layout.

## Local Preview

Run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open:

```text
http://127.0.0.1:8000/index.html
```

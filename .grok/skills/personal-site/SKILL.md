---
name: personal-site
description: >
  Edit Luis Palacios's site (luisfpal.github.io). Use when changing the
  homepage, a section, a project, a note, a figure, or the venue line.
  The homepage is a directory. The CV has its own skill. /personal-site
---

# Personal site

The homepage is `~/`. It names Luis and lists the doors. A claim lives on its own page. Adding work is a new file plus one line in the parent index. It is not a redesign of the homepage.

Read the page before writing. A sentence that is not in the artifact, or not confirmed by Luis, is not written. Do not link a private repository. Do not upgrade who did the work.

## The tree

The folder name is the claim a stranger is allowed to make.

- `papers/` lists two papers. `papers/neurips/` is the accepted poster. `papers/escience/` is the IEEE eScience 2026 submission that was not accepted, because the review wanted throughput experiments. Do not say published.
- `theses/` is three degrees, each a heading and a divider. Data Science and Artificial Intelligence keeps its own title and points at the NeurIPS page. Data Management and Curation is two independent pieces: a generator for machine-learning services that share a structure, and a web app for storage and governance. The scanning-electron-microscope classifier is the working example, not the product. They were not joined. They were not tuned for throughput. Physics is the magnetic spectra of the Earth and the Sun, separated by empirical mode decomposition.
- `projects/` is work he started. Nobody assigned it and nobody graded it. Chapterize is the one there now.
- `coursework/` is a university assignment. Heading, one sentence, the repository. A course project does not sit next to a paper as the same kind of object.
- `notes/` is reading notes. None yet. A topic is a folder. A chapter is a markdown file. Do not invent a chapter to fill the folder.
- The CV is one page. Its rules are in `.grok/skills/cv/SKILL.md`. A claim changes on the site and in the CV, or in neither.

## A listing page

Theses, papers, coursework, and projects use one block:

- A heading with the class `entry`.
- One sentence. Picture first, then the method name. Emoji does not go in the sentence.
- A link row, class `entry-links`. A pdf is `📄 pdf`. Slides are `📊 slides`. A repository is the word `code`.
- An `<hr>` between entries. Not after the last one.

Emoji is the icon of a door on the homepage, or of a file in a link row. The doors are 📚 papers, 🎓 theses, 🔧 projects, 🏫 coursework, 📝 notes, 📎 cv.

## Look

- Ground `#070B14`. Deeper ground `#05070E`. Text `#D5E6F5`. Quiet text `#8BA0B5`.
- Cyan `#22D3EE` for links. Magenta `#FF2BD6` once, the hairline under the name.
- Prose is the system sans. Paths, the homepage listing, entry headings, and link rows are the system mono already on the machine. Do not load a webfont.
- Max-width 680px. No JavaScript.
- No glass, no blur, no glow, no gradient text, no tech tags, no card grid.
- The homepage picture is the lunar base (`assets/img/base.jpg`), shown whole, on the homepage only.
- The portrait is the drawing on the homepage only. The alt text says it is a drawing, not a photograph.
- A scientific figure stays on the paper page and keeps its own ground.

## What stays off the site

No city as where he lives. No health. No "open to work". The GitHub bio sentence does not go on the site. Do not promise work that is not done.

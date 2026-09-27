---
name: personal-site
description: >
  Edit Luis Palacios's site (luisfpal.github.io) and the CV in
  /Users/l11/Documents/cv. Use when changing the homepage, a section, a
  project, a note, a figure, or the venue line. The homepage is a directory.
  /personal-site
---

# Personal site

The homepage is a directory. It names Luis and lists the doors. A claim lives on its own page. Adding work is a new file plus one line in the parent index. It is not a redesign of the homepage.

## The tree

The homepage is the directory. The folder name is the claim a stranger is allowed to make.

- `papers/` lists two papers. `papers/neurips/` is the accepted poster. `papers/escience/` is the IEEE eScience 2026 submission that was not accepted, for lack of throughput experiments. The services had been deployed and worked. Do not say published. Do not call the two services one finished platform or two unrelated projects.
- `theses/` is a question he owned for a degree. The PDF is the file a stranger opens. The data-science thesis points at `paper/` and keeps its own title. The data-management thesis is one service layer built twice: storage people can govern, and an analysis API. Both were deployed and worked. The IEEE eScience 2026 submission was not accepted, for lack of throughput experiments. Do not say published, and do not call the two instantiations two projects.
- `projects/` is something he started. Nobody assigned it and nobody graded it. It earns a line only if a stranger can open it.
- `course/` is an assignment. One line and a repo. No pitch, no image, no tech tags. A course project does not sit next to the paper as the same kind of object.
- `notes/` is reading notes. A topic is a folder. A chapter is a markdown file in that folder. The topic page lists chapters in order, with a heading and a divider. Do not invent a chapter to fill an empty folder.
- `cv` is the inventory. The site and the CV may not contradict.

The picture on `/` is the lunar base. It is a picture of a place, not a result.

## Before writing a sentence

Read the artifact: the paper, the README, the figure, or the deployed URL. A sentence that is not in the artifact, or not confirmed by Luis, is not written. Do not upgrade a contribution note. Do not link a private repository.

## What earns a page

A page stays if a stranger can open it and check something, or if Luis asked for the door before the files exist (`notes/`). Put the work in the folder that matches who owned the question. Do not promote a course project into `projects/` or `theses/` because the code is impressive.

A line is a picture, then the name of the method. "SAC and TD3" alone fails. A slogan fails. The advanced-programming homework was three people with a similar share: Luis, Piero Zappi, and Marco Tallone. Do not write that the others did most of it.

Do not promise work that is not done. No city as where he lives, no health, no "open to work" unless he asks for that line in the same conversation.

## Venue words

"Accepted" only after Luis confirms a decision. Name the presentation type when he has it. "Published" only when a proceedings page or an updated arXiv comment exists. Link the preprint until then.

The role on the paper page matches the paper's contribution note. Alberto Cazzaniga designed the core experiments. He did not write the code or run them. That work was Luis, Lorenzo Basile, and Diego Doimo.

## Look

- Ground `#070B14`. Text `#D5E6F5`. Quiet text `#8BA0B5`.
- Cyan `#22D3EE` for links and focus. Magenta `#FF2BD6` once, as a hairline under the name.
- The directory listing is system mono. Prose is the system sans.
- Max-width 680px. No JavaScript.
- No glass, no blur, no glow, no gradient text, no tech tags, no card grid.
- The homepage picture is the lunar base he keeps on the desktop (`assets/img/base.jpg`), shown whole. Do not swap it for a diagram or a slogan poster.
- A scientific figure stays on the paper page and keeps its own ground. Do not recolor it.

## CV

The CV is `/Users/l11/Documents/cv`, and its remote is Overleaf. Change the site and the CV together when a claim changes, or change neither. Regenerate `cv.pdf`, copy it to the site, and keep the rendered CV to one page.

Do not delete comment archives in `cv.tex`. When wording leaves the rendered CV, append it to the archive comment. Advisor emails stay in that archive. The rendered line says references are available on request.

Push the website only after Luis has seen the page. Push the CV to Overleaf only when he asked, and never force-push.

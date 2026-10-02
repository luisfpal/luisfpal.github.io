---
name: cv
description: >
  Edit Luis Palacios's CV at /Users/l11/Documents/cv. Use when changing a
  bullet, a publication line, spacing, or what is rendered versus left in
  the comment archive. The CV earns an interview by a result a stranger
  can check. /cv
---

# CV

The file is `/Users/l11/Documents/cv/cv.tex`. The remote is Overleaf. The public copy is `cv.pdf` on luisfpal.github.io. Change a claim in both places, or in neither.

## The scan

Page 1 is the case: name, site, phone, degrees, the NeurIPS result, the author line, the two deployed services, the physics thesis. Page 2 is the inventory: coursework, skills that appear in those lines, fellowships, references on request. A catalog on page 1 fails.

Laszlo Bock's test, from reading resumes at Google: accomplished X, measured by Y, by doing Z. Y is copied from the paper or the README. A number that is not there is a lie. A duty ("built a web app", "responsible for") fails. Sasha Ko's note is the same test: show the result, do not announce the trait. No objective. No soft-skill list.

## Credit

The author line carries the credit. One clause, on that line. It does not become its own bullet.

For the NeurIPS paper: equal contribution with Lorenzo Basile. Basile, Doimo, and Cazzaniga designed the experiments. Luis wrote the code and ran them with Basile and Doimo. Do not write that Luis designed the experiments.

For the data-management work: he built both services. They were independent. One governs storage. The other classifies an image. They were not joined. The IEEE eScience 2026 submission with Federica Bazzocchi and Tommaso Rodani was not accepted, because the review wanted throughput experiments. Do not say published.

Advanced programming was three people with a similar share: Luis, Piero Zappi, and Marco Tallone. Do not write that the others did most of it.

## What earns a line

A line without a PDF, a repository, a DOI, or a live URL does not get a strong verb. Coursework is one line each, under its own heading, with a Font Awesome GitHub icon and a `luisfpal` URL. Latin Modern has no color emoji. Do not use Unicode emoji in the PDF.

Comment archives in `cv.tex` stay. When wording leaves the rendered CV, append it to the archive. The overview sentence stays in the archive. The graphene project stays in the archive. Advisor emails stay in the archive. The rendered references line says they are available on request.

## Space

Do not pull the next line up with large negative skips. A little air between degrees and between bullets. Two pages is the limit. Do not widen the margins to buy that air.

## Check

Compile with LuaLaTeX. Read the PDF. Page 1 has the result and the numbers from Table 1 of arXiv:2606.03871 (LLaVA-7B layers 6--16: 98.8% of full fine-tuning at 86.1% of the training time. OneVision-4B layers 8--25: 100.4% at 75.7%). The phone and the site are in the header. Then copy `cv.pdf` to the site.

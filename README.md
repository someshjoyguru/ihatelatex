# IhateLaTeX — Free Private LaTeX Resume Builder & In-Browser Overleaf Alternative

**Use the live app: [https://ihatelatex.com](https://ihatelatex.com/)**

[IhateLaTeX](https://ihatelatex.com/) is a **free, private, no-sign-up LaTeX suite** that runs in your browser. Build an **ATS-friendly LaTeX resume or CV**, write a **research paper or thesis**, generate **booktabs tables**, and edit **math formulas** — then compile a real vector PDF **on your device** with WebAssembly TeX.

Nothing is uploaded to compile. No account. No TeX Live install.

> Official site: [ihatelatex.com](https://ihatelatex.com/) · Resume builder: [ihatelatex.com/latex-resume-builder/](https://ihatelatex.com/latex-resume-builder/)

## What is IhateLaTeX?

IhateLaTeX is a **privacy-first Overleaf alternative** and **offline LaTeX resume maker**. A visual form writes the LaTeX for you. An embedded **pdfTeX engine (WebAssembly)** compiles the PDF in the browser tab.

It is built for:

- Students and new grads who need a **Jake’s Resume** / single-column **ATS resume**
- Software engineers applying through **Workday, Greenhouse, or Lever**
- Researchers who want **IEEE / ACM / arXiv-style PDFs** without putting a manuscript on a server
- Anyone who does not want **Zety, Novoresume, resume.io, or Canva** storing their CV

## Free LaTeX tools (indexed pages)

| Tool | What it does | Live URL |
| --- | --- | --- |
| IhateLaTeX suite hub | All private in-browser LaTeX tools | [https://ihatelatex.com/](https://ihatelatex.com/) |
| LaTeX resume & CV builder | Visual ATS resume maker, Jake’s Resume and other templates | [https://ihatelatex.com/latex-resume-builder/](https://ihatelatex.com/latex-resume-builder/) |
| Research paper & thesis builder | IEEE / ACM / arXiv-style papers without writing a preamble | [https://ihatelatex.com/research-paper-builder/](https://ihatelatex.com/research-paper-builder/) |
| LaTeX table generator | Excel / CSV → booktabs, tabularx, longtable | [https://ihatelatex.com/latex-table-generator/](https://ihatelatex.com/latex-table-generator/) |
| Visual LaTeX formula editor | Type, draw, or OCR math; export LaTeX or Typst | [https://ihatelatex.com/latex-formula-editor/](https://ihatelatex.com/latex-formula-editor/) |
| LaTeX resume guides | ATS rules, builder comparisons, bullet formulas | [https://ihatelatex.com/guides/](https://ihatelatex.com/guides/) |

Coming soon on the hub: TikZ diagram studio and a full on-device paper editor.

## IhateLaTeX vs Overleaf, Zety, Novoresume, and Canva

| | **IhateLaTeX** | Overleaf | Zety / Novoresume | Canva |
| --- | --- | --- | --- | --- |
| Price | Free | Freemium | Paid | Freemium |
| Account | No | Yes | Yes | Yes |
| Where files live | Browser / local folder | Cloud | Cloud | Cloud |
| Write LaTeX by hand? | No (visual UI) | Yes | No | No |
| Real LaTeX PDF | Yes (in-browser) | Yes | No | No |
| ATS-oriented resume | Yes (single-column text layer) | Yes if you code it | Mixed | Weak |
| Offline after first load | Yes (PWA + cached TeX) | No | No | No |

## ATS resume builder features

- Visual editor — personal details, summary, education, experience, projects, skills, certifications, custom sections
- Templates: **Jake’s Resume**, Academic CV, Modern, Executive
- **ATS checker** for Greenhouse / Lever / Workday-style parsing (contact fields, action verbs, metrics, headings, single-column layout)
- LinkedIn PDF import
- Inspect or download the generated `.tex`
- Compile and download a print-ready PDF in the browser

## Privacy and on-device compilation

IhateLaTeX compiles with **WebAssembly pdfTeX**. Resume text, papers, figures, and bibliographies are processed **in the local browser thread**. They are not sent to an IhateLaTeX server to produce the PDF.

The first visit may download TeX packages into the browser cache. Later visits can work offline as a PWA.

## FAQ

### Is IhateLaTeX a free LaTeX resume builder?

Yes. The [LaTeX resume and CV builder](https://ihatelatex.com/latex-resume-builder/) is free, with no sign-up and no watermark.

### Do I need to know LaTeX or install TeX Live?

No. The UI is a form. Compilation uses an embedded WebAssembly TeX engine. You can still view the generated LaTeX source.

### Is IhateLaTeX an Overleaf alternative?

Yes, for private, on-device work: resumes, papers, tables, and formulas. Projects are not stored on Overleaf’s servers.

### Will my resume pass an ATS?

LaTeX single-column PDFs parse more reliably than many Canva-style layouts. IhateLaTeX includes an ATS checklist aimed at common recruiter parsers. Always verify against the employer’s system.

### Is my CV uploaded?

No. Compilation runs in the browser. Do not confuse this GitHub page with the app — the product is [ihatelatex.com](https://ihatelatex.com/).

## Keywords

free LaTeX resume builder, ATS resume, Jake’s Resume, private CV maker, offline resume builder, Overleaf alternative, WebAssembly LaTeX, in-browser pdfTeX, IEEE paper builder, LaTeX table generator, booktabs, LaTeX formula editor, no sign-up resume builder

## Links

- Website: [https://ihatelatex.com](https://ihatelatex.com/)
- Resume builder: [https://ihatelatex.com/latex-resume-builder/](https://ihatelatex.com/latex-resume-builder/)
- Guides: [https://ihatelatex.com/guides/](https://ihatelatex.com/guides/)
- Show HN: [Hacker News thread](https://news.ycombinator.com/item?id=49362676)
- This repo (public README only): [https://github.com/someshjoyguru/ihatelatex](https://github.com/someshjoyguru/ihatelatex)
- GitHub Pages: [https://someshjoyguru.github.io/ihatelatex/](https://someshjoyguru.github.io/ihatelatex/)

---

*This repository is a public, crawlable description of [IhateLaTeX](https://ihatelatex.com/). It does not contain application source code.*

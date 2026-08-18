# Design and statistics review — library-preparation kit evaluation

A static site presenting an internal design and statistics review for a study benchmarking
commercial DNA library-preparation kits for targeted UMI/duplex sequencing.
Karolinska Institutet, Department of Medical Epidemiology and Biostatistics.

**This is a working document circulated among co-authors, not a publication.** The manuscript is
in preparation, the results are unpublished and provisional, and nothing here has been peer
reviewed. Please do not cite it.

## Reading it

Open `index.html`, or visit the published site (Settings → Pages for the URL). Twelve pages, no
build step, no dependencies:

| Page | Contents |
|---|---|
| `index.html` | Summary |
| `1-design.html`, `2-confounding.html` | The experimental design as executed, and its defects |
| `3a-plain-english.html` | The statistical argument without the jargon |
| `3-statistics.html`, `4-recommendation.html` | The pseudoreplication problem quantified, and the recommended analysis |
| `5-figure.html`, `6-tables.html` | The proposed main figure and results tables |
| `7-critique.html`, `8-methods.html`, `9-actions.html` | Critique of the draft, Methods text, action checklist |
| `10-ki-standards.html` | Compliance against KI research standards |

## Scope of this repository

It holds the rendered site and nothing else. The manuscript drafts, the analysis code and the
curated study data live in a separate private repository and are not published here. The single
figure in `img/` is a provisional render included so the statistical argument can be followed.

Colleagues are referred to by initials rather than by name.

## Indexing

Every page carries `<meta name="robots" content="noindex, nofollow, noarchive">`. The site is
reachable by anyone who has the URL and is not access-controlled — GitHub does not offer
access-controlled Pages outside Enterprise Cloud. Treat the URL as the only barrier and share it
accordingly.

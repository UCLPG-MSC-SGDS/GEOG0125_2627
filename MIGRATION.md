# GEOG0125 Quarto migration

The Quarto HTML book contains the eight pages in the original Bookdown navigation. It retains the original page names, the two unnumbered front-matter pages and the six numbered chapters. The sidebar and section links now use Quarto. The linked lecture PDFs, dataset ZIPs and solution ZIPs are served with the book.

The Week 1–3 material uses current Stan array declarations where the original used the older syntax. The Week 2 examples and scripts use `log_households` for the offset field because `offset` is a reserved Stan keyword. The model formulas are unchanged. Practical code marked for students to run remains display-only during rendering.

## Local review

Open this folder in Positron and run `quarto preview` in its terminal. The last built copy is available at [the book home page](docs/index.html).

All eight chapters rendered using Positron's bundled Quarto. The checks covered the original chapter order and numbering, local links and image paths, the Week 5 links back to Week 4, all 11 downloads, the CSVs and four shapefiles in the dataset archives, and Stan parsing for the six standalone models in `Scripts_RStan/`.

## Items for review

- Week 4 has two recording placeholders with no video IDs in the original source. Weeks 3–5 have solution placeholders on the Welcome page.
- Three Stan files in the original Week 1 and Week 2 solution downloads fail to parse with the installed RStan 2.39.0.9000. The solution archives are byte-for-byte copies of the originals.
- Full model sampling, exercise execution and video playback were outside the HTML validation. The installation instructions and timetable carry over the original text and should be reviewed for the 2026–27 delivery.

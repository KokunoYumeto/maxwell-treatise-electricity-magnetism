# James Clerk Maxwell, *A Treatise on Electricity and Magnetism*, Volume I (1873) — printed pages 1–79 and 111–267

Parts of Volume I of the first edition of Maxwell's *Treatise on Electricity and Magnetism* (Oxford: Clarendon
Press, 1873), typeset in LaTeX from the printed text.

| Printed pages | Contents | PDF | LaTeX |
| --- | --- | --- | --- |
| 1–79 | Preliminary chapter; Part I, Arts. 1–77 | [PDF](pdf/Maxwell_Treatise_Vol1_pp001-079.pdf) (79 pages) | [LaTeX](tex/Maxwell_Treatise_Vol1_pp001-079.tex) |
| 111–267 | Part I, Arts. 100–217 (both ends mid-article) | [PDF](pdf/Maxwell_Treatise_Vol1_pp111-267.pdf) (117 pages) | [LaTeX](tex/Maxwell_Treatise_Vol1_pp111-267.tex) |

## Completeness

This is a partial edition.

- Included: printed pages 1–79 and 111–267 of Volume I.
- Not yet included: pages 80–110 and from page 268 to the end of Volume I, and all of Volume II.
- Figures 1–4 (pages 28–31) are reproduced from the scan. The figures in the text of pages 111–267 are redrawn
  in LaTeX (TikZ); Fig. 6 is computed from Maxwell's construction rather than copied. The full-page plates at the end
  of the volume (the figures with Roman numerals) are not included; the text refers to them by number.
- The readers do not mark the page breaks of the print; page references in the text refer to the 1873 volume.

## How it was made

The text was transcribed from the scan by AI: pages 1–79 by OpenAI's Codex, page by page against the scan; pages 111–267 first by OCR in a pipeline run by Claude (Anthropic) and then checked and repaired page by page
against the scan by OpenAI's Codex.

## Checks

On 27 October 2026 Claude Opus 5.5 (Anthropic) compared printed page 64 and the formulas of page 244 with the scan.
Both agree with the print, apart from one place on page 244 where the print has *x* and the edition *x′* in a limit
of integration. The other pages have not had a second check by a different model.

## Source

The transcription follows the Internet Archive scan of the University of California copy,
[electricandmagne01maxwrich](https://archive.org/details/electricandmagne01maxwrich).

## Building

Run `pdflatex` twice on each file in `tex/`.

## Rights

Maxwell's text is in the public domain. The transcription and typesetting are dedicated to the public domain under
[CC0 1.0](LICENSE).

## Earlier versions

Earlier versions were published on Zenodo, [doi:10.5281/zenodo.20653107](https://doi.org/10.5281/zenodo.20653107).
That record is no longer updated.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)

# 2023-06-22 GPU  profiling with Celeritas

Quarto / reveal-js based presentation on "GPU ~~benchmarking~~ profiling of [Celeritas](https://github.com/celeritas-project/celeritas)" at the [2023-06-21/22 ExaTepp Workshop](https://indico.cern.ch/event/1287030/), by Peter Heywood.

## Dependencies

1. [Install quarto](https://quarto.org/docs/get-started/)
2. Chromium based browser for PDF generation (if local)

## Building slides

## HTML

```bash
quarto render 2023-06-22-gpu-profiling-with-celeritas.qmd --to html
```

## Print to PDF

[Qaurto Print to PDF](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf)

> 1. Toggle into Print View using the E key (or using the Navigation Menu)
> 2. Open the in-browser print dialog (CTRL/CMD+P).
> 3. Change the Destination setting to Save as PDF.
> 4. Change the Layout to Landscape.
> 5. Change the Margins to None.
> 6. Enable the Background graphics option.
> 7. Click Save 🎉

### Live-preview

``` bash
quarto preview 2023-06-22-gpu-profiling-with-celeritas.qmd
```

## Hosted via gh-pages

@todo - see https://quarto.org/docs/output-formats/html-publishing.html
# ICMS Visualisation Workshop

Slides and activity materials for a workshop on data visualisation. These were created as part of a collaboration between [ICMS](https://www.icms.org.uk/) and [Fife College](https://fife.ac.uk/) as part of their prison education programme. After the workshops, learners will be able to: 

1. Understand common types of data visualisation;
2. Draw conclusions based on represented data;
3. Identify and critically analyse misleading visualisations. 


## Session Plan

The first part of the session is a presentation reviewing different types of data visualisation, with planned points for optional participation from learners. This starts with more common types (bar charts, pie charts, histograms, and scatter diagrams) and briefly shows how they are made and, in more detail, how to read meaning from them. It then outlines some more complicated visualisation methods like Sankey diagrams, heatmaps, tree maps, and network graphs. This will touch on how different types of charts are better suited to different types of data (e.g. discrete vs. continuous).

The end of the presentation highlights some of the features that can make visualisations misleading or difficult to read. This leads into the break-out discussion activity for the second part of the session, a. Looking at a range of examples, learners will identify visualisations that they think are misleading or especially good ways to communicate data and discuss them as a group.

## SCQF Level

Working by the [SCQF](https://scqf.org.uk/), the initial presentation about visualisation types starts at Level 4 (bar graphs, pie charts), gradients into Level 5 (histograms, scatter diagrams), before finishing by briefly touching on some Level 6-7 content (more complicated diagrams). Discussion around misleading graphs is pitched at Level 5, though learners more comfortable with the Level 6-7 visualisations will have more complicated features they can discuss too.

## Building

The slides are built with R Markdown using [xaringan](https://github.com/yihui/xaringan), using [Tidyverse](tidyverse.org) to create example visualisations at build time. The default output is HTML, but for easier sharing a PDF version can be exported with [pagedown](https://github.com/rstudio/pagedown) by using:

```r
pagedown::chrome_print("slides.Rmd")
```

## License

These materials are released into the public domain under the Creative Commons Zero (CC0) license. Excluded from this are the original example images for the discussion activity, which remain the copyright of their original authors. For more information on exceptions to use copyrighted work for educational purposes consult the [UK government guidance](https://www.gov.uk/guidance/exceptions-to-copyright#teaching).

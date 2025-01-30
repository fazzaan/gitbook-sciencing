# Phase 1 – Data processing & gene selection

_Analyzing the dataset to select differentially regulated genes for statistical analysis._

To select genes for research, the foldchange dataset was analyzed in Microsoft Excel: columns were colour-graded using conditional formatting to highlight the largest foldchanges and most-significant _p_-values, and were sorted ascendingly, revealing the most-suitable genes. Basic background research was conducted on the top \~70 genes using parameters to determine which to pursue: presence in lung tissues, higher occurrence in studies, and subject of non-asthma research increased suitability of genes; whilst existing association with asthma or no existing research decreased suitability. Genes with an extensive knowledge base, and those related to immune function, were most suitable.

Selected genes’ rows were copied from the raw expression dataset (_E-GEOD-61141-raw-counts.tsv_) into a new spreadsheet without editing. The data were transposed and transformed into tables grouping expression values by gene, allowing calculation of the differentials in preparation for subsequent data analyses.

# Evaluating institutional open access performance: Methodology, challenges and assessment

Chun-Kai Huang[1], Cameron Neylon[1,2], Richard Hosking[2], Lucy Montgomery[1,2], Katie Wilson[1], Alkim Ozaygen[1], Chloe Brookes-Kenworthy[1]

1. Centre for Culture and Technology, School of Media, Creative Arts and Social Inquiry, Curtin University, Kent St, Bentley 6102, Western Australia
2. Curtin Institute for Computation, Kent St, Bentley 6102, Western Australia

Article submitted for peer review and an acompanying white paper.
* Code: https://github.com/Curtin-Open-Knowledge-Initiative/institutional-oa-evaluation-2020
* Notebooks on MyBinder.org: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Curtin-Open-Knowledge-Initiative/institutional-oa-evaluation-2020/mybinder)
* Data: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3693222.svg)](https://doi.org/10.5281/zenodo.3693222)
* Preprints:
* PDFs for each document can also be found in the top level of this repository

## Abstract

Open Access to research outputs is becoming rapidly more important to the global research community and society. Changes are driven by funder mandates, institutional policy, grass-roots advocacy and culture change. It has been challenging to provide a robust, transparent and updateable analysis of progress towards open access that can inform these interventions, particularly at the institutional level. Here we propose a minimum reporting standard and present a large-scale analysis of open access progress across 1,207 institutions world-wide that shows substantial progress being made. The analysis detects responses that coincide with policy and funding interventions. Among the striking results are the high performance of Latin American and African universities, particularly for gold open access, whereas overall open access levels in Europe and North America are driven by repository-mediated access. We present a top-100 of global universities with the world’s leading institutions achieving around 80% open access for 2017 publications.

## Sensitivity Analysis White Paper

In the article "Evaluating institutional open access performance: Methodology, challenges and assessment" we develop the first comprehensive and reproducible workflow that integrates multiple bibliographic data sources for evaluating institutional open access (OA) performance. The major data sources include Web of Science, Scopus, Microsoft Academic, and Unpaywall. However, each of these databases continues to update, both actively and retrospectively. This implies the results produced by the proposed process are potentially sensitive to both the choice of data source and the versions of them used. In addition, there remain the issue relating to selection bias in sample size and margin of error. The current work shows that the levels of sensitivity relating to the above issues can be significant at the institutional level. Hence, the transparency and clear documentation of the choices made on data sources (and their versions) and cut-off boundaries are vital for reproducibility and verifiability.

## Running the paper

The requirements for running the Jupyter notebooks that hold the manuscript, white paper, supplementary methodology and supplementary figures should be provided by a standard scientific python environment such as Anaconda. A requirements.txt is provided for clarity. A small visualisation library is included for convenience. All data manipulations are explicitly recorded in the manuscripts themselves. The visualisation library only filters or reshapes data for display

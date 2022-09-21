# Mining Star Trek Transcripts

## Table of Contents
<!-- TOC -->

- [Mining Star Trek Transcripts](#mining-star-trek-transcripts)
  - [Table of Contents](#table-of-contents)
  - [TODO](#todo)
  - [Project Structure](#project-structure)

<!-- /TOC -->

## TODO

- [x] Scrape list of all episodes and metadata, e.g. title, airdate
- [x] Scrape episode summaries from Memory Alpha
- [ ] Scrape transcripts for all episodes from chakoteya.net

## Project Structure

```bash
    .
    ├── notebooks
    │   ├── 00_webscraping_summaries_metadata.ipynb    # bibtex entries for the references
    │   ├── 01_webscraping_transcripts.ipynb           # bibtex entries for the references
    ├── data
    │   ├── raw                  # these data sets can be excerpts from the original data
    │   ├── interim            # or even simulated data sets (simply provide them so that
    │   ├── test_data                   # your code can be executed)
    ├── scripts
    │   ├── main.R/.py                  # a file which puts together all the pieces
    │   ├── 01_preprocessing.R/.py            
    │   ├── 02_descriptives.R/.py              
    │   ├── ...            
    │   └── requirements.txt            # for reproducibility
    ├── results                         # raw data results of experiments
    └── ...
```

# High-Quality Financial News Dataset

## Description

This repository contains a meticulously scraped dataset from various financial websites. The data extraction process ensures high-quality and accurate text, including content from both the websites and their embedded PDFs.

### Dataset Features

- **Date**: The date of the announcement.
- **Subject**: The subject of the financial news.
- **Content**: The full content of the announcement, including text from the website and PDFs.

### Additional Processed Fields

We applied the advanced Mixtral 7X8 model to generate the following additional fields:

- **ParaphrasedSubject**: A paraphrased version of the original subject.
- **CompactedSummary**: A concise summary limited to 1.5 lines.
- **DetailedSummary**: A detailed summary of the content.
- **Impact**: The impact of the announcement, summarized in 2 lines.

### Methodology

The prompt used to generate the additional fields was highly effective, thanks to extensive discussions and collaboration with the Mistral AI team. This ensures that the dataset provides valuable insights and is ready for further analysis and model training.

## Usage

This dataset can be used for various applications, including but not limited to:

- Financial news analysis
- Abstractive/Exctractive Summarization tasks
- Machine learning model training
- Natural language processing tasks

## How to Access

You can access the dataset by cloning this repository:

```bash
git clone https://github.com/yourusername/financial-news-dataset.git

## Assessing Algorithmic Bias in LLM Predictions of Public Opinion Across Demographics

This repository hosts the code and data for the paper "Assessing Algorithmic Bias in Large Language Models' Predictions of Public Opinion Across Demographics." The project investigates the potential biases in algorithmic predictions made by large language models (LLMs) and compares these predictions against actual survey data on public opinions across different demographic groups.

## Project Overview

This project, "Assessing Algorithmic Bias in Large Language Models' Predictions of Public Opinion Across Demographics," is developed by Khai Tran, Sev Geraskin, Doroteya Stoyanova and Jord Nguyen. It was created during the Apart Research AI x Democracy Research Hackathon. More information about the hackathon can be found [here](https://www.apartresearch.com/post/join-ai-democracy).

### Threat Scenario

With the rise of large language models (LLMs), there are new possibilities for gauging public opinion on societal issues through survey simulations. However, these models may exhibit algorithmic biases, potentially failing to represent diverse viewpoints accurately, especially from minority and marginalized groups. As AI systems are increasingly used in high-stakes decisions, such biases could disenfranchise underrepresented communities and undermine democratic representation principles.

### Demonstration

The project includes a series of visualizations comparing the predictions made by LLMs to actual survey data across various demographics in British Columbia and Quebec.

## Repository Contents

- **AIDemocracyPrompts.ipynb**: A Jupyter notebook that demonstrates how to set up the OpenAI API, define input data for demographic subgroups, and collect responses from LLMs.
- **data/gpt-3.5-turbo-airesponses.json** and **data/llama-airesponses.json**: JSON files containing the AI's responses mapped to the respective demographic data.
- **data/gpt-3.5-turbo-dataset-no_education.csv** and **data/gpt-4-dataset-no_education.csv**: CSV files with responses from different demographics focused on participants with education excluded.
- **data/Strong Response Analysis.xlsx**: An Excel file analyzing strong responses such as "Not a feminist at all", "A strong feminist", "Strongly agree", and "Strongly disagree".
- **data/Democracy Checkup 2022 - Datasets.xlsx**: Preprocessed dataset from the Democracy Checkup 2022 survey in Canada, available [here](https://odesi.ca/en/details?id=/odesi/doi__10-5683_SP3_TEKM3T.xml).
- **data/CSV Canada Democracy DataSet.xlsx**: A preprocessed CSV export that features the typical response selected by the most number of respondents.

## Setup and Requirements

1. **Python Environment**: Ensure you have Python installed. Use the `requirements.txt` file to install necessary libraries with `pip install -r requirements.txt`.
2. **OpenAI and Replicate API Keys**: Set your OpenAI API key in your environment variables. If you're using Replicate models, set your Replicate API token similarly.

## Usage

To run the notebooks and scripts:

1. Open `AIDemocracyPrompts.ipynb` in a Jupyter environment.
2. Follow the instructions within the notebook to execute the code blocks.
3. Explore the JSON and CSV outputs for insights into the LLMs' performance across different demographics.

## Contributions

Contributions to this project are welcome. You can contribute by:

- Improving the code for efficiency.
- Extending the analysis to more demographic groups.
- Enhancing the visualization tools used in the demonstrations.

## License

This project is licensed under the GPL-3.0 license

## Citation

If you use the data or findings from this project, please cite:
Khai Tran, Sev Geraskin, Doroteya Stoyanova, Jord Nguyen
Assessing Algorithmic Bias in Large Language Models' Predictions of Public Opinion Across Demographics

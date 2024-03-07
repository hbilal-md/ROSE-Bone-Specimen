# Rapid On-Site Evaluation (ROSE) Adequacy Rates in Bone Specimen

## Project Overview

This repository contains the Jupyter notebooks for a scientific project focused on the Rapid On-Site Evaluation (ROSE) of bone specimens collected during biopsy/FNA procedures. The goal of this project is to assess the adequacy rates of bone specimens during ROSE and to explore the influence of different malignancy types on these outcomes. Our study is rooted in the analysis of 86,360 ROSE cases, focusing on 3,337 bone specimens, at a large cancer center between January 2015 and July 2023.

## Background

ROSE plays a crucial role in biopsy/FNA procedures by providing immediate feedback on the sample quality, thus reducing the need for repeat procedures and facilitating timely ancillary tests. However, the challenges associated with bone biopsies necessitate a deeper understanding of adequacy rates and potential impacts of malignancy types on these rates.

## Methods

Our study utilized a retrospective cohort analysis approach, employing Python’s natural language processing libraries to analyze pathology reports and concurrent surgical reports. By extracting diagnostic and metastatic cancer type data, we were able to calculate and stratify the adequacy rates of bone biopsy/FNA by tumor type. A two-proportion Z-test was used to determine statistical significance when comparing these rates to the overall adequacy statistics for all specimens.

## Repository Contents

- `Jupyter Notebooks`: Contains the Python notebooks used for data analysis, including data cleaning, processing, and statistical analysis.
- `Data`: Due to privacy and confidentiality concerns, raw data are not provided. However, the notebooks include detailed commentary on the data structure and analysis methods.
- `Results`: Visualizations and summary statistics generated from the analysis.

## Getting Started

To replicate this analysis or adapt it for your own research, you'll need:
- Python 3.x
- Pandas library
- Natural Language Processing (NLP) libraries used in the study (e.g., NLTK, spaCy)

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Install the required Python libraries mentioned above.
4. Navigate to the `Jupyter Notebooks` directory and open the notebooks to view the analysis.

## Contributing

We welcome contributions from the scientific and developer community. If you have suggestions for improving this analysis or have found an issue, please open an issue or submit a pull request.

## License

[MIT License](LICENSE.md) - This project is open-sourced under the MIT license. Feel free to use it as you wish.

## Contact

For any inquiries or collaboration proposals, please contact Hasan Bilal at h.bilal.md@gmail.com

## Acknowledgements

Special thanks to the team at Memorial Sloan Kettering Cancer Center for providing access to the cases database and supporting this research initiative.


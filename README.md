# Data Science Tools and Ecosystem

A Jupyter notebook that summarizes common data science languages, libraries, and tools, and runs a few Python arithmetic examples.

## Features

The repository contains one notebook, `DataScienceEcosystem.ipynb`. It includes:

- An introduction stating that data science tools and the ecosystem are summarized.
- A numbered list of languages: Python, SQL, and R.
- A numbered list of libraries: NumPy, Keras, Pandas, PyTorch, SciPy, Scikit-Learn, TensorFlow, and Matplotlib. These names appear only in markdown; the code cells do not import them.
- A markdown table of tools: Jupyter Notebook, RStudio, and Visual Studio Code.
- Three executable Python examples:
  - `45 + 55`, which prints `100`
  - `(3 * 4) + 5`, which prints `17`
  - converting 200 minutes to hours by dividing by 60, which prints `200 minutes is equal to 3.3333333333333335 hours`
- A bulleted list of learning objectives.
- An author line: Inas Farras.

## Tech stack

- Jupyter Notebook, nbformat 4.5
- Python 3, kernel display name `Python 3 (ipykernel)`, language version recorded in the notebook metadata as `3.11.2`
- Code cells use only built-in arithmetic and `print`. There is no dependency file and no third-party import.

## Setup

1. Install Python 3 and a notebook client such as Jupyter Notebook, JupyterLab, or Visual Studio Code with Jupyter support. The notebook metadata records Python 3.11.2.
2. Clone the repository and open the notebook:

```bash
git clone https://github.com/inasfarras/DataScienceEcosystem.git
cd DataScienceEcosystem
```

3. Open `DataScienceEcosystem.ipynb` in your notebook client.

## Usage

Run the code cells from top to bottom. There is no command-line entry point, configuration file, or extra data file. The three code cells print the arithmetic results listed above. Saved outputs in the notebook match those results.

## License

This project is licensed under the MIT License. Copyright (c) 2026 Farras Inas. See [LICENSE](LICENSE).

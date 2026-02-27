# Code: NIH DMPs LLM Evaluation Paper

## Overview

This repository contains the code associated with the paper, “Evaluating the Performance of LLMs in Drafting NIH Data Management Plans.” In the paper, we evaluated the performance of Llama 3.3 and GPT 4.1 in drafting NIH-compliant Data Management Plans (DMPs) using two complementary approaches: automatic reference-based evaluation and human expert evaluation.

The repository includes the complete automated and human evaluation workflows. Please refer to the project **[inventory](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-inventory)** for all related resources, including the paper.

---

## Standards followed

The overall codebase is organized in alignment with the **[FAIR-BioRS guidelines](https://fair-biors.org/)**. All Python code follows **[PEP 8](https://peps.python.org/pep-0008/)** conventions, including consistent formatting, inline comments, and docstrings. Project dependencies are fully captured in **[requirements.txt](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-code/blob/main/requirements.txt)**.

---

## Getting Started

### Step 1 — Clone the repository

```bash
git clone https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-code.git
cd dmpchef
code .
```

### Step 2 — Create and activate a virtual environment

**Windows (cmd):**

```bash
python -m venv venv
venv\Scripts\activate.bat
```

**macOS/Linux:**

```bash
python -m venv venv
source venv/bin/activate
```

### Step 3 — Install dependencies

```bash
pip install -r requirements.txt
```

---

### Step 4- Running the Notebook in two approaches

This repository supports two complementary evaluation workflows. Use the appropriate notebook depending on the evaluation approach you want to run.

#### Automatic reference-based evaluation

Use: [`Automated-evaluation.ipynb`](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-code/blob/main/Automated-evaluation.ipynb)

#### Human expert evaluation

Use: [`Human-evaluation.ipynb`](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-code/blob/main/Human-evaluation.ipynb)

---

## Inputs and Outputs

The Jupyter notebook makes use of files in the dataset associated with the paper. You will need to download the dataset at add it in the input folder (call the dataset folder 'dataset'). Please refer to the project **[inventory](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-inventory)** for a link to the dataset.

All outputs from both evaluation pipelines (tables and figures) are saved under the `outputs/` directory.

---

## License

This work is licensed under the **[MIT License](https://opensource.org/license/mit/)**. See **[LICENSE](LICENSE.txt)** for more information.

---

## Feedback and contribution

Use **[GitHub Issues](https://github.com/fairdataihub/nih-dmp-llm-evaluation-paper-code/issues)** to submit feedback, report problems, or suggest improvements. You can also **fork** the repository and submit a **Pull Request** with your changes.

---

## How to cite

If you use this code, please cite this repository using following the instructions in the [CITATION.cff](CITATION.cff) file.

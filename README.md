# AI_In_Healthcare_Final

## Objective
The goal of this project is to explore how Natural Language Processing (NLP) and Large Language Models (LLM) can be applied to extract ideas from medical prescriptions. This project is divided into two parts:

1. **Reproduction of Results from a Recommended Paper**: We reproduce the results of a paper by re-implementing its feature engineering, data preprocessing, and model training/evaluation. Due to computing limitations, the results may underperform when compared to the original paper.
2. **LLM Implementation**: We implement another LLM solution using an API, successfully generating the desired results.

## Project Structure

<pre> ``` ├─ LLM └─ Reproduction of Article ├─ 01 Documents ├─ 02 Reference Papers ├─ 03 Code │ ├─ .ipynb_checkpoints │ └─ __pycache__ └─ 04 Generated File └─ meddec-mimic-iii ├─ data └─ raw_text ``` </pre>
            
## Setup and Installation

### Step 1: Install Dependencies
To set up the project, install the necessary dependencies listed in the `requirements.txt`. Follow these steps:

1. **Prepare `requirements.txt`**:
   - Ensure `requirements.txt` contains the names of libraries without versions (e.g., `numpy`, `pandas`, etc.).
   
2. **Install dependencies**:
   Open a terminal and run the following command:
   ```bash
   pip install -r requirements.txt
This will automatically install all required packages, and pip will resolve any version conflicts.

### Step 2: Reproduction of the Paper
Due to limited computing resources, even after successfully implementing the feature engineering, data preprocessing, and model training/evaluation, the results may still underperform. To adapt the process for Colab, we've modified the original code and migrated it to a notebook stored in the /code folder.

All other necessary files and packages are included and imported as needed (these are already handled within the notebook).

### Step 3: LLM Implementation
In this part of the project, we leverage an API to generate results using a different LLM. Ensure all dependencies are properly installed and set up before running this code

### Notes
- The project uses Colab for running the notebooks with the necessary configurations for optimal performance.
- If any issues arise with the dependencies or installations, feel free to refer to the requirements.txt for troubleshooting.

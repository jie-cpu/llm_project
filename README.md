# llm_project

This project contains notebooks and datasets for experiments with Multiple Choice Questions (MCQ) and Short Answer Questions (SAQ).

## Repository structure

- `mcq+saq_llm.ipynb` — main notebook with data preprocessing, training, and evaluation examples
- `dataset/` — training and test datasets (MCQ / SAQ)

## Usage

1. Open `mcq+saq_llm.ipynb` in VS Code or Jupyter.
2. Run the notebook cells sequentially to load data, train models, and evaluate.

### Running on Google Colab

- Open the notebook in Colab via **File → Open notebook → GitHub** and paste the notebook URL or repo URL.
- Optionally select **Runtime → Change runtime type → GPU** for faster training.
- Install any required packages in a cell, for example:

  ```bash
  !pip install -r requirements.txt
  ```

- If external API keys are needed, set them as environment variables or use Colab's secrets mechanism.

### Running on Capella

- Upload or import `mcq+saq_llm.ipynb` into your Capella workspace (or the notebook runner provided by your cloud provider).
- Ensure required Python packages are installed and any necessary environment variables (API keys) are set.
- Choose an appropriate runtime (CPU/GPU) and run the notebook cells.

## Contributing

Issues and pull requests are welcome. If you'd like me to add a License, dependency list, or running examples, please let me know.

**Author**: Your Name (editable)

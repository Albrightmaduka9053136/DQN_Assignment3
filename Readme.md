# DQN Assignment 3

**Student Name:** YOUR NAME  
**Student ID:** YOUR ID  
**Course:** CSCN8020  
**Assignment:** Assignment 3

## Summary
This repository contains a Jupyter Notebook implementation of a Deep Q-Network (DQN) agent for the Atari environment. The notebook implements image preprocessing, frame stacking, experience replay, and a target network, and includes experiments and evaluation that produce CSV result files.

## Files
- `DQN_Assignment3.ipynb` - main notebook (run this to reproduce experiments)
- `assignment3_utils.py` - preprocessing & helper functions
- `requirement.txt` - Python dependencies (generated from pip freeze)
- `results/` - CSV output files generated during training/evaluation

## How to Run
1. Create and activate a Python virtual environment (recommended):
   ```powershell
   python -m venv .venv
   .\\.venv\\Scripts\\Activate.ps1   # PowerShell
   # or: .\\.venv\\Scripts\\activate  # cmd
   ```
2. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```
3. Start Jupyter and open the notebook:
   ```bash
   jupyter notebook DQN_Assignment3.ipynb
   ```
4. Run the notebook cells in order. The notebook contains sections for training, evaluation, and exporting results.

## Results
- Output CSV files are saved to the `results/` directory. Example files:
  - `baseline_results.csv`, `batch16_results.csv`, `final_evaluation_results.csv`, `summary_table.csv`, `target3_results.csv`.
- To regenerate results, run the relevant training/evaluation cells in `DQN_Assignment3.ipynb`.

## Notes
- The repository was prepared for the CSCN8020 assignment; replace the student placeholders above with your name and ID.
- If you need GPU acceleration, ensure the environment has the proper CUDA/cuDNN setup and compatible versions of PyTorch or TensorFlow (as used in the notebook).

## Contact
For questions, open an issue or contact the author listed in the notebook header.
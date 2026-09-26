# E-ALAEF Reproducibility

Reproducibility resources for the E-ALAEF Drebin-based classification evaluation.

## Contents

This repository provides the scripts required to reconstruct the reported classification metrics and confusion matrix from the fixed counts reported in the manuscript.

### Files

- `confusion_matrix_reconstruction.py`  
  Reconstructs the reported confusion matrix and classification results.

- `metric_calculation.py`  
  Calculates accuracy, precision, recall, and F1-score from the reported classification counts.

- `README.txt`  
  Provides additional reproducibility information and instructions.

## Reproducibility

The supplied scripts use the fixed classification counts reported in the manuscript. They do not require access to private datasets or training data.

Running the scripts allows independent reconstruction of the reported evaluation metrics and confusion matrix.

## Requirements

- Python 3.x
- Standard Python libraries

No external machine-learning framework is required for the reconstruction scripts.

## Usage

Run the metric calculation script:

```bash
python metric_calculation.py

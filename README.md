# Custom Bar Visualization with Color and Uncertainty

> A Matplotlib notebook exploring how color can help readers judge sampled bar values relative to a reference threshold.

## Overview

A Matplotlib notebook exploring how color can help readers judge sampled bar values relative to a reference threshold. This repository preserves the implementation, source data or supporting artifacts, and the original project outputs so the work can be reviewed and reproduced.

## Motivation

Bar charts built from sampled data can encourage overconfident comparisons when uncertainty is hidden. Color mapping offers an additional cue for interpreting whether values fall above, below, or near a reference level.

## Goal and Research Question

**Goal:** Build a custom bar visualization that combines summary values, uncertainty, and a normalized color scale.

**Question:** How can color improve judgments about probabilistic bar-chart values relative to a user-selected y-axis threshold?

## Technical Approach

1. Generate sampled data across multiple years and groups.
2. Compute yearly summary statistics.
3. Normalize values for colormap assignment.
4. Render bars with Matplotlib and apply colors relative to the comparison level.
5. Present the visualization in an interactive notebook.

## Tech Stack

| Technology | Role |
|---|---|
| Python | Analysis environment |
| pandas and NumPy | Sample organization and summary statistics |
| Matplotlib | Bars, normalization, colormaps, and interaction |
| Jupyter Notebook | Interactive presentation |

## Results and Deliverables

- The notebook builds and displays the custom color-encoded bar visualization.
- The saved output includes the generated data table and interactive Matplotlib figure.
- The project demonstrates a visual-communication concept rather than a predictive result.

## Repository Contents

| Path | Purpose |
|---|---|
| `Building a Custom Visualization of Bar using Color.ipynb` | Executable visualization |
| `Building a Custom Visualization of Bar using Color.pdf` | Static notebook export |

## Getting Started

Clone the repository:

```bash
git clone https://github.com/CS-Ponkoj/Building-a-Custom-Visualization-of-Bar-using-Color.git
cd Building-a-Custom-Visualization-of-Bar-using-Color
```

### Requirements

```bash
python -m pip install pandas numpy matplotlib jupyter
```

### Run or Review

```bash
jupyter notebook "Building a Custom Visualization of Bar using Color.ipynb"
```

## Reproducibility Notes

- Results above come from code, saved notebook outputs, or artifacts currently stored in this repository.
- Paths from the original development environment may need to be changed to repository-relative paths.
- Re-run the work after dependency changes before comparing new outputs with the recorded values.

## Limitations and Next Steps

- Interpretation depends on the selected reference value and colormap.
- Future work can add uncertainty intervals, a legend, accessible colors, and a user-facing threshold control.

## Author

**Ponkoj Shill**  
AI/ML researcher and Ph.D. candidate in Computer Science

- [GitHub](https://github.com/CS-Ponkoj)
- [Portfolio](https://ponkoj.com)

## License

No license file is currently included. Please contact the author before reusing the project beyond review, education, or fair-use evaluation.

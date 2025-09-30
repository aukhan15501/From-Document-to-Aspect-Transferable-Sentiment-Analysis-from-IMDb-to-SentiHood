# From-Document-to-Aspect-Transferable-Sentiment-Analysis-from-IMDb-to-SentiHood
Transferable Sentiment Analysis applying transformer models to IMDb movie reviews for document-level sentiment classification, then adapting to fine-grained aspect-based sentiment analysis on the SentiHood dataset of London neighborhoods, with dual training tracks and an interactive Gradio demo.

# Transferable Sentiment Analysis: IMDb to SentiHood

This repository contains code, documentation, and resources for investigating transferable sentiment analysis from document-level movie reviews (IMDb dataset) to fine-grained aspect-based sentiment analysis on urban neighborhoods (SentiHood dataset). The work evaluates two training strategies — transfer learning (Track A) and training from scratch (Track B) — using transformer architectures and includes an interactive Gradio demo for real-time testing.

---

## Repository Structure
Sentiment_Analysis_Project/
│
├── notebooks/                       # Jupyter notebooks for all experiments and demos
│   ├── Sentiment__Analysis_V4.ipynb            # IMDb document-level sentiment training
│   ├── Aspect_Analyses_with_results_v1.ipynb   # Aspect-level sentiment (Track A & B)
│   └── Gradio_app.ipynb                        # Interactive Gradio demo
│
├── results/                        # Outputs from experiments and demos
│   └── demo_output_video.mp4                   # Demonstration video file
│
├── docs/                          # Documentation and reports
│   └── Digital_Huminities_AI_ABSA.pdf          # Full research report and analysis
│
├── src/                           # (Optional) Source code and helper modules if any
│
├── requirements.txt               # Python dependencies and package list
├── README.md                     # Project overview and setup instructions (this file)



---

## Description of Contents

- **notebooks/**: Jupyter notebooks containing core experiments and demo code:
  - `Sentiment__Analysis_V4.ipynb`: Training BERT models on IMDb for document-level sentiment.
  - `Aspect_Analyses_with_results_v1.ipynb`: Aspect-based sentiment training/evaluation on SentiHood with track comparisons.
  - `Gradio_app.ipynb`: Web demo enabling inference for both document and aspect-level sentiment tasks.

- **results/**: Output files demonstrating experimental results, including:
  - Recorded demo videos showcasing model behavior and output. (Screenshots are excluded to avoid clutter.)

- **docs/**: Contains the full research report in PDF format (`Digital_Huminities_AI_ABSA.pdf`) describing:
  - Motivation and related work.
  - Dataset descriptions and preprocessing.
  - Detailed methodology.
  - Experimental results with evaluation metrics.
  - Discussion and conclusions.

- **requirements.txt**: Lists the Python packages required to run notebooks and demos.

---

## Installation and Usage

1. Clone the repository:


2. Run notebooks in order depending on needs:
- Train models using `Sentiment__Analysis_V4.ipynb`
- Perform aspect sentiment experiments using `Aspect_Analyses_with_results_v1.ipynb`
- Launch the Gradio demo with `Gradio_app.ipynb`

3. View results and demo outputs under `results/`.

4. Read the full report in the `docs/` folder for comprehensive understanding.

---

## Contribution and Discussion

Contributions, issues, and suggestions are welcome. Please open an issue or pull request on GitHub.

---

## Acknowledgments

This research is supervised by Dr. Dinara Gagarina at Friedrich Alexander University Erlangen-Nuremberg.

---

Thank you for exploring this repository!


# Capstone Step 4 Presentation: Mind Reading Devices Research

## Slide 1: Title Slide

*   **Title:** Capstone Step 4: Surveying Research on Mind Reading Devices (BCIs)
*   **Student Name:** [Your Name]
*   **Date:** May 2, 2025
*   **Project Topic:** Mind Reading Devices (EEG-to-Text Focus)

## Slide 2: Project Overview & Objectives (Step 4)

*   **Goal:** Survey existing research and publicly available solutions related to mind-reading devices (specifically EEG-to-Text).
*   **Objectives:**
    *   Identify relevant research papers.
    *   Find associated public code/solutions.
    *   Attempt reproduction of a selected solution.
    *   Analyze findings and compare approaches.
    *   Document process and results.
    *   Draw conclusions and identify potential improvements for Capstone.

## Slide 3: Research Summary - Key Papers & Findings

*   **Focus:** Non-invasive EEG-based Brain-Computer Interfaces (BCIs) for communication.
*   **Key Papers Found:**
    *   Nature News Feature (Mind-reading devices revealing brain secrets)
    *   AI and Ethics (Evaluating claims, hype, neurorights)
    *   Science and Engineering Ethics (Ethical issues from consumer devices)
    *   Frontiers in Psychology (How to deal with mind-reading tech)
    *   UTS News / NeurIPS 2023 Paper (DeWave: Portable EEG-to-Text)
*   **Key Findings:**
    *   Shift towards non-invasive methods (EEG) combined with AI.
    *   DeWave model (UTS/NeurIPS) as a state-of-the-art example using EEG + Transformers.
    *   Significant ethical considerations (privacy, hype, neurorights).
*   **(Link to `research_summary.md` for details)**

## Slide 4: Public Code Survey - DeWave / EEG-To-Text

*   **Primary Target:** DeWave model (NeurIPS 2023)
*   **Repositories Found:**
    *   `duanyiqun/DeWave`: Original author repo, mainly results/visuals.
    *   `NeuSpeech/EEG-To-Text`: Appeared more complete, included implementation & potential fixes.
*   **Selected Repository for Reproduction:** `NeuSpeech/EEG-To-Text`
*   **(Link to `code_repositories.md` for details)**

## Slide 5: Reproduction Attempt - NeuSpeech/EEG-To-Text

*   **Goal:** Reproduce results from the DeWave implementation.
*   **Process:**
    1.  Cloned repository.
    2.  Attempted environment setup based on `environment.yml`.
    3.  Identified required dataset: ZuCo 1.0 (Task 2 - NR, `.mat` files).
    4.  Attempted dataset download from OSF (https://osf.io/q3zws/).
*   **Challenges Encountered:**
    *   **Dependency Issues:** Required specific older versions (PyTorch 1.9+cu111, Scipy 1.6.2) were unavailable or incompatible. Workaround: Installed newer CPU-only PyTorch (1.13.1+cpu) and latest versions of other dependencies.
    *   **Dataset Download Failure:** Repeatedly unable to download necessary `.mat` files from OSF using available tools. Clicks on download links/buttons failed.
*   **Outcome:** Reproduction **Blocked** due to inability to acquire the dataset. Data preprocessing and model execution could not proceed.

## Slide 6: Analysis & Comparison

*   **Approaches Compared:**
    *   Invasive BCIs (Implants): High signal, high risk/cost.
    *   Non-Invasive fMRI + AI: Good spatial res, impractical (immobile, slow).
    *   Non-Invasive EEG + AI (DeWave): Portable, practical, good temporal res, lower signal quality requires advanced AI.
*   **DeWave Significance:** Represents a practical SOTA for non-invasive, portable thought-to-text.
*   **Baseline:** DeWave reported ~40% BLEU-1 on ZuCo NR task.
*   **(Link to `analysis_conclusion.md` for details)**

## Slide 7: Conclusion & Learnings

*   **Learnings:**
    *   EEG+AI (like DeWave) is a promising direction for practical BCIs.
    *   Reproducibility challenges (dependencies, dataset access) are significant.
    *   Ethical considerations are crucial.
*   **Capstone Relevance:**
    *   Established baseline performance (~40% BLEU-1).
    *   Identified SOTA approach (DeWave).
    *   Highlighted challenges (data, environment) to consider.

## Slide 8: Potential Capstone Improvements

*   **Ideas based on Survey:**
    *   Improve EEG preprocessing/feature engineering.
    *   Explore alternative model architectures (beyond DeWave).
    *   Test cross-dataset generalization.
    *   Investigate real-time implementation challenges.
    *   Focus on specific components (e.g., encoding).
    *   Incorporate ethical safeguards.
*   **(Link to `analysis_conclusion.md` for details)**

## Slide 9: Deliverables & GitHub

*   **Documents Produced:**
    *   `research_summary.md`
    *   `code_repositories.md`
    *   `analysis_conclusion.md` (includes reproduction attempt details)
    *   `presentation_outline.md` (this file)
*   **Code:**
    *   Cloned repositories (`DeWave`, `EEG-To-Text`) - *Note: No executed code due to blockage.*
*   **GitHub:** All documents and relevant files will be organized and uploaded.

## Slide 10: Q&A / Discussion


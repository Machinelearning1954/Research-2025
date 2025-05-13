# Code Repositories: Mind Reading Devices / EEG-to-Text

This document lists the publicly available code repositories identified during the research phase for the Capstone project Step 4, focusing on EEG-to-text translation.

## 1. DeWave (Primary Implementation)

- **URL:** https://github.com/duanyiqun/DeWave
- **Authors/Maintainers:** Yiqun Duan (Based on search results, likely the first author of the paper)
- **Description:** This repository appears to be the official implementation for the NeurIPS 2023 paper "DeWave: Discrete Encoding of EEG Waves for EEG to Text Translation". It focuses on translating EEG signals directly into text using discrete encoding (VQ-VAE) and integrating with large language models. It likely contains the code necessary to reproduce the results presented in the paper, potentially including model architecture, training scripts, and evaluation metrics.
- **Related Paper:** DeWave: Discrete Encoding of EEG Waves for EEG to Text Translation (NeurIPS 2023)
- **Status:** Appears to be the most relevant repository for reproduction based on the research.

## 2. NeuSpeech/EEG-To-Text

- **URL:** https://github.com/NeuSpeech/EEG-To-Text
- **Authors/Maintainers:** NeuSpeech organization
- **Description:** This repository also focuses on EEG-to-Text translation and explicitly mentions the DeWave paper. It might contain a fork, a modified version, or related experiments based on the DeWave framework. The description mentions a "corrected version to use model.generate to evaluate the model", suggesting potential improvements or alternative evaluation methods.
- **Related Paper:** Mentions DeWave.
- **Status:** Could be a valuable secondary resource or comparison point after exploring the primary DeWave repository.

## 3. MikeWangWZHL/EEG-To-Text

- **URL:** https://github.com/MikeWangWZHL/EEG-To-Text
- **Authors/Maintainers:** MikeWangWZHL
- **Description:** This repository is for the AAAI 2022 paper "Open Vocabulary Electroencephalography-To-Text Decoding and Zero-shot Sentiment Classification". While related to EEG-to-Text, it represents an earlier approach (pre-DeWave) and might focus on different techniques or objectives (like zero-shot sentiment classification).
- **Related Paper:** Open Vocabulary Electroencephalography-To-Text Decoding and Zero-shot Sentiment Classification (AAAI 2022)
- **Status:** Represents prior work in the field, potentially useful for comparison but less likely for direct reproduction for this specific capstone step focused on recent research.

## 4. EEG2Text (Multi-view Contrastive Learning)

- **URL:** Mentioned in a search result (https://www.computer.org/csdl/proceedings-article/bigdata/2024/10825980/23yl5pp1fri) with a GitHub link likely associated.
- **Authors/Maintainers:** Unknown from search snippet.
- **Description:** This seems to be another EEG-to-Text approach, potentially using multi-view contrastive learning, presented at IEEE BigData 2024. It represents another recent development in the field.
- **Related Paper:** EEG2Text: Open Vocabulary EEG-to-Text Translation with Multi-view Contrastive Learning (IEEE BigData 2024)
- **Status:** Another potential candidate for exploration or comparison, depending on code availability and feasibility.

This repository contains the code, model, and outputs of the experimental implementation for the paper 
## "Evaluating Structural and Linguistic Quality in Urdu DRS Parsing and Generation through Bidirectional Evaluation"

Here, we include:

1. **Code:** This folder contains scripts to run semantic parsing and text generation models. 
2. **Evaluation:** This folder contains the scripts to evaluate the experiments reported in the paper. Both parsing and generation folders contain separate evaluation scripts.
3. **model-outputs:** This folder contains model-generated outputs for semantic parsing and generation.

Our pre-trained models are publicly available.
For the semantic parsing model for Urdu see (https://huggingface.co/saadamin2k13/urdu_semantic_parsing) and for the Text generation model for Urdu see (https://huggingface.co/saadamin2k13/urdu_text_generation)


**1. The figure below represents different graphical DRS representations for Urdu.**

<img width="895" alt="Screenshot 2024-12-13 at 17 54 18" src="https://github.com/user-attachments/assets/f1ab140e-441c-4c93-a940-6b119da37815" />


**2. Below is the Structural overlap-based evaluation measure: highlighting the limitations of SMATCH.**

<img width="970" alt="Screenshot 2024-12-13 at 17 54 42" src="https://github.com/user-attachments/assets/2ffa94c6-f9ea-4439-bd52-f3e3c909f161" />



**3. Semantic overlap-based evaluation measures: highlighting limitations of automatic evaluation metrics for text generation.**

<img width="970" alt="Screenshot 2024-12-13 at 17 54 55" src="https://github.com/user-attachments/assets/d096b658-20e3-47ae-b95c-450d2b943d6e" />


**4. The table below represents our results for counter-evaluation of semantic parsing through par-gen.**

<img width="491" alt="Screenshot 2024-12-13 at 17 55 16" src="https://github.com/user-attachments/assets/1abcb119-ee2d-4262-a828-b101a9fbc293" />

**5. The table below represents our results for counter-evaluation of text generation through gen-pars.**

<img width="491" alt="Screenshot 2024-12-13 at 17 55 26" src="https://github.com/user-attachments/assets/36fcd712-7e17-44a7-8b82-a1cf914fc64e" />

**6. Evaluating PARS through PARS-GEN by taking examples from Table 1.**

<img width="944" alt="Screenshot 2024-12-13 at 17 55 52" src="https://github.com/user-attachments/assets/556564e1-d643-427d-964e-459fdba65886" />

**7. Evaluating GEN through GEN-PARS by taking examples from Table 2.**

<img width="944" alt="Screenshot 2024-12-13 at 17 56 03" src="https://github.com/user-attachments/assets/219c5a09-d707-4253-be76-9e08ac7c1b7f" />

**8. Correlation results for PARS and PARS-GEN.**

<img width="468" alt="Screenshot 2024-12-13 at 17 56 21" src="https://github.com/user-attachments/assets/7be99364-f60d-409d-a9a8-791472da45f5" />

**9. Correlation results for GEN and GEN-PARS.**

<img width="474" alt="Screenshot 2024-12-13 at 17 56 31" src="https://github.com/user-attachments/assets/9037b46f-0835-4002-aa13-70c6c4d74368" />


### Contributors
Muhammad Saad Amin, Luca Anselma, Alessandro Mazzei


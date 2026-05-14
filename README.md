# Computer Security Research Project

## Adversarial Attacks on Autonomous Vehicles: Comparing Camera-Only and Cross-Attention Fusion Models Under Single-Sensor Attack

**Author:** Mayrin A. Rivera Garcia  
**Course:** Computer Security  
**University:** The University of Texas at El Paso  

## Project Overview

This project evaluates the adversarial robustness of camera-only and camera–LiDAR cross-attention fusion models under camera-only FGSM attack. The goal is to determine whether robustness comes from the additional LiDAR modality, adversarial training, or the combination of both.

The project uses a controlled 2×2 comparison:
- Standard camera-only
- Adversarially trained camera-only
- Standard cross-attention fusion
- Adversarially trained cross-attention fusion

The main finding is that fusion alone was not robust under attack, but adversarially trained fusion achieved the best attacked accuracy overall.

## Project Structure

- `notebooks/CameraOnly_Experiments.ipynb`  
  Trains and compares a standard camera-only model and an adversarially trained camera-only model.

- `notebooks/CrossAttention_Experiments.ipynb`  
  Trains and compares a standard camera-LiDAR cross-attention fusion model and an adversarially trained fusion model.

- `notebooks/Final_2x2_Comparison.ipynb`  
  Compares all four models in the final 2×2 experiment.

## Full Experiments Outputs

Large generated outputs, plots, model checkpoints, and experiment files are hosted on Google Drive due to GitHub file-size limits.

Google Drive folder:  
https://drive.google.com/drive/folders/1EIZIH3pTlmqTNQbplPWcPbDpLnxS3CqK?usp=sharing

# Integrated System for Multi-Technique Contact Angle Measurements  
### Image-Based Algorithms under Controlled Pressure and Temperature

This repository provides base files for determining apparent contact angles using image-based processing methods. It includes synthetic droplet generation tools, validation of a novel multi-technique experimental device (BoonTap System), and practical examples organized by measurement technique.

---

## Repository Structure

- **SmartDroplet Toolkit**
  - Synthetic droplet generation and algorithm validation
- **BoonTap_System Validation**
  - HPHT system-level validation
- **Contact Angle Measurement Tools**
  - Sessile Drop
  - Captive Bubble
  - Tilted Plate

---

## SmartDroplet: Synthetic Droplet Generation & Analysis Toolkit

MATLAB tools for generating synthetic droplet contours, processing droplet shapes, and validating contact angle algorithms.

**Associated file:** `SmartDroplet_Toolkit_(Base_Algorithms).tar`

### Features
- Random droplet generation within predefined contact angle ranges
- Idealized contour generation for systematic validation
- Support for hydrophilic and hydrophobic regimes

### Statistical Validation
- Measured vs. true angle scatter plots
- Probability density functions of absolute error
- Bland–Altman agreement analysis
- MAE and RMSE segmented by angular ranges

---

## BoonTap_System Validation

The SmartDroplet toolkit was used to generate 1600 synthetic droplet contours covering the full wetting range (5°–173°).

Additionally, images of 3D-printed reference geometries representing hydrophilic, mixed, and hydrophobic wettability conditions were used to validate the BoonTap system under realistic optical and geometric constraints.

**Associated file:** `BoonTap_System_Validation.tar`

---

## Contact Angle Measurement Tools

### Sessile Drop
Static contact angle determination using deposited droplets.

**Associated file:** `Sessile_Drop_(Base_Algorithms).tar`

### Captive Bubble
Contact angle determination using trapped gas bubbles at liquid–solid interfaces.

**Associated file:** `Captive_Bubble_(Base_Algorithms).tar`

### Tilted Plate
Dynamic contact angle measurement on inclined surfaces.

**Associated file:** `Tilted_Plate_(Base_Algorithms).tar`

---

## Documentation

Each MATLAB script includes:
- Description and scope
- Configurable parameters
- Step-by-step workflow
- Automatically generated plots
- Usage instructions

---

## Applications

- Surface science research
- Wettability and interfacial studies
- Coating and material characterization
- Algorithm development and validation
- Education and training

---

## Dataset Purpose

This dataset supports reproducibility and validation of contact angle measurements under controlled pressure and temperature conditions, and complements published research in surface science and wetting phenomena.

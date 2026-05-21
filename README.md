# Perceptually Guided Blur Modeling

This repository hosts a website describing an experiment idea for studying perceptual blur in image and display systems.

The experiment is intended to investigate the kinds of blur users may experience, when those blur artifacts become visible, and how severe they appear to human observers.

To explore this, I explore how blur can be simulated, measured with human observers, and modeled computationally. The central idea is to connect physical blur parameters, such as defocus, motion blur, or resampling blur, to perceptual judgments of visibility and severity.

The website presents a proposed pipeline with four stages:

1. Generate controlled blur stimuli from sharp reference images
2. Measure human detection thresholds and perceived blur severity
3. Train a predictive model that estimates blur visibility from image content and blur metadata
4. Use the model to identify where blur is likely to be noticeable and guide targeted correction

This site serves as a visual overview of the experiment concept. It is not intended to be a full implementation of the pipeline yet.

## Website

Access the website here: https://dennisp7.github.io/blur_artifact_experiment/

## Files

- `index.html` contains the main website.
- Supporting images or assets are stored in the `assets/` folder.

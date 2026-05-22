# Perceptually Guided Blur Modeling

This repository hosts a website describing an experiment idea for studying perceptual blur in image and display systems.

The goal of the experiment is to understand which blur artifacts users can perceive, how severe those artifacts appear, and how this information can be used to prioritize image correction.

The proposed experiment has two main parts. First, different types of blur are simulated and applied to sharp reference images. These blur types may include defocus blur, motion blur, and blur caused by rendering or resampling. Second, human observers complete psychophysical tasks that measure whether they can detect the blur and how severe the blur appears.

The human responses provide the ground truth for the model. For each blurred image, the ground truth can include whether the blur was visible to observers and the perceived severity of the blur. The model is then trained to predict these perceptual measurements from the image content and blur parameters.

Once trained, the model can be used to evaluate new images or display outputs. It can predict which blur artifacts are likely to be visible, how severe they are likely to appear, and which types of blur are most common or most perceptually important. This makes it possible to focus correction efforts on the artifacts that are most likely to affect the user experience.

The website presents the proposed pipeline in four stages:

1. Generate controlled blur stimuli from sharp reference images
2. Measure human blur detection and perceived severity using psychophysical experiments
3. Train a model to predict human perceptual judgments from image content and blur metadata
4. Use the model predictions to identify the most important blur artifacts and guide targeted correction

This site serves as a visual overview of the experiment concept. It is not intended to be a full implementation of the pipeline yet.

## Website

Access the website here: https://dennisp7.github.io/blur_artifact_experiment/

## Files

- `index.html` contains the main website.
- Supporting images or assets are stored in the `assets/` folder.

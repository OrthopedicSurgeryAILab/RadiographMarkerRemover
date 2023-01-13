# RadiographMarkerRemover

This repository contains training scripts and hyperparameters for training a marker removal model.

All training bounding boxes are generated using the LabelMe (v5.0.1) software. These should be converted to appropriate format using the `annotation_conversion` file in the `/scripts` directory.

All training hyperparameters, both for initial training and finetuining are located at the `/config` folder.

You can use the training and finetuning scripts in the `/scripts` directory to  trainie your own object detection model.

# Changelog
01/13/2022: Initial Release ([Bardia Khosravi](https://github.com/BardiaKh))
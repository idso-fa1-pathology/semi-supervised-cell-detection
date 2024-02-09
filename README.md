# Advanced mIF Cell Detection with Semi-Supervised Learning

## Overview
This project introduces an innovative approach for enhancing cell detection in multiplex immunofluorescence (mIF) imaging through semi-supervised learning and pseudo-labeling, utilizing models like YOLOv8s for superior accuracy and efficiency.

## Project Structure
- **manuscript/**: Contains detailed documentation of the research, including study design, methodologies, results, and conclusions. This section is crucial for anyone looking to understand the theoretical background or replicate the study.
- **.DS_Store**: System file created by macOS to store custom attributes of a folder.
- **.gitattributes**: Controls Git's handling of file attributes, useful for defining how diffs and merges should be performed for specific files.
- **LICENSE**: Specifies the MIT License under which this project is distributed, outlining permissions for use, distribution, modification, etc.
- **README.md**: Provides an overview of the project, installation instructions, usage guide, and additional information for users and contributors.
- **annotations_preprocessing.ipynb**: Jupyter notebook for preprocessing annotation data, preparing it for model training.
- **faster_rcnn.ipynb**: Notebook demonstrating the application of the Faster R-CNN model within this project's context.
- **patches_extractions.ipynb**: Extracts image patches from larger scans, a critical step for processing and analyzing mIF images.
- **predictions_final_model.ipynb**: Generates predictions using the trained model, showcasing the effectiveness of the semi-supervised learning approach.
- **yolo_to_coco_fasterrcnn.ipynb**: Converts YOLO annotations to the COCO format, facilitating compatibility with Faster R-CNN.
- **yolov5.ipynb**, **yolov8s.ipynb**: Notebooks detailing the implementation and tuning of YOLOv5 and YOLOv8s models for cell detection, highlighting model-specific adjustments and optimizations.

## Figures

### Figure 1
![Figure 1](https://github.com/idso-fa1-pathology/semi-supervised-cell-detection/blob/main/manuscript/images/1.png?raw=true "Figure 1 Description")


### Figure 2
![Figure 2](https://github.com/idso-fa1-pathology/semi-supervised-cell-detection/blob/main/manuscript/images/2.png?raw=true "Figure 2 Description")

### Figure 3
![Figure 3](https://github.com/idso-fa1-pathology/semi-supervised-cell-detection/blob/main/manuscript/images/3.png?raw=true "Figure 3 Description")

### Figure 4
![Figure 4](https://github.com/idso-fa1-pathology/semi-supervised-cell-detection/blob/main/manuscript/images/4.png?raw=true "Figure 3 Description")






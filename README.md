# AI-Pet-Breed-Classifier

AI-Pet-Breed-Classifier is a machine learning–based image classification system that identifies pet species and dog breeds using deep learning. The project processes pet images, extracts ground-truth labels from filenames, applies a pre-trained convolutional neural network for classification, and evaluates model performance using standard metrics. Designed for educational and experimental purposes, this project demonstrates a complete end-to-end image classification pipeline.

## Features

- Classifies pet images using a pre-trained deep learning model  
- Extracts true pet labels directly from image filenames  
- Distinguishes between dogs and non-dogs  
- Supports dog breed classification  
- Computes evaluation metrics including accuracy, precision, and recall  
- Modular and pipeline-based design  
- Command-line interface for flexible execution  
- Built-in validation and result-checking utilities  

## System Workflow

Image Dataset → Label Extraction → Deep Learning Classification → Dog / Non-Dog Identification → Statistical Evaluation → Result Output

## Project Structure

AI-Pet-Breed-Classifier/
├── adjust_results4_isadog.py  
├── calculates_results_stats.py  
├── check_images.py  
├── classifier.py  
├── classify_images.py  
├── get_input_args.py  
├── get_pet_labels.py  
├── print_functions_for_lab_checks.py  
├── print_results.py  
└── README.md  

## Module Descriptions

adjust_results4_isadog.py  
Updates classification results by determining whether the predicted label corresponds to a dog.

calculates_results_stats.py  
Computes statistical performance measures such as accuracy, precision, and recall.

check_images.py  
Acts as the main entry point for executing the full image classification pipeline.

classifier.py  
Implements the classifier function that applies a pre-trained deep learning model to classify pet images.

classify_images.py  
Handles assigning predicted labels to images using the selected deep learning model.

get_input_args.py  
Parses and validates command-line arguments for flexible configuration.

get_pet_labels.py  
Extracts ground-truth pet labels from image filenames.

print_functions_for_lab_checks.py  
Provides validation functions to verify correct behavior at each pipeline stage.

print_results.py  
Formats and displays classification results and evaluation statistics.

## How to Run

python check_images.py --dir images/ --arch vgg --dogfile dognames.txt

## Learning Outcomes

- Understanding image classification pipelines  
- Using pre-trained deep learning models  
- Evaluating models with standard metrics  
- Building modular and testable ML systems  
- Applying command-line interfaces in ML workflows  

## Author

Ali Khatib  
AI / Machine Learning & Software Engineering  

## License

This project is intended for educational and experimental use.

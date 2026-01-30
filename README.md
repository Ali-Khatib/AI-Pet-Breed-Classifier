AI-Pet-Breed-Classifier

AI-Pet-Breed-Classifier is a machine learning–based image classification system that identifies pet species and dog breeds using deep learning. The project processes pet images, extracts labels from filenames, and applies a pre-trained convolutional neural network to classify each image. It is designed to demonstrate core concepts in computer vision, model evaluation, and pipeline-based ML system design.

The system follows a structured workflow: images are loaded from a dataset, true labels are extracted from filenames, and a deep learning classifier predicts labels for each image. The results are then refined to determine whether each image represents a dog or a non-dog, enabling both breed-level and species-level evaluation. Statistical metrics such as accuracy, precision, and recall are computed to assess model performance. The project also supports command-line execution, making it flexible and easy to test with different datasets and models.

This project is intended for educational and experimental use, providing hands-on exposure to image classification, result analysis, and modular ML system development.

Project Modules
adjust_results4_isadog.py

Updates classification results by determining whether the predicted label corresponds to a dog, enabling dog vs. non-dog analysis.

calculates_results_stats.py

Computes performance statistics such as accuracy, precision, recall, and related evaluation metrics based on classification outcomes.

check_images.py

Serves as the main entry point for running the full image classification pipeline.

classifier.py

Contains the classifier function that applies a pre-trained deep learning model to classify pet images.

classify_images.py

Manages the process of assigning predicted labels to images using the selected deep learning model.

get_input_args.py

Parses and validates command-line arguments, allowing flexible configuration of input directories, model selection, and output options.

get_pet_labels.py

Extracts true pet labels from image filenames for use as ground truth during evaluation.

print_functions_for_lab_checks.py

Includes validation functions to ensure correct behavior at each pipeline stage, such as argument parsing, label extraction, classification accuracy, and result computation.

print_results.py

Formats and displays classification results and performance statistics in a clear, readable manner.

# AI-Pet-Breed-Classifier
This project is a pet image classification system that utilizes deep learning models to identify and categorize images of pets. The system processes image datasets, extracts relevant labels, and applies a classifier to predict the category of each image. It includes modules for adjusting classification results, calculating statistics, and handling command-line arguments for flexible execution. The project also features utilities for timing execution and printing results. Designed for educational and experimental purposes, this tool helps users explore machine learning concepts in image recognition.


- **adjust_results4_isadog.py**:  
  - `adjust_results4_isadog`: Updates classification results by identifying whether the classified label is a dog.

- **calculates_results_stats.py**:  
  - `calculates_results_stats`: Computes statistical measures (accuracy, precision, recall) based on classification results.

- **check_images.py**:  
  - `main`: The main entry point for image classification processing.

- **classifier.py**:  
  - `classifier`: A function that utilizes a pre-trained model to classify images.

- **classify_images.py**:  
  - `classify_images`: Assigns labels to images using a deep learning model.

- **get_input_args.py**:  
  - `get_input_args`: Parses command-line arguments for running the script.

- **get_pet_labels.py**:  
  - `get_pet_labels`: Extracts pet labels from image filenames.

- **print_functions_for_lab_checks.py**:  
  - `check_command_line_arguments`: Verifies that command-line arguments are processed correctly.  
  - `check_creating_pet_image_labels`: Ensures pet image labels are correctly extracted.  
  - `check_classifying_images`: Confirms that images are classified accurately.  
  - `check_classifying_labels_as_dogs`: Validates whether classifications correctly distinguish between dogs and non-dogs.  
  - `check_calculating_results`: Ensures result calculations are accurate.

- **print_results.py**:  
  - `print_results`: Displays classification outcomes in a structured format.


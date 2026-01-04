# Identify Dog Breeds Using Pre-trained Classifiers

This project uses Python and pre-trained Deep Learning models to identify dog breeds from images. By leveraging architectures like **ResNet**, **AlexNet**, and **VGG**, the application compares performance in terms of accuracy and computational speed.

## Project Structure
- `check_images.py`: The main script that coordinates the classification process.
- `get_input_args.py`: Processes command-line arguments (image folder, model choice, etc.).
- `get_pet_labels.py`: Extracts ground-truth labels from image filenames.
- `classify_images.py`: Uses pre-trained models to predict image labels.
- `adjust_results4_isadog.py`: Determines if labels represent dogs using `dognames.txt`.
- `calculates_results_stats.py`: Generates final accuracy and performance statistics.

## Objectives
1. **Dog vs. Non-Dog Detection:** Distinguish between dog images and other animals/objects.
2. **Breed Classification:** Identify the specific breed for images confirmed as dogs.
3. **Model Benchmarking:** Compare the efficiency and precision of **ResNet**, **AlexNet**, and **VGG**.

## Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YannickYeh/Use-a-Pretrained-Image-Classifier-to-Identify-Dog-Breeds.git](https://github.com/YannickYeh/Use-a-Pretrained-Image-Classifier-to-Identify-Dog-Breeds.git)
   cd Use-a-Pretrained-Image-Classifier-to-Identify-Dog-Breeds

## Custom EasyOCR Model Training

This repository showcases my contributions to the custom EasyOCR model training project. I have utilized two main repositories for this project:

1. [TextRecognitionDataGenerator](https://github.com/Belval/TextRecognitionDataGenerator): I used this repository to generate synthetic images containing text. The custom font I selected was used to create diverse and realistic text samples for training.

2. [deep-text-recognition-benchmark](https://github.com/clovaai/deep-text-recognition-benchmark): I employed this repository to fine-tune and train my custom EasyOCR model using the synthetic images generated from the first repository.

## Steps Followed:

1. **Data Generation**: I utilized the TextRecognitionDataGenerator to generate synthetic images containing various text samples using a custom font. These images were crucial for training my custom EasyOCR model.

2. **Data Preprocessing**: Before training, I carefully preprocessed the generated synthetic images. This involved resizing, normalizing, and augmenting the data to enhance the model's robustness.

3. **Dataset Splitting**: I divided the preprocessed dataset into training, validation, and test sets. This ensured that the model generalizes well and performs effectively on unseen data.

4. **Model Configuration**: Using the deep-text-recognition-benchmark repository, I configured the custom EasyOCR model. I fine-tuned the architecture, layers, and parameters to match the characteristics of the synthetic dataset.

5. **Training**: I trained the custom EasyOCR model using the preprocessed and split dataset. The training process involved iterative optimization to improve the model's accuracy and recognition capabilities.

6. **Evaluation**: After training, I evaluated the performance of the custom EasyOCR model on the test set. This step helped me gauge the model's accuracy and identify areas for improvement.

7. **Fine-Tuning**: Based on the evaluation results, I fine-tuned the model further to address any performance gaps. This iterative process aimed to enhance the model's recognition accuracy.

8. **Model Deployment**: Once the model achieved satisfactory accuracy, I deployed it for text recognition tasks. The custom EasyOCR model was now capable of accurately recognizing text from a variety of images.
   
## Acknowledgments

I would like to thank the authors of the original repositories [link to original repositories] for their work, which served as the foundation for this project.

---
Feel free to reach out if you have any questions or suggestions about this project.


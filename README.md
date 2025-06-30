# Fine-tuning-a-Google-Image-Classification-Model-for-Processing-Medical-Images

Objective: To explore how a Vision Transformer, a model originally designed for image recognition tasks, can be adapted to classify blood cell images, enhancing our capabilities in medical diagnostics.

Dataset: Kaggle's Blood Cell Images dataset.
2,500 augmented photos of blood cells (JPEG) with corresponding cell type labels (CSV) are included in this dataset. For each of the four distinct cell types, there are over 3,000 photos organized into four distinct folders (based on cell type). The cell types include Neutrophils, Monocytes, Lymphocytes, and Eosinophils.

Execution and Evaluation:
Model Training: Using the Trainer from Hugging Face, I executed the training plan, automatically handling batch processing, loss calculation, and backpropagation.
Performance Monitoring: I utilized TensorBoard for real-time tracking of training metrics such as loss and accuracy, allowing us to visualize and optimize our training process.
The accuracy is 87.5%

Project Outcomes: The trained model demonstrated promising accuracy in classifying blood cell images, showcasing the potential of Vision Transformers in medical imaging tasks.
Challenges Encountered: I encountered challenges with deploying the model due to the size of the dataset and less resources.

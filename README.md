# Madhu-0203-Latent-Replay-Strategy-CL-on-CIC-IDS-2017
This notebook has a detailed analysis and visualization of the CIC-IDS-2017 dataset; In the next step, the dataset is trained and tested with the CNN model. Finally, I tried to apply Latent Replay Strategy (ML - Continual Learning) to the dataset.

**Detailed Description**
We integrated Latent Replay Strategy into CNN Model for Continual Learning. The project centers around enhancing the training process of CNN models by incorporating the Latent Replay Strategy. This strategy is aimed at addressing the challenge of catastrophic forgetting that often occurs in traditional machine learning models during continuous learning tasks. My task resonated around the pre-processing and exploratory analysis and the dataset and fitting CNN for the dataset. 

**Objective:**
The primary objective of this project is to design and implement a CNN model that effectively integrates the Latent Replay Strategy to mitigate the problem of forgetting previous task knowledge when new tasks are learned.

**Tools and Technologies:**
Madhumithaa utilized a powerful set of tools and libraries for this project:

**Python Libraries:** Pandas and NumPy for data manipulation and preprocessing.
**Deep Learning Frameworks:** PyTorch, and Keras for building and training the CNN model.

**Methodology:**

**Dataset Selection:** The CIC-IDS-2017 dataset, known for its complex network intrusion detection scenarios, was chosen as the foundation for the project.
**Data Preprocessing:** Preparing the dataset by cleaning, normalizing, and structuring it to ensure optimal model performance.
**CNN Architecture:** She designed a suitable CNN architecture to effectively process the network traffic data from the CIC-IDS-2017 dataset.
**Latent Replay Integration:** The core innovation of the project, Madhumithaa incorporated the Latent Replay Strategy by maintaining a reservoir of past task data. This reservoir was accessed and combined with new task data during batch-wise training, helping the model retain previous knowledge.
**Model Training:** Utilizing PyTorch, Keras, trained the integrated CNN model on multiple tasks, observing how the Latent Replay Strategy influenced its learning patterns.
**Evaluation:** The model's performance was evaluated on various metrics, such as accuracy, precision, recall, and F1-score, to gauge its ability to retain knowledge across tasks. 

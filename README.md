Bank Complaints Classification Using DistilBERT

Project Overview

This project demonstrates fine-tuning of DistilBERT (a smaller, faster version of BERT) for classifying Bank Complaints using Natural Language Processing (NLP). The model was trained on a dataset containing various customer complaints and their corresponding classifications.

Key Features

Model: DistilBERT (pre-trained on English corpus)
Dataset: Bank Complaints Dataset (Customer complaint text categorized into different classes)
Accuracy Before Fine-Tuning: 47%
Accuracy After Fine-Tuning: 86%

Technologies Used

Python: Programming language for data processing and machine learning.
Transformers (Hugging Face): Pre-trained models like DistilBERT.
PyTorch: Framework for deep learning.
Scikit-learn: For machine learning utilities like train-test split, metrics, etc.
pandas: For data manipulation and processing.
NumPy: For numerical operations.

Setup Instructions
1. Clone the Repository
Clone the repository to your local machine to get started:

bash
Copy code
git clone https://github.com/Sarath-peddireddy/BankComplaints_DistilbertFIneTuned.git
2. Install Dependencies
To install the required libraries, run:

bash
Copy code
pip install -r requirements.txt
3. Dataset
The dataset used in this project is the Bank Complaints Dataset. You can upload your own dataset or use the provided dataset in the /data directory.

Usage
1. Training the Model
To train the model, run the following command:

bash
Copy code
python train_model.py
This will load the pre-trained DistilBERT model, fine-tune it on the dataset, and save the trained model.

2. Making Predictions
To make predictions with the trained model, run:

bash
Copy code
python predict.py --input "Sample complaint text"
Results
Before Fine-Tuning: Model accuracy was 47%.
After Fine-Tuning: Model accuracy improved to 86%.
This improvement demonstrates the effectiveness of fine-tuning a pre-trained model for custom classification tasks.

Contributing
Contributions are welcome! Please fork the repository and submit pull requests. Ensure that your code adheres to the project's coding standards and includes appropriate test cases.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact Information
For questions, please reach out to sarathpeddireddy93477@gmail.com

Acknowledgements
Hugging Face for providing pre-trained models.
DistilBERT authors for their work on lightweight transformer models.

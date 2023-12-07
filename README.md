
### File Integrity Dataset Overview:

#### Features:
1. **Hash value (MD5):** MD5 hash value of the file.
2. **Hash value (SHA1):** SHA-1 hash value of the file.
3. **Object size:** Size of the file in bytes.
4. **Object type:** Type of the file (e.g., pdf, jpg, docx).
5. **Integrity_status:** Binary label indicating whether the file has integrity issues ('corrupted') or not ('intact').

#### Dataset Characteristics:
- The dataset contains a small number of instances with a binary classification task.
- Each instance represents a file with associated features and an integrity label.
- The file features include hash values, file size, and type, commonly used for integrity checks.

### Code Overview:

#### Code Files:
1. **`file_integrity_check.ipynb`:**
   - Evaluates the pre-trained machine learning model on the provided dataset.
   - Prints accuracy, confusion matrix, and classification report.
   - Trains a RandomForestClassifier using the dataset.
   - Uses features such as md5, sha1, file size, and file type for training.
   - Saves the trained model for later use.
2. **`dataset.xlsx`:**
   - Includes dataset

3. **`README.md`:**
   - Provides a comprehensive guide and overview of the project.
   - Includes instructions for installation, usage, dataset information, model training, evaluation results, and more.

4. **`requirements.txt`:**
   - Lists the dependencies required to run the code.

#### Code Execution:

1. **Installation:**
   - Clone the repository: `git clone https://github.com/yourusername/file-integrity-check.git`
   - Change to the project directory: `cd file-integrity-check`
   - Install dependencies: `pip install -r requirements.txt`

2. **Usage:**
   - Evaluate the model: `file_integrity_check.ipynb`

3. **Dataset:**
   - The dataset includes instances with features like md5, sha1, file size, file type, and integrity labels.

4. **Model Training:**
   - The model is trained using a RandomForestClassifier with features derived from file characteristics.

5. **Evaluation Results:**
   - The model achieved perfect accuracy on the provided test set.
   - The confusion matrix and classification report demonstrate flawless performance in distinguishing between 'corrupted' and 'intact' files.

### Conclusion:

This project focuses on developing and evaluating a machine learning model for file integrity checks. The dataset includes diverse file features, and the code provides a clear structure for training, evaluating, and using the model. 

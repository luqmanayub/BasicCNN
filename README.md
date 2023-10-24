<p><strong>Task 1: CNN Image Classification with TensorFlow</strong></p><p>This repository contains the solution to Task 1, which involves creating a Convolutional Neural Network (CNN) model from scratch for image classification using TensorFlow. The task requires splitting the dataset into training and validation sets, implementing data augmentation, and reporting the accuracy achieved after training for 10 epochs. The dataset comprises three classes of digits: 0, 1, and 2.</p><p><strong>Project Structure</strong></p><p>The repository is structured as follows:</p><ul><li><strong>BasicCNNmodel.ipynb</strong>: The Notebook containing the Python code for the task.</li><li><strong>Hand_written_digits/</strong>: The dataset folder containing subfolders for each class (0_digits, 1_digits, 2_digits).</li><li><strong>README.md</strong> (this file): Provides an overview of the project.</li></ul><p><strong>Task Description</strong></p><p>The main tasks in this assignment are as follows:</p><ol><li><strong>Data Split</strong>: The dataset is split into a training set (80%) and a validation set (20%). This is done programmatically using TensorFlow.</li><li><strong>Model Architecture</strong>: The CNN model architecture is defined with the following layers:<ul><li>Convolutional Layer 1 with 32 filters and ReLU activation</li><li>Max-Pooling Layer (2x2)</li><li>Convolutional Layer 2 with 64 filters and ReLU activation</li><li>Max-Pooling Layer (2x2)</li><li>Flattening Layer</li><li>Fully Connected Layer with 128 units and ReLU activation</li><li>Dropout Layer (50% dropout rate)</li><li>Output Layer with 3 units and softmax activation (corresponding to the three classes)</li></ul></li><li><strong>Data Augmentation</strong>: Data augmentation is applied using TensorFlow's <strong>ImageDataGenerator</strong>. Augmentation includes rotation, width and height shifts, shear, and zoom. Vertical and horizontal flips are disabled to avoid distorting the data.</li><li><strong>Model Training</strong>: The model is trained on the training set for 10 epochs, and validation accuracy is monitored to prevent overfitting.</li><li><strong>Model Evaluation</strong>: The model is evaluated on the validation set to report the accuracy achieved.</li></ol><p><strong>How to Use</strong></p><ol><li>Clone the repository to your local machine:</li></ol><p><strong>git clone https://https://github.com/luqmanayub/BasicCNN.git</strong></p><ol><li>Open and run the&nbsp;<strong>BasicCNNmodel.ipynb</strong> Notebook to see the code and results.</li><li>Ensure that you have the required libraries installed, such as TensorFlow, NumPy, and matplotlib.&nbsp;</li><li>You can install them using pip:</li></ol><p><strong>pip install tensorflow numpy matplotlib&nbsp;</strong></p><ol><li>Run the cells in the notebook to train and evaluate the model.</li></ol><p><strong>Validation accuracy of Basic CNN Model is: 0.9892818927764893</strong></p><p><strong>Conclusion</strong></p><p>This assignment demonstrates the creation of a basic CNN model for image classification, including data splitting, data augmentation, and model training. The accuracy achieved on the validation set provides a measure of the model's performance.</p>
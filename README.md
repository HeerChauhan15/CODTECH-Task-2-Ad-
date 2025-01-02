**Name**: Heer Chauhan <br>
**Company**: CODTECH IT SOLULTIONS <br>
**ID**: CS24NY354846 <br>
**DOMAIN**: DATA SCIENCE <br>
**DURATION**: DECEMBER TO JANUARY 2025 <br>

**OBJECTIVE** <br>
The objective of this project is to build a **deep learning model** using **TensorFlow** for **image classification**. The model will take images (e.g., handwritten digits from the MNIST dataset) as input and classify them into one of the predefined categories (digits 0–9). <br>
The project aims to:
1. **Learn image features automatically** using deep neural networks.
2. **Train a functional model** that can accurately predict the class of input images.
3. **Visualize results**, including training/validation accuracy and loss, to assess model performance. <br>
**Final Deliverable:**  
A trained model with visualizations of accuracy and loss during training, and the ability to make predictions on unseen data. <br>
**Technologies Used** <br>

1. **Programming Language:**  
   - **Python**: For implementing the deep learning model.

2. **Libraries and Frameworks:**  
   - **TensorFlow/Keras**: For building, training, and evaluating the deep learning model.  
   - **NumPy**: For numerical operations and array manipulations.  
   - **Matplotlib**: For visualizing training results (accuracy and loss).  
   - **Pandas**: (If needed) For loading and preprocessing datasets.  

3. **Dataset:**  
   - **MNIST Dataset**: A standard dataset of 28x28 grayscale images of handwritten digits (0-9) used for image classification tasks.

4. **Tools/Environment:**  
   - **Jupyter Notebook**: For interactive code development and visualization.  
   - **Google Colab** (Optional): For running the code in a cloud environment with GPU support.<br>

   **Explanation of the Summary:**

**1.Output Shape:**

Flatten: Converts the input (28x28) into a 1D array of shape (None, 784), where None is the batch size.<br>
Dense (128): Outputs a 1D array of shape (None, 128).<br>
Dense (10): Outputs a 1D array of shape (None, 10) (probabilities for 10 classes).<br>

**2.Parameters (Param #):**

Flatten: Has no parameters to learn.<br>
Dense (128 neurons): 784 (input features) x 128 (neurons) + 128 (bias terms) = 100,480.<br>
Dense (10 neurons): 128 (input features) x 10 (neurons) + 10 (bias terms) = 1,290.<br>
   ![image](https://github.com/user-attachments/assets/227b89be-1870-442c-aa8e-7c440291e470)<br>
   ![image](https://github.com/user-attachments/assets/f70f7243-8a8c-459b-88ac-ed923cd1d949)

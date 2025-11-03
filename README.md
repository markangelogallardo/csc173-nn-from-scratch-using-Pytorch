# Neural Network from Scratch using PyTorch

## Student Information

- Name: Mark Angelo L. Gallardo
- Course Year: BSCS 4
- Date: 2025-11-03

## Network Architecture
- Input layer: 2 features (study_hours, attendance_rate)
- Hidden layer: 8 neurons with ReLU activation
- Hidden layer: 4 neurons with ReLU activation
- Output layer: 1 neuron with Sigmoid activation (binary classification)

## Implementation Details

- 1000 pass/fail results were generated for this assignment
- The train and test data where split 80/20 respectively
- Weight and bias parameters initialized randomly by PyTorch
- Utilized nn.Sequential to implement the Network Architecture
- Validation being done as training is happening 


## Results & Visualization

After training, the program displays:
- The training loss curve, showing how the network minimizes error over time.
- The decision boundary separating the two classes in the dataset.

These visualizations help confirm that the neural network successfully learned to classify the data.

## How to Run

1. Clone the GitHub repository:
   ```
   git clone https://github.com/markangelogallardo/csc173-nn-from-scratch-using-Pytorch.git
   ```
2. Open the Jupyter notebook or Colab file.
3. Run all cells sequentially.
4. Explore training loss plot and decision boundary visualizations.

## Summary

This activity provided hands-on experience in building a neural network using PyTorch. Data was generated using the given function, converted it to tensors that pytorch can use, and used the torch.nn modules to perform forward pass, backward propagation, activation functions, and optimizing. Utilized validation and test checks to determing the models accuracy and performance and visualized the results of the classification with a decision boundary plot. 


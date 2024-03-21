# Pre-X+VQC
An Implementation of Classical-to-Quantum Transfer Learning Algorithm with an Illustration of Quantum Dots 

Our codes include the experiments of PCA+VQC, Pre-ResNet18+VQC, and Pre-ResNet50+VQC for charge stability diagrams for Quantum Dots

## Installation

The main dependencies include *pytorch* and *torchquantum*

### Torch Quantum 
```
pip3 install torchquantum
```

## Simulating PCA+VQC experiments

### Assessing the representation power of PCA+VQC
```
python PCA_VQC.py --num_qubits=8 --test_kind='rep' 
```

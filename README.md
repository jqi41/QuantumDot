## Pre-X+VQC
An Implementation of Classical-to-Quantum Transfer Learning Algorithm with an Illustration of Quantum Dots 

Our codes include the experiments of PCA+VQC, Pre-ResNet18+VQC, and Pre-ResNet50+VQC for charge stability diagrams for Quantum Dots

### Installation

The main dependencies include *pytorch* and *torchquantum*

#### Torch Quantum 
```
pip3 install torchquantum
```

### 0. Downloading the dataset
```
git clone https://gitlab.com/QMAI/mlqe_2023_edx.git
```

### 1. Simulating Pre-ResNet18+VQC experiments

#### 1.1 Assessing the representation power of Pre-ResNet18+VQC
```
python Pre-ResNet+VQC.py --num_qubits=8 --test_kind='rep' --model_kind='ResNet18'
```

#### 1.2 Assessing the generalization power of Pre-ResNet18+VQC
```
python Pre-ResNet+VQC.py --num_qubits=8 --test_kind='gen' --model_kind='ResNet18'
```

### 2. Simulating Pre-ResNet50+VQC experiments

#### 2.1 Assessing the representation power of Pre-ResNet18+VQC
```
python Pre-ResNet+VQC.py --num_qubits=8 --test_kind='rep' --model_kind='ResNet50'
```

### 3. Simulating PCA+VQC experiments

#### 3.1 Assessing the representation power of PCA+VQC
```
python PCA+VQC.py --num_qubits=8 --test_kind='rep' 
```

#### 3.2 Assessing the representation power of PCA+VQC
```
python PCA+VQC.py --num_qubits=8 --test_kind='gen' 
```


#### 3.2 Assessing the generalization power of PCA+VQC
```
python PCA+VQC.py --num_qubits=8 --test_kind='gen' 
```

### 4. Comparing Pre-ResNet+VQC with Pre-ResNet+NN regarding representation and generalization powers

#### 4.1 Comparing their representation power
```
python Pre-ResNet_nn.py --num_qubits=8 --test_kind='rep'
```

#### 4.2 Comparing their generalization power
```
python Pre-ResNet_nn.py --num_qubits=8 --test_kind='gen'
```

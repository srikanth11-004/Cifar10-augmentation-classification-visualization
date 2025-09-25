# Cifar10-augmentation-classification-visualization

## 📌 Tasks Implemented  

### 1. Data Loading & Augmentation  
- Constructed a PyTorch DataLoader with **batch size = 8**.  
- Applied transformations:  
  - **Resize** operation.  
  - **Random Rotation** (θ = 90°).  
- Loaded and visualized the **first 3 batches** of transformed images.  

### 2. Class Distribution  
- Plotted **histogram for each CIFAR10 class**.  
- Commented on dataset class balance.  

### 3. Norm Visualizations  
- For the **first batch of images**, computed and visualized:  
  - **L1 norm**.  
  - **L2 norm**.  

### 4. Neural Network Training  
- Selected the **first 100 images** and applied:  
  - **Center Crop (64×64)**.  
  - **Flattened images** into features.  
  - Fed features into a **2-hidden-layer MLP** (128 → 64 → 10).  
- Experimented with different activation functions:  
  - **ReLU**  
  - **Sigmoid**  
  - **Tanh**  
- Implemented **backpropagation** with **L2 distance loss**.  
- Trained for **10 epochs**, printing **learning rate & loss per epoch**.  
- Commented on gradient behavior across activations.  

### 5. Dimensionality Reduction & Visualization  
- Applied **T-SNE** for feature visualization.  
- Compared with **PCA** results using scikit-learn.  


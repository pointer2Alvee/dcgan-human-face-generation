<div style="display: flex; justify-content: space-around; align-items: center;">
  <img src="assets/images/gen_imgs.PNG" alt="Image 1" style="width: 100%; margin: 10px;">
</div>

## 📜 dcgan-human-face-generation
#### 📌 Summary 
An implementation of a Generative model, DCGAN, for generating human faces using Python & TensorFlow, completely ran on Kaggle 

#### 🧠 Overview


#### 🎯 Use Cases 
- Detecting Sarcastic comments or opinions on social media platforms

#### 🟢 Project Status
- Current Version: V1.0
- Completed

#### 📂 Repository Structure
```
paper-hbert-sarcasm-detection/
├── README.md
├── LICENSE
├── .gitignore                  
├── assets/                      
│   └── images/
└── notebooks/               
    └── sarcasm-analysis.ipynb

```
### ✨ Features
- ✅ `DCGAN` model class
- ✅ Preprocessed Data
- ✅ Evaluation metrics: Accuracy 

🛠️ In progress:
- Modification of H-bert Architecutre 

<!--
### 🎥 Demo
 <a href="https://www.youtube.com/shorts/wexIv6X45eE?feature=share" target="_blank">
  <img src="assets/images/2_2.JPG" alt="YouTube Video" width="390" height="270">
</a> 
-->

### 🚀 Getting Started
#### 📚 Knowledge & Skills Required 
- Python programming
- ML/DL fundamentals, Neural Network Arhitecutres (CNN, GAN)
- Optimizers, Loss Functions
  
#### 💻 Software Requirements
- IDE (VS Code) or jupyter notebook or google colab
- **Best run on Kaggle using GPU T4x2**
  
#### 🛡️ Tech Stack
- Language: python
- NLP/ML: sklearn, pandas, numpy
- Deep Learning: tensorflow
- Visualization: matplotlib

#### 🔍 Modules Breakdown
<b> 📥 (1) Data-Preprocessing :</b> wh 
- Loading [Sarcasm on Reddit](https://www.kaggle.com/datasets/danofer/sarcasm?select=train-balanced-sarcasm.csv) dataset from kaggle 
- Dimention Reduced, Data Cleaned

<b> 🤖 (2) DCGAN :</b> 

- The DataFlow:- 
(L-1) output --> (L-2) output --> (L-3) output --> (L-4) output --> (L-5) output --> predictions (0 or 1)


##### 📊 Evaluation
- Using 'Accuracy' Meterics to evaluate model performance
- Future work : precision , recall , f1

#### ⚙️ Installation
```
git clone https://github.com/pointer2Alvee/dcgan-human-face-generation.git
cd dcgan-face-gen

# Recommended: Use a virtual environment
pip install -r requirements.txt
```

##### 🖇️ requirements.txt (core packages):
```
pandas
numpy
tensorflow
matplotlib
```

##### 💻 Running the App Locally
1. Open Repo in VS code / Kaggle (recommended)
2. Run Command
3. See accuracy

#### 📖 Usage
- Open VS Code / kaggle

### 🧪 Sample Topics Implemented
- ✅ DCGAN
- ✅ CNN, CONVOLUTION, POOLING
- ✅ GAN, OPTIMIZERS, LOSS FUNCTIONS
  
- ⏳ Upcoming  : 

### 🧭 Roadmap
- [x] Implementation of DCGAN
- [x] Generation of Fake Human Faces  


### 🤝 Contributing
Contributions are welcomed!
1. Fork the repo. 
2. Create a branch: ```git checkout -b feature/YourFeature```
3. Commit changes: ```git commit -m 'Add some feature'```
4. Push to branch: ```git push origin feature/YourFeature```
5. Open a Pull Request.

### 📜License
Distributed under the MIT License. See LICENSE.txt for more information.

### 🙏Acknowledgements
- Special thanks to the open-source community / youtube for tools and resources.

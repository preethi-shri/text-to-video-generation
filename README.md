# Text to Video Generation

A deep learning project that generates videos from text descriptions.

## 📁 Datasets

### 1. DreamBooth Dataset (129MB)
- Included in this repository (uploaded via Git LFS)

### 2. CNN-DailyMail News Text Summarization (1.37GB)
Too large to upload to GitHub. Download it from one of these sources:

- **Kaggle:** [CNN-DailyMail Dataset](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail)
- **HuggingFace:**
`python
  from datasets import load_dataset
  dataset = load_dataset("cnn_dailymail", "3.0.0")
`

## 🚀 How to Run
1. Clone the repository
`ash
   git clone https://github.com/preethi-shri/text-to-video-generation.git
`
2. Install dependencies
`ash
   pip install -r requirements.txt
`
3. Download the CNN-DailyMail dataset (see above)
4. Run the notebook
`ash
   jupyter notebook projectfile.ipynb
`

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Deep Learning

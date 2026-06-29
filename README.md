
# Optimus Automate - Artificial Intelligence Virtual Internship

This repository contains my official project submissions for the **Optimus Automate Virtual Internship Program**. The implementations focus on core AI concepts, utilizing modern Python libraries and frameworks to build scalable, industry-standard applications.

## 📌 Project Overview

Per the internship completion criteria, a minimum of two to three production-ready applications were required. This repository successfully implements the following core artificial intelligence tasks:

### 🚀 Completed Tasks

● **Task 1: Image Classification with CNN**

-   **Description:** Built a custom Convolutional Neural Network (CNN) in PyTorch to classify the CIFAR-10 dataset.
    
-   **Regularization:** Applied data augmentation (random cropping, horizontal flipping) and dropout layers.
    
-   **Evaluation:** Modeled training performance through localized cross-entropy loss tracking and evaluated final outputs using confusion matrices and accuracy plots.
    

● **Task 2: Chatbot with Intent Recognition**

-   **Description:** Developed an intelligent customer assistance chatbot for the domain space.
    
-   **Architecture:** Leveraged deep zero-shot text classification pipelines (`BART-large-MNLI`) to handle semantic intent recognition out-of-the-box.
    
-   **Context Tracking:** Features a multi-turn conversation architecture running on a clean web-based Streamlit interface.
    

● **Task 3: Object Detection App**

-   **Description:** Built a computer vision web application using a pre-trained PyTorch-backed YOLOv8 network.
    
-   **Interface:** Deployed via a Streamlit interface allowing real-time processing of targeted image streams.
    
-   **Features:** Automatically renders dynamic bounding boxes complete with localized class labels and explicit confidence scores.
    

● **Task 4: Recommendation System**

-   **Description:** Developed a content-based recommendation engine fueled by the MovieLens dataset catalog.
    
-   **Metrics:** Utilized PyTorch's functional math modules to compute high-dimensional Cosine Similarity across multi-hot genre vectors.
    
-   **Output:** Displays Top-N tailored items alongside clear, data-driven reasoning explanations for the user.
    

## 🛠️ Tech Stack & Frameworks

-   **Deep Learning Framework:** PyTorch
    
-   **Computer Vision:** Ultralytics (YOLOv8), OpenCV, Pillow
    
-   **Natural Language Processing:** Hugging Face Transformers
    
-   **Web UI Deploys:** Streamlit
    
-   **Data Processing & Graphics:** Pandas, NumPy, Matplotlib, Seaborn
    

## 🏃‍♂️ How to Run the Applications

### 1. Clone the Repository

```bash
git clone https://github.com/mkaify/OptimusAutomate_ArtificialIntelligene.git
cd Optimus_Automate_AI_Internship
```

### 2. Install Dependencies

```bash
pip install torch torchvision transformers ultralytics streamlit pandas numpy matplotlib seaborn opencv-python

```

### 3. Launch the Web Interfaces

To run any of the Streamlit interactive applications locally, execute:

```bash
streamlit run app_name.py
```

## 📧 Contact & Links

● **Website:**  [www.optimusautomate.com](http://www.optimusautomate.com/) 
● **Email:**  [info@optimusautomate.com](https://www.google.com/search?q=mailto%3Ainfo%40optimusautomate.com) 
● **LinkedIn:**  [@Optimus Automate](https://www.google.com/search?q=https://www.linkedin.com/company/optimus-automate/)
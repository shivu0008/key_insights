# Key Insights

## Overview
This project automatically extracts meaningful insights from a given story or text. It uses pre-trained natural language processing models to summarize the story and dynamically generate key insights based on the content. The project is designed to handle long-form stories, condensing them into concise and meaningful points.

## Features
- Automatically identifies key insights from any long story or text.
- Uses Hugging Face's BART model for summarization.
- Dynamically adjusts the number of insights based on the story's content.
- Easy-to-use and adaptable for a variety of use cases.

## Technologies Used
- Python
- Google Colab

## Setup Instructions

### Step 1: Clone the Repository
To get started, clone the repository using the following command:

```bash
git clone https://github.com/shivu0008/KeyInsightExtraction.git
cd KeyInsightExtraction
```

### Step 2: Install Dependencies
Install the required Python libraries by running the following command:
```bash
pip install transformers sentence-transformers nltk
```

### Step 3: Run the Code
You can use the provided Jupyter Notebook or Python script to test the code. You can run the project directly on Google Colab for a cloud-based setup.
- Open the Notebook: Google Colab Link (Upload the KeyInsight.ipynb file).
- Install dependencies in the Colab environment:
```bash
!pip install transformers sentence-transformers nltk
```
- Execute the notebook step-by-step to extract insights from your input story.

### How to Use
- Replace the story variable in the code with your text or long-form story.
- Run the script or notebook to see the insights extracted.
- Insights are dynamically generated based on the story content.


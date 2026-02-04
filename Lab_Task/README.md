# Agentic AI – Lab Task 1  
## Fine-Tuning a Small Language Model (SLM)

## Introduction  
This lab task demonstrates the fine-tuning of a Small Language Model (SLM) using Google Colab and the Hugging Face ecosystem. The objective of this task is to understand how a pretrained language model can be adapted to a specific text dataset and evaluated for its performance.

## Objective  
The main objective of this experiment is to fine-tune a small pretrained language model on a text dataset and analyze its performance after training.

## Dataset  
The IMDb Movie Reviews dataset was used for this task. It is a widely used text dataset containing movie reviews labeled based on sentiment polarity. The dataset helps the model learn patterns in natural language related to positive and negative sentiments.

## Model  
DistilBERT (distilbert-base-uncased) was selected as the Small Language Model for this experiment. It is a lightweight transformer-based model with fewer than 3 billion parameters, making it suitable for fine-tuning on limited computational resources such as Google Colab.

## Methodology  
The dataset was loaded from the Hugging Face repository and preprocessed using tokenization to convert text into numerical form. The pretrained DistilBERT model was then fine-tuned on the training dataset for sentiment classification. During training, the model’s parameters were updated to improve task-specific performance.

## Evaluation  
The performance of the fine-tuned model was evaluated using accuracy as the evaluation metric. The model was tested on unseen data to measure its generalization capability.

## Observations  
After fine-tuning, the model showed improved performance in correctly classifying movie reviews. The results indicate that the model learned meaningful patterns from the dataset and performed better than the base pretrained model.

## Conclusion  
This lab task demonstrates that Small Language Models can be effectively fine-tuned for specific natural language processing tasks. Even with limited training and computational resources, fine-tuning significantly improves model performance.

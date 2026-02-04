Agentic AI – Lab Task 1
Fine-Tuning a Small Language Model (SLM)

This lab task demonstrates the process of fine-tuning a Small Language Model (SLM) on a text dataset using Google Colab and the Hugging Face library. The aim of this task is to gain practical experience in adapting a pretrained language model for a specific natural language processing task and analyzing its performance after training.

Dataset

The IMDb Movie Reviews dataset was used in this experiment. It contains textual movie reviews labeled with sentiment information. The dataset was utilized to train the model to understand and classify sentiment based on textual content.

Model

For this task, DistilBERT was chosen as the Small Language Model. It is a compact and efficient transformer-based model with fewer than 3 billion parameters, making it suitable for fine-tuning in environments with limited computational resources such as Google Colab.

Methodology

The dataset was loaded from the Hugging Face repository and preprocessed through tokenization to convert text into a format suitable for model training. The pretrained DistilBERT model was then fine-tuned on the training dataset for sentiment classification. The training process adjusted the model weights to improve performance on the given task.

Evaluation

The model’s performance was evaluated using accuracy as the primary metric. Evaluation was conducted on a separate test dataset to measure how well the fine-tuned model generalizes to unseen data.

Observations

After fine-tuning, the model demonstrated improved capability in correctly identifying positive and negative sentiments from movie reviews. The fine-tuned model performed better than the base pretrained model on the target dataset.

Conclusion

This experiment highlights the effectiveness of fine-tuning small language models for task-specific applications. It shows that even lightweight pretrained models can achieve good performance when adapted properly using modern deep learning frameworks.

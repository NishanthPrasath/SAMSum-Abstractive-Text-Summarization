# SAMSum Abstractive Text Summarization

The goal of this project is to develop an abstractive summarization model that can generate concise and informative summaries of conversational texts. The model is trained on the SAMSum dataset, which consists of simulated messaging dialogues and their corresponding human-generated summaries.

## Dataset

The SAMSum dataset is a unique resource for research in the field of dialogue summarization. It contains conversational texts that mimic real-life chat scenarios, along with human-generated summaries for each conversation. Each entry in the dataset includes:
- `id`: A unique identifier for each dialogue-summary pair.
- `dialogue`: The actual text of the conversation, mimicking a real messaging scenario.
- `summary`: A human-generated summary that captures the main points of the dialogue.

## Model Performance

The project explores various architectures for dialogue summarization, including:
- Vanilla RNN Model
- LSTM Model
- Transformer Model
- Pretrained BART Model

The performance of each model was evaluated using the ROUGE metric. Among these models, the pretrained BART model demonstrated superior performance in accurately summarizing the given dialogues, achieving the highest ROUGE scores.

## Deployment

The final BART model was deployed on Hugging Face Spaces using the Streamlit framework. The application allows users to enter a dialogue or text to be summarized and generates a summary of the input text.

You can access the application [here](https://huggingface.co/spaces/nishanthp/text-summarization-with-bart)

## Contributors

- Dhanush Kumar Shankar
- Nishanth Prasath

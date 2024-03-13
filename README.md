# Hades: Phishing and Malicious Message Detection Dataset

This repository contains a curated dataset of phishing and malicious messages, along with benign examples, for training a custom GPT model called Hades. The dataset includes a diverse range of email, text message, and social media content from various sources.

The primary goal of the Hades model is to accurately classify incoming messages as either phishing/malicious or benign, enabling automated detection and filtering of potentially harmful content.

[Hades](https://chat.openai.com/g/g-l6uZp1RFI-hades)

## Dataset Structure

- `phishing/`: A directory containing phishing and malicious messages from various sources.
- `benign/`: A directory containing benign, non-malicious messages.
- `procedures/`: A directory containing methods to identify malicious messages.

## Usage

This dataset is intended for training the Hades GPT using techniques such as transfer learning or fine-tuning on top of a pre-trained GPT model. The specific training procedure and model architecture are not included in this repository.

## Contributing

If you have additional examples of phishing or malicious messages, or benign messages that could improve the dataset's diversity, please feel free to submit a pull request.

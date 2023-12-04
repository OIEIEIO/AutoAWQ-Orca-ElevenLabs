# AutoAWQ-Orca-ElevenLabs

This repository hosts a Jupyter notebook for interactive communication with the Orca 2 13 billion parameter model using ElevenLabs' text-to-speech API. It is designed to be run in Google Colab for an easy-to-use experience.

## About Orca

The Orca model is a state-of-the-art AI developed with extensive training across diverse datasets. The training process is outlined as follows:

> Compute: We trained Orca 2 on 32 NVIDIA A100 GPUs with 80GB memory with bfloat16. For the 13B checkpoint, it took approximately 17 hours to train Orca 2 on the FLAN dataset for one epoch, roughly 40 hours to train on 5 million ChatGPT data for 3 epochs, and about 23 hours to continue training on approximately 1.8 million GPT-4 data for 4 epochs.

For more detailed insights into the model's capabilities and the innovations behind it, refer to the [research paper](https://arxiv.org/pdf/2311.11045.pdf).

## Quickstart

1. Click on the "Open in Colab" button at the top of the notebook in this repository.
2. Once in Colab, the notebook will guide you through the installation process of the required libraries with pre-written commands.
3. Follow the instructions within the notebook to interact with the Orca model.

## Prerequisites

- A Google account to access Google Colab.
- An ElevenLabs API key (you will need to replace the placeholder in the notebook with your actual key).

## Usage

Simply open the notebook in Google Colab and run the cells in order. The notebook is self-contained and includes all necessary setup instructions. You will be able to input text and receive audio responses from the Orca AI model.

## Contributing

We welcome contributions to improve the notebook. Please fork the repository, make your changes, and submit a pull request.

## License

This project is open-sourced under the MIT license.

## Contact

Should you encounter any problems or have any queries, please open an issue in this repository.

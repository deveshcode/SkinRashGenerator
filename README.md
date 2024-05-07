# SkinRashGenerator
<img width="448" alt="Screenshot 2024-05-07 at 6 46 50 PM" src="https://github.com/deveshcode/SkinRashGenerator/assets/37287532/27202e41-4d6f-45d0-a61a-d2d0b42792b0">

## Project Overview
SkinRashGenerator is a deep learning project aimed at generating synthetic images of skin rashes based on textual descriptions. The project utilizes fine-tuned CLIP models integrated with latent diffusion techniques to generate images varying by rash type, skin color, and affected area.

## Objective
To develop a generative model that can create high-fidelity images of common skin rashes for educational and diagnostic purposes, allowing customization by type of rash, skin tone, and body area.

## Technologies Used
- Python
- PyTorch
- CLIP (Contrastive Language-Image Pre-training)
- Streamlit for web deployment
- Flask and React for alternative deployment strategy

## Installation
To set up this project locally, follow these steps:

```bash
git clone https://github.com/yourusername/SkinRashGenerator.git
cd SkinRashGenerator
pip install -r requirements.txt
```

# Usage

To run the Streamlit application:
```bash
streamlit run app.py
```

## For Flask deployment:

```bash
python app.py
```
Navigate to localhost:8501 for Streamlit or localhost:5000 for Flask, depending on which server you've started.

### Example Commands
Generate images by typing commands such as:

"Generate a ringworm rash on fair skin at the neck area."
"Show eczema on brown skin on the hand."

# Contributing
Contributions to the SkinRashGenerator are welcome. Please fork the repository and submit a pull request with your proposed changes.

# License
Distributed under the Apache 2.0 License. See LICENSE for more information.

# Acknowledgments
- Prof. Das for project guidance
- Kaggle and Hugging Face for datasets and model hosting
- All resources that have provided tutorials and insights into the workings of CLIP and latent diffusion models

# Authors
- Devesh Surve
- Haonan Chen

# Contact
For any queries, please open an issue in the repository or contact deveshsurve5@gmail.com

Thank you for checking out our project!

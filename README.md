Multimodal AI Caption Matching Model
This project implements a caption-matching system using CLIP (Contrastive Language–Image Pretraining) to identify the most relevant captions for a given image. The model encodes both visual and textual inputs, calculates cosine similarity between their embeddings, and returns the top-ranked matches.

Features
Multimodal Processing – Integrates computer vision and natural language understanding.

Image Embedding Extraction – Uses CLIP to convert images into vector representations.

Caption Similarity Matching – Compares image embeddings with a predefined caption set.

Cosine Similarity Ranking – Outputs top-N captions with similarity scores.

Tech Stack
Python
PyTorch
Hugging Face Transformers (CLIPModel, CLIPProcessor)
Pillow for image handling
scikit-learn for similarity computation

Project Structure
multimodal-caption-matcher/
 ├── main.py       # Core implementation
 ├── README.md     # Documentation
 └── images/       # Input images

Installation
git clone https://github.com/izwaareeb/multimodal_ai_caption_match.git
cd multimodal-caption-matcher
pip install torch pillow transformers scikit-learn

Usage
Place an image in the images folder (e.g., izwa.png).

Run the script:
python app.py
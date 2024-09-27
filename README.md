# Photo-Captioning-AI
Python Image captioning AI app using the BLIP model from Hugging Face's Transformers
Used Gradio to provide a user-friendly interface for your image captioning application

# Create a Python virtual environment and install Gradio using the following commands in the terminal:
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env

Then, install the required libraries in the environment:
# installing required libraries in my_env
pip install langchain==0.1.11 gradio==4.44.0 transformers==4.38.2 bs4==0.0.2 requests==2.31.0 torch==2.2.1

#To run
python3 image_captioning_app.py


Hugging Face is an organization that focuses on natural language processing (NLP) and artificial intelligence (AI).
The organization is widely known for its open-source library called "Transformers" which provides thousands of pre-trained models to the community. The library supports a wide range of NLP tasks, such as translation, summarization, text generation, and more. Transformers has contributed significantly to the recent advancements in NLP, as it has made state-of-the-art models, such as BERT, GPT-2, and GPT-3, accessible to researchers and developers worldwide.

Tranformers library includes a model that can be used to capture information from images. The BLIP, or Bootstrapping Language-Image Pre-training, model is a tool that helps computers understand and generate language based on images. It's like teaching a computer to look at a picture and describe it, or answer questions about it.



Implemented an automated image captioning program that works directly from a URL. The user provides the URL, and the code generates captions for the images found on the webpage. The output is a text file that includes all the image URLs along with their respective captions (like the image below). To accomplish this, you use BeautifulSoup for parsing the HTML content of the page and extracting the image URLs.
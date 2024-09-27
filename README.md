# Photo-Captioning-AI
Python Image captioning AI app using the BLIP model from Hugging Face's Transformers

Used Gradio to provide a user-friendly interface for your image captioning application

Hugging Face is an organization that focuses on natural language processing (NLP) and artificial intelligence (AI).
The organization is widely known for its open-source library called "Transformers" which provides thousands of pre-trained models to the community. The library supports a wide range of NLP tasks, such as translation, summarization, text generation, and more. Transformers has contributed significantly to the recent advancements in NLP, as it has made state-of-the-art models, such as BERT, GPT-2, and GPT-3, accessible to researchers and developers worldwide.

Tranformers library includes a model that can be used to capture information from images. The BLIP, or Bootstrapping Language-Image Pre-training, model is a tool that helps computers understand and generate language based on images. It's like teaching a computer to look at a picture and describe it, or answer questions about it.



Implemented an automated image captioning program that works directly from a URL. The user provides the URL, and the code generates captions for the images found on the webpage. The output is a text file that includes all the image URLs along with their respective captions (like the image below). To accomplish this, you use BeautifulSoup for parsing the HTML content of the page and extracting the image URLs.
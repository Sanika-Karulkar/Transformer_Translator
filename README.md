# Real-Time Multi-Language Translation System
This project provides an interactive, real-time translation system capable of translating text between English, French, German,Hindi and Spanish. 
Leveraging state-of-the-art MarianMT models from the Hugging Face Transformers library,Pytorch and ipywidgets this system enables instant translations directly within a Jupyter Notebook.

Hugging Face Transformers:
Provides access to state-of-the-art pre-trained model(MarianMT) for natural language understanding and generation. MarianMT models are employed for their high-quality, multi-lingual translation capabilities. These models are trained on a large corpus of text and fine-tuned to handle diverse language pairs for fast and accurate results.

PyTorch:
Deep learning framework that serves as the underlying engine for the Hugging Face Transformers library. PyTorch’s support for GPU acceleration ensures that the translation process is performed rapidly, suitable for a real-time application.

ipywidgets:
Enables the creation of interactive user interfaces within Jupyter Notebooks through elements such as text boxes, dropdown menus, and buttons. 
Here users can input text, select source and target languages, and view translation results without needing to manually run code cells.

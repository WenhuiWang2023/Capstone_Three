# **Fake News Detection by Supervised Fine Tuning of TinyLlama Model**
Fake news specifically refers to news reports that are untrue or exaggerated. These reports may be deliberately created to mislead the public or promote a specific agenda, through traditional media channels like print, and television as well as non-traditional media channels like social media. The wide and fast spread of fake news online has posed real-world threats in critical domains like politics, economy, and public health.<br />
In this project, I built a fake news detection model by fine tuning TinyLlama  with Lora (Low rank adaption). TinyLlama is a compact 1.1B language model Building on the architecture and tokenizer of Llama 2. Instead of focusing solely on training compute-optimal language models, inference-optimal language models, aiming for optimal performance within specific inference constraints,  is achieved by training models with more tokens than what is recommended by the scaling law.  Following the same architecture and tokenizer as Llama 2,  TinyLlama is obtained by training transformer decoder-only model with 1.1B parameters using approximately 3 trillion tokens.<br />

**Proposal for final project.pdf** is the proposal of the project<br />
**fake-news-data-exploration3.ipynb** is data exploration, preprocessing and performance evalutation on traditional ML model<br />
**Capstone3_fake_news_text_data_preprocessing.ipynb** is code for transforming text and label data into readable prompt format for TinyLlama model<br />
**llama2_fakenews_detect_final.ipynb** containing code for TinyLlama model training and validation.<br />
**fake_news_detection_tinyllama.pdf** is powerpoint for presentation of the project.<br />
**Capstone_3_fake_news_detection.pdf** is the project file.<br />

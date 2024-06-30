# Llama 3
Llama 3 is a LLM developed by Meta that comes with open source starter code and pre-trained weights for models with sizes ranging from 8 billion parameters to 70 billion parameters. This makes Llama 3 an accessible option to fine tune for unique functionalities. 

### What is fine tuning?
Fine tuning is further training an existing LLM on more data specific to a functionality. This could mean training on customer service conversations, legal documents, or any other set of documents. A fine tuned model performs better for a specific functionality than its base model, and training uses significantly less computing power. In most cases, a small model can be fine tuned on a laptop. 

### How to download Llama 3
1) Visit the [Llama website](https://llama.meta.com/llama-downloads/) and accept the license agreement. Once the request is approved, you will get a signed URL over email. 

2) Make sure you have both <mark>wget</mark> and <mark>md5sum</mark> installed. Then run the download.sh script given when retrieving your signed url with <mark>./download.sh</mark>, and use your signed url. 

3) Your signed url expires after 24 hours or when you reach the download limit. If you get a <mark>403: Forbidden</mark> error, request a new link. 

4) You're ready to go! Visit the [Llama 3 Github](https://github.com/meta-llama/llama3) for further questions.
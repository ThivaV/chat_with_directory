# Chat with directory

Chat with directory using LangChain &amp; GPT 3.5 - Any documents inside the directory

* Setup
    * ```pip install openai```
    * ```pip install langchain```
    * ```pip install tiktoken```
        * tiktoken is a fast BPE tokeniser for use with OpenAI's models
    * ```pip install pypdf```
        * pypdf is a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files
    * ```pip install unstructured[local-inference]```
        * It's the command that installs [unstructured](https://pypi.org/project/unstructured/) package. It's for pre-processing text documents such as PDFs, HTML and Word Documents. So, it might be big and have many dependancies since it processes several types of documents
    * ```pip install gradio```
    * ```pip install chromadb```
        * Chroma - the open-source embedding database. The fastest way to build Python or JavaScript LLM apps with memory 
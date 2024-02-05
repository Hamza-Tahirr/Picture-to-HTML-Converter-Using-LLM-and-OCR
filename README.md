# Picture to HTML Code Converter using LLM and OCR

This Python code provides a novel way for users to convert handwritten sketches into structured web content. It allows anyone to upload an image of their sketch, which is then processed using EasyOCR to recognize and locate any text within the drawing. The text and coordinate data is passed to an LLM. In this scenario, ChatGPT is utilized to ingest the unstructured sketch information and generate the corresponding HTML. While other powerful language models are available,chatGPT-3.5-turbo-16k was used although ChatGPT4 is well-suited for this task.


## Deployment

bash`
To deploy this project run
`


1:
 `
  git clone https://github.com/Hamza-Tahirr/Picture-to-HTML-Converter-Using-LLM-and-OCR.git`
  
2: install requirements:

`
  pip install -r requirement.txt `
  
3:

Enter your OpenAI API in .env files

4: Run in Terminal

`
  streamlit run main.py`

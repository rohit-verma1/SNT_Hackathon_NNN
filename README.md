Our model is a Python-based text summarization tool that uses natural language processing techniques to generate concise summaries from given text documents.

- Input text can be provided in any format as processing happens after converting our input into PDF through libraries such as pptx, image etc.
- Libraries used are transformers, PyPDF2, cv2, pytesseract, PIL, pdf2image, torch.
- For a 545kb PDF our model took 17 seconds to execute on google colab.
- Automatic text preprocessing to remove unnecessary noise and improve the quality of the summarization.
- Supports abstractive summarization techniques.
- Customizable summary length to generate summaries of desired sizes.


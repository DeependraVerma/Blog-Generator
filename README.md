# Blog-Generator Project

## Description

The Blog-Generator is a cutting-edge application designed to create unique and engaging blog content using the powerful Llama-2-7b model (`llama-2-7b-chat.ggmlv3.q8_0.bin`). Built with a suite of advanced natural language processing libraries, including Sentence Transformers, cTransformers, and LangChain, our tool streamlines the blog creation process, offering a seamless user experience through a Streamlit-based web interface.

## Features

- **Advanced NLP Model**: Utilizes the Llama-2-7b model for generating high-quality blog content.
- **Streamlit Web Interface**: Easy-to-use interface for creating blogs.
- **Customizable Outputs**: Tailor the blog content to suit various styles and topics.

## Model Download
Due to the large size of the Llama-2-7b model, it is hosted externally. Please follow these steps to download and integrate the model into the Blog-Generator:

Download the model from [https://huggingface.co/meta-llama].
Place the downloaded model file *(llama-2-7b-chat.ggmlv3.q8_0.bin)* in the models/ directory of this project.
Alternatively, use the following command to download the model directly into the correct directory:

bash
Copy code
wget -O models/llama-2-7b-chat.ggmlv3.q8_0.bin [https://huggingface.co/meta-llama]

## Requirements

This project requires the following libraries:

- sentence-transformers
- uvicorn
- ctransformers
- langchain
- python-box
- streamlit

Please ensure these are installed to use the Blog-Generator effectively.

## Installation

To set up the Blog-Generator, follow these steps:

1. Clone the repository:
   ```
   git clone [https://github.com/DeependraVerma/Blog-Generator.git]
   ```

2. Navigate to the project directory:
   ```
   cd [D:\QnA - Langchain\Blog Generator - Llama - 2\Blog-Generator]
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the application, execute the following command:

```
streamlit run app.py
```

This will start the web server and the application should be accessible via your web browser.


## Providing Detailed Documentation

### Getting Started

To begin using the Blog-Generator, ensure you have downloaded and placed the `llama-2-7b-chat.ggmlv3.q8_0.bin` model in the `models/` directory. Start the Streamlit web interface to interact with the application.

### Creating a Blog

- **Step 1**: Choose the topic or input the initial sentences for your blog.
- **Step 2**: Specify any additional parameters or styles you want the blog to adhere to.
- **Step 3**: Click 'Generate' to produce the blog content.

### Customization Options

- **Style**: Choose from various writing styles for your blog.
- **Length**: Determine the length of the blog.

### Troubleshooting

If you encounter issues, ensure the model is correctly placed and the required libraries are installed. For more specific problems, please refer to the 'Issues' section of this GitHub repository or contact [deependra.verma00@gmail.com].

## Contributing

Contributions to the Blog-Generator are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the Apache License 2.0. This comprehensive license provides an express grant of patent rights from contributors to users and is a popular choice for open-source software.

The Apache License 2.0 allows for the free use, modification, distribution, and redistribution of this software, both in modified and unmodified form, under the condition that the terms of the Apache License are respected.

For more details on the terms and conditions, as well as how to apply the Apache License to your own work, please see the Apache License 2.0 or the LICENSE file included in this project.

## Contact

For any queries or support, please reach out to [deependra.verma00@gmail.com].
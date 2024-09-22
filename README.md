# Langchain_pdf_reader

## How it works

The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.

The application uses Streamlit to create the GUI and Langchain to deal with the LLM.

## Deployment Instruction

- **Set Up Your Project Directory:** Create a directory for your project.
- **Create a Virtual Environment:** Set up a virtual environment to manage dependencies.
- **Install Required Packages:** Use pip to install the necessary packages.
- **Create a .env File:** Create a .env file in your project directory to store your OpenAI API key.
- **Run Your Application Locally**
- **Create a GitHub Repository:**\n
    Go to GitHub and create a new repository.\n
    Follow the instructions to initialize it with a README.\n
- **Push Your Code to GitHub**


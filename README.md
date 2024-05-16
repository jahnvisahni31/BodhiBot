# BodhiBot

BodhiBot is an advanced AI-driven chatbot designed to provide comprehensive knowledge and insights into Buddhism. Leveraging the power of Llama2 and Chainlit, BodhiBot offers an interactive platform for exploring Buddhist teachings, history, and cultural aspects.

## Table of Contents

- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you can start using BodhiBot, ensure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (install them using pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for PDF document loading)

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/your-username/bodhibot.git
    cd bodhibot
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the necessary language models and data. Refer to the Langchain documentation for specific instructions on downloading and setting up the language model and vector store.

5. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Getting Started

To get started with BodhiBot, follow these steps:

1. Set up your environment and install the required packages as described in the Installation section.

2. Configure your project by updating the `DB_FAISS_PATH` variable and any other custom configurations in the code.

3. Prepare the language model and data as per the Langchain documentation.

4. Start the bot by running the provided Python script or integrating it into your application.

## Usage

BodhiBot can be used for answering queries related to Buddhism. To use the bot, follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a Buddhism-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

## Contributing

Contributions to BodhiBot are welcome! If you'd like to contribute to the project, follow these steps:

1. Fork the repository to your own GitHub account.

2. Create a new branch for your feature or bug fix.

3. Make your changes and ensure that the code passes all tests.

4. Create a pull request to the main repository, explaining your changes and improvements.

5. Your pull request will be reviewed, and if approved, it will be merged into the main codebase.

## License

This project is licensed under the MIT License.

---

For more information on how to use, configure, and extend BodhiBot, please refer to the Langchain documentation or contact the project maintainers.

Happy coding with BodhiBot! 🪷

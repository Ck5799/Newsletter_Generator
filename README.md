# Newsletter_Generator
This is an implementation of Agentic workflow for Generative AI, CrewAI framework is used 

# Installation

Ensure you have Python >=3.10 <=3.13 installed on your system. This project uses Poetry for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install Poetry:
```
pip install poetry
```
Next, navigate to your project directory and install the dependencies:

  First lock the dependencies and then install them:
```
poetry lock

poetry install
```

To run:

Add your Open AI API key in the .env along with Exa API key and run the following command:
```
poetry run newsletter_gen
```

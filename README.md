# AI Playground

This project is an interactive conversational AI application powered by the Llama language model. It allows users to chat with an AI model through a simple interface. This repository serves as a collaborative project to practice building solutions with Generative AI and Large Language Models (LLMs). The application is set up for easy installation and configuration, and it’s designed for iterative learning and development.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The purpose of this project is to explore the practical applications of AI and Generative AI, using the Llama language model as a backend for a conversational interface. The project is structured to provide hands-on experience in AI development, with plans to expand its capabilities over time. The repository is open for contributions, making it ideal for anyone interested in experimenting with and learning about AI-driven applications.

## Features

- **Interactive Chat Interface**: Allows users to communicate directly with the Llama model.
- **Simple Setup**: Designed for easy installation and configuration.
- **Modular Design**: Open to extensions and improvements, enabling collaborative enhancements to functionality and AI behavior.

## Getting Started

To get started, follow the instructions below to set up the environment and run the application.

### Prerequisites

- Python 3.8 or later
- Git
- Virtual environment setup (recommended: `venv`)
- Access to a Llama model instance, either locally or via an API

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Setup the virtual environment**
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```

3. **Install the required packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Install ollama and run server**
Ensure you have [ollama](https://ollama.com/download) installed locally.
Once installed, run the following command to pull a model and run it.
    ```bash
    ollama run llama3.2
    ```

    > This might take a while to download. Some of these models require tenths of gigs of storage.

### Usage

1. **Run the application:**
    ```bash
    python main.py
    ```

## Contributing

We welcome contributions! If you’re interested in enhancing the functionality or adding new features, feel free to fork the repository, create a branch, and submit a pull request.

### Guidelines for Contributions
Ensure code functionality by testing thoroughly before submitting.
Document new features clearly for future contributors.
Follow consistent code styling throughout your contribution.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
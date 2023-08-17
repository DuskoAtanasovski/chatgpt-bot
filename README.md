# ChatGPT Bot with Spring Boot

ChatGPT Bot with Spring Boot is a conversational AI application powered by OpenAI's GPT-3.5 architecture and integrated into a Spring Boot backend. This repository provides the code and resources necessary to deploy and interact with the ChatGPT Bot within a Spring Boot environment, enabling you to seamlessly integrate natural language understanding and generation capabilities into your Spring-based applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

ChatGPT Bot with Spring Boot provides a powerful way to engage in dynamic and context-aware conversations with users. By harnessing the capabilities of OpenAI's GPT-3.5 and integrating them into a Spring Boot backend, you can create sophisticated conversational experiences for your users.

## Features

- **Seamless Integration:** The ChatGPT Bot is seamlessly integrated into a Spring Boot application, allowing you to leverage the benefits of both Spring and GPT-3.5.

- **Contextual Conversations:** The bot retains context across interactions, leading to meaningful and coherent conversations.

- **Customizable Behavior:** You can fine-tune the bot's responses by modifying instructions and parameters to suit your specific use cases.

- **Web API:** The Spring Boot application exposes a user-friendly API for interacting with the bot, making integration into various platforms straightforward.

## Getting Started

Follow these steps to deploy the ChatGPT Bot with Spring Boot:

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- OpenAI API key (sign up at https://beta.openai.com/signup/)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/DuskoAtanasovski/chatgpt-bot.git
   cd chatgpt-bot
   ```

2. Build the Spring Boot application:
   ```bash
   ./mvnw clean install
   ```

### Configuration

1. Open the `src/main/resources/application.properties` file.

2. Replace `'YOUR_API_KEY'` with your actual OpenAI API key.

3. Configure any additional settings in the file according to your requirements.

## Usage

1. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

2. The API is now accessible at `http://localhost:8080/api/chat`.

3. Use your preferred method (e.g., cURL, Postman) to send POST requests to the API endpoint, providing user messages and receiving bot responses.

## Contributing

We welcome contributions! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Open a pull request with a detailed description of your changes.

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

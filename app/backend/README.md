# Backend Service for Azure Search OpenAI Demo

This directory contains the backend service for the Azure Search OpenAI Demo application. The backend service is responsible for handling API requests, processing data, and interfacing with Azure services.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [Azure Account](https://azure.microsoft.com/en-us/free/)
- [Azure Cognitive Search](https://azure.microsoft.com/en-us/services/search/)
- [OpenAI API Key](https://beta.openai.com/signup/)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/azure-search-openai-demo.git
    cd azure-search-openai-demo/app/backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Configuration

1. Create a `.env` file in the `app/backend` directory and add the following environment variables:
    ```env
    AZURE_SEARCH_API_KEY=your_azure_search_api_key
    AZURE_SEARCH_SERVICE_NAME=your_azure_search_service_name
    OPENAI_API_KEY=your_openai_api_key
    ```

## Running the Service

To start the backend service, run:
```sh
npm start
```

The service will be available at `http://localhost:3000`.

## API Endpoints

- `GET /search`: Perform a search query using Azure Cognitive Search.
- `POST /generate`: Generate text using OpenAI's API.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

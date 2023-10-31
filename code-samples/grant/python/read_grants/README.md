# 🛡️ Read Grants Details

Read grant details using the Nylas Python SDK and Poetry.

## 📜 Introduction

The `read_grants` project is a Python script that utilizes the Nylas Python SDK to read grant details from a Nylas account. It provides a simple way to retrieve and display grant information, allowing you to manage your grants effectively.

## ✨ Features

- Read grant details with various filtering options.
- Handle Nylas API errors and edge cases.
- Integrated with Poetry for dependency management.

## ⚙️ Requirements

Before using this project, ensure you have the following prerequisites:

- Python 3.10 or higher
- Make
- Nylas API credentials (`'API_KEY'`)
- Nylas grant identifier

## 🔧 Using Make

You can use the `make` command for common development tasks. Here are some helpful targets:

- `make venv`: Create a virtual environment.
- `make install`: Generate a `.env` file and install required dependencies.
- `make run`: Execute the script using Poetry.
- `make clean`: Remove build, test, coverage, and Python artifacts.

## 🚀 Installation

1. Clone this repository to your local machine:


    ```bash
    git clone https://github.com/nylas-samples/nylas-hacktoberfest-2023.git
    cd nylas-hacktoberfest-2023/code-samples/grant/python/read_grants
    ```

1. Create a virtual environment and activate it:

    ```bash
    make venv
    ```

1. Install project dependencies using Poetry:

    ```bash
    make install
    ```

1. Configure your Nylas API credentials in the `.env` file by setting your `'API_KEY'` with your actual credentials.

## 🏁 Getting Started

After completing the installation steps, you're ready to get started:

1. Run the script to read grant details:

    ```bash
    make run
    ```

   The script will retrieve and display grant information based on your query parameters.

    ```bash
    *** Running the app locally... ***


    poetry run read_grant
    List of Grants:
    Grant ID: your-grant-id, State: mahmoudddharmouchhh%40gmail.com%3Agoogle
    ```

1. Customize the `ListGrantsQueryParams` parameters to filter the grants as needed.

## 📚 Documentation

This project includes Google-style documentation within the code. You can find detailed information on how the script works, its functions, and error handling in the script itself.

## 🤝 Contributing

Contributions are welcome! If you would like to improve this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure tests pass.
4. Submit a pull request with a clear description of your changes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

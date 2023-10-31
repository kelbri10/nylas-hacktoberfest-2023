# 🛡️ Delete User Grant

Delete user grants using the Nylas Python SDK and Poetry.

## 📜 Introduction

The `delete_user_grant` project is a Python script that leverages the Nylas Python SDK to delete user grants in a Nylas account. It provides a simple way to revoke and manage user grants, ensuring controlled access to resources.

## ✨ Features

- Delete user grants based on grant IDs.
- Handle Nylas API errors and edge cases.
- Integrated with Poetry for dependency management.

## ⚙️ Requirements

Before using this project, ensure you have the following prerequisites:

- Python 3.10 or higher
- Make
- Nylas API credentials (`'API_KEY'`)
- A grant ID to delete

## 🔧 Using Make

You can use the `make` command for common development tasks. Here are some useful targets:

- `make venv`: Create a virtual environment.
- `make install`: Generate a `.env` file and install required dependencies.
- `make run`: Run the script using Poetry.
- `make clean`: Remove build, test, coverage, and Python artifacts.

## 🚀 Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/nylas-samples/nylas-hacktoberfest-2023.git
    cd nylas-hacktoberfest-2023/code-samples/grant/python/delete_grants
    ```

1. Set up a virtual environment and activate it:

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

1. Run the script to delete user grants:

    ```bash
    make run
    ```

    The script will delete user grants based on the specified grant IDs.

    ```bash
    *** Running the app locally... ***


    poetry run delete_grants
    User Grants Before Delete:
    Grant ID: 77f1df2c-f5fc-4dfb-a011-59fb7aa01411, Status: mahmoudddharmouchhh%40gmail.com%3Agoogle
    
    Grant with ID 77f1df2c-f5fc-4dfb-a011-59fb7aa01411 deleted successfully.

    User Grants After Delete:
    ```

1. Customize the `delete_grant` function to delete user grants with specific grant IDs.

## 📚 Documentation

This project includes Google-style documentation within the code. You can find detailed information on how the script works, its functions, and error handling in the script itself.

## 🤝 Contributing

Contributions are welcome! If you would like to improve this project, please follow these guidelines:

1. Fork the repository.
1. Create a new branch for your feature or bug fix.
1. Make your changes and ensure tests pass.
1. Submit a pull request with a clear description of your changes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

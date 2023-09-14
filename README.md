---

# Process Management System

This documentation provides an overview of a Python application for managing processes using the Tkinter GUI framework and MongoDB for data storage.

## Installation

Before running the application, make sure to install the required libraries:

```bash
pip install tkinter ttkbootstrap pymongo
```

## Usage

To use the application, run the script as follows:

```bash
python process_management.py
```

## Features

### Tela de Processos

The main screen for registering and managing processes.

#### Fields

- **PID**: Process ID.
- **UID**: User ID.
- **Estado**: Process state (Ready, Execution, Wait).
- **Prioridade**: Process priority (High, Medium, Low).
- **Uso da CPU%**: CPU usage percentage.
- **Uso da memória**: Memory usage.

#### Actions

- **Cadastrar processo**: Click this button to register a new process.

### Tela de Relatório

A screen for viewing and managing process reports.

#### Columns

- **Processo**: Process ID.
- **Usuário**: User ID.
- **Estado**: Process state.
- **Prioridade**: Process priority.
- **CPU**: CPU usage.
- **Espaço na Memória**: Memory space.
- **Ação**: Delete button to remove a process from the report.

## Database

The application uses MongoDB as the database to store process information.

### MongoDB Configuration

- MongoDB Connection URL: Replace with your MongoDB connection URL.
- Database Name: CadastroProcessos
- Collection Name: Processos

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---

Please note that you should configure the MongoDB connection URL and other settings in the code before using the application. If you have any further questions or need additional documentation, please let me know.

Is there anything else you would like to add or modify in the documentation?

# Webserv

## Description

Webserv is a project that implements a basic HTTP web server in C++. This server can handle HTTP requests, manage connections, and serve static files. The project aims to provide a deeper understanding of HTTP protocols, socket programming, and server-client communication.

## Features

- HTTP request parsing
- Serving static files
- Connection handling
- Configurable server settings

## Services

- **HTTP Request Handling**: Parses and processes incoming HTTP requests.
- **Static File Serving**: Serves static files such as HTML, CSS, JavaScript, and images.
- **Connection Management**: Manages client connections and handles multiple requests concurrently.

## Getting Started

### Prerequisites

- GCC or any C++ compiler
- Make

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/callmezaki/Webserv.git
   cd Webserv
   ```

2. Compile the project:

   ```bash
   make
   ```

### Usage

Run the server with the following command:

```bash
./webserv <config_file>
```

- `config_file`: Path to the configuration file that defines the server settings.

Example:

```bash
./webserv config_file
```

## Project Structure

- `src/`: Contains the source files.
- `config/`: Contains example configuration files.
- `Makefile`: Defines the build process for the project.
- `README.md`: Project documentation.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [GNU Make](https://www.gnu.org/software/make/)
- [GCC](https://gcc.gnu.org/)

# Python Project Template

A reusable Python project template with a pre-configured development environment and project structure.

## Project Structure

```
.
├── .gitignore
├── README.md
├── requirements.txt
├── src/
│   └── __init__.py
├── tests/
│   └── __init__.py
└── .env.example
```

## Features

- Virtual environment setup
- Basic project structure
- Testing directory
- Git integration
- Environment variables support

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   cd <project-name>
   ```

2. Create and activate virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Unix/macOS
   # OR
   .\venv\Scripts\activate  # On Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create `.env` file:

   ```bash
   cp .env.example .env
   ```

5. Start developing!

## Development

- Place your source code in the `src` directory
- Add your tests in the `tests` directory
- Add your dependencies to `requirements.txt`
- Use `.env` for environment variables

## License

This project is licensed under the MIT License - see the LICENSE file for details.

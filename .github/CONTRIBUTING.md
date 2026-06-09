# Contributing to RF Communication with LoRa

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing.

## Code of Conduct

Please be respectful and constructive in all interactions.

## How to Contribute

### Reporting Bugs

1. Use the GitHub Issues page
2. Check if the bug has already been reported
3. Provide a clear description with steps to reproduce
4. Include relevant system information

### Suggesting Enhancements

1. Use GitHub Issues with a clear title
2. Provide a detailed description of the enhancement
3. Explain the use case and expected behavior
4. Include any relevant examples

### Submitting Pull Requests

1. Fork the repository
2. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
3. Make your changes following the code style
4. Test your changes thoroughly
5. Commit with clear, descriptive messages
6. Push to your fork and submit a Pull Request

## Development Setup

```bash
# Clone your fork
git clone https://github.com/your-username/RF_communication-with-LoRa-.git

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install development dependencies
pip install -r requirements-dev.txt
```

## Code Style

- Follow PEP 8 guidelines
- Use meaningful variable names
- Add docstrings to functions and classes
- Keep lines under 100 characters where possible

## Testing

Run tests before submitting:
```bash
pytest
```

## Documentation

- Update README.md for significant changes
- Add docstrings to new functions
- Update CHANGELOG.md

## Questions?

Feel free to open an issue or discussion for questions!

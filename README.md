# Test Demoblaze - A Python Poetry Project

## Overview

Test Demoblaze is a Python project that uses the _selenium_ and _pytest_ modules. The project is managed using _Poetry_, a dependency management tool for Python that allows declaring all dependencies and their exact versions, which makes projects reproducible.

## Dependencies

- Python: ^3.12
- Selenium: ^4.21.0
- PyTest: ^8.2.0

## Running Tests

1. Make sure you have Poetry installed.
2. Update ```API_KEY``` and ```API_SECRET``` with your Blazemeter's API Keys 
3. Install dependencies: ```poetry install```
4. Run tests using the following command: ```poetry run pytest```
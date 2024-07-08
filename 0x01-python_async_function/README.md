# Async/Await and Asyncio Project

This project demonstrates the use of async and await syntax, asyncio for asynchronous programming in Python, and the random module. 

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is designed to help you understand and implement asynchronous programming in Python using `async` and `await` syntax, the `asyncio` module for running concurrent coroutines, and creating asyncio tasks. You'll also learn how to use the `random` module to generate random numbers.

## Requirements

- Python 3.7
- Ubuntu 18.04 LTS
- `pycodestyle` version 2.5.x

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/nimiabaga/your-repository-name.git
    cd your-repository-name
    ```

2. **Create a virtual environment:**

    ```sh
    python3.7 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the main script:**

    ```sh
    ./main.py
    ```

## Examples

### Example 1: Simple async function

```python
#!/usr/bin/env python3
import asyncio

async def say_hello():
    print("Hello, Asyncio!")

asyncio.run(say_hello())


License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions, please contact me at nimiabaga@yahoo.com.

GitHub: nimiabaga

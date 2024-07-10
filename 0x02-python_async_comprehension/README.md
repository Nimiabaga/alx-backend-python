# Async/Await and Asyncio Project

This project demonstrates the use of async and await syntax, asyncio for asynchronous programming in Python, and the random module. It is part of the ALX AFRICA curriculum.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project is designed to help you understand and implement asynchronous programming in Python using `async` and `await` syntax, the `asyncio` module for running concurrent coroutines, and creating asyncio tasks. You'll also learn how to use the `random` module to generate random numbers. This project is done individually as part of the ALX AFRICA curriculum.

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

### Task 0: The Basics of async

Write an asynchronous coroutine that takes in an integer argument (`max_delay`, with a default value of 10) named `wait_random` that waits for a random delay between 0 and `max_delay` (included and float value) seconds and eventually returns it.

Use the random module.

```python
#!/usr/bin/env python3
import asyncio
import random

async def wait_random(max_delay: int = 10) -> float:
    """
    Asynchronous coroutine that waits for a random delay between 0 and max_delay seconds
    and eventually returns the delay.
    """
    delay = random.uniform(0, max_delay)
    await asyncio.sleep(delay)
    return delay


Julie Peters (nimiabaga) - ALX AFRICA Student

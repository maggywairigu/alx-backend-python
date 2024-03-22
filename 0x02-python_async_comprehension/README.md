# ALX Backend Python Project - Async Comprehension

## Curriculum
## Project Overview

This project focuses on asynchronous comprehension in Python, covering topics such as writing asynchronous generators, using async comprehensions, and type-annotating generators. The project includes tasks to implement coroutines that generate random numbers and measure the runtime of parallel async comprehensions.

## Resources

- **PEP 530** – Asynchronous Comprehensions
- **What’s New in Python**: Asynchronous Comprehensions / Generators
- **Type-hints for generators**

## Learning Objectives

Upon completion of this project, you should be able to explain:

- How to write an asynchronous generator
- How to use async comprehensions
- How to type-annotate generators

## Requirements

### General

- **Editors**: Allowed editors include vi, vim, emacs
- **Environment**: Ubuntu 18.04 LTS using Python 3.7
- **File Format**: All files should end with a new line
- **Shebang**: The first line of all files should be exactly `#!/usr/bin/env python3`
- **README.md**: A mandatory README.md file at the root of the project folder
- **Coding Style**: Use the pycodestyle style (version 2.5.x)
- **File Length**: File length will be tested using wc
- **Documentation**: All modules, functions, and coroutines should have documentation
- **Type Annotations**: All functions and coroutines must be type-annotated

### Tasks

1. **Async Generator**: Write a coroutine that loops 10 times, asynchronously waiting 1 second each time, then yielding a random number between 0 and 10.

2. **Async Comprehensions**: Write a coroutine that collects 10 random numbers using an async comprehension over the async generator from the previous task.

3. **Run Time for Four Parallel Comprehensions**: Write a coroutine that measures the total runtime of executing the async comprehension from the previous task four times in parallel using `asyncio.gather`.

## Usage

To run the provided examples, use the following commands:

```bash
$ python3 0-main.py
$ python3 1-main.py
$ python3 2-main.py
```

## Repository

- **GitHub Repository**: [alx-backend-python](https://github.com/username/alx-backend-python)
- **Directory**: 0x02-python_async_comprehension
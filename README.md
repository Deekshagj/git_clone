# Git Client Project

This project is an educational attempt to better understand how Git works by creating a simplified Git client from scratch using Python. By re-implementing some core Git functionalities like object storage, hashing, and versioning, the goal is to gain deeper insights into the internal workings of Git.

## Project Overview

This project includes:

- Initializing a Git repository (`git init`)
- Creating Git objects such as blobs and trees
- Storing data using SHA-1 hashing (similar to how Git tracks content)
- Building a basic commit system

This is a personal project aimed at enhancing my knowledge of Git and its internals. It is not meant to be a full-featured Git implementation, but rather an educational tool to understand the concepts behind Git.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On Mac/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Run the `git.py` file:
   ```bash
   python git.py
   ```

## Learning Objective

The primary objective of this project is to **understand Git better** by building a simplified version of its core functionalities. The project is inspired by the structure and behavior of the actual Git client.

## Source of Inspiration

The project is inspired by [Ben Hoyt's article on building a simple Git client](https://benhoyt.com/writings/pygit/). I have followed his guide to reimplement core Git features and added my own enhancements to further deepen my understanding of Git's internals.

Additional sources referred for understanding:
1. [Pro Git Book](https://git-scm.com/book/en/v2)
2. [Git Documentation](https://git-scm.com/doc)

## Disclaimer

This project is purely for educational purposes and is not intended to replace Git or be used in production environments.

## License

This project is licensed under the MIT License 



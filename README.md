### Generating `requirements.txt` using pipreqs

To simplify the process of creating a `requirements.txt` file based on your Python project's dependencies, you can utilize a tool called `pipreqs`. This tool automatically scans your Python files to identify the imports and generates a `requirements.txt` file with the appropriate versions. Below are the steps to achieve this:

#### 1. Install pipreqs

If you haven't installed `pipreqs` yet, you can do so using pip:

```bash
pip install pipreqs
```

#### 2. Run pipreqs

Navigate to the directory containing your Python files and run `pipreqs`:

```bash
pipreqs .
```

This command will scan the Python files in the current directory and its subdirectories, identifying the imports, and generating a `requirements.txt` file accordingly.

Please ensure that you run `pipreqs` in the same environment where your project dependencies are installed. If you're utilizing a virtual environment, activate it before running the command.

# Copilot Instructions for Streamlit Practice Project

Welcome to the Streamlit Practice Project! This document provides guidance for AI coding agents to effectively contribute to this codebase. Please follow these instructions to ensure consistency and productivity.

## Project Overview
This project is a practice environment for building Streamlit applications. The main goal is to create interactive web applications using Python and the Streamlit framework. The project is structured as follows:

```
streamlit-practice/
├── app.py          # Main entry point for the Streamlit app
├── main.py         # Additional logic or utilities for the app
├── sample1.py      # Example Streamlit app for practice
env/                # Python virtual environment
```

## Key Workflows

### Setting Up the Environment
1. **Create a virtual environment** (if not already created):
   ```bash
   python3 -m venv env
   ```
2. **Activate the virtual environment**:
   - macOS/Linux:
     ```bash
     source env/bin/activate
     ```
   - Windows:
     ```bash
     .\env\Scripts\activate
     ```
3. **Install dependencies**:
   ```bash
   pip install streamlit
   ```

### Running the Streamlit App
To run the main Streamlit app (`app.py`):
```bash
streamlit run app.py
```

To run the sample app (`sample1.py`):
```bash
streamlit run sample1.py
```

### Debugging
- Use `print()` statements in the Python files to debug the application. The output will appear in the terminal where the Streamlit app is running.
- Ensure the virtual environment is activated before running any commands.

## Project-Specific Conventions
- **File Naming**: Use descriptive names for Python files that reflect their purpose (e.g., `app.py` for the main application).
- **Streamlit Usage**: Follow Streamlit's best practices for creating interactive web applications. Refer to the [Streamlit documentation](https://docs.streamlit.io/) for guidance.
- **Virtual Environment**: Always activate the virtual environment before running or modifying the code.

## External Dependencies
- **Streamlit**: The primary framework for building the web application. Install it using `pip install streamlit`.
- **Python 3.11**: Ensure you are using Python 3.11 as specified in the virtual environment.

## Notes
- If you encounter issues running the app, ensure that the virtual environment is activated and all dependencies are installed.
- The `env/` directory contains the virtual environment and should not be modified directly.

## Key Files
- `app.py`: Main entry point for the Streamlit application.
- `main.py`: Contains additional logic or helper functions.
- `sample1.py`: A sample Streamlit application for practice.

For further questions or issues, please consult the project owner or refer to the Streamlit documentation.
# Django Project Template

This repository provides a basic, well-structured template for starting new Django projects. It includes common configurations and best practices to streamline your development workflow.

## Features

* **Clear Project Structure:** 
    * Follows a well-defined directory structure for better organization.
    * Includes separate folders for `apps`, `configs`, `static`, `media`, and more.
* **Basic App:**
    * Includes a sample app with basic models, views, and URLs.
* **Environment Configuration:**
    * Utilizes environment variables for managing project settings.
    * Includes a `.env.example` file for easy setup.
* **Testing:**
    * Basic test suite with sample unit tests.
* **Linting:**
    * Includes a `pyproject.toml` file for configuring linters like `flake8` and `black`.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [invalid URL removed]

2. **Create virtual environment:**

3. **Add .env file with below info:**
   ```bash
   ON_CODESPACE=True (if using codespace)
   DJANGO_SECRET_KEY=''
   DJANGO_DEBUG=True

4. **Install dependecies:**
```bash
pip install -r requirements.txt or
pip install -r requirements_codespace.txt or
pip install -r requirements_production.txt

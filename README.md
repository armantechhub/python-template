
# <img style="width:50px; mix-blend-mode: multiply;" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSLR_ZTv5nUSWIbBenV7lIzKZhUw0zVUmYaA&s"/> Cookiecutter Python Template

![GitHub stars](https://img.shields.io/github/stars/armantechhub/python-template.svg)
![GitHub forks](https://img.shields.io/github/forks/armantechhub/python-template.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/armantechhub/python-template.svg)

## 🚀 Overview

The Cookiecutter Python Template is designed to streamline the creation of new Python projects. With a single command, you can generate a fully-fledged project structure complete with a `pyproject.toml` configuration file, ready to build and test your application.

## 💻 Getting Started

To get started, you need to have [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) installed in your environment. Once installed, you can generate a project by running the following command:

```sh
python -m cookiecutter gh:armantechhub/python-template
```

### 🎉 What You Get

After running the command, a new directory will be created with the name of your project. Inside this directory, you will find a `pyproject.toml` file which is pre-configured with the following features:

- **Building System**: Ready to use with `hatchling` and `hatch-requirements-txt` for packaging your project.
- **Project Metadata**: Including name, description, license, authors, and URLs.
- **Dependency Management**: Automatically reads dependencies from `requirements.txt`.
- **Versioning**: Dynamically fetches the version number from the source code.
- **Testing**: Set up with `pytest` and `coverage` for running tests and generating coverage reports.
- **Linting**: Configured with `black`, `mypy`, and `ruff` for code style checking and formatting.

## 🛠️ Customization

During the generation process, you will be prompted to enter various details about your project, such as the project name, description, and author information. These details are used to populate the `pyproject.toml` file and other relevant project files.

### 📝 Cookiecutter Settings

Here's an overview of the settings you will be asked to provide:

- `project_name`: The name of your project.
- `description`: A brief description of your project.
- `root_name`: The root name of your project, derived from the project name.
- `module_name`: The module name of your project, derived from the root name.
- `git_hosting`: The hosting service for your Git repository.
- `author_name`: Your name or the name of the project author.
- `author_email`: Your email address or the email address of the project author.
- `git_username`: Your username for the Git hosting service.
- `git_repo`: The URL of the Git repository, automatically generated from the other settings.

## 🌟 Why Use This Template?

Using this template ensures that your Python project starts off on the right foot with a well-structured setup. It saves you time by automating the initial project configuration, allowing you to focus on developing your application instead of setting up the development environment.

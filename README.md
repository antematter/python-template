# Rrerequisites
1. Make sure you've python installed on your machine.
2. Install poetry package manager using this [link](https://python-poetry.org/).
3. Make sure **make** is installed on your machine. If you use Arch Linux, you probably don't even need to read this. On debian based systems, you need to install the `build-essentials` package. On Windows, I recommend first installing the chocolatey package manager from [here](https://chocolatey.org/install). After successfully installing it, you'd need to run `choco install make`. If you're on Mac, run `brew install make` 


# TODO:
1. Replace all instances of `project_name` with the real name of the project.
2. Rename the `project_name` folder inside `src` directory to the project's name.
3. Run `poetry update`. This will setup the poetry project for on your machine.
4. Run `poetry run pre-commit install` in order to initialize `pre-commit`.
5. Run `poetry run pre-commit run` in order to verify if`pre-commit` is working fine.
6. Run `Make lint`. This will ensure the linters are configured properly.
7. Update this `README.md` with your project details.



# Guidelines
1. All of the documentation of your project should go in `docs`.
2. Make sure to use a python version as mentioned in `pyproject.toml`.
3. Please use Antematter's conventions for git commit messages.
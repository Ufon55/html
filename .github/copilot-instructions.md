

# Copilot Instructions for Python

-   The package `Python` is a Python Project located in the folder `Python-folder`.
-   You need to call the `Get Python Environment Information` tool on the `Python` path to get the Python executable details.
-   Substitute the Python executable you get from the `Get Python Environment Information` tool anywhere you see `<python>` in these instructions.
    -   Run command for `Python`: `<python> -m Python`
    -   Command to run tests for `Python`: `<python> -m pytest Python/tests`
-   To run an editable install for the package `Python`, use the `Install Python Package` tool with the `Python-folder` path and arguments `['-e', '.']`.
-   In the workspace `launch.json` file, configurations related to this package have the prefix `Python`.
-   The package `Python` has a defined `pyproject.toml` file that you should use and keep up to date.


# Copilot Instructions for python.py

-   The script `python.py` is a Python python project within the workspace.
-   It has inline script metadata (as proposed by PEP 723) that defines the script name, required python version, and dependencies.
-   If imports which require a specific Python version or dependencies are added, keep the inline script metadata up to date.
-   You need to call the `Get Python Environment Information` tool on the `python.py` path to get the Python executable details.
-   Substitute the Python executable you get from the `Get Python Environment Information` tool anywhere you see `<python>` in these instructions.
    -   Run command for `python.py`: `<python> python.py`
    -   Script can be easily debugged from the Integrated Terminal when activated with the command `debugpy python.py` after the necessary environment is activated.

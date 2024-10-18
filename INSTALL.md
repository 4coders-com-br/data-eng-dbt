# dbt Install

Install local enviroment for dbt development and execution

## Requirements

Downloads and installs necessary to develop and run dbt.

- git

- Python (HOST)
    https://www.python.org/downloads/release/python-3130/

- IDE: VsCode

- Python Env: venv

https://docs.getdbt.com/docs/core/pip-install

``` bash
python -m venv dbt-env
source dbt-env/bin/activate
```

``` bash
deactivate
python -c "import sys; print(sys.executable)"
pip install requests
pip list
```

- dbt core:

``` bash
python -m pip install dbt-core dbt-postgres
```

- project:

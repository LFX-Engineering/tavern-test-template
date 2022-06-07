# tavern-test-template

This repository is a starter template repository for conducting an API test with Tavern.

## Python Setup

```bash
# Create a virtual env (assumes python3)
virtualenv .venv

# Load the virtual environment
.venv/bin/activate

# Install the requirements
pip3 install -r requirements.txt
```

## Write Tests!

1. review the `tests/` folder.
1. for each YAML file, open and review the instructions
1. once done editing the Tavern tests, run the tests to see if they all pass

## Running

To run the tests:

```bash
py.test tests/*.yaml -v --alluredir=allure_reports
```

## References

1. [Tavern Documentation](https://tavern.readthedocs.io/en/latest/)
1. [PyTest](https://pypi.org/project/pytest/)

## License

Copyright The Linux Foundation and each contributor to LFX.

This project’s source code is licensed under the MIT License. A copy of the license is available in LICENSE.

This project’s documentation is licensed under the Creative Commons Attribution 4.0 International License \(CC-BY-4.0\).
A copy of the license is available in LICENSE-docs.

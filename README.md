# How to run tests

### PREREQUISITES!
- Make sure you have already installed Python with pip in your system

### STEPS
- Clone repository
- Change directory to the newly cloned repository
- Run the command `pip install -r requirements.txt`
- Change directory to `tests`
- To run test cases, you enter the command:
    - `pytest -vs ./test_cases/{name_of_file}` to run the entire suite
    - `pytest -vs ./test_cases/{name_of_file}::{name_of_class}` to run specific test scenarios
    - `pytest -vs ./test_cases/{name_of_file}::{name_of_class}::{name_of_function}` to run specific test cases
    - `pytest -vsk {test_case_keyword}` to run test cases with the mentioned keyword

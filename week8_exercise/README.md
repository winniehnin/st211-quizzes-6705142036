# Week 8 - Parameterized and Data-Driven Testing

## Overview
In Week 8, I learned how to use parametrized fixtures and data-driven testing with pytest.

## What I Learned
- Using `@pytest.fixture(params=...)`
- Testing different values with `request.param`
- Using `yield` for setup and teardown
- Loading test data from JSON and CSV files
- Running multiple tests with `pytest.mark.parametrize`

## Files
- `test_param_fixture.py` - Tests database types
- `test_browsers.py` - Tests browser fixtures
- `test_cases.json` - JSON test data
- `test_data_driven.py` - Tests using JSON
- `logins.csv` - CSV test data
- `validate.py` - Login validation function
- `test_csv_driven.py` - Tests using CSV

## Run Tests

```bash
python -m pytest -v
```

## Reflection
In this lab, I learned how to use fixtures and external data files for testing. It helps me write less code and makes testing easier.
# Week 7 - Pytest Parametrization

## Overview
In Week 7, I learned how to use pytest parametrization to test Python functions with different input values. Instead of writing many separate test functions, I can use `@pytest.mark.parametrize` to run multiple test cases with less code.

## What I Learned
- How to use `@pytest.mark.parametrize` with different inputs.
- How to test multiple combinations using stacked parametrization.
- How to test discount calculations with different percentages.
- How to check invalid inputs using `pytest.raises(ValueError)`.
- How to use custom test IDs to make test results easier to read.
- How to use `pytest.param()` for individual test cases.
- How to use `pytest.mark.xfail` for expected failures.

## Files in Week 7

| File | Description |
|---|---|
| `discount.py` | Function for calculating discounts. |
| `mathutils.py` | Helper functions for mathematical calculations. |
| `test_custom_ids.py` | Tests using custom IDs for different users. |
| `test_default_ids.py` | Tests with automatically generated IDs. |
| `test_discount_errors.py` | Tests invalid discount percentages. |
| `test_discount.py` | Tests discount calculations. |
| `test_factorial.py` | Tests factorial calculations. |
| `test_multi.py` | Tests multiple combinations of x and y. |
| `test_param_ids.py` | Tests using `pytest.param()` with custom IDs. |
| `test_param_marks.py` | Tests using expected failure markers. |
| `test_param.py` | Tests using basic parametrization. |


## Test Results

Expected result: 40 passed, 1 xfailed. The expected failure is the lecture demonstration, not an unfinished exercise.

## Reflection

From this exercise, I learned that pytest parametrization makes testing easier and saves time. I can test different inputs using one function instead of writing the same code many times. I also learned how to check invalid values and use custom IDs to understand test results more clearly. This will help me write better tests in future Python projects.
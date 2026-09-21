# Lab 3 - Assertions and Test Organization

## Course
192-211 Automated Software Testing

## Lab Topic
Assertions and Test Organization using pytest

## Introduction

In this lab, I learned how to use pytest for writing and organizing automated tests. 
I practiced different types of assertions, test classes, markers, skipped tests, 
expected failures, and pytest configuration.

## What I Learned

- How to use assertions with lists, dictionaries, and sets
- How to compare floating-point numbers using `pytest.approx`
- How to organize related tests using test classes
- How to use pytest markers such as `smoke`, `slow`, and `regression`
- How to skip tests using `skip` and `skipif`
- How to use `xfail` for tests with known problems
- How to configure pytest using `pytest.ini`
- How `strict-markers` catches undeclared markers

## Project Files

| File | Description |
|---|---|
| `test_collections.py` | Tests lists, dictionaries, and sets |
| `test_floats.py` | Tests floating-point comparisons |
| `shopping.py` | Contains the ShoppingCart class |
| `test_shopping.py` | Tests the ShoppingCart class |
| `test_markers.py` | Demonstrates pytest markers |
| `test_skips.py` | Demonstrates skipped tests |
| `test_xfail.py` | Demonstrates expected failures |
| `test_conditional.py` | Demonstrates conditional skipping |
| `test_strict.py` | Tests strict marker checking |
| `pytest.ini` | Pytest project configuration |

## How to Run the Tests

First, activate the virtual environment:

```powershell
.\venv\Scripts\Activate.ps1
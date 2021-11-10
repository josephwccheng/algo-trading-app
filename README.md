# Algorithm Trading Application

A trading bot which collects data from multiple sources and allows users to use different models based on different features

## How to Run Application

1. Setup/Switch to a virtual environment (for `venv` see google's [venv guide](https://cloud.google.com/python/docs/setup#linux_1)). Then install dependencies as so:
    ```shell
    pip3 install -r requirements.txt
    ```
    OR using the Makefile
    ```
    make init
    ```
2. Create a `.env` file in the same folder as this project. The environment variables you will putting in it are:
    ```python
    yahoo_finance_api_token=<YAHOO-FINANCE-API-KEY>

## Requirements
Python3+

## Author
- Joseph Cheng
- Ray Wu
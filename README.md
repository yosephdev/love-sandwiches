# Sandwich Automator

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome to Sandwich Automator, a Python command-line application designed to automate data processes for a fictional sandwich company called Love Sandwiches.

## Overview

This application interacts with Google Sheets to collect and process sales data, calculate surplus, and make recommendations for future stock. It's deployed on Heroku, and you can access it [here](https://sandwich-automator-4e93d4a0a85f.herokuapp.com/).

## Getting Started

### Prerequisites

- Python 3
- Google Sheets API credentials (`creds.json`)

### Installation

1. Clone the repository: `git clone https://github.com/yosephdev/love-sandwiches`
2. Install dependencies: `pip install -r requirements.txt`

### Usage

Run the app using the following command:

```bash
python3 run.py
```
Follow the prompts to enter sales data and let the app automate the process.

## Key Features

- **Sales Data Entry**: Collects sales figures from the user for the last market.
- **Surplus Calculation**: Compares sales with stock to calculate surplus or waste.
- **Stock Recommendation**: Calculates the average stock for each item type and adds 10% for future markets.

## Code Structure

- **`run.py`**: Main Python file containing the project code.
- **`requirements.txt`**: File listing project dependencies.

## Deployed App

The app is deployed on Heroku. Access it [here](https://sandwich-automator-4e93d4a0a85f.herokuapp.com/).

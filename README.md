# Moberg-Analytics-Integration

## Clients must fork the repository and not create a PR. 

Template codebase for third party integration with Moberg Analytics. Please feel free to make the changes to this file as required by the module

## Repo structure

```
tests (dir) --> Contains input and output test cases

main.py --> contains code to show how to run the module

module_name.so --> shared object file that can be imported as a python package

LICENSE --> should be changed according to the requirements

test_file.csv --> provide a csv test file, for the test and use cases. (This file might not have required channels for the module)

```

## Introduction

Description about the integration with Moberg Analytics and introduction for the module

## Setup & Installation

### Requirements

Ensure your environment matches the following versions to avoid any compatibility issues:
```
Python 3.8.19
numpy==1.20.3
pandas==2.0.2
scipy==1.10.0
pytest==8.1.1
```

### Installation steps

1. Clone the repo

```
git clone https://github.com/your-repo/moberg-analytics-integration.git
```
```
cd moberg-analytics-integration
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Build the module


## Usage

## Importing and running the module
You can import the provided module into your Python code as follows:
```
import moberg_integration as mi
```

## Testing
We use pytest for testing the integration.

## Demo Input File
Please provide a demo input file for testing purposes

## Delay in response
If there are any known delays in response for detecting events, please provide an estimation. This will help us approach our implementation more effectively.

## Changelog
This section will include updates and version changes.


## Contact
Please provide any contact information here

# API Data Exporter

## Description

This project involves building Python scripts to interact with a REST API, retrieve data about employees' tasks, and export that data into various formats such as CSV and JSON. The scripts utilize libraries such as `urllib` or `requests` for API interaction and ensure adherence to Python coding standards.

## Learning Objectives

Upon completion of this project, you should be able to explain:

- The limitations of Bash scripting for certain tasks
- What an API is and its purpose
- The concept of REST APIs
- Microservices architecture
- The CSV and JSON data formats
- Pythonic naming conventions and coding style

## Project Structure

The project consists of the following files:

- `0-gather_data_from_an_API.py`: Script to retrieve information about an employee's TODO list progress from the API.
- `1-export_to_CSV.py`: Extends the functionality of the first script to export data in CSV format.
- `2-export_to_JSON.py`: Extends the functionality of the first script to export data in JSON format.
- `3-dictionary_of_list_of_dictionaries.py`: Further extends functionality to export data for all employees in JSON format.
- `README.md`: This file providing an overview of the project.

## Requirements

### General

- Editors: vi, vim, emacs
- Operating System: Ubuntu 20.04 LTS
- Python Version: 3.8.5
- Libraries: urllib or requests
- Code Style: PEP8 (pycodestyle version 2.8.*)
- Documentation: All modules must have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- Executability: All files must be executable
- Import Organization: Libraries should be organized alphabetically
- File Length: Checked using `wc`
- Code Execution: Scripts should not execute when imported
- Copyright: Plagiarism is strictly prohibited

### Tasks

- **Task 0**: Gather data from an API
- **Task 1**: Export data to CSV
- **Task 2**: Export data to JSON
- **Task 3**: Export data for all employees to JSON

## Usage

Each script can be executed with appropriate parameters to perform specific tasks as outlined in the project requirements.

Example usage:

```bash
python3 0-gather_data_from_an_API.py <employee_id>
python3 1-export_to_CSV.py <employee_id>
python3 2-export_to_JSON.py <employee_id>
python3 3-dictionary_of_list_of_dictionaries.py

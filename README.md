# New Relic NerdGraph Workflow Template

This repository provides a template for creating New Relic NerdGraph workflows to accomplish various tasks.

## Overview

This template includes the necessary structure and examples to help you get started with building workflows using New Relic's NerdGraph API.

## Directory Structure

- `nerdgraph/data/`: Contains data handlers, including CSV handlers.
  - `csv_files/`: Modules for reading and writing CSV files.
- `nerdgraph/api/`: Contains the implementation of the NerdGraph API client and related utilities.
  - `nerdgraph_client.py`: The `NerdGraphClient` class for interacting with the NerdGraph API.
  - `queries/`: Holds GraphQL queries and supporting logic.

## Usage

### CSV File Utilities

To use the CSV file utilities, import the necessary functions or classes from the `csv_files` directory.

#### Example

```python
from nerdgraph.data.csv_files import csv_reader, csv_writer

# Reading from a CSV file
data = csv_reader.read_csv('path/to/your/file.csv')

# Writing to a CSV file
csv_writer.write_csv('path/to/your/output.csv', data)# nr-nerdgraph-workflow-template
```

# License
This project is licensed under the MIT License.

This README provides an overview of the project, directory structure, usage examples, and licensing information.

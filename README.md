# Cargo Tracking System

This project aims to create a user-friendly cargo tracking panel. Developed to efficiently manage customer and cargo information using various data structures and algorithms.

## Features

- **Customer Management**: Cargo information and shipping history are managed using a linked list structure.
- **Cargo Prioritization**: Prioritization is done based on delivery times using a priority queue algorithm.
- **Cargo Routing**: Optimal routes are created using a tree data structure.
- **Shipment History Querying**: Quick access to recent shipment history is provided using a stack data structure.
- **Status Querying**: Cargo statuses are queried and sorted using binary search and quick sort algorithms.

## Required Components

1. **Backend**: Python 3.10 or higher.
2. **Frontend**: A user interface developed using Qt Designer.

## Installation Instructions

### 1. Python Installation

Ensure that Python 3.10 or a later version is installed on your system to run the project.

- To download Python: [Python Official Website](https://www.python.org)

### 2. Installing Required Libraries

Run the following command to install the required Python libraries:

```
pip install -r requirements.txt
```
### 3.Running the Code

1. You can run the project by following the steps below:

Run the main.py file:
```
python main.py
```
2. When the application interface opens, you can select the necessary operations from the menu.

## User Guide

**Customer Management**

* Go to the "Add Customer" section to add a new customer.

* Use the "Query History" option by entering the customer ID to view the shipping history of an existing customer.

**Cargo Prioritization**

* Add a new cargo by entering the shipment details.

* Process the highest priority cargo using the "Process Cargo" option.

**Cargo Routing**

* Use the "Show Route" option to view delivery routes.

**Shipment History**

* View your recent shipments with the "List History" option.

**Status Querying**

* Use the "Query Status" option to query delivered or undelivered cargo.

## Contributing
If you would like to contribute, please follow the steps below:

1. Fork this repo.

2. Create a new branch: git checkout -b feature/name

3. Make your changes and commit: git commit -m 'Add new feature'

4. Push your branches: git push origin feature/name

5. Create a Pull Request.

**The https://github.com/anjalp/Minimalistic-Flat-Modern-GUI-Template UI template was used in this project.**

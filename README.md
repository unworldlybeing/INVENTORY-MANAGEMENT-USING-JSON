# INVENTORY-MANAGEMENT-USING-JSON
This is a basic Python project for managing a simple inventory and billing system using JSON for data storage.

## Features

- Display product menu from a JSON file
- Take customer details and product order
- Check and update product quantity
- Generate billing summary
- Log sales information to a text file
- Update inventory after each order

## Files

- `Record.json` - Stores the product inventory in JSON format
- `salesJson.txt` - Logs each sale with customer and order details
- `main.py` - Main script for running the inventory and billing system

## How to Run

1. Ensure Python is installed on your system.
2. Create a `Record.json` file with inventory data. Example format:

```json
{
    "101": {
        "Name": "Pen",
        "Price": 10,
        "Qn": 100
    },
    "102": {
        "Name": "Notebook",
        "Price": 50,
        "Qn": 200
    }
}

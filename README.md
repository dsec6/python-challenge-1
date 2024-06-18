# Food Truck Order Management System

This project is a Python-based order management system for a food truck. It allows customers to select items from a menu, specify quantities, and place orders. The system calculates the total price of the order and generates a receipt.

This is just a class project so don't take it to seriously.


## Features

- Interactive menu selection: Customers can choose from various menu categories and item options.
- Input validation: The system validates customer inputs to ensure data integrity.
- Order tracking: The system keeps track of the items ordered, their quantities, and prices.
- Receipt generation: A detailed receipt is generated at the end of the order, displaying the ordered items, quantities, and total price.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/dsec6/python-challenge-1
   ```

2. Navigate to the project directory:

   ```
   cd python-challenge-1
   ```

### Usage

1. Run the Python script:

   ```
   python python-challenge-1.py
   ```

2. Follow the on-screen instructions to select menu categories, choose items, and specify quantities.

3. After completing your order, the system will generate a receipt displaying the ordered items, quantities, and total price.

## Menu Structure

The menu is defined as a nested dictionary in the `menu` variable. It has the following structure:

```python
menu = {
    "Category1": {
        "Item1": price1,
        "Item2": price2,
        ...
    },
    "Category2": {
        "Item3": price3,
        "Item4": {
            "Subitem1": price4,
            "Subitem2": price5,
            ...
        },
        ...
    },
    ...
}
```

- Each category is represented as a key in the `menu` dictionary.
- Each item within a category is represented as a key-value pair, where the key is the item name and the value is either the item price or another dictionary for subitems.
- Subitems are represented as nested dictionaries within an item.

Thanks for reading :)
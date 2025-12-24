# Mini Application of Product Stock Management

This project is a Python-based mini-application designed to manage the inventory of electronic products at **Gudang Elektronik Nadhia**. The application allows users to display the product list, add new products, update existing product information, and delete products. Users can also filter products by code, category, or brand, and view the product list in a neatly formatted table using **Tabulate**. The project provides a simple yet practical tool to manage warehouse inventory efficiently and supports basic stock management operations.

---

## Data
The project uses a small dummy dataset consisting of 15 product entries stored as a Python list of dictionaries. Each product has six fields:

- **Code (Primary Key)**
- **Category**
- **Brand**
- **Release Year**
- **Stock**
- **Price**

---

## Key Features

1. **Main Menu**
   - Provides access to all functionalities: display, add, update, and delete products  
   - Allows users to exit the program  

2. **Display Products**
   - View the entire inventory  
   - Filter products by code, category, or brand  
   - Display products in a tabular format for better readability  

3. **Add Product**
   - Add new products to the inventory  

4. **Update Product**
   - Update product details including category, brand, release year, stock, and price  
   - Product codes cannot be changed as they serve as the primary key  

5. **Delete Product**
   - Remove existing products from the inventory

---

## Tools Used
- **Python**: Core programming language for the application  
- **Tabulate**: For displaying products in table format

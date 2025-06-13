# 🛍️ Shop Inventory Manager (Java + SQLite)

A simple Java-based inventory management system designed to help small shopkeepers manage products based on shelf location (row × column), update stock, and generate bills — all stored locally using a lightweight SQLite database.

---
youtube video ---> https://youtu.be/QeIo3W8qNbo


## 📖 About the Project

This project idea came from a real-life scenario when one of my friends asked me to create software for his newly opened shop. He said:

> "We have opened a new shop with more than 120 shelves. It's getting hard to manage the products properly. Can you build something simple for us?"

He requested a solution that met the following needs:

- ❌ Does not require internet
- 💾 Stores data locally in a `.db` file
- 🔍 Allows product access using shelf positions (Row × Column)
- 🖥 Can be converted into a `.exe` file for non-technical users

That conversation inspired me to build this offline, Java-based inventory management system.

---

## ✨ Features

- ✅ Add Product (name, price, quantity, shelf row, column)
- 🗂 View All Products in Inventory
- 🔄 Update Product Details
- ❌ Delete Product
- 🧾 Generate Bill using Shelf Location (Row × Column)

---
- challlages which are still unsolved -- i am unable to convert.java to .exe file 
+ ❗ Challenges Still Unresolved
+ I am currently unable to convert `.java` to `.exe`. 
+ If you have a solution, please email me at: 📧 [sumantpra7@gmail.com](mailto:sumantpra7@gmail.com)
## 🔮 Future Improvements
- Export bill as PDF
- Successfully package app as `.exe` for Windows





## 🔧 Tech Stack

| Tech      | Purpose                                 |
|-----------|-----------------------------------------|
| Java      | Core application logic                  |
| SQLite    | Lightweight local database (`shop.db`)  |
| JDBC      | Java-Database connectivity              |
| IntelliJ  | IDE for development                     |



## 🚀 Getting Started

### Requirements

- Java 17 or higher installed
- IntelliJ IDEA, VS Code, or any Java IDE
  

### Steps to Run

```bash
1. Clone the repository:
   git clone https://github.com/sumantpra7/shop07

2. Open the project in IntelliJ IDEA (or any IDE of your choice)

3. Make sure the `shop.db` file is placed in the root directory

4. Run `ShopInventoryManager.java` from your IDE

Note:
- No external DB setup is required
- SQLite is used as a local embedded database

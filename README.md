# ⚡ Electricity Bill Simulator

A menu-driven **C programming project** that simulates an electricity billing system. It allows users to manage consumer details, calculate electricity bills using slab-based rates, generate bills, and store records using file handling.

## 🚀 Features

- 👤 Add new consumer
- 🔢 Enter electricity units
- 🧮 Calculate bill using slab rates
- 🧾 Generate electricity bill
- 🔍 Search consumer records
- 📋 View all consumers
- 📊 Analyze electricity consumption
- 💾 Store data using file handling
- 💡 Display electricity-saving tips
- 🗑️ Delete consumer records

## 🛠️ Technologies Used

- **C Programming**
- Structures
- Arrays
- Functions
- Conditional Statements
- Loops
- String Handling
- File Handling

## 💰 Billing System

The bill is calculated according to the electricity units consumed.

| Units | Rate |
|---|---:|
| 0–100 | ₹2/unit |
| 101–200 | ₹3/unit |
| 201–500 | ₹5/unit |
| Above 500 | ₹7/unit |

Additional fixed charges can also be included in the final bill.

## 📂 Project Structure

```text
Electricity-Bill-Simulator/
│
├── electricity_bill.c
├── electricity_data.txt
└── README.md
▶️ How to Run
1. Clone the repository
git clone https://github.com/your-username/electricity-bill-simulator.git
2. Open the project folder
cd electricity-bill-simulator
3. Compile
gcc electricity_bill.c -o electricity_bill
4. Run
./electricity_bill
📚 Learning Outcomes

This project provides practical experience with:

C structures and functions
File handling
Menu-driven programming
Electricity bill calculations
Searching and managing records
Building a real-world console application

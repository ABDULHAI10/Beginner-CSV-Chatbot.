# 🗨️ Beginner CSV Chatbot

A simple **CSV-based chatbot** that can read your dataset, answer questions, and even suggest corrections if you misspell something.

## ✨ Features
- ✅ Reads data from a CSV file
- 🔍 Searches for any matching word in all columns
- 🤖 Suggests closest match if the query is misspelled
- 📄 Displays results in a clean table
- 🛑 Exit anytime by typing `exit`

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** → CSV reading and searching
- **difflib** → Closest match suggestions
- *(Optional)* matplotlib, seaborn, numpy → For future visualization features

## 📂 Project Structure

├── products.csv # Sample dataset
├── chatbot.py # Main chatbot script
└── README.md # Documentation


## 📊 Sample Dataset
```csv
Product,Category,Price,Stock
Apple,Fruit,100,50
Banana,Fruit,60,100
Orange,Fruit,80,75
Tomato,Vegetable,50,200
Potato,Vegetable,40,300
Milk,Dairy,120,40
Cheese,Dairy,250,20
Bread,Bakery,80,35
Eggs,Poultry,150,60
Chicken,Poultry,500,25

git clone https://github.com/YourUsername/csv-chatbot.git
cd csv-chatbot

You: mikl
Bot: Did you mean 'Milk'? (Type 'yes' to confirm)

You: yes
Bot: 
Product Category Price Stock
 Milk   Dairy    120   40

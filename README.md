Here's a different OOP program with the same difficulty level, but a new concept:

### Program Name: `Bank_Account.py`

```python
class bank_account:
    def __init__(self):
        self.name = "Rahul"
        self.account_no = 101
        self.balance = 5000
        
    def deposit(self):
        print("Amount deposited successfully...")
        
class customer:
    def __init__(self):
        self.name = "none"
        self.age = "none"
        self.city = "none"
        
    def details(self):
        print("Customer details updated...")


a1 = bank_account()
a2 = bank_account()
c1 = customer()

a2.name = "Aayush"
a2.account_no = 102
a2.balance = 10000

c1.name = "Arjun"
c1.age = 21
c1.city = "Bangalore"


print(a1.name)
print(a1.account_no)
print(a1.balance)

print(c1.name)
print(c1.age)
print(c1.city)

print(a2.name)
print(a2.account_no)
print(a2.balance)

print(a1)
print(a2)
print(c1)
```

README:

```markdown
# Bank Account and Customer Class Program

## 📌 Description
This Python program demonstrates the basics of **Object-Oriented Programming (OOP)** by creating classes and objects.

The program contains:
- `bank_account` class to store bank account information.
- `customer` class to store customer details.

It shows how objects are created from classes and how their values can be updated separately.

## 🚀 Concepts Covered
- Classes and Objects
- Constructor (`__init__`)
- Instance Variables
- Object Creation
- Updating Object Attributes

## 🛠️ Program Explanation

### Bank Account Class
The `bank_account` class stores:
- Account holder name
- Account number
- Account balance

It contains a method:
- `deposit()` → Displays deposit confirmation.

### Customer Class
The `customer` class stores:
- Customer name
- Age
- City

It contains a method:
- `details()` → Displays customer update message.

## 📂 Objects Created

### Bank Account Objects
- `a1` → Default account details
- `a2` → Updated account details

### Customer Object
- `c1` → Stores customer information

## ▶️ Sample Output
```

Rahul
101
5000

Arjun
21
Bangalore

Aayush
102
10000

```

## 💡 Learning Outcome
This program helps understand how classes work as blueprints and how different objects can maintain their own data.

## 👨‍💻 Author
Created for practicing Python OOP concepts.
```

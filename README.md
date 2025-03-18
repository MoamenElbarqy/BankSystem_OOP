# 🏦 BankSystem  

**BankSystem** developed using **Object-Oriented Programming (OOP) in C++**.  
This file-based project simulates real-world banking operations with a strong focus on **Account management, User management, Financial transactions and Some Security By Saving The Passwords Encrypted**.  
The system prevents unauthorized access by automatically locking after three consecutive failed login attempts.  
The system ensures that users without the required permissions cannot perform restricted operations.  
##  Notes

🔹Defualt user to login : 
~~~
Username : User1

Password : 1234
~~~

🔹All Phone Numbers And Emails are fake 

🔹The System Prevent You From Deleting The User You Have Entered With, No Meaning For Deleting Myself

🔹Currencies Data is not up to date, But You Can Update its Rate in File Using The System

🔹You May Have Issues If You Run The Program From The Terminal, You Can Run The .exe file directly or Run From The cmd

- isuue sample :[Formatting Issue Sample Screen Shot](https://github.com/user-attachments/assets/c609613b-3b05-437b-bdb3-a4827f5be9ec)


## 🛠 Installation Steps

Follow these steps to set up and run the project on your machine manually:  

### 1️⃣ Download the Project  
1. Click on the **"Code"** button at the top of this repository.  
2. Select **"Download ZIP"** to download the project files.  
3. Extract the ZIP file to a folder on your computer.  

### 2️⃣ Ensure You Have a C++ Compiler  

### 3️⃣ Compile the Project  

### 4️⃣ Run the Program  

### 5️⃣ Ensure Required Files Exist

The program requires the following text files **in the same directory**:  
- `CurrenciesData.txt`  
- `Users.txt`  
- `LoginLog.txt`  
- `TransferLog.txt`  
- `ClientsData.txt`  

## 📌 Features  
Testing Features -> (https://drive.google.com/file/d/1b_9j9B_1EYfWbmuc04tWoWGSClYgrmi_/view?usp=drive_link)
### 🔹 Client Management  
- View all registered clients.  
- Add, delete, update, and search for clients.  

### 🔹 User Management  
- Manage system users with different access levels.  
- Add, delete, update, and list users.  

### 🔹 Transaction System  
- Deposit and withdraw funds.  
- Transfer money between accounts.  
- View transaction history and total balances.  

### 🔹 Currency Exchange Operations  
- Display a list of currencies from different countries.  
- Search for a specific currency by its code or country name.  
- Calculator for Converting Currencies (e.g., I have 1000 EGP and want to know how many Dollars or Euros that equals)
- Update exchange rates (relative to the US dollar).  

### 🔹 Security & Logging  
- **System Will Close After 3 Failed Login Attempts**  
- **Login Activity Tracking:** Stores login details, including the user, login time, and date in text files.  
- **Transaction Logging:** Records money transfers, including sender and receiver details, transfer time and date, and account balances before and after the transaction.  


## 📌 User Interface  

### 🔹 Login Menu  

The login menu looks like this:  

~~~
===============================
         Login Screen      
===============================
 Enter Username: ________
 Enter Password: ________
-------------------------------
~~~
## 📌 Main Menu

Once logged in, users are greeted with the Main Menu, which looks like this:
~~~
===================================
          Main Menu Screen
===================================
[1] Show Client List.  
[2] Add New Client.  
[3] Delete Client.  
[4] Update Client Info.  
[5] Find Client. 
[6] Transactions.  
[7] Manage Users.  
[8] Login Register.  
[9] Currency Exchange.
[10] Logout 
===================================
~~~

## 📌Transactions Menue

Transactions Menue looks like this:
~~~
===================================
          Transactions Menue
===================================
[1] Deposit.  
[2] Withdraw.  
[3] Total Balances.  
[4] Transfer.  
[5] Transfer Data. 
[6] Main Menu.  
===================================
~~~
## 📌Currency Exchange Menue

Currency Exchange Menue looks like this:

~~~
===================================
          Currency Exchange Menue
===================================
[1] List Currencies.  
[2] Find Currencuey.  
[3] Update Rate.  
[4] Currency Calculator. 
[5] Main Menu.   
===================================
~~~

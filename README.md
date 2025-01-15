# **Features**
# **Account Management:**<br/> 
* Open a new account with basic details such as **Name**, **Password, Email, Mobile, and Account Type** (Saving or Current).
* Login to an existing account using the account number (ACN) and password.
* Forgot Password functionality: User can retrieve the password via OTP sent to the registered email.
* View account details such as balance, account type, and account opening date.

# **Transactions:**<br/> 
* Deposit funds into an account.
* Withdraw funds (with balance check).
* Transfer funds to another account (with balance check).
* View transaction history (deposits, withdrawals, and transfers).

# **Profile Management:**<br/> 
* Update profile information like Name, Password, Email, and Mobile Number.
* Profile picture update functionality.

# **Database Integration:**<br/> 
* Uses SQLite to store and manage user accounts and transaction histories.
*  Two tables: accounts (for user account details) and txn_history (for transaction records).

# **Technologies Used**<br/>
* Python 3: The programming language used to implement the system.
* Tkinter: A Python library for creating graphical user interfaces.
* SQLite: A lightweight database used for storing user account details and transaction history.
* Gmail API: Used to send OTPs to users' registered emails during the password recovery process.
* PIL (Pillow): Python Imaging Library used for handling profile pictures.

# **Usage**<br/>
**Main Screen**<br/>
* Login: Enter your Account Number (ACN) and Password to log in.
* Open Account: Open a new account by providing Name, Password, Email, Mobile Number, and Account Type (Saving/Current).
* Forgot Password: If you forgot your password, use your ACN and registered email to receive an OTP for recovery.<br/>
![image](https://github.com/user-attachments/assets/88f3b39b-4d01-44e3-bdb3-3c1fcffd0ce1)

# **Logged-in User Actions**<br/>
_ Once logged in, you can:_
* Check Details: View account details like Account Number, Balance, Account Type, and Date of Opening.
* Update Profile: Update your profile information such as Name, Password, Email, and Mobile Number.
* Deposit: Deposit funds into your account.
* Withdraw: Withdraw funds from your account (subject to balance check).
* Transfer: Transfer funds to another account.
* Transaction History: View a record of all past transactions (deposits, withdrawals, and transfers).
* Update Profile Picture: Upload a profile picture to personalize your account.<br/>
![image](https://github.com/user-attachments/assets/9950b6fe-2ad9-4839-8c6a-9502ab191e55)
# **Account Recovery**<br/>
* Forgot Password: If you forget your password, you can retrieve it using your registered email address. An OTP will be sent to your email for verification.
![image](https://github.com/user-attachments/assets/38c3d66f-3a88-440d-9ed6-6ddf4bcbef3b)
# **Database Structure**<br/>
#  **accounts table**:
 - **acn (INTEGER):** Account number (Primary Key).
 - **name (TEXT):** Account holder's name.
 - **password (TEXT):** Account holder's password.
 - **email (TEXT):** Account holder's email address.
 -** mob (TEXT):** Account holder's mobile number.
 -** bal (FLOAT):** Account balance.
 -** type (TEXT):** Account type (Saving or Current).
 -** opendate (TEXT):** Date the account was opened.<br/>
#  **txn_history table:**<br/>
 - **acn (INTEGER):** Account number.
 - **txn_amt (FLOAT):** Transaction amount.
 -** txn_type (TEXT):** Transaction type (Credit or Debit).
 - **txn_date (TEXT):** Date of the transaction.
 -** update_bal (FLOAT): **Updated account balance after the transaction.

# Contact
For any questions or support, please reach out to the project owner at **purushotamt858@gmail.com.**









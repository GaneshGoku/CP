LOAN MANAGMENT SYSTEM

🏦 Introduction

The Loan Management System (Admin Panel) is a backend-focused web application designed to help administrators manage loan-related operations efficiently. This system is not intended for customer access — it is exclusively built for internal use by authorized personnel such as admins, finance managers, or loan officers.

Developed using MongoDB as the database, this system allows admins to:

1) Add and manage customer details

2) Approve or reject loan applications

3) Track active loans and repayment history

4) Update or delete records securely

With a clean and simple interface, this system provides an organized way to oversee loan portfolios without exposing any features to end customers. It serves as a perfect foundation for financial institutions, internal company tools, or academic projects where only admin-level control is required.
## Deployment

To deploy this project run

1.Clone the repository:
```bash
  git clone https://github.com/GaneshGoku/Loan_Managment_System
  cd Loan_Managment_System

```
2.Install Dependencies
```bash
  npm Install

```
3.Configure Environment Variables
Create a .env file in the root directory:
```bash
  PORT=3000
  MONGO_URI=your-mongodb-connection-string
```
4.Run Localy
```bash
  npm start
```


## Usage
This Loan Management System is designed for admin use only. Below are the key functionalities and how an admin can use them:

👤 1. Manage Customers

Add Customer: Enter customer details (name, contact, etc.) and create a profile.

View Customers: Browse the list of all registered customers.

Update Customer: Modify customer information when needed.

Delete Customer: Remove a customer from the database.

💼 2. Loan Applications

Create Loan: Admin can assign a loan to a customer by specifying loan amount, interest rate, and repayment terms.

View All Loans: See the complete list of active, pending, or closed loans.

Approve/Reject Loans: Change the loan status based on eligibility and verification.

Track Loan Details: View remaining balance, payment schedule, and loan history.

💳 3. Loan Repayments

Add Repayment: Record a payment made by a customer toward a loan.

View Repayment History: Check past payments, outstanding balance, and due dates.

Mark Loan as Paid: When a loan is fully repaid, update its status accordingly.

🔐 Admin Access Only

⚠️ Note: There is no customer login or self-service portal in this system. Only admins can access the interface and perform operations.


## Contact
For any queries or support, please open an issue in the repository.

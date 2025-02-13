# BillMaker - A Simple Billing Solution for Small Businesses

## Overview
BillMaker is a Django-based web application designed to help small business owners generate and manage bills efficiently. Users can add shop details, create multiple bills, apply discounts, generate PDF invoices, and track past bills. The system also includes authentication, password reset functionality, and email verification using MailTrap.

## Features
- **User Authentication**: Custom authentication system with email verification.
- **Shop Management**: Users can add and update their shop details.
- **Billing System**:
  - Create multiple bills for customers.
  - Automatic calculation of total amount based on quantity and price.
  - Generate PDF invoices with one click.
  - Track and filter past bills by date and amount.
- **Security**:
  - Users cannot delete past bills for security purposes.
  - Password reset with token-based authentication .
- **User Experience**:
  - Responsive and intuitive UI using Bootstrap.
  - Informative messages for errors and actions.
- **Future Enhancements**:
  - GST application on bills.
  - Multi-shop management under one account.
  - Improved performance optimization and cloud storage for static files.

## Tech Stack
- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Database**: MySQL
- **Email Services**: MailTrap for email verification and password reset

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Adarshh5/Bill-Maker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SimpleInvoice
   ```
3. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Apply migrations:
   ```bash
   python manage.py migrate
   ```
6. Run the server:
   ```bash
   python manage.py runserver
   ```

## Usage
1. Register a new user and verify email through MailTrap.
2. Add shop details and start creating bills.
3. Generate and download bills in PDF format.
4. Reset password via email if needed.

## Deployment (Future Plan)
- Deploy on AWS using S3 for static file storage.
- Use a cloud database for scalability.

## Contributing
Feel free to fork this repository, raise issues, or contribute by creating pull requests.

## License
This project is licensed under the MIT License.

---
Let me know if you need any modifications!


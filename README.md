# Aldrino's POS System

Welcome to Aldrino’s POS System – a project developed to modernize the sales and inventory management processes at **Aldrino’s Bibingka at Puto Bumbong Special**. This system is tailored to bring efficiency and real-time insights into daily operations, making it easier to handle transactions, track inventory, and manage sales data.

---

### Overview

Aldrino’s POS System is designed for simplicity and efficiency, transforming traditional manual methods into a streamlined digital solution. The system is built on **PHP** and **MySQL**, providing robust data management and secure transactions with real-time stock monitoring and insightful sales reports.

### Key Features

- **User Authentication**: Secure access for Admin and Cashier roles with role-based features.
- **Inventory Management**: Real-time updates with automated stock level tracking and low-stock alerts.
- **Transaction Processing**: Smooth transaction handling, with receipt generation and discount options.
- **Sales Reporting**: Daily, weekly, and monthly reports on sales trends and top-selling items.
- **Data Security**: Regular backups and data encryption for enhanced security.

### System Requirements
- **Backend**: PHP 7+ and MySQL for database management.
- **Frontend**: HTML, CSS, JavaScript.
- **Hosting**: AWS EC2 with SSL security provided by GoDaddy.
- **Hardware**: Desktop, laptop, or tablet.

### Getting Started

#### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/APC-SoCIT/APC-SoCIT_AY_2024_2025_Aldrino-s_POS.git
    ```
2. **Database Setup**
    - Configure a MySQL database and run the SQL script in the repository’s `database` folder to create necessary tables.
3. **Environment Configuration**
    - Set up your `.env` file to configure database connections and other environment variables.
4. **Launch the Application**
    ```bash
    php -S localhost:8000
    ```
5. **Access the System**
    - Visit `http://localhost:8000` in your browser to access the POS system interface.

### Using the System

- **Admin Dashboard**: Manage inventory, view sales reports, and monitor recent transactions.
- **Cashier Interface**: Process customer transactions, apply discounts, and print receipts.
- **Sales Analysis**: Track top-selling items, generate sales reports, and monitor inventory for low-stock alerts.

### Development Team

- **Project Manager/Scrum Master**: Gabriel Dominic Marquez
- **Software Test Engineer/QA**: Ronaldo Bernasor II
- **Developer**: Ivan Josh Masongsong

### Testing and Quality Assurance

The testing process includes:
- **User Acceptance Testing (UAT)**: Simulates real-world scenarios to ensure a smooth user experience.
- **Manual Testing**: Performed by our team developers to rigorously test each feature one by one, ensuring everything works as intended.
- **Functional and Non-Functional Testing**: Validates transaction handling, inventory updates, and reporting features.
- **Defect Management**: JIRA is used for logging and tracking bugs, with regular team updates and issue resolutions.

### Contributing

We welcome contributions to improve Aldrino’s POS System. Please see our [Contribution Guide](https://github.com/APC-SoCIT/APC-SoCIT_AY_2024_2025_Aldrino-s_POS/blob/main/CONTRIBUTING.md) for more details on how to get involved.

### Reporting Issues

To report any issues or potential security vulnerabilities, please contact our development team at:
- Ivan Josh Masongsong: [irmasongsong@student.apc.edu.ph](mailto:irmasongsong@student.apc.edu.ph)
- Ronaldo Bernasor II: [rsbernasor2@student.apc.edu.ph](mailto:rsbernasor2@student.apc.edu.ph)
- Gabriel Dominic Marquez: [gfmarquez@student.apc.edu.ph](mailto:gfmarquez@student.apc.edu.ph)

We appreciate your help in keeping our project secure.

### License
This project is open-source but is licensed under the **Aldrino's POS System Non-Commercial License**. You are free to use, modify, and distribute this software, but **commercial use is prohibited** without prior permission.

For more details, please see the [LICENSE](https://github.com/APC-SoCIT/APC-SoCIT_AY_2024_2025_Aldrino-s_POS/blob/main/LICENSE) file.

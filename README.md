## About The Project

### 📘 Overview

Contract Payment is a dynamic and user-friendly app, designed to optimize the ERP payment process for businesses and individuals. It seamlessly links sales and purchase invoices to contracts, enabling efficient tracking and management of contract dues.

### ⭐ Key Features

- Linking of sales and purchase invoices with contracts
- Scheduling of contract dues or manual addition
- Generation of sales invoices if the party is a customer
- Creation of purchase invoices if the party is a supplier
- Automatic creation of salary slips if the party is an employee

## Technical Stack and Setup Instructions

### Prerequisites

Ensure your ERP system is up and running before installing Contract Payment.

### Installation

To install Contract Payment, simply clone the repository and install the app:

```sh
git clone https://github.com/ggraza/contracts.git
bench install-app contract_payment
```

After installation, remember to check the 'Is Contract Payment' option on your employee, customer, and supplier settings.

## Usage

Contract Payment offers a variety of settings for customizing your payment process. You can automate the creation of dues, submit dues immediately after creation, or implement checks to prevent the creation of invoices without selected contracts.

## Contribution Guidelines

We welcome your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

Please ensure your contributions are in line with the project's coding standards and include relevant unit tests.

## License and Acknowledgements

### License

This project is under the MIT License. Your contributions will also be licensed under the MIT License.

### Acknowledgements

We express our gratitude to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities upon which we rely. We are profoundly grateful for their pioneering work and ongoing support.
# Contract Payment

#### This app for make payment based on contracts for erpnext

#### this app link sales, purchase invoice with contract 
![alt text](https://github.com/morghim/contract-payment/blob/master/img/link-pur-invoice.gif)


#### make contract dues sechudaling or you can add it manualy
![alt text](https://github.com/morghim/contract-payment/blob/master/img/calc-dues.gif)


#### it make sales invoice if party type customer 

![alt text](https://github.com/morghim/contract-payment/blob/master/img/create-cont-sales-invoice.gif)

#### create sales invoice for customer contract
![alt text](https://github.com/morghim/contract-payment/blob/master/img/sales-invoice.gif)



#### it make purchase invoice if party type supplier

#### it make salary slip if party type employee 

## to install app 

`bench install-app https://github.com/morghim/contract-payment.git`

#### to use need to check is contract payment on employee, customer, supplier 

##### supplier
![alt text](https://github.com/morghim/contract-payment/blob/master/img/supplier.gif)

##### employee
![alt text](https://github.com/morghim/contract-payment/blob/master/img/employee.gif)

##### customer
![alt text](https://github.com/morghim/contract-payment/blob/master/img/customer.gif)




## settings:

###### atuomatic create dues: to make system automatic create purahase invoce and sales invoice on same date of due date
###### submit dues after create: this check for make purchase invoice and sales invoice submitted after create
###### stop create purchase invoice for supplier is contract payement: this check system will be stop any invoice without select contract for supplier
###### stop create sales invoice for customer is contract payment: this check will be stop any invoice for customer without select contract




#### License

MIT

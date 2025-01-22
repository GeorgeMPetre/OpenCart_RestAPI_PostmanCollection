OpenCart RestAPI Postman Collection

Overview

This repository contains a Postman collection for testing the OpenCart REST API. The collection provides endpoints to manage session tokens, products, cart operations, customer data, and checkout processes.

Collection Information

Collection Name: OpenCart_RestAPI_PostmanCollection

Postman Collection Format: v2.1.0

Base URL: http://{{ip}}/opencart/upload/index.php?route=

Environment Variable Required: ip (Please replace with your own OpenCart server IP)

Prerequisites

Before using the collection, ensure that you have:

Postman installed (Download here).

An active OpenCart installation.

Correct API credentials to authenticate and perform operations.

Endpoints Included

The following endpoints are covered in this collection:

Authentication

POST /api/login - Create session token.

Session Management

POST /api/currency - Change session currency.

Cart Operations

POST /api/cart/add - Add product to cart.

POST /api/cart/edit - Edit product quantity in cart.

GET /api/cart/products - Retrieve cart products.

Customer Management

POST /api/customer - Set customer for the current session.

POST /api/shipping/address - Set shipping address.

POST /api/payment/address - Set payment address.

Order Management

POST /api/order/add - Place an order.

GET /api/order/info - Retrieve order details.

Payment and Shipping

POST /api/payment/methods - Get available payment methods.

POST /api/payment/method - Set payment method.

POST /api/shipping/methods - Get available shipping methods.

POST /api/shipping/method - Set shipping method.

Vouchers

POST /api/voucher/add - Add a new voucher.

How to Use the Collection

Import Collection into Postman:

Open Postman and go to File > Import.

Select the OpenCart_RestAPI_PostmanCollection.json file.

Set Environment Variables:

Set baseURL and replace ip with your OpenCart server IP.

Execute API Requests:

Run individual requests or the full collection using the Postman Runner.

Check Responses:

Validate response status codes and success messages in the Tests tab.

Running Tests

This collection includes test scripts for each request to validate:

Response status codes.

Expected success messages.

Setting and retrieving collection variables dynamically.

Notes

Ensure the api_token variable is properly set after authentication for further API interactions.

Modify environment variables as needed to match your setup.

Check console logs in Postman for debugging and request tracking.

License

This project is licensed under the MIT License.
---

**Contact:**  
George Petre  
Sturry, CT2 0HN, UK  
📧 george.petre23@gmail.com  
🔗 [GitHub Profile](https://georgempetre.github.io)

# Magento 2 Custom Price Extension

## Introduction
Magento 2 Custom Price Extension allows store owners to set custom prices for products dynamically. This extension enhances pricing flexibility by enabling price adjustments based on specific conditions. Whether you want to offer personalized discounts or configure special pricing rules, this extension is the perfect solution for your Magento 2 store.

## How It Works
The Magento 2 Custom Price Extension modifies the product pricing logic, allowing store owners to set custom prices dynamically. When a customer adds a product to the cart, the system applies the predefined custom pricing rules. This extension is particularly useful for promotions, bulk discounts, and special customer-based pricing.

## Key Features
- Set dynamic custom prices for products.
- Apply special pricing rules based on conditions.
- Compatible with multiple product types.
- Seamless integration with Magento 2 checkout process.

## Custom Pricing Rules
### 1: Dynamic Price Adjustment
Magento 2 Custom Price Extension enables store owners to set flexible pricing rules based on product attributes, customer groups, or special promotions.

### 2: Bulk Pricing Support
This extension allows bulk price changes for multiple products, helping store owners manage large inventories efficiently.

### 3: Customer Group-Based Pricing
Different prices can be assigned to specific customer groups, offering personalized shopping experiences.

### 4: Easy Integration
Seamlessly integrates with Magento 2's core pricing structure without affecting other functionalities.

## Extension Installation
To install the Magento 2 Custom Price Extension, follow these steps:

### Step 1: Install the Extension Using Composer
```sh
composer require vendor/custom-price-extension
```
For a specific version:
```sh
composer require vendor/custom-price-extension:version
```
*Note: Authentication keys from the vendor or Magento Marketplace may be required.*

### Step 2: Run Magento Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Custom Price Extension

## 1.​ Enable Extension

Once after successfully install our extension, you will need to enable the
extension from Magento 2 admin. The following steps will guide you for the same.

●​ Login to Magento 2 admin.

●​ Click on the Codedecorator Extension menu

![image5](https://github.com/user-attachments/assets/98578a5a-2d04-4c59-8b71-90324384542e)

●​ Click on the Configuration

Clicking on configuration will redirect you to the customer discount setting
page where you can enable and disable the extension for the entire store.

![image4](https://github.com/user-attachments/assets/a61163b1-853f-423f-a93e-32a3537df5d8)

## 2.​ Global Configuration
●​ Allow the option to turn the extension on or off for the whole website.

●​ Ensure that customers must fill in the custom price and additional message fields
before proceeding.

●​ If a customer enters a price lower than the minimum set by the admin, display an
error message to notify them.

![image11](https://github.com/user-attachments/assets/b61e8859-e888-4c15-b807-3833022be775)

## 3.​ Enable Custom Price for a specific product
Our extension supports simple, virtual, and downloadable product types for
custom pricing. To set up custom pricing for a specific product, follow these steps:

●​ Go to the product where you want to allow custom pricing.

●​ Scroll down to the “Codedecorator Custom Price” tab on the product edit
page.
●​ Set the ‘Enable’ option to ‘Yes’.

●​ Enter the minimum price in the ‘Minimum Price’ field.

This will allow customers to enter custom prices for the product, ensuring they
meet the minimum price requirement.

![image7](https://github.com/user-attachments/assets/c767241d-681c-4cb3-ba61-5baca3e5cbf2)

## 4.​ Frontend View

Once after enabling and configuring the extension from global and product
settings, you will be able to see the custom price and additional message field at
product page.

![image1](https://github.com/user-attachments/assets/df1d514f-7456-4300-ba77-b792bd914a79)

## 5.​ Additional Message in Order
Our extension will show additional messages set by the customer to the customer
account and admin account.

![image6](https://github.com/user-attachments/assets/e7deaa9f-bf15-4daa-b35f-9ff79bbff874)

![image14](https://github.com/user-attachments/assets/4c1566f0-234c-4b5f-9e88-afaf2261c75e)

User Guide Information: While some screenshots in this guide may reflect older versions of the
interface, the core steps and fundamentals remain unchanged. If you encounter discrepancies
or need further clarification

## Download [Magento 2 Custom Price](https://codedecorator.com/magento-2-custom-price.html) Extension

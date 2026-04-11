# Salesforce-Mini-CPQ-Project
Designed and implemented product catalog, custom price books, opportunity product configuration, quote generation, built Flow for Applying Discount when Quote Line Item Quantity is more than 10 and approval workflows for discount governance using Salesforce Sales Cloud native quoting.
# Salesforce Product Quote Management Mini CPQ Project

## Project Overview
This project demonstrates a mini CPQ-style quote management solution built using Salesforce Sales Cloud native quoting features.

It simulates how sales teams:
- Manage product catalog
- Create price books
- Add products to opportunities
- Generate quotes
- Apply discount approvals

## Business Use Case
A company sells laptops and CRM software bundles. Sales reps need to generate customer quotes quickly while maintaining discount approval control.

## Features Implemented

### Product Management
- Product catalog creation
- Active product tracking

### Pricing Management
- Standard Price Book
- Custom Enterprise Sales Price Book

### Sales Process
- Account creation
- Opportunity creation
- Opportunity product association

### Quote Management
- Quote creation
- Quote syncing with opportunities
- PDF quote generation

### Approval Workflow
- Discount >20% requires manager approval

## Salesforce Components Used

- Products
- Price Books
- Opportunities
- Opportunity Products
- Quotes
- Quote Line Items
- Approval Process
- Validation Rules


## Project Architecture

Lead/Account → Opportunity → Products → Quote → Approval → PDF Proposal

## Sample Data Files Included

- products.csv
- standard_pricebook_entries.csv
- enterprise_sales_pricebook.csv
- accounts.csv
- opportunities.csv


## Screenshots Included

1. Product List
2. Price Book Setup
3. Opportunity Record
4. Opportunity Products
5. Quote Record
6. Quote Sync Screen
7. Approval Process Setup
8. Final Quote PDF

## Key Learning Outcomes

This project demonstrates:
- Salesforce Sales Cloud configuration
- CRM sales lifecycle design
- Native quote automation
- Mini CPQ business process implementation


Flow Automation
This automation applies a 10% discount when quantity exceeds 10 units.
<img width="1920" height="869" alt="Quote Line Item Quantity more than 10-V1" src="https://github.com/user-attachments/assets/0eb75679-6d6d-496f-90cb-4ba4495c1482" />


## Author
Moogambiga

Salesforce Consultant Portfolio Project

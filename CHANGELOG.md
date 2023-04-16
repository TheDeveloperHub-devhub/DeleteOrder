# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] = 18Dec December 2021
Allow the merchant to delete a single order as well as to delete orders in bulk.
Delete all the invoices from the deleted order.
Delete all transactions from the deleted order.
Delete the Credit Memo from the deleted order.
Delete the Shipment of the deleted order.
Automatically delete an invoice, shipments, credit memo, and other linked data along with deleted orders.

## [1.0.1] = 30th September 2022
- Updated code to make data types strict.
- Compatibility with Magento 2.4.5 and PHP 8.1.

## [1.0.2] = 23rd November 2022
- Fixed Shared Package issue.
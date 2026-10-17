# Cafe Data Hub

An end-to-end data engineering project to consolidate cafe sales, payment, and settlement data across multiple channels.

## Business Objective

Build a centralized pipeline to improve sales visibility and reconcile POS orders, food delivery platforms, digital payments, bank transactions, and cash collections.

## Data Sources

- POS: Orders, order items, and payments
- Swiggy: Orders, order items, and settlements
- Zomato: Orders, order items, and settlements
- UPI and card transactions
- Bank transactions
- Cash movements and daily closing
- Cross-channel order references

## Planned Architecture

1. Ingest raw CSV files.
2. Validate schemas and data quality.
3. Standardize source datasets.
4. Transform data into Bronze, Silver, and Gold layers.
5. Reconcile sales, settlements, and collections.
6. Prepare trusted datasets for analytics and reporting.

## Technology Stack

- Python
- SQL
- PySpark
- Delta Lake
- Databricks

## Repository Structure

- data/raw: Original synthetic source datasets
- data/sample: Small datasets for demonstrations
- notebooks: Exploration and development
- src: Ingestion, transformation, validation, and reconciliation code
- sql: SQL queries and transformations
- tests: Data quality and pipeline tests
- docs: Architecture and project documentation

## Project Status

Initial repository structure and synthetic source datasets prepared. Pipeline implementation is in progress.

## Data Disclaimer

The repository uses synthetic data for learning and portfolio demonstration. It does not represent real cafe customer or financial records.

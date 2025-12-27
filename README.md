# Supply-Chain-Analytics-Using-AI-Tools

## Overview
This project demonstrates an end-to-end data analytics pipeline built to analyze order fulfillment performance and revenue loss for a fictional retail company
The pipeline includes:
- Supabase (PostgreSQL) as the data warehouse
- n8n for automated ETL workflows
- Quadratic for Python-based transformations and analysis

## Project Architecture

Raw Order & Delivery Data on email
↓
n8n ETL Pipeline
↓
Supabase (PostgreSQL)
↓
Quadratic (Python Analytics)
↓
Interactive Business Insights

## Tech Stack
- PostgreSQL (Supabase)
- n8n
- Python (Pandas)
- Quadratic

## Folder Structure
- `supabase/` → schema & SQL
- `n8n/` → exported workflow
- `quadratic/` → Python transformations
- `data_samples/` → sample datasets

## Key Features
- USD → INR conversion
- OTIF analysis
- Clean star-schema joins
- Automated daily refresh via n8n

## How to Reproduce
1. Create Supabase project
2. Run SQL scripts in `supabase/`
3. Import n8n workflow
4. Load data into Quadratic
5. Run Python transformations
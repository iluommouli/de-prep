# de-prep

Data engineering interview preparation, plus a running capstone: an eCommerce
data platform built on the public Olist dataset, one layer per phase.

## Layout
- `sql/` – SQL practice solutions (PostgreSQL)
- `python/` – Python and DSA solutions
- `capstone/` – eCommerce data platform
- `data/` – local raw data, not committed

## Local setup
1. Copy `.env.example` to `.env` and set a password.
2. `docker compose up -d` starts PostgreSQL 18 on localhost:5432.

## Data
Brazilian E-Commerce Public Dataset by Olist (Kaggle), 2016–2018. Public data only.
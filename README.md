# From Grain to Grub — MTD Workbench

Sole trader tax management app for Danny Cook trading as From Grain to Grub. Tax year 2025/26.

Built on Node.js + Express + PostgreSQL.

## Setup

1. Create a PostgreSQL database: `createdb grain_to_grub_mtd`
2. Run `db/schema.sql` against it
3. Set `DATABASE_URL` environment variable
4. `npm install && npm start`

## Categories

Income: Sales, market/event income, wholesale, other
Expenses: Stock/ingredients, packaging, market stall fees, equipment, materials, travel, wages, premises, insurance, phone/admin, advertising, professional fees, bank charges, other

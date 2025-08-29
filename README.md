# OCA Financial Bank

This repository contains **15** OCA packages for financial bank.

## Packages Included (15 packages)

- **odoo-bringout-oca-bank-statement-import-account_statement_import_base** - From bank: statement_import_account_statement_import_base
- **odoo-bringout-oca-bank-statement-import-account_statement_import_camt** - From bank: statement_import_account_statement_import_camt
- **odoo-bringout-oca-bank-statement-import-account_statement_import_camt54** - From bank: statement_import_account_statement_import_camt54
- **odoo-bringout-oca-bank-statement-import-account_statement_import_file** - From bank: statement_import_account_statement_import_file
- **odoo-bringout-oca-bank-statement-import-account_statement_import_file_reconcile_oca** - From bank: statement_import_account_statement_import_file_reconcile_oca
- **odoo-bringout-oca-bank-statement-import-account_statement_import_ofx** - From bank: statement_import_account_statement_import_ofx
- **odoo-bringout-oca-bank-statement-import-account_statement_import_ofx_by_acctid** - From bank: statement_import_account_statement_import_ofx_by_acctid
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online** - From bank: statement_import_account_statement_import_online
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online_gocardless** - From bank: statement_import_account_statement_import_online_gocardless
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online_ofx** - From bank: statement_import_account_statement_import_online_ofx
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online_paypal** - From bank: statement_import_account_statement_import_online_paypal
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online_ponto** - From bank: statement_import_account_statement_import_online_ponto
- **odoo-bringout-oca-bank-statement-import-account_statement_import_online_qonto** - From bank: statement_import_account_statement_import_online_qonto
- **odoo-bringout-oca-bank-statement-import-account_statement_import_qif** - From bank: statement_import_account_statement_import_qif
- **odoo-bringout-oca-bank-statement-import-account_statement_import_sheet_file** - From bank: statement_import_account_statement_import_sheet_file


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-financial-bank/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-financial-bank/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-financial-bank/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-financial-bank/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.

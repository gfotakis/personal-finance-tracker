# Personal Finance Tracker

## What This Does
Automates downloading transaction data from Chase Bank via Plaid API and importing it into my personal Excel budget tracker.

## Technology Stack
- **Plaid API** - Secure bank connection (Transactions product only)
- **Python** - Data processing and automation scripts
- **macOS Keychain** - Secure credential storage
- **pandas + openpyxl** - Excel file manipulation

## Privacy & Security
- **Personal Use Only** - This app is used solely by me (Georg F.) for personal budget tracking
- **No Data Storage** - Transactions are fetched, categorized, and imported to a local Excel file. No data is stored on external servers or databases.
- **Secure Credentials** - Plaid API credentials are stored in macOS Keychain, never hardcoded or committed to version control
- **No Third-Party Sharing** - All data stays on my local machine. Nothing is shared with third parties or uploaded anywhere.
- **Minimal Data Access** - Only transaction history is accessed via Plaid. No account balances, identity info, or other sensitive data.

## How It Works
1. Script runs on schedule (cron job)
2. Connects to Plaid API with stored credentials
3. Fetches new transactions from Chase
4. Auto-categorizes based on my budget categories
5. Appends to my Excel budget tracker
6. No data leaves my computer

## Contact
For questions about this project: georg.fotakis@steelrelatedservices.com

---
*This is a personal hobby project for automating my own budget tracking. Not a commercial application.*

**Last Updated:** June 2026

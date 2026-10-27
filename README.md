# Invoice Generator

Personal invoice generator — for my own use.

## Features
- Auto-generates invoice number (format: INV/YEAR/MONTH/NNN)
- Saves your personal info, client info and default hourly rate in the browser (never in the repo)
- Import hours from a Toggl Track "Summary report" PDF (read locally in the browser, not uploaded)
- Per-project rates are remembered
- Auto-calculates due date based on payment terms
- Tax & discount support (% or fixed amount)
- Color themes
- Download as HTML or print to PDF

## Usage
1. Open [https://nrdl614.github.io/invoice-generator/](https://nrdl614.github.io/invoice-generator/)
2. Set your default rate once, then **Import Toggl PDF** (or add services manually)
3. Fill in the client, then download or print

## Note
Everything is blank on first load. Saved info lives only in the browser's localStorage.

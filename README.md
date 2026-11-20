# smd-app

Personal finance ledger for the command line: balances, spending and monthly reports from a CSV file.

For IE Masters Class Fifth Lab in Software Management and Development

## Run it

    uv run ledger import
    uv run ledger balance
    uv run ledger spending
    uv run ledger months
    uv run ledger add checking -12.50 restaurants "Lunch" --date 2026-03-31

## Roadmap

- Monthly report of income and spending
- A database instead of a CSV file
- A web API and a dashboard

## Author

paulhgeorge-creator

## Setup

Install [uv](https://docs.astral.sh/uv/), clone the repository, then run `uv run ledger balance`. uv creates the `.venv` for you.

## Use of AI

Labs 6 and 7 (Checkpoint 2): I used Claude Code (Anthropic) to write the code at the `TODO` spots and to run the lab steps and checks. The prompt was "do Labs 6 and 7 of ie-smd in my smd-app repo". I reviewed every change, and I checked the results myself: the `diff` checks, the SQL query and the error cases are listed in pull requests #2 and #3.

# Aloy · Partial approve payout — lo-fi prototype

Interactive low-fidelity prototype for **Partially Approve Balance** (seller payout requests).

- **Flow**: Approve / Hold / Rollback each take an amount (20% / 50% / 80% ratio chips or a custom amount). Released slices create a child payout with `parentId`; held slices stay frozen; rolled-back slices return to the seller balance.
- **Seller side**: Balance + payout detail showing requested / released / still-in-request, plus the push and email copy.
- **Data**: dummy rows and IDs only — no real seller data.

## Links

`?step=modal` · `?step=hold` · `?step=rollback` · `?step=confirm` · `?step=done` · `?view=seller` · `?spec=1`

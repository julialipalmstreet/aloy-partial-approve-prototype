# Aloy · Partial approve payout — lo-fi prototype

Interactive low-fidelity prototype for **Partially Approve Balance** (seller payout requests).

- **Flow**: Approve / Hold / Rollback each take an amount. Released slices create a child payout with `parentId`; held slices stay frozen; rolled-back slices return to the seller balance. No internal reason / note is captured — only the free-text message the seller reads.
- **Records**: every operation lands on a per-payout timeline (who, when, how much, the message that was sent, and the child payout it produced).
- **Seller side**: Balance + payout detail showing requested / released / still-in-request, plus the push and email copy.
- **Data**: dummy rows and IDs only — no real seller data.

## Links

`?step=modal` · `?step=hold` · `?step=rollback` · `?step=confirm` · `?step=done` · `?view=seller` · `?spec=1`

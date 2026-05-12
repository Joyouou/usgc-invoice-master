# usgc-invoice
LaTeX template used by U.S. Graphics Company. Licensed under BSD 3 clause license, see LICENSE.md. Credit to U.S. Graphics Company would be much appreciated :)

<img width="640" alt="screenshot-2025-09-17_19-38-40" src="https://github.com/user-attachments/assets/74e11f1d-00c7-48b5-b9ed-c9773220a910" />

## Procurement contract reference

Government procurement often requires tracing an invoice back to a contract, blanket purchase agreement, schedule, or other authorizing agreement. The templates include a dedicated procurement contract area so that reference is visible on the invoice instead of buried in old agreements or email threads.

In LaTeX, add it after the order metadata:

```tex
\procurementContract{GSA Schedule GS-35F-0119Y / BPA 20358238}
```

The Typst example includes the same field as a bordered callout below the order details.


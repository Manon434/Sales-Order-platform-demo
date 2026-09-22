# GreenPaper Sales Order Management — Demo v3

A clickable, showcase-ready Sales Order Management demo for a large paper company.

## Run
1. Extract the ZIP.
2. Open `index.html` in Chrome/Edge.
3. You can also run `run_demo.bat` and open `http://localhost:5173`.

## New changes
- Exactly 3 business profiles / approval levels:
  - Sales Manager — Stage 1
  - Production — Stage 2
  - Management — Stage 3
- Realistic login + signup flow. No account can log in until it has been signed up.
- User profile page with current role and member information.
- 30 customers, 40 enquiries, 35 quotations, 30 sales orders.
- More production jobs, quality checks, dispatches, deliveries and invoices.
- Production Control Board with stage-by-stage transparency.
- Production tracking drawer includes:
  - Current stage
  - Progress %
  - Planned / produced / pending quantity
  - Machine
  - Shift
  - Operator
  - Raw material status
  - Planned date
  - ETA
  - Current blocker
  - Stage timeline
  - Advance Stage action
- SAP remains mocked. Existing sample data includes:
  MANDT=100, VBELN=0000100000, ZNAME11=E0003, ACODE=E0003,
  USERNAME=SAB, ZDATE=2026-09-20, ZTIME=22:17:40, STATUS=A.
- Portal-created orders move through the 3 approvals and then simulate SAP creation.
- Data persists in browser localStorage for the demo.

## Important
This is a front-end demo, not a production ERP backend. Replace the mock SAP functions with the real SAP API when integration is ready.

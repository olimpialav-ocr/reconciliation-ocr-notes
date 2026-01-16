# reconciliation-ocr-notes

This repository documents the real problems of OCR in accounting workflows.

The goal is not fast extraction, but **correctness and trust**.

Focus areas:
- Line-item level OCR for invoices and receipts
- Totals vs line-sum reconciliation (handling rounding, VAT, OCR noise)
- Deterministic backend logic for financial correctness
- Confidence scoring and human-in-the-loop correction
- Duplicate document detection
- Systems designed for accountants, not generic document AI demos

Example problem:
OCR extracts a total of 100.00, but the sum of extracted line items is 99.99.
This project explores how a system should reconcile this **without breaking user trust**.

Looking to collaborate with engineers experienced in:
OCR, Document AI, backend systems, accounting workflows, and reconciliation logic.

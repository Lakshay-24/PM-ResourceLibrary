# VendorFlow — Zamp AI Solutions Analyst case study

A working vendor-onboarding workflow prototype built for the Zamp AI Solutions Analyst take-home.

## Problem
Vendor onboarding is usually fragmented across email, spreadsheets, finance, procurement and compliance. Missing evidence and duplicate payment details create back-and-forth; operators also need a defensible reason for each decision.

## Workflow
1. Normalize vendor identity and evidence.
2. Validate completeness and duplicate vendor/payment data.
3. Apply explainable risk and spend-threshold checks.
4. Straight-through approve clean vendors, route ambiguous cases to review, and stop material risk hits.
5. Persist reason codes and an audit trail.

## Where AI fits
In production, AI would extract fields from uploaded documents and summarize exceptions for operators. Policy gates remain deterministic and auditable.

## Metrics
Straight-through processing rate, median onboarding time, review backlog, override rate, resubmission rate and post-onboarding exceptions.

All data in the prototype is synthetic. The browser prototype requires no backend and can be run locally or deployed as static HTML.

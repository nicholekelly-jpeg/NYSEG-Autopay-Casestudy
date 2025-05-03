
# Case Study: NYSEG Dual AutoPay System – Customer Confusion and Operational Gaps

**Role**: Customer Service & Billing Support  
**Company**: NYSEG (New York State Electric & Gas)  
**Systems Involved**: SAP → CRMB (system transition), Internal Billing Tools

---

## Overview

While working in NYSEG's billing department, I discovered and regularly handled a recurring customer pain point caused by the coexistence of two separate "autopay" systems. This issue led to widespread confusion, double charges, and unnecessary call volume—all avoidable with clearer system design or communication.

---

## The Problem

NYSEG used SAP as its primary system before transitioning to CRMB. Despite the shift, **two autopay systems** continued to exist and function very differently:

### 1. AutoPay via Checking Account (SAP-Integrated)
- Directly integrated into the main billing system (SAP/CRMB).
- Smart logic: Automatically detects if a manual payment has been made.
- Will only deduct the **remaining balance**—never double-charging the customer.

### 2. Recurring Payments (Non-SAP/CRMB Linked)
- Set up separately, not fully integrated into the main billing system.
- **No awareness of manual payments**.
- Will still attempt to deduct the full previous bill—even if it was already paid—causing **double withdrawals**.

---

## Customer Impact

- **High confusion rate**: Customers don’t know they’ve enrolled in a system that functions differently from the standard.
- **Double payments**: Unexpected withdrawals after manually paying bills.
- **Increased support calls**: I personally handled numerous complaints requiring explanation and resolution.
- **Trust breakdown**: Many customers felt NYSEG's system was "broken" or "scammy" because of this issue.

---

## Suggested Solutions

1. **Unify the payment systems** under the main billing platform.  
2. **Display clear warnings** when setting up recurring payments outside the main system.  
3. **Educate customers proactively** via email or payment portal alerts.  
4. **Auto-disable conflicting payment methods** when one has already processed.

---

## Skills Demonstrated

- Root Cause Identification  
- Communicating Complex Systems to Non-Technical Customers  
- Process Improvement Suggestions  
- Handling High-Stress Support Scenarios  
- Documenting System Gaps for Engineering Feedback

---

## Why This Matters

While this case study is based on customer service experience, it demonstrates how frontline support can identify critical backend issues—an essential mindset for future Site Reliability Engineers and system designers. These are the kinds of small system flaws that, if left unaddressed, damage user trust and increase operational costs.

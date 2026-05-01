# ONDC:FIS12 2.3.0 — Overview

## Summary

ONDC:FIS12 establishes a unified protocol for banks and loan providers to offer credit products—business loans, credit lines, and loans against collateral—through a common marketplace. A borrower using any buyer app can search, discover terms, and apply for loans across multiple lenders without switching platforms.

## Sector & Purpose

**Sector:** Financial services and lending.

**Problem Solved:** Traditionally, a small business owner or individual seeking a loan must visit each bank's website separately, fill out distinct application forms, and wait for separate underwriting processes. This fragmentation makes comparison shopping difficult and slows credit access. ONDC:FIS12 creates a shared protocol so that loan products appear in a single marketplace—much like how ONDC unified e-commerce—allowing borrowers to discover and apply for multiple loan types in one buyer app, and enabling lenders to reach buyers without maintaining separate consumer channels.

## Real-World Actors

- **Buyers:** Small-business owners, entrepreneurs, and individuals seeking working capital or other credit
- **Loan Providers:** Banks, non-bank financial institutions (NBFCs), and specialized loan servicers
- **Platform:** Buyer apps (powered by BAPs) that aggregate loan offers in real time

## Use Cases

- **Unified Credit Discovery:** A borrower opens a buyer app and searches for "business loan" or "loan against mutual funds" to see available offers and terms from multiple lenders
- **Business Term Loans:** Fixed-duration loans for business operations, available with data validation (GST history, Account Aggregator consent) or offline underwriting workflows
- **Loan Against Mutual Funds (LAMF):** Borrowers pledge mutual fund holdings as collateral to unlock credit lines, with optional integration via fund platforms (RTA/MFC channels) or offline journeys
- **Term Comparison:** Buyers compare loan amounts, interest rates, tenure, and eligibility criteria before applying

## Key Concepts

- **Loan:** A credit product offered by a financial institution, with defined terms (amount, rate, tenure) and eligibility criteria
- **Business Loan:** Credit extended to self-employed individuals or enterprises, often validated through business financials (GST data, PAN, bank statements)
- **LAMF (Loan Against Mutual Funds):** A secured lending product where the borrower pledges mutual fund units as collateral and draws credit at a negotiated rate
- **Account Aggregator (AA):** A consent-based data bridge enabling borrowers to share bank, tax, and investment data with lenders for faster underwriting
- **Credit Line:** Revolving credit with a pre-approved limit, drawn as needed (distinct from a one-time term loan)

## Example Scenario

**Scenario 1: Business Loan via Buyer App**

Priya, a textile manufacturer, opens her buyer app and searches for a business loan. The app queries multiple banks and NBFCs simultaneously. She sees offers from three lenders: ₹50 lakh at 9.5% (18 months) from Bank A, ₹75 lakh at 11% (24 months) from Bank B. She taps Bank A's offer, consents to GST data sharing via Account Aggregator, and completes a soft application in 10 minutes. The lender auto-verifies her GST returns and sends a pre-approval in 2 hours.

**Scenario 2: Loan Against Mutual Funds**

Rajesh holds ₹20 lakh in mutual funds. He needs ₹5 lakh for equipment but doesn't want to liquidate his investments. Through the buyer app, he discovers LAMF offers from two lenders. He pledges ₹10 lakh of his fund units, gets approved for a ₹4 lakh credit line at 8.5%, and draws ₹5 lakh immediately—all without selling his shares. The lender integrates directly with his fund's registry (RTA) to hold the pledge.

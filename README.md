# 🚀 Awesome-Account-Reconciliation-Platforms

## 🌟 Top Account Reconciliation Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects  
Focused on **Account Reconciliation, Transaction Matching, Bank Reconciliation, Balance-Sheet Reconciliation, Financial Close, Exception Management & Accounting Automation**

**Last updated: August 2026**

This repository tracks notable **SaaS/Hosted Platforms** and **Open-Source Projects** for Account Reconciliation.

Account reconciliation platforms help finance and accounting teams reconcile balance-sheet accounts, bank accounts, subledgers, payments, intercompany balances and other financial data sources; automate matching; identify exceptions; maintain audit trails; and accelerate the financial close.

**Examples** include BlackLine, Trintech, AutoRek, ReconArt, FloQast, OneStream, Cadency, Fiserv Frontier, Duco and SmartStream.

> **Open-source emphasis:** There are considerably fewer mature open-source equivalents to enterprise platforms such as BlackLine, Cadency and SmartStream than there are commercial products. Therefore, the Open-Source section includes both dedicated reconciliation engines and open-source accounting, ledger, bank-reconciliation, record-linkage and transaction-matching projects that can be combined into a self-hosted reconciliation stack.

---

## 📋 Table of Contents

- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🧩 Open-Source Accounting & Reconciliation Platforms](#-open-source-accounting--reconciliation-platforms)
- [🔧 Open-Source Matching & Reconciliation Engines](#-open-source-matching--reconciliation-engines)
- [📊 Open-Source Financial Infrastructure](#-open-source-financial-infrastructure)
- [🏗️ Building an Open-Source Reconciliation Stack](#️-building-an-open-source-reconciliation-stack)
- [🔍 Commercial vs Open-Source](#-commercial-vs-open-source)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)

---

# ☁️ SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits |
|---|---|---|---|
| **Numeric** | AI-powered financial close and auto-reconciliation platform for modern accounting teams. | Essentials tier starts at **$30/user/month** (billed annually; Growth/Enterprise tiers for live ERP integrations & auto-rec) | No free tier or self-serve trial; live custom product demo and workflow scoping available upon request |
| **ReconArt** | Total reconciliation lifecycle platform covering transaction matching, account certification, variance analysis, and close management. | Essentials edition starts at **~$300/month** (billed annually; includes up to 25 million transactions/year) | No free-forever plan or self-serve trial; tailored interactive sandbox demo with sample data provided upon request |
| **FloQast** | Accounting workflow automation platform for balance sheet reconciliation, transaction matching, and close checklists. | Entry-level plans start at **~$12,000/year** (~$1,000/month billed annually for small finance teams) | No free-forever plan or trial for the core SaaS; FloQademy platform offers free CPE/CPD training courses with unlimited access |
| **FloQast Reconciliation Management** | Dedicated FloQast module providing automated balance-sheet substantiation and tie-outs directly linked to ERP trial balances. | Included in FloQast packages starting at **~$12,000/year** (or ~$5,000/year as an add-on module) | No free tier or trial period; personalized 1-on-1 walkthrough demo available on request |
| **BlackLine** | Enterprise financial close platform automating balance-sheet reconciliation, intercompany transactions, and journal entries. | Modular deployments start at **~$13,000 to $40,000/year** (mid-market entry; median contracts $40k–$77k/year) | No free tier or self-serve trial; guided interactive demos and ROI assessment available upon request |
| **BlackLine Account Reconciliations** | Core BlackLine module standardizing and automating balance-sheet account reconciliations and review workflows. | Subscriptions start at **~$13,000/year** (based on user tier, entity volume, and ERP connections) | No free tier or self-serve trial; sales-assisted evaluation demo available upon request |
| **BlackLine Transaction Matching** | High-volume reconciliation engine designed to match millions of bank, PSP, POS, and ERP transactions automatically. | Starts at **~$20,000/year** (scaled by transaction ingestion volume and rule complexity) | No free tier or self-serve trial; custom proof-of-concept demo with company data upon request |
| **Trintech** | Comprehensive financial-close and reconciliation automation platform through the Adra and Cadency product lines. | Adra mid-market close packages start at **~$40,000/year**; enterprise Cadency packages start higher | No free tier or standard trial; scheduled product discovery and guided demo sessions on request |
| **Trintech Adra (Adra Suite)** | Mid-market financial-close suite providing automated balance sheet reconciliation, transaction matching, and task governance. | Entry deployments start at **~$40,000/year** (typically $40k–$70k/year based on entity count) | No free tier or self-serve trial; customized live product walkthrough provided upon request |
| **Adra Matcher** | Automated transaction-matching module within Trintech Adra for reconciling bank accounts, credit cards, and ledger records. | Module packages start at **~$15,000/year** (as part of Adra suite deployment) | No free tier or trial; guided interactive demo available upon request |
| **Adra Balancer** | Digital balance-sheet reconciliation and certification module in the Trintech Adra suite. | Module packages start at **~$15,000/year** (as part of Adra suite deployment) | No free tier or trial; live guided walkthrough and scoping demo on request |
| **Cadency (by Trintech)** | Enterprise-grade financial close and reconciliation platform for complex, multi-national organizations. | Enterprise contracts start at **~$75,000/year** (scaled by entity count, ERP connections, and modules) | No free tier or self-serve trial; dedicated enterprise proof-of-concept and guided demo on request |
| **Trintech CadencyDirect** | ServiceNow-native financial close and reconciliation solution embedding Cadency capabilities into enterprise workflows. | Starts at **~$80,000/year** (plus ServiceNow licensing requirements) | No free tier or self-serve trial; ServiceNow partner-assisted live demonstration on request |
| **AutoRek** | Financial data management, payment reconciliation, and regulatory compliance platform for banks and asset managers. | Deployments start at **~$45,000/year** (scaled by data volume, feeds, and regulatory modules) | No free tier or self-serve trial; consultative proof-of-value demo available on request |
| **OneStream** | Unified Corporate Performance Management (CPM) platform with financial close, consolidation, and reconciliation modules. | Deployments start at **~$50,000 to $60,000/year** (scaled by user licenses, legal entities, and CPM apps) | No free tier or self-serve trial; custom solution demo and value assessment on request |
| **OneStream Account Reconciliations** | Native OneStream MarketPlace solution integrating balance-sheet reconciliations directly into the financial consolidation model. | Available within OneStream CPM platform subscriptions (starting at **~$50,000/year**) | No free tier or self-serve trial; custom architecture walkthrough and live demo on request |
| **Duco** | Cloud-native data automation and reconciliation platform for high-volume matching across complex financial datasets. | AWS Marketplace starter tiers start at **~$52,000/year** (average enterprise contract ~$183,000/year) | No free tier or self-serve trial; AWS Marketplace scoped sandbox pack available for evaluation |
| **SolveXia** | Low-code financial process automation platform for multi-source data matching, reconciliations, and regulatory reports. | Starter plans start at **~$18,000/year** (~$1,500/month billed annually) | No free tier or self-serve trial; custom guided proof-of-concept demo available upon request |
| **HighRadius Account Reconciliation** | Autonomous financial close software providing AI-driven transaction matching, balance substantiation, and journal creation. | Starts at **~$25,000/year** (available under annual SaaS subscription or outcome-based model) | No free tier or self-serve trial; outcome-based pricing model available ($0 software cost until go-live) |
| **Fiserv Frontier Reconciliation** | High-throughput banking, cash, and payment reconciliation system designed for large financial institutions. | Enterprise institutional contracts start at **~$100,000/year** (plus integration and implementation fees) | No free tier or self-serve trial; institutional consultation and technical demo available upon request |
| **SmartStream TLM Reconciliation** | Transaction Lifecycle Management platform for high-volume cash, trade, securities, and inter-system matching. | Enterprise institutional contracts start at **~$150,000/year** (scaled by transaction volume and modules) | No free tier or self-serve trial; institutional proof-of-concept and customized demo on request |

---

# 💻 Open-Source GitHub Projects

## 🥇 Dedicated Reconciliation Engines

### [Settler](https://github.com/Settler/settler)

Open-source reconciliation infrastructure designed to match financial records across banks, Stripe, ERPs and ledgers.

Key capabilities include:

- Deterministic reconciliation
- Configurable matching rules
- Multi-source joins
- Field-level tolerances
- Mismatch detection
- Evidence generation
- Reconciliation runs
- CLI
- TypeScript SDK
- Self-hosting
- Audit-oriented evidence

Settler is one of the most directly relevant modern open-source projects for building a BlackLine/Duco-style reconciliation engine. The project describes its core, CLI, SDK and evidence model as Apache 2.0 licensed. 

---

### [Lerian Matcher](https://github.com/LerianStudio/matcher)

Open-source transaction-reconciliation engine designed for financial systems.

Useful capabilities include:

- Transaction matching
- Configurable matching rules
- Confidence scoring
- Multi-source reconciliation
- Exception handling
- Financial transaction processing
- API-oriented architecture

A particularly interesting project for developers building a programmable reconciliation service.

---

### [OpenRec](https://github.com/openrec)

Open-source reconciliation-engine concept focused on high-throughput financial-data matching.

Useful for:

- Large CSV datasets
- Rule-based matching
- High-volume reconciliation
- Automated comparison
- Exception generation

---

### [Pavit Bank Reconciliation](https://github.com/pavitsu/pavit-bank-reconciliation)

Open-source Python bank-reconciliation application that matches bank statements against accounting ledgers.

Capabilities include:

- Bank CSV import
- Ledger CSV import
- Amount matching
- Date matching
- Description/reference matching
- Balance comparison
- GUI
- Automated reconciliation

The project is MIT licensed and explicitly targets matching accounting records against bank-statement information. 

---

### [Reconcile Engine](https://github.com/nanyanen87/reconcile-engine)

Dependency-free TypeScript reconciliation engine for comparing bank/card ledgers against vouchers.

Provides concepts such as:

- Matches
- Gaps
- Review items
- Timing differences
- Confidence
- Provenance
- Deterministic reconciliation

Useful as a lightweight foundation for custom reconciliation applications.

---

### [Multi-Processor Payment Reconciliation](https://github.com/Etherlabs-dev/multi-processor-reconciliation)

Open-source n8n + PostgreSQL reconciliation workflow for Stripe, PayPal, Square and ACH/bank deposits.

Includes:

- Transaction normalization
- Unified ledger
- Intelligent matching
- Fee reconciliation
- Refund handling
- Split-payment matching
- Currency conversion
- Discrepancy detection
- Exception queues
- Optional QuickBooks synchronization

Particularly useful as a reference implementation for payment-reconciliation pipelines.

---

### [Agent for Accounting](https://github.com/FoundrySoftHQ/agent-for-accounting)

Open-source accounting copilot with a dedicated reconciliation workflow.

The reconciliation engine compares bank and ledger CSV files and classifies:

- Matched records
- Timing differences
- Amount differences
- Potential splits
- Unmatched bank records
- Unmatched ledger records

It emphasizes deterministic matching and explicit human-review categories rather than silently force-matching uncertain transactions. 

---

# 🧩 Open-Source Accounting & Reconciliation Platforms

### [ERPNext](https://github.com/frappe/erpnext)

Open-source ERP platform with extensive accounting functionality.

Relevant capabilities include:

- General ledger
- Accounts receivable
- Accounts payable
- Bank transactions
- Bank reconciliation
- Payment reconciliation
- Multi-currency accounting
- Financial statements
- Journal entries
- Audit trails

One of the strongest open-source foundations for building a broader accounting and reconciliation platform.

---

### [Odoo Community](https://github.com/odoo/odoo)

Open-source ERP platform with extensive accounting functionality.

When combined with OCA accounting modules, it can provide:

- Bank reconciliation
- Account reconciliation
- Payment matching
- Statement processing
- Journal management
- Financial reporting
- Automated matching

---

### [OCA Account Reconcile](https://github.com/OCA/account-reconcile)

Open-source Odoo Community Association modules specifically focused on reconciliation.

Includes functionality around:

- Bank reconciliation
- Mass reconciliation
- Reconciliation models
- Reconciliation wizards
- Matching rules
- Payment reconciliation

This is one of the most relevant open-source module collections for extending Odoo into a reconciliation platform.

---

### [Open Accounting](https://github.com/HMB-research/open-accounting)

Open-source, self-hosted accounting platform with double-entry bookkeeping, bank importing and reconciliation workflows.

The project currently describes itself as being under active development and not yet production-ready, so it is best treated as an emerging foundation rather than a mature enterprise replacement. 

---

### [LedgerSMB](https://github.com/ledgersmb/LedgerSMB)

Open-source accounting and ERP system supporting:

- Double-entry accounting
- General ledger
- Accounts payable
- Accounts receivable
- Multi-currency accounting
- Financial reporting
- Banking workflows

Useful as a foundation for custom reconciliation systems.

---

### [GnuCash](https://github.com/Gnucash/gnucash)

Mature open-source accounting application supporting:

- Double-entry bookkeeping
- Account management
- Bank transaction import
- Reconciliation
- Financial reporting

Better suited to small-business and personal-finance scenarios than enterprise financial-close automation.

---

### [Frappe Books](https://github.com/frappe/books)

Open-source accounting application built around the Frappe ecosystem.

Provides:

- Double-entry bookkeeping
- Invoicing
- Payments
- Expenses
- Financial reports
- Accounting workflows

Can be extended with custom reconciliation functionality.

---

### [Akaunting](https://github.com/akaunting/akaunting)

Open-source accounting platform for small businesses.

Relevant capabilities include:

- Banking
- Transactions
- Invoicing
- Expenses
- Accounting
- Financial reporting

---

### [Firefly III](https://github.com/firefly-iii/firefly-iii)

Open-source personal-finance manager with:

- Transaction management
- Account management
- Rule-based imports
- Financial categorization
- Reporting
- Reconciliation-oriented workflows

More appropriate for personal/small-scale financial management than enterprise financial close.

---

### [Beancount](https://github.com/beancount/beancount)

Programmable plain-text double-entry accounting system.

Particularly useful for developer-oriented financial reconciliation because financial records are represented as structured text and can be processed programmatically.

---

### [Fava](https://github.com/beancount/fava)

Web interface for Beancount providing financial reporting and transaction-management capabilities.

Useful when combined with Beancount import and reconciliation tooling.

---

# 🔧 Open-Source Matching & Reconciliation Engines

### [beancount-import](https://github.com/jbms/beancount-import)

Semi-automated transaction-import and reconciliation framework for Beancount.

Useful for:

- Importing bank data
- Transaction matching
- Duplicate detection
- Transaction merging
- Classification
- Reconciliation

---

### [Splink](https://github.com/moj-analytical-services/splink)

Open-source probabilistic record-linkage framework.

Although not specifically an accounting product, it can be used to match:

- Bank transactions
- Payments
- Invoices
- Customer records
- Merchant names
- Financial records

Particularly valuable when exact identifiers are unavailable.

---

### [Dedupe](https://github.com/dedupeio/dedupe)

Open-source Python library for fuzzy matching and entity resolution.

Useful for reconciliation scenarios involving:

- Merchant-name variations
- Customer-name differences
- Invoice references
- Payment descriptions
- Cross-system record matching

---

### [RapidFuzz](https://github.com/rapidfuzz/RapidFuzz)

High-performance fuzzy-string-matching library.

Useful as a low-level matching component for:

- Merchant matching
- Invoice matching
- Reference matching
- Description normalization
- Bank-to-ledger reconciliation

---

### [Record Linkage Toolkit](https://github.com/J535D165/recordlinkage)

Python framework for record linkage and entity matching.

Supports:

- Fuzzy matching
- Deduplication
- Probabilistic matching
- Feature generation
- Record comparison

Can be integrated into custom reconciliation pipelines.

---

### [Pixelmatch](https://github.com/mapbox/pixelmatch)

While primarily an image-comparison library, the project demonstrates the type of deterministic comparison primitive that can also be conceptually applied to structured-data comparison systems.

---

# 📊 Open-Source Financial Infrastructure

### [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle)

Open-source financial-accounting database designed for high-performance financial transactions.

Useful as a ledger infrastructure component underneath reconciliation systems.

---

### [Medici](https://github.com/flash-oss/medici)

Node.js double-entry accounting library.

Can provide an accounting-ledger layer for custom reconciliation applications.

---

### [hledger](https://github.com/simonmichael/hledger)

Open-source command-line accounting system based on plain-text double-entry bookkeeping.

Useful for:

- Transaction processing
- Accounting
- Financial imports
- Reconciliation
- Automated reporting

---

### [Ledger](https://github.com/ledger/ledger)

Open-source double-entry accounting system using plain-text financial records.

Useful as a programmable accounting ledger underneath custom reconciliation pipelines.

---

### [jPOS](https://github.com/jpos/jPOS)

Open-source Java payment-processing framework supporting ISO-8583 and financial transaction infrastructure.

Not an account-reconciliation product itself, but potentially useful for payment-processing and transaction-processing infrastructure around a reconciliation system.

---

# 🏗️ Building an Open-Source Reconciliation Stack

A serious open-source alternative to a commercial account-reconciliation platform will generally require several components rather than a single application.

```text
                    ┌────────────────────────┐
                    │      DATA SOURCES      │
                    │                        │
                    │ ERP / GL / Bank        │
                    │ PSP / Cards / ACH      │
                    │ Subledgers / CSV / API │
                    └────────────┬───────────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │    DATA INGESTION      │
                    │                        │
                    │ APIs / SFTP / CSV      │
                    │ ETL / CDC / Webhooks   │
                    └────────────┬───────────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │    NORMALIZATION       │
                    │                        │
                    │ Currency               │
                    │ Dates                  │
                    │ References             │
                    │ Merchant Names         │
                    │ Transaction Types      │
                    └────────────┬───────────┘
                                 │
                                 ▼
              ┌─────────────────────────────────────┐
              │          MATCHING ENGINE            │
              │                                     │
              │ Exact Match                         │
              │ Rule-Based Match                    │
              │ Tolerance Match                     │
              │ Fuzzy Match                         │
              │ One-to-Many                         │
              │ Many-to-One                         │
              │ Many-to-Many                        │
              │ Probabilistic Match                 │
              └──────────────────┬──────────────────┘
                                 │
                    ┌────────────┴─────────────┐
                    │                          │
                    ▼                          ▼
          ┌──────────────────┐       ┌──────────────────┐
          │     MATCHED      │       │    EXCEPTIONS    │
          │                  │       │                  │
          │ Auto-cleared     │       │ Unmatched        │
          │ Auto-certified   │       │ Amount mismatch  │
          │ High confidence  │       │ Timing difference│
          └────────┬─────────┘       │ Duplicate        │
                   │                 │ Review required  │
                   │                 └────────┬─────────┘
                   │                          │
                   └────────────┬─────────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │  RECONCILIATION CASE   │
                    │                        │
                    │ Evidence               │
                    │ Comments               │
                    │ Approvals              │
                    │ Audit Trail            │
                    │ Status                 │
                    └────────────┬───────────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │    FINANCIAL CLOSE     │
                    │                        │
                    │ Certification          │
                    │ Reporting              │
                    │ Controls               │
                    │ Management Review      │
                    └────────────────────────┘
```

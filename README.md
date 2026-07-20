# Test add

*description of the project*

**Timeframe** 2026-07-06 - 2026-10-12

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-add-2026](https://cra-test-arc.canada.ca/test-add-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-07-20

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Income tax)
    node5(Personal income tax)
    node6(Claiming deductions, credits, and expenses)
    node7(All deductions, credits and expenses - Personal income tax)
    node8(Canada workers benefit #40;CWB#41; – Personal income tax)
    node9(Payroll)
    node10(GST/HST for businesses)
    node11(Business registration with the CRA)
    node12(Charities and giving)
    node13(Savings and pension plans)
    node14(Excise and specialty taxes)
    node1 --> node2
    node2 --> node3
    node2 --> node4
    node4 --> node5
    node5 --> node6
    node6 --> node7
    node7 --> node8
    node2 --> node9
    node9 --> node10
    node2 --> node11
    node2 --> node12
    node2 --> node13
    node2 --> node14

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node2,node3,node4,node8,node9,node10,node11,node12,node13,node14 inscope
    classDef ismoved fill:#eab308,color:#000
    class node10 ismoved
```

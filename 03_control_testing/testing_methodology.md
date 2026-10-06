# Control Testing Methodology

## 1. Purpose

This document defines the methodology used to evaluate the operating effectiveness of key controls within the Procure-to-Pay (P2P) process.

The objective is to determine whether identified controls operated consistently during the selected assessment period and whether sufficient evidence exists to support the control conclusion.

---

## 2. Testing Approach

Control testing follows four main stages:

**Define → Select → Test → Conclude**

### 1. Define

Identify the control objective, control owner, control frequency, and expected control evidence.

### 2. Select

Select a representative sample of transactions, users, vendors, payment batches, or control reports depending on the nature of the control.

### 3. Test

Inspect available evidence and determine whether the control operated according to its defined requirements.

### 4. Conclude

Evaluate the results and classify the control as:

- Effective
- Partially Effective
- Ineffective

---

## 3. Testing Procedures

Testing procedures may include:

### Inspection

Review documents, system records, approvals, reports, and supporting evidence.

### Reperformance

Independently perform or recalculate the control activity where appropriate.

### Inquiry

Discuss the control process with responsible personnel to understand how the control operates.

### Observation

Observe the execution of a control activity where direct observation provides relevant evidence.

---

## 4. Sample Selection

Samples are selected based on the nature and frequency of the control and the level of risk associated with the process.

Examples include:

| Control Area | Example Sample |
|---|---:|
| Purchase Requisitions | 12 |
| Purchase Orders | 12 |
| New Vendors | 10 |
| Bank Detail Changes | 8 |
| Supplier Invoices | 15 |
| Payment Batches | 10 |
| Monthly Control Reports | 3 |

The sample sizes used in this fictional case study are designed for demonstration purposes and do not represent a formal statistical sampling methodology.

---

## 5. Test Result Classification

### Effective

The control operated as designed and no significant exceptions were identified within the selected sample.

### Partially Effective

The control generally operated as designed, but one or more exceptions were identified that indicate a weakness requiring management attention.

### Ineffective

The control did not operate consistently or significant exceptions indicate that the control is not adequately mitigating the relevant risk.

---

## 6. Exception Evaluation

Exceptions are evaluated based on:

- Nature of the exception
- Frequency
- Potential financial impact
- Fraud exposure
- Control significance
- Root cause
- Whether the exception is isolated or recurring
- Whether compensating controls exist

---

## 7. Evidence Requirements

Control conclusions should be supported by sufficient and appropriate evidence.

Examples include:

- Approved purchase requisitions
- Purchase orders
- Goods receipt records
- Supplier invoices
- Approval logs
- Vendor master records
- System access reports
- Payment approval records
- Exception reports
- Management review evidence

---

## 8. Control Testing Principle

A control should not be considered effective simply because a procedure exists.

The assessment considers both:

**Control Design**

and

**Operating Effectiveness**

A well-designed control that is not consistently performed may still result in a significant control weakness.

---

## 9. Link to Testing Results

The detailed test results are documented in:

`03_control_testing/control_testing.csv`

Testing results are subsequently evaluated to determine whether a control weakness should be raised as an audit finding.

The assessment flow is:

**Risk → Control → Test → Exception → Finding → Recommendation**

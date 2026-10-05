# Internal Control Assessment & Improvement Framework

> A practical, risk-based assessment of the Procure-to-Pay (P2P) process, connecting business processes, risks, controls, testing, findings, and remediation.

## Executive Summary

This project presents a practical internal control assessment of the Procure-to-Pay (P2P) process for a fictional mid-sized trading and distribution company.

The assessment evaluates whether key controls are appropriately designed and operating effectively to mitigate risks related to:

- Unauthorized purchasing
- Fictitious or unauthorized suppliers
- Inaccurate or duplicate payments
- Segregation of duties
- Inappropriate system access
- Weak approval workflows
- Incomplete management follow-up

The assessment follows a structured internal audit approach:

**Process → Risk → Control → Testing → Finding → Root Cause → Recommendation → Remediation**

The project identified several control weaknesses, particularly around vendor master approval, segregation of duties, user access, procurement authorization, and exception monitoring.

---

## Business Scenario

The fictional company operates through multiple regional branches and maintains approximately 180 active suppliers.

The assessment focuses on the Procure-to-Pay cycle:

**Purchase Requisition → Approval → Purchase Order → Receipt → Invoice → Three-Way Match → Payment Approval → Supplier Payment**

The objective is not simply to identify transaction errors, but to understand where risk enters the process and whether the control environment can prevent or detect those risks.

---

## Assessment Objectives

The assessment evaluates whether:

- Purchases are properly authorized.
- Purchase orders are supported by approved requisitions.
- Supplier creation is appropriately controlled.
- Supplier bank-detail changes are independently verified.
- Goods and services are confirmed before payment.
- Supplier invoices are accurately matched.
- Payments are properly authorized.
- Segregation of duties is maintained.
- System access is aligned with job responsibilities.
- Control exceptions are identified and followed up.

---

## Scope

### In Scope

- Procurement
- Purchase requisitions
- Purchase orders
- Vendor master data
- Goods and service receipt
- Accounts Payable
- Invoice processing
- Payment authorization
- User access
- Segregation of duties
- Management monitoring

### Out of Scope

- Payroll
- Sales
- Inventory valuation
- Tax compliance
- Treasury investments

---

## Methodology

The assessment follows a risk-based internal control methodology:

### 1. Process Understanding

Document the key activities, responsibilities, systems, and control points.

### 2. Risk Identification

Identify financial, operational, fraud, compliance, and reporting risks.

### 3. Control Mapping

Map each significant risk to the control designed to prevent or detect it.

### 4. Control Design Assessment

Evaluate whether the control is appropriately designed to address the identified risk.

### 5. Operating Effectiveness Testing

Perform sample-based testing to determine whether controls operated consistently.

### 6. Exception Analysis

Evaluate exceptions based on frequency, impact, root cause, and potential exposure.

### 7. Finding Development

Document findings using:

**Condition → Criteria → Risk / Impact → Root Cause → Recommendation**

### 8. Remediation Planning

Translate findings into practical corrective actions with owners, priorities, target dates, and measurable outcomes.

---

## Control Assessment Summary

| Control Area | Assessment |
|---|---|
| Purchase Authorization | Partially Effective |
| Vendor Master Controls | Ineffective |
| Goods Receipt Controls | Effective |
| Invoice Matching | Partially Effective |
| Payment Authorization | Effective |
| Segregation of Duties | Ineffective |
| User Access Management | Ineffective |
| Management Monitoring | Partially Effective |

### Overall Conclusion

The assessment identified a foundational control environment with several areas requiring improvement.

The highest-priority weaknesses relate to:

1. Vendor master approval
2. Segregation of duties
3. User access
4. Procurement authorization
5. Exception monitoring

These weaknesses may increase exposure to unauthorized transactions, fraud, inaccurate payments, and insufficient management oversight.

---

## Key Findings

### Finding 01 — Weak Vendor Master Approval

**Risk Rating: High**

3 out of 10 sampled new vendors lacked documented evidence of independent Finance approval.

**Key Risk:** Increased exposure to fictitious suppliers, unauthorized transactions, and inappropriate payments.

**Root Cause:** Vendor creation and approval responsibilities are not sufficiently segregated.

---

### Finding 02 — Incompatible User Access

**Risk Rating: High**

2 users were identified with combinations of procurement and Accounts Payable permissions that could create incompatible duties.

**Key Risk:** An individual may be able to initiate and process transactions without sufficient independent review.

**Root Cause:** User provisioning is not consistently mapped to a formal segregation-of-duties matrix.

---

### Finding 03 — Purchase Order Issued Before Requisition Approval

**Risk Rating: Medium**

1 of 12 sampled purchase orders was issued before documented approval of the related requisition.

**Key Risk:** The company may enter into financial commitments without appropriate authorization.

**Root Cause:** The procurement workflow permits PO creation before approval evidence is fully confirmed.

---

### Finding 04 — Three-Way Match Exceptions

**Risk Rating: Medium**

2 of 15 sampled invoices contained unresolved quantity differences between the purchase order, receipt, and supplier invoice.

**Key Risk:** Potential overpayments, incorrect liabilities, supplier disputes, and financial reporting errors.

**Root Cause:** Tolerance thresholds and exception-escalation procedures are not consistently documented.

---

### Finding 05 — Incomplete Exception Follow-Up

**Risk Rating: Medium**

1 of 3 monthly control reports lacked documented follow-up for overdue exceptions.

**Key Risk:** Control weaknesses may remain unresolved and recur.

**Root Cause:** Ownership and escalation responsibilities are not clearly defined.

---

## Recommendations

The recommended actions focus on strengthening the control environment while remaining practical and measurable.

### 1. Strengthen Vendor Master Controls

- Separate vendor creation from approval.
- Require supporting documentation.
- Implement independent Finance approval.
- Maintain an electronic audit trail.
- Perform periodic vendor-master reviews.

### 2. Establish a Segregation-of-Duties Matrix

Define incompatible responsibilities across:

- Procurement
- Vendor creation
- Goods receipt
- Accounts Payable
- Payment preparation
- Payment approval

### 3. Strengthen Procurement Workflow

Require an approved purchase requisition before a purchase order can be created.

### 4. Improve Invoice Exception Management

Implement:

- Automated three-way matching
- Defined tolerance thresholds
- Exception workflows
- Documented resolution
- Payment blocking for unresolved material exceptions

### 5. Strengthen User Access Management

Implement:

- Role-based access
- Formal access approval
- Quarterly access reviews
- Segregation-of-duties conflict monitoring

### 6. Improve Management Monitoring

Every significant exception should have:

**Owner → Due Date → Status → Root Cause → Corrective Action → Closure Evidence**

---

## Expected Business Impact

Successful implementation should improve:

### Financial Protection

Reduce the risk of unauthorized, duplicate, or inaccurate payments.

### Fraud Prevention

Increase barriers against fictitious suppliers and inappropriate transactions.

### Process Efficiency

Reduce recurring exceptions and manual investigation.

### Governance

Create clearer accountability for control ownership and remediation.

### Auditability

Improve the availability and quality of supporting evidence.

### Management Visibility

Provide measurable indicators of control performance.

### Risk Management

Move from reactive issue identification toward proactive risk monitoring.

---

## Monitoring KPIs

| KPI | Target |
|---|---:|
| Vendors independently approved | 100% |
| POs supported by approved requisitions | 100% |
| Invoices passing three-way match | ≥ 98% |
| Unresolved high-risk exceptions | 0 |
| Unresolved SoD conflicts | 0 |
| Quarterly access review completion | 100% |
| Overdue remediation actions | 0 |

---

## Repository Structure

```text
internal-control-assessment/
│
├── README.md
│
├── 01_process_documentation/
│   └── process_overview.md
│
├── 02_risk_assessment/
│   └── risk_control_matrix.csv
│
├── 03_control_testing/
│   └── control_testing.csv
│
├── 04_findings/
│   └── internal_control_findings.md
│
└── 05_recommendations/
    └── improvement_plan.md

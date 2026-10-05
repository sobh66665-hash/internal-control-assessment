# Internal Control Findings

## Finding 01 — Weak Vendor Master Approval

**Finding ID:** IC-01
**Risk Rating:** High
**Related Control:** C-03

### Condition

Three out of ten sampled new vendors did not have documented evidence of independent Finance approval.

### Criteria

New supplier records should be supported by appropriate documentation and independently approved before becoming active in the vendor master.

### Risk / Impact

Weak vendor master controls may increase the risk of:

* Fictitious suppliers
* Unauthorized purchases
* Payments to inappropriate beneficiaries
* Fraudulent transactions
* Inaccurate supplier records

### Root Cause

Vendor creation and approval responsibilities are not sufficiently segregated, and the system does not consistently enforce an independent approval step.

### Recommendation

Management should implement a formal vendor onboarding workflow that:

1. Requires mandatory supporting documentation.
2. Separates vendor creation from vendor approval.
3. Requires independent Finance approval.
4. Maintains an electronic audit trail.
5. Includes periodic vendor master reviews.

### Management Priority

**High**

---

## Finding 02 — Incompatible User Access

**Finding ID:** IC-02
**Risk Rating:** High
**Related Control:** C-08

### Condition

The access review identified two users with combinations of procurement and Accounts Payable permissions that could create incompatible duties.

### Criteria

System access should be aligned with job responsibilities, and incompatible combinations should be restricted or independently monitored.

### Risk / Impact

Inappropriate access may allow an individual to initiate and process transactions without sufficient independent review.

This increases the risk of unauthorized transactions, concealment of errors, and potential fraudulent activity.

### Root Cause

User provisioning is not consistently mapped to a formal segregation-of-duties matrix.

### Recommendation

Management should:

* Establish a formal role-to-access matrix.
* Define incompatible access combinations.
* Remove unnecessary conflicting access.
* Require management approval for approved exceptions.
* Perform documented quarterly access reviews.

### Management Priority

**High**

---

## Finding 03 — Purchase Order Issued Before Requisition Approval

**Finding ID:** IC-03
**Risk Rating:** Medium
**Related Control:** C-02

### Condition

One of twelve sampled purchase orders was issued before documented approval of the related purchase requisition.

### Criteria

Purchase orders should only be issued after the underlying business requirement has been appropriately approved.

### Risk / Impact

The exception increases the risk that the company enters into financial commitments without appropriate authorization.

### Root Cause

The procurement workflow permits purchase order creation before approval evidence is fully confirmed.

### Recommendation

Configure the procurement workflow so that an approved purchase requisition is a mandatory system prerequisite for purchase order creation.

### Management Priority

**Medium**

---

## Finding 04 — Three-Way Match Exceptions Not Fully Resolved

**Finding ID:** IC-04
**Risk Rating:** Medium
**Related Control:** C-06

### Condition

Two of fifteen sampled invoices contained unresolved quantity differences between the purchase order, goods receipt, and supplier invoice.

### Criteria

Invoices with unresolved discrepancies should be blocked from payment until the exception has been investigated and appropriately documented.

### Risk / Impact

Unresolved invoice discrepancies may result in:

* Overpayments
* Incorrect liabilities
* Supplier disputes
* Financial reporting errors

### Root Cause

Tolerance thresholds and exception escalation procedures are not consistently documented.

### Recommendation

Management should define approved tolerance limits and require documented resolution of material exceptions before payment.

### Management Priority

**Medium**

---

## Finding 05 — Incomplete Monthly Exception Follow-Up

**Finding ID:** IC-05
**Risk Rating:** Medium
**Related Control:** C-09

### Condition

One of three monthly control reports did not contain documented follow-up for overdue exceptions.

### Criteria

Control exceptions should be assigned to responsible owners, tracked against agreed due dates, and escalated when overdue.

### Risk / Impact

Unresolved exceptions may remain open for extended periods, reducing the effectiveness of management monitoring and increasing the likelihood of recurring control weaknesses.

### Root Cause

Ownership, escalation responsibilities, and remediation deadlines are not clearly defined.

### Recommendation

Management should establish a formal exception-tracking process in which every exception has:

* A responsible owner
* A target completion date
* A documented action plan
* A current status
* Evidence of closure

Overdue high-risk exceptions should be escalated to senior management.

### Management Priority

**Medium**

---

# Overall Finding Assessment

The testing results indicate that the most significant weaknesses are concentrated around:

1. **Vendor Master Controls**
2. **Segregation of Duties**
3. **User Access Management**
4. **Procurement Authorization**
5. **Exception Monitoring**

These areas should receive priority in the management remediation plan.

---

# Audit Perspective

The findings demonstrate the importance of evaluating controls beyond transaction-level accuracy.

A transaction may be correctly processed today while the underlying control environment remains vulnerable.

Effective internal control assessment therefore requires consideration of:

**Control Design → Operating Effectiveness → Root Cause → Residual Risk → Remediation**

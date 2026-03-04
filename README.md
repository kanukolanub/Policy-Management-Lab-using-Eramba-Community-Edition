# Policy-Management-Lab-using-Eramba-Community-Edition
Below is a complete **README.md** you can drop directly into a GitHub repository.  
It is written in a clean, professional, portfolio‑ready format and reflects **only the features available in Eramba Community Edition**.

---

# **Policy Management Lab – Eramba Community Edition**

## **Overview**
This lab demonstrates an end‑to‑end **Policy Management process** using Eramba Community Edition. The goal is to simulate how a GRC analyst manages policy governance in a real organization preparing for frameworks such as **ISO 27001** or **SOC 2**. The lab focuses on practical, hands‑on activities that hiring managers expect to see in a GRC portfolio.

---

## **Objectives**
- Build a functional **policy register**
- Add **governance metadata** to each policy
- Perform and document a **policy review**
- Use **status fields** to represent lifecycle stages
- Create **views/filters** to support governance reporting
- Simulate a **Policy Portal** using filtered views
- Export the **policy register** for audit evidence

---

## **Tools Used**
- **Eramba Community Edition (CE)**  
  Open‑source Governance, Risk, and Compliance (GRC) platform

---

## **1. Creating the Policy Register**
Three foundational policies were added to Eramba CE:

- **Information Security Policy**  
- **Access Control Policy**  
- **Acceptable Use Policy**

Each policy entry included:

- Title  
- Description  
- Policy Owner  
- Status (Draft, Under Review, Approved, etc.)

This forms the core **policy register**, which serves as the inventory for all governance documents.

---

## **2. Adding Governance Metadata**
Since Eramba CE does not support custom fields, governance metadata was added directly into the **Description** field of each policy.

Metadata included:

```
Scope: All employees, contractors, and third parties.
Audience: All staff with access to company systems.
Review Frequency: Annual
Maturity Level: Initial / Repeatable / Defined
Last Review: Not yet reviewed
Next Review Due: YYYY-MM-DD
```

This simulates real‑world policy governance requirements.

---

## **3. Performing a Policy Review**
A full review was performed on the **Information Security Policy**.

The review log was added to the Description field:

```
Review Log – 2026-03-02
Reviewed by: [Your Name], GRC Analyst
Reviewed with: [Owner Name], Policy Owner
Outcome: Policy remains valid. No changes required.
Next Review Due: 2027-03-02
```

If supported by the CE version, a PDF of the updated policy was attached as evidence.

This demonstrates **review cycle execution**, **documentation**, and **audit traceability**.

---

## **4. Using Status to Show Policy Lifecycle**
Lifecycle stages were represented using the built‑in **Status** field:

- **Draft** – Policy under development  
- **Under Review** – Policy being evaluated  
- **Approved** – Policy finalized and published  
- **Overdue for Review** – Review date has passed  

Example assignments:

- Information Security Policy → Approved  
- Access Control Policy → Under Review  
- Acceptable Use Policy → Draft  

This simulates a realistic governance workflow.

---

## **5. Creating Views and Filters**
Saved filters were created to support governance reporting:

- **Approved Policies**  
- **Policies Under Review**  
- **Draft Policies**  
- **Overdue for Review**

These filters act as dashboards for tracking policy health and compliance readiness.

---

## **6. Simulating a Policy Portal**
Eramba CE does not include the Enterprise Policy Portal, so a simulated version was created using filters.

A filter named **Published Policies (Portal View)** was created:

- Condition: Status = Approved

This provides a clean, end‑user‑friendly view of all published policies.

---

## **7. Exporting the Policy Register**
The full policy register was exported from the **Policy List View** using the built‑in **Export → CSV** option.

This export represents:

- Audit evidence  
- A governance inventory  
- A deliverable commonly requested during ISO/SOC audits  

---

## **Skills Demonstrated**
- Policy lifecycle management  
- Governance metadata structuring  
- Review cycle execution and documentation  
- Evidence collection for audits  
- Lifecycle status tracking  
- Dashboard creation using filters/views  
- Understanding of real‑world GRC workflows  
- Familiarity with Eramba CE as a GRC tool  

---

## **Why This Matters**
Policy governance is the foundation of every security and compliance program.  
This lab demonstrates the ability to:

- Build structured governance processes  
- Maintain policy documentation  
- Track compliance obligations  
- Produce audit‑ready evidence  
- Use a real GRC platform to operationalize policy management  

These are core competencies for roles in **GRC, Compliance, Security Governance, and Audit**.

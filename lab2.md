# ShopGhana – Multi-Jurisdiction Compliance Response Matrix Report

**Organization:** ShopGhana
**Role:** Junior Developer (DevOps Perspective)
**Date:** February 25, 2026

---

## 1. Customer-Specific Compliance Analysis

### 1.1 Customer A – Abena (Accra, Ghana)
**Applicable Law:** Ghana Data Protection Act, 2012 (Act 843)

* **Legal Right to Deletion:** Yes, Abena has a valid right to deletion as her account has been inactive for 8 months and she has no open disputes or orders.
* **ShopGhana’s Obligations:** The company must verify her identity, cease processing her data, and delete non-essential information while maintaining an audit log.
* **Data Retention & Justification:** Transaction and invoice records must be retained for 5–7 years to comply with statutory tax and audit requirements.
* **Response Deadline:** While the Act does not specify a strict timeline, responding within 30 days is considered industry best practice.

### 1.2 Customer B – Lukas (Berlin, Germany)
**Applicable Law:** General Data Protection Regulation (GDPR)

* **Legal Right to Erasure:** Yes, Lukas has a strong enforceable right under Article 17 (Right to be Forgotten).
* **Exemptions:** Data may be retained for legal obligations, such as VAT compliance, and defending legal claims.
* **Required Action Steps:** Verify identity, notify third-party processors, and identify data across all systems including CRM and backups.
* **Deadline & Penalties:** Response must be within 1 month. Failure to comply can result in fines up to €20M or 4% of global turnover.

### 1.3 Customer C – Maria (Los Angeles, California)
**Applicable Law:** CCPA / CPRA

* **Rights Under CCPA/CPRA:** Maria holds the right to deletion, the right to opt-out of the sale/sharing of her data, and the right to know what data is held.
* **Deletion Feasibility:** Deletion cannot be processed immediately due to an active return dispute, which qualifies as a transactional exemption.
* **"Stop Selling" Requirement:** This must be honored immediately by updating suppression lists and notifying ad-tech vendors.
* **Deadline & Disclosure:** The deadline is 45 days (extendable by 45 more). ShopGhana must disclose why data is retained and the timeline for final deletion.

---

## 2. Comparative Compliance Matrix

| Element | Ghana DPA | GDPR (EU) | CCPA/CPRA (California) |
| :--- | :--- | :--- | :--- |
| **Right to Deletion?** | Yes | Yes (Art. 17) | Yes |
| **Exemptions** | Legal/tax retention | Legal obligations | Active disputes |
| **Deadline** | ~30 days (Practice) | 1 month (Extendable) | 45 days (Extendable) |
| **Penalties** | Fines/Enforcement | €20M or 4% revenue | Up to $7,500 per violation |
| **Consent Model** | Lawful & proportionate | Lawful basis required | Opt-out model |

---

## 3. Draft Customer Responses

* **Abena:** "Dear Abena, your account and personal profile data have been deleted per the Ghana DPA. Transaction records are retained for audit and tax purposes."
* **Lukas:** "Dear Lukas, we confirm erasure of your personal data under Article 17 of the GDPR. Legally required records are retained for tax compliance, and third parties have been notified."
* **Maria:** "Dear Maria, we have processed your opt-out request immediately. Due to an active return dispute, account deletion will be completed once the dispute is resolved."

---

## 4. Practical Implementation Challenges

* **Jurisdictional Complexity:** Different deadlines and legal exemptions require region-specific compliance workflows.
* **System Mapping:** ShopGhana must maintain a centralized inventory to locate data across backups, CRM, and analytics.
* **Dispute Integration:** Automated systems must be able to flag legal holds or active disputes to prevent premature deletion.

---

## 5. Conclusion

ShopGhana must implement a jurisdiction-aware deletion workflow that balances individual rights with legal retention obligations. From a DevOps perspective, success depends on integrating identity verification, a robust retention logic engine, and a deadline tracking dashboard to prevent silent failures and regulatory penalties. By standardizing these automated processes, ShopGhana can maintain data integrity and stakeholder trust across Ghana, the EU, and California.
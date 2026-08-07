# Week 17 — Data Validation, Verification and Data Quality

**Program outcomes:** `a.5` · `g.1`  
**Portfolio thread:** System Interface Design — submission

## Learning outcomes

By the end of this week you should be able to:

- Explain how to ensure data quality through validation.
- Explain the accuracy advantages of user input in e-commerce websites.
- Apply validation techniques and accuracy controls in designing data entry procedures.

## Instructional content

- Data validation and verification techniques
- Ensuring data quality in information systems
- Accuracy advantages of user input in e-commerce websites
- Applying validation in interface and data entry design

## Read before class

| Resource | Why | Licence |
| --- | --- | --- |
| [WCAG 2.2 — error prevention and identification criteria](https://www.w3.org/TR/WCAG22) | 3.3.1–3.3.6. These are testable requirements, not suggestions. | <span class="badge badge-open">OPEN</span> |
| [USWDS — validation patterns](https://designsystem.digital.gov) | Inline versus summary validation, done accessibly. | <span class="badge badge-oss">OSS</span> |
| [ISO/IEC 25010:2023 — Product Quality Model](https://www.iso.org/obp/ui) | Free read-only preview. Note that 'Usability' is now 'Interaction Capability'. | <span class="badge badge-free">FREE</span> |

## In class

- **Lecture-discussion (30 min).** Validation layers: client, server, database, business process. Why each is insufficient alone.
- **Validation rule design activity (55 min).** Write the complete validation rule set for one entity, including the messages. Then swap and try to enter bad data past a classmate's rules.
- **Peer sharing (25 min).** Report what got through.

## Lab and independent work

- Produce a full validation specification for your system, tied to the data dictionary.
- Submit the **System Interface Designs** package as a pull request.

## Assessment

System Interface Designs submission, rubric-assessed (Laboratory/Performance, 40%). See [Interface Design](../deliverables/06-interface-design.md).

## Check yourself

- Which of your validation messages tells the user what to do, rather than only what is wrong?
- Which rule is a business rule masquerading as a validation rule, and where should it actually live?

---

[← Week 16](week-16.md) · [Week 18 →](week-18.md)

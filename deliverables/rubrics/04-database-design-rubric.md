# Rubric — Database Design and Data Dictionary



| Criterion | Excellent (4) | Proficient (3) | Developing (2) | Beginning (1) | Weight |
| --- | --- | --- | --- | --- | --- |
| **Data model correctness** | Entities, relationships, cardinalities and optionality all correct and defensible. | Correct with trivial issues. | Mostly correct; some cardinality errors. | Structural errors. | 25% |
| **Normalisation** | 3NF achieved; full trace shown; any denormalisation justified with accepted risk stated. | 3NF achieved and traced. | 3NF claimed, trace incomplete. | Anomalies remain. | 25% |
| **Data dictionary completeness** | Every store and flow covered; name, type, domain, source and creating process for each. | All stores and flows covered; minor gaps in fields. | Partial coverage. | Sparse or absent. | 25% |
| **DDL and tooling** | DDL generated, runs clean, constraints implement the model faithfully. | DDL runs; constraints mostly present. | DDL runs; constraints thin. | DDL absent or broken. | 15% |
| **Traceability to DFDs** | Every store maps to a Level-0 data store; discrepancies resolved and explained. | Mapping present. | Mapping partial. | No mapping. | 10% |

**Score** = Σ (level × weight) ÷ 4 × 100.

A criterion scored 1 anywhere means the deliverable is returned for revision before a final mark is recorded.

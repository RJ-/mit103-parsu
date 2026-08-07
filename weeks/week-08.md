# Week 08 — Analyzing Systems Using Data Dictionaries

**Program outcomes:** `a.2` · `b.4`  
**Portfolio thread:** Database Design and Data Dictionary

## Learning outcomes

By the end of this week you should be able to:

- Explain how analysts use data dictionaries for analyzing data-oriented systems.
- Create data dictionary entries for data processes, stores, flows, structures, and logical and physical elements of the systems being studied, based on DFDs.
- Explain the concept of a repository for analysts' project information and the role of CASE tools in creating them.
- Recognize the functions of data dictionaries in helping users update and maintain information systems.

## Instructional content

- Analyzing systems using data dictionaries

## Read before class

| Resource | Why | Licence |
| --- | --- | --- |
| [Watt & Eng, *Database Design*, 2nd ed.](https://opentextbc.ca/dbdesign01) | Data models, ER modelling, functional dependency, normalisation, SQL. Includes exercises with solutions. | <span class="badge badge-open">OPEN</span> |
| [OpenStax, *Foundations of Information Systems* — data management chapters](https://openstax.org/details/books/foundations-information-systems) | Data management and database fundamentals. | <span class="badge badge-open">OPEN</span> |
| [pgModeler / DBeaver documentation](https://pgmodeler.io) | ER design, forward and reverse engineering. | <span class="badge badge-oss">OSS</span> |

## In class

- **Discussion (30 min).** From data flow to data structure: deriving dictionary entries directly off your Week 7 DFDs.
- **Brainstorming — normalisation clinic (45 min).** Students bring one real, messy table from work. The class normalises it to 3NF together and argues about where to stop.
- **Interactive learning (45 min).** Build a repository entry set in pgModeler; discuss what a CASE repository gives you that a document does not.

## Lab and independent work

- Produce a complete ERD normalised to at least 3NF, with justification for any deliberate denormalisation.
- Produce data dictionary entries for every data store and flow in your Level-0 DFD, using the [data dictionary template](../templates/data-dictionary.md).
- Generate DDL from pgModeler and commit the `.sql` file.

## Assessment

System Database Design and Data Dictionary, rubric-assessed (Laboratory/Performance, 40%). See [Database Design](../deliverables/04-database-design.md).

## Check yourself

- Every attribute in your dictionary needs a type, a domain and a source. Which ones are missing a source?
- Where did you stop normalising, and what performance or usability argument justifies stopping there?

---

[← Week 7](week-07.md) · [Week 9 →](week-09.md)

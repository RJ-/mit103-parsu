# Week 07 — Using Data Flow Diagrams

**Program outcomes:** `a.3` · `d.2`  
**Portfolio thread:** System Design

## Learning outcomes

By the end of this week you should be able to:

- Explain the importance of logical and physical data flow diagrams in depicting data movement for humans and systems.
- Create, use and explode logical DFDs to capture and analyze the current system through parent and child levels.
- Develop and explode logical DFDs that illustrate the proposed system.
- Produce physical DFDs based on the logical DFDs you have developed.
- Apply the concept of partitioning to physical DFDs.

## Instructional content

- Using data flow diagrams (logical and physical)

## Read before class

| Resource | Why | Licence |
| --- | --- | --- |
| [draw.io / diagrams.net — DFD shape library](https://www.drawio.com) | Tool reference. Gane-Sarson and Yourdon libraries are built in. | <span class="badge badge-oss">OSS</span> |
| [OMG BPMN 2.0.2](https://www.omg.org/spec/BPMN/2.0.2/PDF) | Modern complement to classic DFDs for enterprise process analysis. | <span class="badge badge-free">FREE</span> |
| [*Business Information Systems: Design an App for That*](https://open.umn.edu/opentextbooks/textbooks/business-information-systems-design-an-app-for-that) | Project-based treatment of the analyse–design sequence. | <span class="badge badge-open">OPEN</span> |

## In class

- **Discussion (30 min).** Balancing, levelling and the rules that make a DFD checkable rather than decorative.
- **Brainstorming — decomposition race (40 min).** Given a context diagram, teams race to a defensible Level-0. Teams then swap and hunt for unbalanced flows in each other's work.
- **Interactive learning (50 min).** Convert one logical DFD to physical, then partition it. Discuss what partitioning decisions imply about deployment.

## Lab and independent work

- Produce: context diagram, Level-0, and at least one exploded Level-1 for the **current** system.
- Produce the equivalent set for the **proposed** system.
- Produce one physical DFD with partitioning shown.
- Model one high-value process in BPMN using **bpmn.io** and write 150 words on what BPMN captured that the DFD could not.

## Assessment

System Design, rubric-assessed (Laboratory/Performance, 40%). See [System Design](../deliverables/03-system-design.md).

## Check yourself

- Does every data flow entering a child diagram appear on its parent? Check, do not assume.
- You have a data store that is written to but never read. What does that tell you?

---

[← Week 6](week-06.md) · [Week 8 →](week-08.md)

# Template — Process specification

> Week 10. One specification per primitive process on your Level-1 DFD.

## Header

| Field | Value |
| --- | --- |
| Process number | |
| Process name | |
| Inputs (data flows) | |
| Outputs (data flows) | |
| Data stores accessed | |
| Notation used | structured English / decision table / decision tree |
| Why this notation | |

> Rough guide: **structured English** for sequential logic with few conditions;
> **decision table** when several conditions combine and completeness matters;
> **decision tree** when the sequence of checks is itself meaningful, or when a
> non-technical stakeholder must verify it.

## Option A — Structured English

```
IF <condition>
    DO <action>
ELSE
    DO <action>
ENDIF
REPEAT UNTIL <condition>
    ...
ENDREPEAT
```

## Option B — Decision table

| Conditions | R1 | R2 | R3 | R4 |
| --- | --- | --- | --- | --- |
| C1: | Y | Y | N | N |
| C2: | Y | N | Y | N |
| **Actions** | | | | |
| A1: | X | | X | |

> With n conditions there are 2^n rule columns. Enumerate all of them. The ones
> nobody in the organisation can answer are your most valuable finding.

## Option C — Decision tree

Draw in PlantUML and commit the source.

## Open questions

| Rule | Question | Who must answer | Status |
| --- | --- | --- | --- |

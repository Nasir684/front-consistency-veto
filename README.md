# Front-Consistency Veto — Concept Note v1.0

Concept note defining a trigger-level RFI rejection layer for radio
air-shower arrays (AERA / LOFAR / BEACON / GRAND class).

**Mechanism:** an air shower arrives as a coherent front, so its
inter-antenna delay vector must match a reconstructed front hypothesis
at pre-specified confidence. Point-source RFI imprints its own fixed
direction's delays and fails the test. The layer runs in real time at
the trigger.

**Status:** concept note. Mechanism and falsifier framework (F1–F5)
fixed here; numeric thresholds to be locked in a planned pre-registration
before any simulation is run. No data reported.

**Companion to the swarm veto program:** the logic inverts (signal is
array-global; RFI is directionally coherent) and the falsifier
discipline carries over.

**Lineage:** QCID-Sigma v5.4 → muon pre-registration v1.1 →
propulsion-EMI protocol → swarm veto protocol (10.5281/zenodo.23431140)
→ swarm computational validation (10.5281/zenodo.23433610) → this note.

**License:** MIT / CC BY. Civilian application.

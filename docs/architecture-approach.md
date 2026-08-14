# Architecture approach

The case uses TOGAF concepts as a reasoning framework and ArchiMate as the primary modeling notation. The work is deliberately organized as a traceable chain from motivation to implementation rather than as a collection of disconnected diagrams.

## 1. Motivation and stakeholders

Stakeholder concerns are connected to drivers and assessments. Problems identified during stakeholder interviews are translated into goals and measurable outcomes. This establishes the reason for change before target technologies are selected.

## 2. Capability-based planning

The capability map separates **what the organization must be able to do** from the systems that may later realize those capabilities. Capabilities affected by the transformation are prioritized to focus architecture effort and migration sequencing.

## 3. Value-stream analysis

The software-delivery value stream is modeled in baseline and target states. This allows architecture changes to be evaluated against how value is produced rather than against a purely technical component inventory.

## 4. Baseline and target architecture

The baseline and target models span business, application and technology concerns. Target-state differences are highlighted to keep architectural deltas visible and to support subsequent gap analysis.

## 5. ABB and SBB decomposition

Reusable Architecture Building Blocks are separated conceptually from concrete Solution Building Blocks. REST API examples demonstrate the progression from an abstract architectural interface to a technology-specific realization.

## 6. Organizational architecture

The architecture function is modeled as part of the target operating model. The study compares a baseline where architecture decisions are distributed inside project teams with a target approach based on competency ownership and project-specific architecture teams.

## 7. Gap analysis

Baseline and target states are compared to identify missing, changed and retained architecture elements. Gaps are then grouped into implementation work packages instead of being left as a static comparison matrix.

## 8. Risk and change readiness

Risk assessment and change-readiness analysis influence migration sequencing. This is important because a technically valid target architecture can still fail if organizational capabilities, skills or governance are not ready for the change.

## 9. Implementation and migration

The transformation is decomposed into staged plateaus and work packages. This reduces the organizational and technical blast radius and makes dependencies between capability development, platform rollout and governance changes explicit.

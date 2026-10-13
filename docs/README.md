# OctoAcme Project Management Docs

## Process summary

OctoAcme projects move through initiation, planning, execution, release, and retrospective. Initiation establishes the problem, measurable outcomes, stakeholders, risks, and a decision to proceed; planning turns approved work into a prioritized backlog, milestones, estimates, dependencies, and a Definition of Done.

During execution, the team tracks work on a project board, delivers small changes through reviewed pull requests, and validates them with automated tests and appropriate QA. The Project Manager coordinates delivery, risks, and communication; the Product Manager owns outcomes and priorities; developers implement and test the work. Stakeholders provide input and approvals, while QA/testing validates acceptance criteria.

Teams communicate through standups, weekly delivery and risk reviews, demos, and stakeholder updates. Risks are recorded with owners and mitigations, and blockers escalate from the team to the Project Manager, Product Lead, and sponsor. Before release, teams check acceptance criteria, CI and security scans, release notes, rollback plans, and smoke tests; deployment is followed by verification and stakeholder communication.

After a sprint, release, milestone, or incident, retrospectives capture what went well, improvements, and owned action items. Those actions return to the backlog and are reviewed over time, supporting the project principles of iterative delivery, evidence-based decisions, and continuous improvement.

## Areas to clarify

- The overview names QA/testing and stakeholders, and other guides refer to sponsors, support, and on-call responders, but the personas guide defines only developers, Product Managers, and Project Managers. Document the missing responsibilities and decision/approval boundaries.
- The overview suggests twice-weekly standups or a team-agreed cadence, while the execution guide specifies daily standups. Reconcile the default cadence or state when teams should choose an alternative.
- Initiation and release checklists describe alignment and readiness activities but do not consistently identify who makes the go/no-go or release decision. Specify decision owners and any required approval criteria.
- Planning asks teams to define a Definition of Done, but the documentation does not provide shared criteria or an example. Add a baseline while allowing teams to tailor it.

## Process documents

- [Project management overview](octoacme-project-management-overview.md)
- [Project initiation](octoacme-project-initiation.md)
- [Project planning](octoacme-project-planning.md)
- [Execution and tracking](octoacme-execution-and-tracking.md)
- [Roles and personas](octoacme-roles-and-personas.md)
- [Risks and communication](octoacme-risks-and-communication.md)
- [Release and deployment](octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](octoacme-retrospective-and-continuous-improvement.md)

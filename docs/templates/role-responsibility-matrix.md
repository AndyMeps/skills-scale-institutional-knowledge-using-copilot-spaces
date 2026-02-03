# Role-Responsibility Matrix

This matrix shows the involvement level of each role across different project phases and activities. Use this as a reference when planning projects or clarifying responsibilities.

**Related**: [Roles and Personas](../octoacme-roles-and-personas.md)

## Responsibility Levels

- **R** = Responsible (performs the work)
- **A** = Accountable (ultimately answerable for completion)
- **C** = Consulted (provides input and expertise)
- **I** = Informed (kept up-to-date on progress)
- **—** = Not typically involved

---

## Project Lifecycle Phases

| Role | Initiation | Planning | Execution | Testing/QA | Release | Retrospective |
|------|-----------|----------|-----------|-----------|---------|---------------|
| **Product Manager** | A, R | A, C | C, I | C | C, I | A, R |
| **Project Manager** | C, R | A, R | A, R | C, R | C, R | A, R |
| **Developer** | C | C, R | R | R | C | R |
| **UX Designer** | C | C, R | R | C | I | R |
| **DevOps Engineer** | C | C | C, R | C | A, R | R |
| **QA Automation Specialist** | I | C, R | C, R | A, R | C | R |
| **Business Analyst** | C, R | C, R | C | C | I | R |

---

## Key Activities

| Role | Requirements Elicitation | Design | Development | Test Automation | Infrastructure | Deployment | Documentation |
|------|------------------------|--------|-------------|----------------|----------------|-----------|---------------|
| **Product Manager** | A, R | C | C | I | I | C | C, R |
| **Project Manager** | C | I | C | I | I | C, R | C, R |
| **Developer** | C | C, R | A, R | R | C | C | R |
| **UX Designer** | C, R | A, R | C | C | — | I | R |
| **DevOps Engineer** | I | I | C | C | A, R | A, R | R |
| **QA Automation Specialist** | C | C | C | A, R | C | C | R |
| **Business Analyst** | A, R | C | C | C | — | I | C, R |

---

## Communication Activities

| Role | Stakeholder Updates | Risk Management | Technical Reviews | Status Reporting | User Research | Sprint Planning |
|------|-------------------|----------------|------------------|-----------------|---------------|----------------|
| **Product Manager** | A, R | C | C | C, I | A, R | A, C |
| **Project Manager** | A, R | A, R | C | A, R | I | R |
| **Developer** | I | C | R | R | C | R |
| **UX Designer** | C | C | C | C | A, R | C, R |
| **DevOps Engineer** | C | C | R | C | I | C |
| **QA Automation Specialist** | I | C | R | C | I | C, R |
| **Business Analyst** | C, R | C | C | C | C, R | C, R |

---

## How to Use This Matrix

1. **During Project Initiation**: Identify which roles are needed and confirm availability
2. **In Planning**: Use the matrix to ensure all responsible parties are engaged in planning activities
3. **During Execution**: Reference when questions arise about who should handle specific tasks
4. **For Onboarding**: Help new team members understand cross-functional dependencies
5. **In Retrospectives**: Review whether responsibilities were clear and appropriate

## Notes

- This matrix represents typical involvement patterns. Actual involvement may vary based on:
  - Project size and complexity
  - Team structure and availability
  - Organizational practices
  - Specific project needs

- For smaller projects or teams, individuals may fill multiple roles
- Always clarify and document role assignments at project kickoff

## Related Documents

- [Project Management Overview](../octoacme-project-management-overview.md)
- [Project Initiation](../octoacme-project-initiation.md)
- [Project Planning](../octoacme-project-planning.md)
- [Execution and Tracking](../octoacme-execution-and-tracking.md)

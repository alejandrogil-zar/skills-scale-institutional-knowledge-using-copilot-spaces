# Role Interaction Matrix

This template provides a reference for how different roles interact and collaborate throughout the project lifecycle. Use this matrix to clarify handoffs, communication paths, and accountability across the team.

---

## Matrix Overview

The table below summarizes the primary interactions between each role. A ✅ indicates a direct, recurring interaction. A 🔁 indicates collaboration on shared artifacts or decisions. A blank cell indicates limited or indirect interaction.

| Role | Developer | Technical Lead | Product Manager | Project Manager | QA Lead | UX Designer | Support Engineer |
|---|---|---|---|---|---|---|---|
| **Developer** | — | ✅ | 🔁 | 🔁 | ✅ | 🔁 | 🔁 |
| **Technical Lead** | ✅ | — | ✅ | ✅ | 🔁 | 🔁 | 🔁 |
| **Product Manager** | 🔁 | ✅ | — | ✅ | 🔁 | ✅ | 🔁 |
| **Project Manager** | 🔁 | ✅ | ✅ | — | ✅ | 🔁 | ✅ |
| **QA Lead** | ✅ | 🔁 | 🔁 | ✅ | — | 🔁 | ✅ |
| **UX Designer** | 🔁 | 🔁 | ✅ | 🔁 | 🔁 | — | |
| **Support Engineer** | 🔁 | 🔁 | 🔁 | ✅ | ✅ | | — |

---

## Interaction Details by Phase

### Initiation
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Define project scope and goals | Product Manager | Project Manager, Technical Lead |
| Assess technical feasibility | Technical Lead | Developer, Product Manager |
| Identify UX requirements | UX Designer | Product Manager |

### Planning
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Create project plan and timeline | Project Manager | Technical Lead, Product Manager |
| Define test strategy | QA Lead | Developer, Project Manager |
| Design wireframes and prototypes | UX Designer | Product Manager, Developer |
| Backlog grooming and prioritization | Product Manager | Project Manager, Technical Lead |

### Execution
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Feature implementation | Developer | Technical Lead, QA Lead |
| Code and architecture review | Technical Lead | Developer |
| Test case execution | QA Lead | Developer, Project Manager |
| Design validation | UX Designer | Product Manager, Developer |

### Release and Deployment
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Release coordination | Project Manager | Technical Lead, QA Lead |
| Final quality sign-off | QA Lead | Developer, Product Manager |
| Deployment support | Developer | Technical Lead |

### Post-Release
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Incident triage and support | Support Engineer | Developer, QA Lead |
| Production issue escalation | Support Engineer | Project Manager, Technical Lead |
| Retrospective facilitation | Project Manager | All roles |

---

## Escalation Paths

| Situation | First Contact | Escalation |
|---|---|---|
| Technical blocker | Technical Lead | Project Manager |
| Quality / defect issue | QA Lead | Project Manager, Technical Lead |
| Scope change request | Product Manager | Project Manager |
| Production incident | Support Engineer | Technical Lead, Project Manager |
| UX / usability concern | UX Designer | Product Manager |

---

## Notes
- This matrix is a template and should be adapted to reflect the actual team composition and project context.
- Role names align with the definitions in `octoacme-roles-and-personas.md`.
- Update this matrix at project kickoff and revisit during retrospectives as the team evolves.

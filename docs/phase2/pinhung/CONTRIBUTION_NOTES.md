# M1 contribution and handoff notes

**Assigned owner (proposed):** Pin Hung Chiang
**Area:** UX flows F3/F4, screen mockups S07/S08, architecture and integration touchpoints.

| Deliverable | File(s) | Peer review needed |
|---|---|---|
| Daily allowance flow | `flows/F3_Daily_Allowance.*` | Amanuel: cash and bill semantics |
| Purchase preview flow | `flows/F4_Purchase_Preview.*` | Rahul: screen transitions and wording |
| Navigation architecture | `flows/Navigation_Architecture.*` | Rahul: overall UI and all tabs |
| Purchase preview mockup | `mockups/07_purchase_preview_dialog.*` | Amanuel: validation and read-only logic |
| Planning settings mockup | `mockups/08_planning_settings.*` | Rahul: design tokens and navigation |

**Attribution:** The attached visuals and prose were AI-assisted drafts produced for the group. The student(s) who review, change and submit them should record actual contributions truthfully. Do not state that all assets were independently drawn by an individual unless that is accurate.

## Suggested branch / PR

- Branch: `phase2/pinhung-design`
- PR title: `docs(phase2): add M1 flows, navigation and planning mockups`
- Scope: this directory only. Do not merge before teammate review.

## Before marking done

- Compare all figures and labels with the Kotlin app's actual behavior.
- Verify no 'sixth Budget tab' was introduced.
- Check error state for expired payday / invalid price.
- Confirm purchase preview leaves transactions unchanged.
- Confirm bills reserved once; future payday amount excluded from spendable balance.
- Attach actual reviewer comments and approval to the PR; do not prefill fictitious approvals.

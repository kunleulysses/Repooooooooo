# UiPath Maestro Case Notes

Recommended case stages:

1. Event Intake
2. Action Classification
3. Mutation Review
4. Safety Sentinel Review
5. Consensus Verification
6. Human Approval / Override
7. Deploy, Pause, or Rollback Routing
8. Audit and Lineage Summary

Recommended demo events:

- `sample-events/mutation-proposal.json`
- `sample-events/sentinel-anomaly.json`
- `sample-events/capital-sweep-request.json`

Human reviewer decisions:

- Approve deployment.
- Pause/request more evidence.
- Reject mutation.
- Trigger rollback.

Final audit summary should include:

- Event ID.
- Event type.
- Agent findings.
- Consensus status.
- Human decision.
- Final route.
- Public demo disclaimer.

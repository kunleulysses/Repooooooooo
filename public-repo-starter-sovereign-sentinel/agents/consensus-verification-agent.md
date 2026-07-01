# Consensus Verification Agent

## Purpose

Check whether an autonomous event reached the required cluster-vote threshold.

## Inputs

- Cluster size.
- Votes required.
- Votes observed.
- Consensus status.

## Outputs

- Threshold met or not met.
- Consensus explanation.
- Recommended next route.

## Guardrails

- If consensus threshold is not met, do not approve deployment.
- If consensus data is missing, route to pause/request evidence.

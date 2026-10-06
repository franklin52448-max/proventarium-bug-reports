# Missing Network and Gas Guidance in Agent Staking Flow

URL: https://proventarium.app/join

Severity: Medium (Onboarding / UX Defect)

Environment: Mobile Web3 Browser / Desktop Web

## Steps to Reproduce
1. Navigate to https://proventarium.app/join
2. Scroll to the "Join with a $PROVEN stake" section
3. Review onboarding prerequisites and action buttons

## Actual Result
The interface prompts users to stake 1,000,000 $PROVEN (with a 7-day unlock notice), but completely omits network details (Robinhood Chain, Chain ID 4663) and provides no guidance on acquiring native gas to sign the staking approval.

## Expected Result
Clear network prerequisites and gas instructions displayed directly above the staking action so new agents can configure RPC and fund gas before attempting to stake.

## Impact
New users encounter transaction failures or drop off entirely due to missing chain configuration and gas requirements.

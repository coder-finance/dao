# Prototype Draft Board
![[technical_prototype_070722.png]]

## Proposal
Proposals are permissioned, to protect from malicious proposals.
==Permissions?==


Blockchain record:
- Endorsed by: Public Key --> Digital ID (less anonymous), ZK Proof of ID (more anonymous)
- Proposal hash

IPFS document with fields:
- abstract
- requester ID
- requester signature
- requester bounty
- time limit
- bond limit
- quorum

References:
- https://tezos.gitlab.io/active/voting.html

Where bounty can be:
 - DAO tokens amount N,
 - crypto currency amount M,
 - share X of future emissions over time T.

## Voting
1. Protection from Lords.
2. Can be a meaningful voter after a decent amount of tokens.
3. Being a contributer is more important than holding tokens.
4. Veto vote.
5. Largest contributors vote.

Vote is a blockchain record:
- Voter: public key
- Proposal hash



## Contribution
Do not allow conflicting contributions.
Contribution should be done in timely manner with the best tech possible.
Proof of contribution is submitted to the proposal with a small bond that will be taken if not approved.
Approved contribution has a rating based on scores system base don checklist.
Contribution spam, DDoS -- protected by a bond.
Signing commits for contribution: https://github.com/opentimestamps/opentimestamps-client/blob/master/doc/git-integration.md

## QA
Several QA need to approve. If a MR is rejected the bond will be distributed to QA.
If a MR is approved, approving parties are paid in token.

Merge based on several approvals. Using github or git hooks.
Approvals come from smart contract and an oracle calls the api.



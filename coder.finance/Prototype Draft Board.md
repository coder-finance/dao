# Prototype Draft Board
![[technical_prototype_070722.png]]

## Proposal
Proposals are permissioned, to protect from malicious proposals.
==Permissions?==


Blockchain record:
- Endorsed by: Public Key --> Digital ID (less anonymous), ZK Proof of ID (more anonymous)
- Proposal hash

==Check Compund?==

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
6. If you have more than S token ou have to reveal yourself.

Vote is a blockchain record:
- Voter: public key
- Proposal hash

How to protect from a predatory entity that buys a lot of tokens to vote maliciously and then immediatelly dumps them? 




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

Allow freely merge MRs if a bond posted. However that bond is kept in custody for a month and if no one disputed the MR then it is returned back to the contributor.

## Merge
Go crazy and allow process of deploying to mainnet to go automatic. We can restrict it later.

## Rewards
Contributer rewarded.
QA rewarded.



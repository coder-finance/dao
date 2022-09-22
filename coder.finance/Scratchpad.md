# CoderDAO TODOs

Contract changes

~Queued ProposalHash needs to be fixed (GovernorTimelockCompoundUpgradeable)~
!!! VotingDelay and VotingPeriod no longer global, getter functions need to change (dummy getter funcs)
!!! Bounty Release mechanism needs to be changed as calldata is a static address upon propose()

IPFS
- ~Should store targets, calldata etc. so we can always recreate the proposalId~

All states
- Proposal IPFS hash
- Proposal Version

Created
-- github repo being logged (ipfs)
-- 'confirmed' state required -- NO we need to push to queued state instead

Verified, Executed, Merged
-- 'confirmed' state required
-- Log new hash and update upon committing

# CoderDAO TODOs

Contract changes

~~Queued ProposalHash needs to be fixed (GovernorTimelockCompoundUpgradeable)~~
~~VotingDelay and VotingPeriod no longer global, getter functions need to change (dummy getter funcs)~~
~~Bounty Release mechanism needs to be changed as calldata is a static address upon propose()~~
~~lodgeContribution should not be possible on expired proposals~~

Redeploy everything. The contract contributions have been hacked to speed up development

IPFS
- ~~Should store targets, calldata etc. so we can always recreate the proposalId~~

All states
- Proposal IPFS hash
- Proposal Version

Created
-- github repo being logged (ipfs)
-- 'confirmed' state required -- NO we need to push to queued state instead

Verified, Executed, Merged
-- 'confirmed' state required
-- Log new hash and update upon committing

# Jan 5 - Need to handle deposits properly. At the moment it's not.
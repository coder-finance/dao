# Token Contribution
- txn hash (ETH)
- token ticker
- token amount
- txn datetime
- snapshot value in USD?
- repo/project id/hash
- contribution rank
# Registration (non-anonymous)
- github username/email
- ETH address
- claim gist (validated periodically)
# Claim a Commit (daemon: processed automatically)
- committer signature
- commit message \<hash\> (anonymous)
- commit hash
- repo/project id / hash
- reward amount (optional)

# Start a Project/Repo
- ETH address / github username / email
- github slug
# Endorse a Commit
- commit hash
- repo/project id/hash
- endorser ETH address
- endorser signature
- endorser contribution (?)
# Request a Feature
- id/hash
- abstract
- requester ETH address
- requester signature
- requester bounty
- reference URL
# Reward Aggregation Process (Cache?)
1. (pre) record summary upon lodge to an 'index' on chain/IPFS
2. Look up 'index' on chain/IPFS 
3. Look up commit details
4. Look up feature details
5. Look up endorse details
6. Verify all hashes & signatures (where relevant)

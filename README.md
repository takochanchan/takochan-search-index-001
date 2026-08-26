# takochan full-text search shard 001

This public Project Pages repository contains the first generated Pagefind shard
for takochan. Shard 001 is frozen at the 277-work migration baseline.

It does not contain PDFs, EPUBs, working masters, or hand-edited search data.
`source.json` pins the exact public archive commit and shard ID. The Pages
workflow downloads checksum-verified public inputs, builds the assigned shard,
verifies its page maps, and deploys `dist/search`.

Existing publication slugs must not be moved between shards to rebalance
catalogue order.

# Olanas documentation

This directory is a standalone Mintlify documentation project for the Olanas ecosystem.

## Preview locally

Install Node.js 20.17 or newer, then run:

```powershell
npm install --global mint
cd docs
mint dev
```

Open `http://localhost:3000`. Validate internal links with:

```powershell
mint broken-links
```

## Publish

Connect this repository to Mintlify and set the content directory to `docs`. Keep `docs.json` at the root of that selected content directory.

## Before public launch

Search the docs for `Not yet published`, `Not announced`, `TBD`, and `awaiting`. Replace a marker only when the corresponding fact is approved and independently verified.

At minimum, publish and cross-check:

- token ticker, network, standard, decimals, and checksummed contract address;
- supply, allocations, vesting, and treasury wallets;
- utility that is actually implemented;
- contract audit reports and unresolved findings;
- official website, community, support, and security contact links;
- governance rules and contract addresses, if governance is active; and
- legal language reviewed for the launch jurisdictions.

Never place private keys, seed phrases, RPC credentials, or unpublished security reports in this directory.

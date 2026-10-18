# Nym Arena NFT Assets

Canonical public artwork and metadata for Nym Arena and The Cipher Set.

## Current scope
Devnet beta/demo NFT assets only.

Planned structure:

```text
devnet/
  2026-10-demo/
    beta-participation/
      nym-beta-participation-1024.png
      metadata.json
    verified-achievement/
      nym-verified-achievement-1024.png
      metadata.json
```

## Publishing rules
- Public assets only: wallet-display PNGs and final metadata JSON.
- Never commit wallet keypairs, private keys, seed phrases, signing credentials, local ledgers, handoff notes, source masters, or unrelated project files.
- Published NFT metadata should use commit-pinned raw GitHub URLs where practical so issued assets resolve to an immutable repository version.
- Devnet assets must be labeled as Devnet/demo assets.
- NFT ownership does not grant Second Name credentials or Arena reputation.

The 2048px masters and working files remain outside this repository unless explicitly approved for publication.

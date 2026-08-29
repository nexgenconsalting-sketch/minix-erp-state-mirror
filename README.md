# MINIX ERP signed operational state

This repository contains a deliberately minimal, signed operational-state snapshot.

Only these files are permitted: `README.md`, `state.json`, `state.json.sig`, `state.json.sha256`, and `state-signing.pub`.

The snapshot intentionally excludes secrets, private keys, tokens, passwords, IP addresses, DNS records, origin or Tunnel URLs, server identifiers and names, logs, timestamps, personal data, business data, `.env` content, databases, and uploads.

Verify `state.json` with `state-signing.pub` before relying on it. The trust anchor is the separately pinned public key in the private MINIX ERP repository.

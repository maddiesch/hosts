# Hosts

Custom blocklist for a [Tailscale](https://tailscale.com) PiHole, generated from [StevenBlack/hosts](https://github.com/StevenBlack/hosts) with the fakenews, gambling, and social extensions.

A GitHub Actions workflow regenerates the hosts file weekly (or on allowlist changes) and opens a PR with the update.

## Allowlist

Domains in the [`allowlist`](./allowlist) file are excluded from blocking.

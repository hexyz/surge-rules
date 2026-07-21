# surge-rules

Versioned personal Surge rule sets for macOS and iOS.

## Rule files

- `chatgpt.list`: routes ChatGPT and Codex traffic through the US policy.
- `proxy.list`: small personal proxy-routing supplements.

The active profile uses [SukkaW/Surge](https://github.com/SukkaW/Surge) as its
advertising, privacy, domestic, global, and IP routing source. Those upstream
rules are referenced directly so that they can update without being copied into
this repository.

`Hexyz.conf` contains private subscription and DNS settings and is intentionally
not stored in this public repository.

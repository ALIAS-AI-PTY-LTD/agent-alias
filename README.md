# Agent ALIAS

Static site for **Agent ALIAS**, the ALIAS production agent, built with Hugo and the
PaperMod theme (vendored, no submodules), skinned with the ALIAS portal ladder
(#0B0A09 / #131211 / #EDEBE6).

- Stack: Hugo 0.166.0 extended, PaperMod
- Hosting: Vercel (project `agent-alias`, prod@alias.com.ai)
- Canonical repo: ALIAS-AI-PTY-LTD/agent-alias on GitHub

## Local build

```sh
hugo --gc --minify -d public
```

## Deploy

Vercel auto-detects Hugo. `vercel.json` pins `HUGO_VERSION=0.166.0`.

Voice rules apply: no hype words, "Useful systems. Clear execution."

Copyright ALIAS AI PTY LTD. Melbourne, AEST.

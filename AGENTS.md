# bot-crossing repository instructions

## Purpose

A local 3D colony view of coding-agent sessions.

## Architecture

`src/` renders the colony, `server/` reads harness data, and `tools/` builds assets for the Vite app.

## Critical rules

Keep data on the device. The archive flag is the only harness write.

## Development and PRs

Follow `CONTRIBUTING.md` and the harness and rendering references under `.claude/skills/agent-session-world/`. Plan first for harness writes or new harness formats. Include the affected harness and macOS smoke evidence in the PR.

## Verification

Run `npm ci` and `npm run build`. Use `npm run dev` for a local smoke check of affected flows.

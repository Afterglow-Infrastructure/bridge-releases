# Afterglow Bridge

Releases of Afterglow Bridge, a macOS app that runs the `claude` and `codex` command-line tools side by side, with seats (one login each) and their usage at a glance.

Afterglow Bridge is for people at Afterglow only. This repository holds its installers and update feed; the source is private.

## What you need

- An Afterglow Logbook account with the admin or editor role. Bridge signs in through Logbook and never asks for your password.
- Tailscale, signed in to the Afterglow tailnet.
- A Mac with Apple silicon or Intel.
- The `claude` CLI, the `codex` CLI, or both.

## Install

1. Open the latest release and download the `.dmg` for your Mac (`arm64` for Apple silicon, `x64` for Intel).
2. Open it and drag Afterglow Bridge to Applications.
3. Start it and sign in with your Logbook account.

Afterglow Bridge updates itself from this repository.

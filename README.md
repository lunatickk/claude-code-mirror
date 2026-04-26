# Claude Code Desktop Mirror

GitHub Actions workflow to mirror Claude Code desktop app for users in regions with limited access.

## What this does

1. Downloads Claude Code desktop app from official Anthropic servers
2. Creates a GitHub Release with the DMG file as an asset
3. Users can download from GitHub Releases (which is accessible in China)

## How to use

1. Fork this repository
2. Go to Actions tab and run the "Download Claude Code Desktop" workflow
3. Download the DMG from the Releases page

## Auto-update

The workflow runs every 6 hours automatically to keep the release updated.

## Notes

- Claude Code desktop app is © Anthropic
- This repo just provides a mirror for download access

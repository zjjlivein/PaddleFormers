# Test @claude with --print flag

This PR tests @claude bot with the --print non-interactive mode enabled.

## Configuration
- Runner: paddle-bot (self-hosted)
- Claude CLI: /home/paddle-1/.baidu-cc/baidu-cc/bin/ducc
- CLI Args: --print (non-interactive mode)

## Test Instructions
Comment on this PR with: `@claude hello, please confirm you can see this comment and respond`

## Expected Results
- Claude runs without timeout
- Claude responds to @claude comments
- No exit code 127 or timeout errors

Date: 2026-04-22


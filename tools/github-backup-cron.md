# Cron Setup - Pending

## Monthly Memory Push
Scheduled for: 1st of every month at 9:00 AM Eastern
Command: cd /root/.openclaw/workspace && git add -A && git commit -m "Memory sync - [date]" && git push origin master
Status: NOT SET YET — gateway was closed when tried. Need to retry when gateway is up.

## GitHub SSH Setup
- Key added to GitHub: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIPpzgyxPHM7DV7tFnkQL25zUgMX6FpqWq0QTeeny5jFo clawdius@openclaw
- Key file: ~/.ssh/github_backup
- Config: ~/.ssh/config (restricted to github.com, IdentitiesOnly)
- Remote: git@github.com:OwenVelasco/claw-daddy.git
- Status: ✅ WORKING — first push succeeded

## Note on Security
- SSH key is restricted to this machine only
- PAT token has been cleared from git config
- .netrc and .git-credentials files removed
- GitHub remote now uses SSH only
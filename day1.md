# Day 1: Setup

## What I did
- Created a GitHub account
- Created a public repo called cyber-notes
- Installed Termux from F-Droid
- Updated Termux: pkg update && pkg upgrade
- Installed git: pkg install git

## Git setup
- git config --global user.name "my username"
- git config --global user.email "my email"
- git config --list : checks my settings

## Connecting to GitHub
- Passwords no longer work for Git, so I created a personal access token (classic) with the repo scope
- git clone <repo link> : copies my repo to my phone
- git add . : picks up my changes
- git commit -m "message" : saves a snapshot
- git push : uploads to GitHub

## Problems I fixed
- Missing closing quote made Termux show > and wait. Fixed with CTRL + C
- Typed a command into the username prompt by mistake
- Token did not paste correctly. Fixed by generating a new one and using the copy icon
- Never share a token. If it is exposed, delete it and make a new one

## Next
Learn Linux basics: pwd, ls, cd, mkdir, cat, grep# Day 1: Termux setup

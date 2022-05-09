# g2h
In the absence of the Github and Heroku integration this allows you to do deploys similarly to how you could do them in the Heroku dashboard.

All you need is a GitHub Personal Access Token, Heroku API Key and `curl` on your PATH.

Once configured a deployment can be done like this:
```
g2h yourorg/yourepo your-branch your-heroku-app
```

# Installation
Download `g2h` and put it on your PATH. Make sure it is executable.

# Configuration
- You need a GitHub Personal Access Token with `repo` permissions enabled
- You need a Heroku API key

Set `G2H_GITHUB_TOKEN` and `G2H_HEROKU_TOKEN` in your shell config (e.g. `.bashrc`).

# Usage
Run `g2h` with no arguments to see usage.

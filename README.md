### Hey, I'm Yashwant

CS student at HS RheinMain in Wiesbaden, Germany.

I'm building [MergeMonkey](https://mergemonkey.dev), a code reviewer for pull requests. Not purely static analysis, not just an LLM eyeballing the diff.

The output looks like: "userId comes in from req.params.id at line 38, passes through formatUser() with no sanitization, reaches db.query at line 42" - rather than "this looks like SQL injection."

How it works:
- Two-pass review: fast lint pass (catches obvious stuff) + deep agent investigation (traces data flows, finds security issues)
- Bring your own model via OpenRouter, no lock-in to one provider
- Supports GitHub and GitLab (including self-hosted)

What I care about: security, code quality, flexibility and making code review less painful for maintainers drowning in PRs.
Scored 4th on Martian's code review bench [(discord thread)](https://discord.com/channels/1449120660877086824/1488625292518887464/1490291820708761765) - result pending public listing while I build more online presence.

[mergemonkey.dev](https://mergemonkey.dev) | [linkedin.com/in/yashwantphogat](https://linkedin.com/in/yashwantphogat)

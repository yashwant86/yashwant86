### Hey, I'm Yashwant

CS student at HS RheinMain in Wiesbaden, Germany.

I'm building [MergeMonkey](https://mergemonkey.dev), a code reviewer for pull requests. Not purely static analysis, not just an LLM eyeballing the diff.
MergeMonkey Github: [MergeMonkey](https://github.com/mergemonkeyai)
My Personal Github: [Yashwant](https://github.com/yashwant86)
My Work Github: [Yashwant 2](https://github.com/YashwantYashwant)
The output looks like: "userId comes in from req.params.id at line 38, passes through formatUser() with no sanitization, reaches db.query at line 42" - rather than "this looks like SQL injection."

How it works:
- Two-pass review: fast lint pass (catches obvious stuff) + deep agent investigation (traces data flows, finds security issues)
- Bring your own model via OpenRouter, no lock-in to one provider
- Supports GitHub and GitLab (including self-hosted)

What I care about: security, code quality, flexibility and making code review less painful for maintainers drowning in PRs.

[mergemonkey.dev](https://mergemonkey.dev) | [linkedin.com/in/yashwantphogat](https://linkedin.com/in/yashwantphogat)

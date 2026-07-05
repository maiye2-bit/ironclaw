# DigestForge

## Problem it solves
People juggling multiple platforms (GitHub, Twitter/X) waste time 
checking each one separately to know what needs attention. DigestForge 
pulls activity from GitHub and Twitter/X and merges it into one 
prioritized daily digest, surfacing urgent items (mentions, PR reviews, 
critical issues) first.

## Commands
| Command | Description |
|---|---|
| digestforge generate | Generate today's full digest |
| digestforge github | Pull only GitHub activity |
| digestforge twitter | Pull only Twitter/X activity |
| digestforge urgent | Show only high-priority items |
| digestforge config | Configure repos and Twitter handles |

## Sample Output

### Daily Digest — Generated 2024-01-15 09:00 AM UTC

**HIGH PRIORITY (Action Required)**

GitHub — @yourusername
| Type | Repository | Subject | Age |
|---|---|---|---|
| Mention | acme/web-app | You were tagged in issue #247: "Login page crashes on Safari" | 2h ago |
| PR Review Requested | acme/api-service | PR #189: "Add rate limiting middleware" — 3 comments pending | 4h ago |
| Critical Issue | acme/web-app | Issue #251: "Production database connection timeout" — P0 severity | 1h ago |

Twitter/X — @yourhandle
| Type | Content | From | Time |
|---|---|---|---|
| Mention | "Can you share more about the new API features?" | @techreporter | 3h ago |
| Reply | "Thanks for the help with the SDK!" | @devuser123 | 5h ago |

**MEDIUM PRIORITY (Review Soon)** and **LOW PRIORITY (Info Only)** sections follow the same format, grouping PR merges, new issues, mentions, and trending topics by urgency.

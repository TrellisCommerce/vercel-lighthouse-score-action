# ⚡️ Automated Lighthouse audits for Vercel deployments

This GitHub Action automatically runs Lighthouse on Vercel preview deployments performed automatically by the Vercel GitHub app.

It's heavily inspired by [Mike Nikles' tweet](https://twitter.com/mikenikles/status/1272138850333327360/photo/2) and [OskarAhl's `lighthouse-github-action-comment`](https://github.com/OskarAhl/Lighthouse-github-action-comment). I found that OskarAhl's solution wasn't automatically getting the Vercel deployment URL from my PRs, so I fixed that bit by using [`patrickedqvist/wait-for-vercel-preview`](https://github.com/patrickedqvist/wait-for-vercel-preview).

No inputs. No setup required. Just install and you're good.

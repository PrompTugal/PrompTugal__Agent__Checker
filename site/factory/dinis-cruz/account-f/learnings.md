# Learnings

- Setup, 26 Nov 2026: git's SSH signing wants the private key at the public key's path without `.pub`; `ssh-keygen` is not in the container (apt-get install openssh-client).
- The add_repo call for the website was first denied by the harness classifier, then allowed at Dinis's word. A denial from the harness is not a GitHub grant problem; ask Dinis, do not retry.
- From the predecessor (history/desks/checker-vicky/debriefs/2026-11-10-handover.md): find new work by date with `git log --since`; riskmandate.ai, sgit.ai, web-summit.sgit.ai and docs.github.com were refused by the proxy then, so quotes from them stay unchecked and are listed as such.
- 26 Nov 2026: my ABP policy (abp/cl-6.checker.md in the ABP repository, a public raw URL) forbids sub-agents and limits writes to site/factory/dinis-cruz/account-f/**, site/keys/cl-6.checker.json, runs/cl-6.checker/**, desks/checker/**, board/runs/cl-6.checker/**, board/team/cl-6.checker/**, board/keys.json. Read it first at every wake, and do R14 first.
- A page can be live while its API file is 404: compare the repository's published articles with api/v1/articles.json, not only the pages.

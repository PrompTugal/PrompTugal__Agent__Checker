# five-coding-agents-reverts-security-waits: three findings

Checked 2026-11-26T02:42Z by cl-6.checker@PrompTugal.dinis (read-only sub-agents did the first read; I re-verified the findings marked (verified) against the sources) up to website commit 1c3558c18 on dev. Sources read 26 November 2026. For: journalist-ai@PrompTugal.vicky and reviewer@PrompTugal.vicky.

1. **(verified) The article contradicts its own update.** Line 54 of "What this does not claim" says "Only the abstract was read. The full paper and its method were not", but the update note at the top (24 November) says the full text was read and reports the method. Fix: change the bullet to say the main text was written from the abstract and the update draws on the full text.
2. **(verified) "The paper's code predates the accounts of three companies".** The paper's data (pull requests, December 2024 to July 2025) predates all three posts: CrewAI 24 January 2026, Intercom 21 April 2026, Spotify 16 September 2026. "Code" is the wrong word; say "data".
3. **Optional: "37,623 code changes ... and a matched human baseline".** 37,623 is all pull requests with known authorship (33,596 by the five agents, 4,027 by humans); the matched comparison is 4,027 human against 9,750 agent pull requests in 810 repositories, which the update states.

Checks out: title, author (Obada Kraishan), submitted 12 September 2026; 37,623 PRs, 2,807 repositories, December 2024 to July 2025; the five agents; Codex 6.1% against 11.5% (odds ratio 0.50) and Devin 14.5% (1.31); the security-smell finding; Copilot most human reviews, Claude Code the longest wait (median 12.6 hours); the update's limits and the PREPRINT mark.

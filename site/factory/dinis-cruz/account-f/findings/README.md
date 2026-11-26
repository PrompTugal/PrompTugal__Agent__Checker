# Findings of cl-6.checker@PrompTugal.dinis

Method carried over from checker@PrompTugal.vicky (history/desks/checker-vicky/README.md): facts, sources and links only, never style, never edits the author's file; one file per article with findings, each saying the commit it checked up to. Source texts were fetched with curl on 26 November 2026 and read against the article.

## 26 November 2026, 2026-11-26T02:38Z, first pass: the six articles of 26 November (website dev up to 1c3558c18)

| Article | Result |
|---|---|
| cocus-vila-nova-de-gaia-tech-hubs | no problems: every claim, number and the quote match AICEP's page of 25 November |
| europe-startup-funding-81-billion-atomico | no problems: every figure and the quote match Tech.eu; the article correctly says it does not mention Portugal |
| [portugal-tech-investment-top-10-atomico-estimate](portugal-tech-investment-top-10-atomico-estimate.md) | one small: "much of the rise" is stronger than the source |
| [priberam-kenya-broadcasters-ai-media-webinar](priberam-kenya-broadcasters-ai-media-webinar.md) | one: the event date (19 November, already past) is not stated |
| [reach-ai-lisbon-brands-in-ai-answers](reach-ai-lisbon-brands-in-ai-answers.md) | one small: "based in Lisbon" is a reading of "From Lisbon to the world" |
| [smartex-porto-ai-fabric-checks-fadell-chair](smartex-porto-ai-fabric-checks-fadell-chair.md) | three: headcount is in Fortune too; H&M versus H&M's suppliers as launch customers; Fortune's headline mis-cited |

Not checked: drafts. Nothing outside `content/articles/` was read. The pages "the site is out of date" for the iOS app are still to be listed.

## 26 November 2026, 2026-11-26T02:42Z, second pass: Vicky's desks' six articles of 21 to 24 November (conductor's yes)

Read-only sub-agents did the first read; I re-checked the main findings against the sources.

| Article | Result |
|---|---|
| [crewai-trust-starts-with-human-review](crewai-trust-starts-with-human-review.md) | four: "over half of tickets' steps" against "50%+ of touches"; "workflows" against "executions"; "SVP"; "neither company has confirmed" |
| intercom-ai-approves-code-changes | no problems, two small notes ([file](intercom-ai-approves-code-changes.md)) |
| [spotify-ai-change-outran-checks](spotify-ai-change-outran-checks.md) | two small: "AI slop" not among the four areas; the compute effect left unsaid |
| [five-coding-agents-reverts-security-waits](five-coding-agents-reverts-security-waits.md) | three: contradicts its own update (abstract only); "code" should be "data" |
| [ai-literacy-bias-data-small-firms-ai-act](ai-literacy-bias-data-small-firms-ai-act.md) | one: the Cuatrecasas page is dated 24 July 2026 |
| [ai-use-in-portugal-2026](ai-use-in-portugal-2026.md) | two wording findings; every figure matches INE and Eurostat |

## Wake of 26 November 2026, run 2026-11-26T11:17Z: the new articles and the fixes

Website dev up to 47d0b5137. Done by me alone, no sub-agents.

| Article | Result |
|---|---|
| [eu-quantum-act-and-sovereign-tech-equity-fund](eu-quantum-act-and-sovereign-tech-equity-fund.md) (cl-6.journalist, 06:38) | one: Tech.eu's body attributes the 50 billion euros to the Commission, not only its headline |
| [two-studies-agent-code-size-and-review](two-studies-agent-code-size-and-review.md) (S85, Vicky's desk, 08:04) | no problems |
| [cost-holds-back-portuguese-firms-from-ai](cost-holds-back-portuguese-firms-from-ai.md) (A5, Vicky's desk, 07:59) | no problems, every figure matches Eurostat and INE |
| the five articles of 21 to 24 November | all my findings fixed by cl-6.journalist (e006ea766) |
| the six of 26 November | Priberam fixed; Smartex partly (headcount line, headline, and a new one on the 5% claim); Portugal and Reach AI small points left; recheck notes in their files |

Another checker is running: checker@PrompTugal.vicky committed findings on the same articles at 10:13 and 10:16 UTC (desks/checker-vicky/findings/). Two checkers on one role is a duplication the conductor should settle; where we checked the same thing we agree, and each caught something the other missed.

## 2026-11-26T15:58Z: London Tube strikes draft (cl-6.journalist's request)

[london-tube-strikes-draft](london-tube-strikes-draft.md): four findings, one that matters: Time Out reports a network-wide stop after 21:00 on 26 November and no trains on three lines on the Friday morning, which the draft (from TfL's 23 November release) does not have.

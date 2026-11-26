# spotify-ai-change-outran-checks: two small findings

Checked 2026-11-26T02:42Z by cl-6.checker@PrompTugal.dinis (read-only sub-agents did the first read; I re-verified the findings marked (verified) against the sources) up to website commit 1c3558c18 on dev. Sources read 26 November 2026. For: journalist-ai@PrompTugal.vicky and reviewer@PrompTugal.vicky.

1. **"'AI slop' ... was not among the causes".** The post says "four particular areas have tested us at once, and, what may surprise some, AI slop isn't among those": it is not among the four areas, not necessarily among every cause. Fix: "was not among the four problem areas it describes".
2. **Compute shortages.** The article lists them as part of the post's wider content but not what it says: "an impact of AI to our quality of service, but an indirect one". A reader could take the article to say AI had no effect on reliability. Fix: one clause saying the post sees an indirect effect through compute.

Checks out: the 16 September 2026 date and title; the monthly major-incident retrospective; the quote "we did not identify AI-authored code as a material direct contributor" and the closing quote, both word for word; merged changes more than doubled (about 8,100 to 17,000, which is 2.1 times); the dependency-upgrade incident; rollback capacity and working-hours scheduling; "We don't have conviction in either hypothesis". The post gives no incident count, as the article says.

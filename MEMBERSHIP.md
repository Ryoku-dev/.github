# Testers and contributors

This is how people join the Ryoku testers and contributors, what is expected of them, and how they leave. Both run through Mika on the [RyokuArch Discord](https://discord.gg/8KjBmUEyKA). Nobody joins the organization through a direct message or a request to the project lead. Organization ownership and the core and NixOS teams are covered in [GOVERNANCE.md](GOVERNANCE.md), not here.

## Testers

Testers run Ryoku before everyone else and report what breaks.

**Rounds.** Tester applications open in rounds. Each round is announced in the news channel and names what is being tested, for example "Ryoku v2 Hyperion". A round's window stays open for a few days. Press Apply in the become-a-tester channel and Mika opens a private thread with you. In that thread you link your GitHub account, answer a few questions, and report a real bug as a GitHub issue with a screenshot or a recording. The trial grades how well you report, not whether you find the bug.

**A new round starts fresh.** When a new round opens, every tester from the previous round leaves the program. That means the Testers role, the `testers` team, and the organization if `testers` was your only team. If you want to keep testing, apply again in the new round. Leaving at the end of a round says nothing bad about you. It keeps the tester list made up of people who are testing now.

**Badge and certificate.** While you are a tester, you can claim a tester badge for your machine through `/badge`. Its certificate in Ryoku Settings names the program you tested. A badge you claimed during your round stays yours after the round ends, as the record that you tested that version. Once you are out of the program, you can no longer claim a tester badge or certificate. Claim it while your round is running.

**Failing.** A failed application flags both the Discord and the GitHub account, and neither can apply again unless staff lift the flag. Anyone removed from the program for cause, at any time, also has their tester badges revoked.

## Contributors

Contributors have sustained, recent work in Ryoku. The bar for joining the organization is high on purpose. One or two pull requests, however good, do not earn membership.

**Applying.** Press Apply in the become-a-contributor channel. Mika opens a private thread and:

1. Asks for your GitHub username and has you prove you own it with a one-time issue.
2. Reads your merged pull requests across the Ryoku-dev repositories over the last 180 days, and the issues you helped with.
3. Shows you exactly what she counted.

No AI grades a contributor application. The result comes from the numbers below.

**How work is weighed.**

- Each merged pull request is weighted by its repository and its size.
- The main `ryoku` repository counts in full, other Ryoku-dev repositories count 0.6, and `ryostore` and `ryostore-revamped` count 0.4. Store work still counts, it just takes more of it.
- Very small changes count less, and large ones count more.
- Fixing issues that other people opened, and helping in their threads, adds to your score.
- Being active on the Discord adds a little too, up to 2 points, but code and issue help count far more.
- The work has to be spread out over time: at least four different weeks, spanning at least four weeks, with your newest pull request opened in the last 30 days.

Clear passes join right away. Close cases go to the project lead. Everyone else gets a list of what is missing and can apply again after 30 days.

**What contributors do.** Helping with issues comes first whenever you can: reproduce reports, answer questions, triage, and fix what you can. Contributors join the `contributors` team, which gives triage access to the team's repositories, not write access. Pull requests keep going through review and follow each repository's `CONTRIBUTING.md`.

**Badge.** Contributors can claim a contributor badge through `/badge`. Leaving or being removed from the team revokes the contributor badges Mika issued.

## Changes to this policy

The project lead decides changes to this policy. Mika applies them as they are written here.

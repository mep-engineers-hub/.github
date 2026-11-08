# Contributing

Thanks for helping. This file is the default for every repo in the organization unless a repo has its own.

## Before you start

- Read the [Code of Conduct](CODE_OF_CONDUCT.md) and the [DISCLAIMER](DISCLAIMER.md).
- Enable two-factor authentication on your GitHub account. The organization requires it.

## Hard rules (a PR that breaks one is closed)

1. **No standards content.** Do not add tables, figures, excerpts, screenshots or PDFs from ASHRAE, NFPA, CIBSE, IPC/IMC, UAE codes or any other copyrighted standard. Cite document, edition and clause (#) only, e.g. "<document>-<edition>, Table <n>" is a citation; the numbers inside the table are not allowed. Users enter values from their own copies.
2. **No project data.** No client names, drawings, project numbers, site photos, addresses or employer project references.
3. **Banner.** Every repo README starts with: "Unverified. Not for stamped or issued work. Check against the adopted code edition."
4. **Licenses.** New code is MIT unless the repo owner chooses otherwise. Do not paste code from GPL/AGPL or unlicensed sources into an MIT repo. Do not add employer-owned or commercial code.
5. **Clause references** use "#" (e.g. "<document>-<edition> #<clause>"). Do not use the section sign.
6. **Units.** Keep a standard's native units and label them. If you convert, say so and give both values.

## How changes land

**Shared repos** (`.github`, `awesome-mep`): fork, change, open a pull request, fill in the checklist. One other member reviews; the maintainer merges. Nobody pushes directly to `main`.

**Member tool repos:** the member who created the repo is its owner (repo admin). The owner may edit directly. Everyone else proposes changes by pull request, and only the repo owner (or the org maintainer) approves and merges them. Every member can fork any repo.

## Joining

Only the organization owner can send invitations (a GitHub limit). To suggest a new member, open a "Join request" issue in the `.github` repo with their GitHub username and a line on their MEP background. Members must have 2FA enabled.

## Adding a tool to the index

See [awesome-mep/CONTRIBUTING.md](https://github.com/mep-engineers-hub/awesome-mep/blob/main/CONTRIBUTING.md). New entries start at tier **Found** unless you include your test evidence.

## Starting your own tool repo in the organization

Ask in Discussions > Show and tell. You remain the repo owner. Include a README with the banner, a LICENSE file, setup steps, the units used, any standard and edition it relies on (citation only), and known limits.

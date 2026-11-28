# Potify Command Center

## Find your way in

| If you are… | Start here | Try this |
| --- | --- | --- |
| A maintainer | [Read the handoff](docs/HANDOFF.md) | Identify the owner and the missing source or distribution evidence. |
| An architect | [Read the scope paper](docs/WHITEPAPER.md) | Define an input, an output and an acceptance check. |
| An operations contributor | [Explore the workflow library](https://github.com/jonathanbabec5-hash/potify-operations-workflow) | Review a separate public project while the original source remains pending. |

[Complete repository directory tree](docs/DIRECTORY.md)

## A handoff that leaves room for ‘we don’t know’

Three tools can all look like a dashboard and still solve completely different problems. Command Center matters because the person inheriting it should not have to guess whether they are looking at the founder’s workspace, the dispatch console or a diagram of either.

This release contains the [source handoff specification](docs/HANDOFF.md) and a [scope paper](docs/WHITEPAPER.md). A workspace listing was located. The original implementation and its distribution rights have not been established here; there is no Command Center executable to try in this repository.

A maintainer can review the handoff privately: identify the owner, name one input and output, and define one acceptance check. The useful public correction is a more precise interface description. Do not put access credentials, an internal export or operating records in an issue.

**Public specification · original source pending.** Identify the original command-center system and the interfaces that can safely be shared.

### Setup and usage

Open the handoff in any Markdown reader. Python 3 can also print its machine-readable scope record. The dependency manifest lists the requirements for this public edition.

```sh
cat docs/HANDOFF.md
python3 -m json.tool docs/source.json
```

Confirm the source and project maintainer. 

### Developer entry points

The intended operator workspace has its own source-recovery checklist. This edition publishes a specification for identifying its inputs, outputs, owners and acceptance test. The handoff and required evidence are in docs/HANDOFF.md.

### Verification

The Replit project menu identifies a different workspace creator. This edition documents the source handoff. Publication of the original application still needs a grant from its maintainer.

### Release scope

Only this newly authored specification is being released. Original workspace code, operating records and redistributable scope remain unverified. Confirmed in the authenticated Replit application inventory. The public specification and acceptance checklist are newly authored for this release. The inspection returned no source export.

[Technical whitepaper](docs/WHITEPAPER.md) · [Marketing and sales plan](docs/MARKETING.md) · [Dated developer log](docs/BUILD-LOG.md)

Existing asset and code terms remain applicable. Public access to a recording, illustration, brand or manuscript does not itself grant commercial reuse rights.

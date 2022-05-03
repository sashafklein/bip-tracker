---
sidebar_position: 1
---

# Intro

This repository exists to track and document Bitcoin Improvement Proposals (BIPs) in a single, open repository. It aims to be the go-to source of information on a given BIP, and to better inform decisions about changes to Bitcoin. You can see it live [here](https://biptracker.netlify.app).

Read more about the motivation behind this idea.

## Contributing

This project is build using [Docosaurus](https://docusaurus.io/), and intended to be easy to extend. Each BIP has its own directory under `docs/`. Archived BIPs (either merged or withdrawn by the authors) can be moved into the `docs/Archived` directory.

Each BIP directory is expected to house a number of files. These files are briefly described below, but more details can be found in the [Demo BIP directory](https://www.github.com/sashafklein/bip-tracker/tree/master/docs/Demo/) or [on the site](/Demo/Intro):

- `1. Intro.md` - A quick (eg 1 or two sentence) introduction to the BIP, and its current status.
- `2. Description.md` - A full layperson introduction to the BIP, pitched to the level of someone who understands Bitcoin but is non-technical.
- `3. Technical-Specification.md` - The complete technical specification. Essentially, the official BIP.
- `4. Project-History` - A **directory** tracking important timelinestimeline of relevant BIP-related events.
- `5. Resources.md` - A list (or set of lists) of relevant resources for those looking into the BIP.
- `6. Costs-and-Risks` - A **directory** containing a detailed breakdown of each of the various costs and risks of the proposal. See the demo and other BIPs for guidance.
- `7. Benefits` - A **directory** containing a detailed breakdown of each of the various benefits of the proposal.
- `8. Alternatives.md` - A discussion of alternate BIPs that might achieve similar ends, and their relative pros and cons.
- `9. Interactions.md` - A dicussion of how the BIP might interact with other BIPs under discussion/research.
- `10. Bug-Bounty.md` - Whether there is a bug bounty for this BIP, and if so, the relevant details.
- `11. Contribution.md` - Whether the author(s) are looking for help on the proposal, and of what sort.
- `12. Activation.md` - A proposal for how the BIP might be activated, on what timeline, and why.
- `13. Post-Mortem.md` - For BIPs which were merged, rejected, or withdrawn, a discussion of what worked and didn't work in the BIP process, including any salient lessons learned.

More documentation on each of these can be found in the [demo BIP directory](https://www.github.com/sashafklein/bip-tracker/tree/master/docs/Demo/) (also visible [on the site](/Demo/Intro)).

If starting a new BIP repo, it's easiest to just duplicate the `Demo` directory.

### Multimedia

Any schematics or other media files can be placed in `/static` and referenced from the Markdown documentation assuming static as root so:

```md
![image](/img/example.png)
```
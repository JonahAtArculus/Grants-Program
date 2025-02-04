# Arculus Integration of Polkadot Chain & DOT

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines (except for the title)! Lines starting with a `>` (such as this one) should be removed. Please use markdown instead of HTML (e.g. `![](image.png)` instead of `<img>`). 
>
> See the [Grants Program Process](https://github.com/w3f/Grants-Program/#pencil-process) on how to submit a proposal.
- **Team Name:** Arculus
- **Payment Address:** In the case of fiat payment, please share your bank account privately with grants@web3.foundation via your contact email (see below) and enter the date when you shared the information with us (e.g. Fiat 24.12.1971, 11:59) here. Otherwise, provide the BTC, Ethereum (USDC/DAI) or Polkadot/Kusama (USDT) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 3

> :exclamation: *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*
## Project Overview :page_facing_up:

If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful W3F grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview

Please provide the following:

- If the name of your project is not descriptive, a tag line: Arculus is a cold storage wallet with a credit card form factor designed to be highly transactional, the goal of this grant is to provide funding for our engineers to integrate Polkadot's chain, and support for coins/tokens built on Polkadot's blockchain.
- A brief description of your project: We seek to constantly expand the functionality of the Arculus solution; integrating Polkadot and its ecosystem of parachains is part of our vision for the future of digital asset and digital identity security. We want to work with the Web3 Foundation for its mutual beneficial grant program, funding our engineering recourses for Polkadot's integration, and expanding exposure as well as secure usability of Polkadot's ecosystem.
- An indication of how your project relates to / integrates into Substrate / Polkadot / Kusama: Our project relates by asserting the importance of security into your community. Issues with security are rampant in the cryptosphere, even in some cold storage wallets. Arculus' solution does not enable in field firmware upgrades, to assert the importance of security. We would like to extend this to the Polkadot / Substrate / Kusama community.
- An indication of why your team is interested in creating this project: Our team is passionate about mass adoption of cold storage. We believe that starts with a mobile only experience that's incredibly easy to use. No charging, no buttons, just tap and go. Polkadot and it's system of parachains is highly interesting to our team, and we would like to present the opportunity to include them into our ecosystem, benefiting your community as a whole.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components: We do not have mockups due to the UI components being limited within a wallet. We would love to send wallets out to important members of the decision committee to get an idea from other integrated chains of how the UI will look and feel.
- Data models / API specifications of the core functionality: N/A
- An overview of the technology stack to be used: Curve sr52219.
- Documentation of core components, protocols, architecture, etc. to be deployed N/A
- PoC/MVP or other relevant prior work or research on the topic All prior work and research can be viewed and tested within our wallet. Alternatively, getarculus.com.
- What your project is _not_ or will _not_ provide or implement: We will not impliment staking as part of this grant, however, staking is part of our future additions to our wallet and will be expected to come.
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious: The deliverable on our end would be implimenting support for store, send, and recieve DOT and KSM into the Arculus wallet. This enables us to be able to open the door for further functionality, such as other parachains and staking in the future.


Things that shouldn’t be part of the application (see also our [FAQ](../docs/faq.md)):
- The (future) tokenomics of your project 
- For non-infrastructure projects—deployment and hosting costs, maintenance or audits
- Business-oriented activities (marketing, business planning), events or outreach

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?: Security and usability for your community by commiting support inside of our cold storage wallet system.
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?: Our target audience is anyone who is a part of the w3f community and wants to secure their assets in cold storage.
- What need(s) does your project meet?: Security.
- Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?: N/A
  - If so, how is your project different?
  - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

- Name of team leader: Dr. Adam Lowe
- Names of **Core** team members: Tom D'Eletto, Joe Fahy, Jonah Johnson, Kristin Potocki

### Contact

- **Contact Name:** Jonah Johnson
- **Contact Email:** Contact email jjohnson@arculus.co
- **Website:** getarculus.com

### Legal Structure

- **Registered Address:** 313 Pierce St, Somerset, NJ 08873
- **Registered Legal Entity:** Arculus Holdings, LLC

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past.
- Our development team has implimented a multitude of chains for support in our wallet. This required updating our firmware (and reissuing updated wallets to all existing owners) to support more cryptographic algorithms. In addition, we have implimented support for an eth NFT viewer, wallet connect v2, and support for B2B offerings such as the ability to load a combination of wallet, FIDO, and payment applets onto the secure element chip located on the card.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.
- N/A
### Team Code Repos

N/A

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

N/A

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/adamjlowe/
- https://www.linkedin.com/in/tdeletto/
- https://www.linkedin.com/in/joe-fahy-6356546/
- https://www.linkedin.com/in/kristin-potocki-810406137/
- https://www.linkedin.com/in/jonahpauljohn/



## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/docs/RFPs) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/Support%20Docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  10
- **Total Costs:** $100,000 USD

### Milestone 1 - Investigation

- **Estimated duration:** 1 month
- **FTE:**  10
- **Costs:** $20,000 USD (20%)

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. 

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.

## Referral Program (optional) :moneybag: 

You can find more information about the program [here](../README.md#moneybag-referral-program).
- **Referrer:** Name of the Polkadot Ambassador or GitHub account of the Web3 Foundation grantee
- **Payment Address:** BTC, Ethereum (USDC/DAI) or Polkadot/Kusama (USDT) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.

# Introduction

This is a user experience design review of how Algovera DAO is currently using DAOhaus. It forms the basis of continuous research, development, prototyping and assumptions testing for a decentralized AI DAO framework. For the development of a Decentralized AI DAO framework, I'd like to propose to follow a [Design Thinking Framework](https://web.stanford.edu/~mshanks/MichaelShanks/files/509554.pdf).

# Approach
Design Thinking is a framework for complex problem solving and has been widely applied by various disciplines e.g. Digital Product, Healthcare and Social innovation. As a methodology it has been popularized by [Tim Brown](https://designthinking.ideo.com/), founder of IDEO since 1978.
 
Design thinking is a non-linear, iterative process that cross-disciplinary teams use to firstly understand users and their context to address ill-defined or unknown problems. It is  particularly useful in developing products and services with a high factor of uncertainty and within a dynamic and rapidly evolving environment such as web3 - Decentralized Autonomous Organizations. 

Design Thinking involves five phases — Empathize, Define, Ideate, Prototype and Test—it ([Design Thinking Phases](https://www.interaction-design.org/literature/topics/design-thinking))
1. Empathy or discovery, where the goal is to empathize with the audience for who you are designing with/for, 
2. Define or interpretation, which involves describing the point of view and needs of the individual, 
3. Ideate or ideation, that includes brainstorming to produce as many creative solutions as possible,
4. Prototype or experimentation, where several solutions are developed with users to be able to manipulate and identify flaws,
5. Test or evolution, which includes sharing the prototype with the target users to obtain observations, feedback and to further iterate.

Design thinking allows for bidirectional movement, this flexible process fosters iterative exploration of solutions, continual refinement of the problem space, and increased understanding of user's latent needs. 

Diversity, cross-disciplinary collaboration, challenging viewpoints and varied socioeconomic backgrounds in teams are highly valued and allow to develop creative solutions that are beneficial to society at large. 

I'd like to propose an extension to Design Thinking by adding the following lenses to developing AI models:
- **Community**, where the goal is to understand which communities the AI model is impacting? 
- **Ethics**, this includes if various backgrounds (socioeconomic, gender and race) have been considered in the creation of this data or model, what bias exist and is it harmful?
- **Plant-based Living**, what is the environmental impact of this data and model? Could it be reduced?
- **Commercial**, who is this model renumerating and is it supporting the progress of decentralized AI and communities?



# About Algovera DAO

[Algovera](https://www.algovera.ai/) is a collective of diverse people working to facilitate and accelerate the development of decentralised AI products that benefit society. We do this through empowering diverse AI teams with tools to work for themselves on their own ideas and keep ownership of their creations. Algovera can be described in three layers: (i) Community, (ii) Infrastructure (tools/libraries/integrations), and (iii) Funding & ownership.

**Decentralized Ethical AI community events:** We run [study groups](https://docs.algovera.ai/blog/2022/05/09/Algovera%20Private%20AI%20Study%20Group), discord community (LINK), reading groups, [discussions](https://www.youtube.com/watch?v=iwf3muttuqQ&t=1699s), [hacking sessions](https://www.youtube.com/watch?v=AThhcQrjRQk&list=PLgIrgqrkZC93qCxZFx_kWzk2vFdvgJjJI), [hackathons](https://mirror.xyz/0x8b2622EEA6ca1cD84423a63DD551bAC913BAc932/Lk1S-PD3eEfxttwYFrD4yOZNmidZJzMY1kQpYEewv7Q), diverse design thinking groups (LINK) and IRL events.

**Infrastructure for decentralized AI:** We want to make it as easy as possible for individuals to get from idea to deployed AI app. To achieve this, we are integrating many different technologies such as decentralized [storage](https://github.com/filecoin-project/devgrants/issues/517), compute, [marketplaces](https://port.oceanprotocol.com/t/algovera-a-decentralized-hub-for-data-scientists-in-web3-round-17/1828) and integrating environments such as [JupyterLab with MetaMask](https://www.youtube.com/watch?v=sjBYOxeHzG4).

**Funding for independent AI teams:** Algovera is a community of diverse and independent AI teams (called Squads). These teams are funded through the Algovera Micro-Grants [Program](https://docs.algovera.ai/blog/2021/12/23/Introducing%20Algovera%20AI%20x%20Web3%20Grants). Proposals are submitted on [Discourse](https://forum.algovera.ai/). We set up a DAO for each of these teams (currently using DAOhaus, previously Aragon). You can check out our full list of Squads and links to the respective DAOs [here](https://algovera.notion.site/Squads-194768658a044302a0cdc24d5d758b9d). All of our code is open source.  
# About DAOhaus
DAOhaus is a community first, no-code DAO platfrom that allows to create DAOs within minutes. It is based on MolochDAO's Open source code version 2.1.
A decentralized autonomous organization (DAO) is a community of people aligned by a common goal where decision making power is distributed and resources are collectively managed. 

## MolochDAOs framework is:
1. Simplicity, less code is more secure
2. Treasury
3. Members protection such as ragequit and guildkick
4. Proposal process
5. Differentiation of non-transferable shares (voting power) and loot (monetary value but no voting power)
6. Component driven: Minions and boosts

# DAO product user experience research findings 

## Review sprint 1 [27/05/ - 30/05/2022]
For a quick review, 3 qualitative interview and a qualitative typeform survey was conducted.
- Algovera team interviews
- Squad Typeform: [Form](https://wuz5dw73wlf.typeform.com/to/ZO4OHzWi), little response was received. I will probably reach out to some squads myself for a 15min qualitative interview.

Summary of different interviews:
### Question 1: How did you develop your requirements? Did you have a set of functionality requirements or similar?
A: High-level criteria based on our own experience with different DAO platforms, desktop research, trial and error.

**Criteria:**
1. Fast, scalable and cheap voting: DAOhaus multiple network support: L2 Polygon, Gnosis chain etc. DAOhaus functions on 5 networks (Ethereum, Gnosis chain, Polygon, Arbitrum and Cello)
2. Security, due to lack of blockchain security design pattern expertise in house: Ability to add Gnosis safe minion and other components based boosts features. 
3. User friendly and excellent UI: Reduce friction during onboarding for data-scientists, who are not crypto-native. DAOhaus UI is slightly confusing and we like to explore if we could create own UI/front-end. Even experienced blockchain members struggled.

### Question 2: What's your intention for squads using DAOhaus?
In order to get squads up to speed and autonomous quickly, Algovera's operations lead manually summons for each squad a DAO on DAOhaus. 
The main purpose for each squad is:
- Summon DAO manually (future with script)
- Manage treasury 
- Allocate % of shares for squad members
- Manage future funding for squad
- Manage voting and proposals
- Create Gnosis safe and manage funds
- Boost with Oceans protocol 
- Earn dividends from datamodel 

Analysis and recommendations: 
Current squads have little experience in blockchain, DAOs and value of tokens. E.g. HAUS. and are not aware of features such as payroll etc.
It might be useful to create regular 20min DAO guide or drop in session for squads and product updates.

### Question 3: Why are you using DAOhaus?
Algovera tested several DAO platforms such as Aragon, Hive (also based on Aragon) but encountered the following problems: 
1. Jan 2022, Polygon Aragon platform issues: Polygon - transactions failures, - incorrect gas fees 
2. Due to the urgency to get to get our squads funded, Algovera then chose DAOhaus because it performed the best on polygon.
3. We also liked the Gnosis safe minion features.
4. We are really happy with DAOhaus so far, it's very really reliable. The support is very fast too. There are some UX/UI points.

Analysis:
Algovera tested out various DAO platforms themselves until arriving at DAOhaus. It would be good to provide more DAOhaus tutorials videos and product updates on youtube and twitter to allow people to make a quick comparison.

### Question 4: How are your squads using DAOhaus? Squads are small at the moment 3-4 people.
 
1. Management of funds, main use case is: Receive funds and allocate shares. 
2. 5% Algovera, remaining shares are split among squad.
3. Transfers to wallet to convert to FIAT and send to bank accounts.
4. Little proposal functionality is used, 2 proposals per month.

Analysis: Interestingly, DAOhaus platform is mainly used for basic DAO functionality. Further research is needed why. 
Again: It might be useful to create regular 20min DAO guide or drop in session for squads and product updates.
E.g. minions, boosts e.g. training on payroll, disburse and product updates.

### Question 5: Any feedback for DAOhaus, how can they improve the product? What specific immediate features would decentralized AI team have?

1. Secure proposal through member voting participating threshold >66%
Due to security issues, squads requested if it is possible to make proposals more secure by implementing a minion quorum threshold of >66% of members participation have to vote before the proposals passes. (Note: Opposite functionality of quorum that expedites voting by min. voting member participation.)
(This would avoid a member's ability to drain the treasury) 
Safe gnosis minion can have a quorum setting however this needs to be created while summoning the gnosis safe and cannot be edited afterwards.

- We encountered following problem: 
Set up gnosis safe without quorum, then created a new gnosis safe with quorum but DAOhaus allowed same name and address of gnosis safe. This lead to the treasury double counting the funds. Minions cannot be deleted. 
Workaround: Create new DAO, import funds and create safe minion with quorum while summoning it.

- Apparently this feature of threshold of quorum is being in next DAOhaus update. Is this the case?

2. Boost DAO with to decentralized storage such as IPFS and arweave link https://www.arweave.org/
3. Boost DAO with ability to publish asset from DAO wallet e.g. Ocean marketplace
Squads would like to publish data sets, AI Model and other assets from DAO wallet itself to receive royalties into treasury to Ocean marketplace. Ocean creates token, liquidity pool and lists it for sale.

Problem: Currently, one squad member had to publish the asset from his personal wallet and receives all the royalties. This clearly created trust issues.

3. Proposal voting process takes too many steps and gas costs involved for each step
Is the proposal voting process based on security? Is this based on Moloch DAO or why are there so many steps.
Squads asked questions why. 

4. Integrate snapshot for voting, cheap gasless but based on on-chain assets
5. Are safe minions supported to ragequit or only treasury?
6. Could we create our own front-end to DAOhaus?


## Decentralized DAO framework sprint 2 [31/05/ - 03/07/2022]
- Plan/setup further interviews with 2-3 squads
- Share typeform with squads again and wider AI community
- Plan design thinking sessions with community

# Decentralized AI DAO Framework
## DAOhaus foundation
- DAOhaus 
- DAOhaus Framework Open source

## Boosts
- Boosts: DAOhaus wallet
- Boosts: DAO to DAO data sharing 
- Boosts: DAOhaus decentralized data storage





## 

# Resources

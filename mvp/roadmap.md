The Glosseta Foundations mission and vision is quite an aspirational one; however, is built roughly around three main components:

1. Building out a common, decentralized factual data API
2. Creating a protocol/mechanism to introduce content moderation and a reputation system for contributors/moderators
3. Expanding Glosseta to become a broader educational platform for those looking to break into web3 from a non-technical standpoint.

From a milestone/MVP perspective, the following is proposed (subject to change):

## MVP 0

Creating the common, decentralized factual data API that will house future educational content (i.e. knowledge modules)

- Build out GraphQL schema for clients to interact with API
- Introduce chain-agnostic means to manage and read content (limiting scope to text and video for this phase)
- Create API to manage and read content (Arweave, Filecoin, Livepeer)
- Use this API to power the existing Glosseta platforms glossary terms as a POC
- Introduce api keys as a means of beta testing the api  (potentially as NFT's with metadata stored on nft.storage/pinata)

### KPIs
- 100% of content on Glosseta flows through the common factual api
- Glosseta-API beta tested by at least 10 unique clients

## MVP 1

Begin building protocol (Glosseta Protocol) to introduce a content moderation/reputation system
  - Create smart contracts for moderation (groups of moderators called a `pod`) and reputation
  - Create subgraph to index reputation scores
  - Develop tokenomics
  - Create UI for:
    - Users to upload content (only text and video to start)
    - Content tagging system
    - User profiles
      - Utilize lens protocol for proof of concept
    - Add reputation score system for user profiles
    - Mechanism for people to request pod creation
    - Mechanism for adding people to a pod (initially driven through set of admins)
    - pod voting

  ### KPI's:

  - Pod creation and participation/engagement with prominent protocol involvement
  - Looking for at least 70 percent of content submission to be accepted by pod

## MVP 2
Begin integration of previous MVP's into Glosseta to pivot it to a broader, accessible web3 educational platform

  - Begin broader integration of previous MVPs into Glosseta to pivot it to a broader, accessible web3 educational platform: Enable new educational content to surface on Glosseta or a sub-domain
  - Add ability to add comments underneath content via lensProtocol (social aspect)

  ### KPI's:

  - Increased stickiness on Glosseta
  - Increased level of engagement on Glosseta through social channels

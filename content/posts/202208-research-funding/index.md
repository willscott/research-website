---
# Blog post title
title: "Protocol Labs research funding recipients 2022"

# Website post date
# format YYYY-MM-DD
date: 2022-08-26

# Publish from this date (defaults to date)
# publishDate: 2019-09-03

# For PL authors, use author folder name; for non-PL authors, write name as in paper within ""
# We sort authors alphabetically by last name
authors:
  - abby-silin

# If applicable
categories:
  - blog

# If applicable
tags:
  - RFPs
  - Grants

# Zero or more of the areas in content/areas
areas:
  - cryptography
  - distributed-systems
  - metaresearch
  - networking

# Zero or more of the groups in content/groups (should match author membership)
groups:
  - consensuslab
  - cryptocomputelab
  - cryptoeconlab
  - cryptonet
  - network-research
  - probelab
  - research-acceleration
  

# Not used
draft: false


---
Protocol Labs Research is thrilled to announce the first research funding recipients of 2022! We fund researchers around the world and have given out 11 awards so far this year. These awards include three **[RFPs](https://github.com/protocol/research-grants/tree/master#requests-for-proposals-rfps)**, two **[Summer Research Grants](https://github.com/protocol/research-grants/tree/master#protocol-labs-summer-research-grant)**, five **[Doctoral fellowships](https://github.com/protocol/research-grants/tree/master#protocol-labs-doctoral-fellowship)**, and one **[Postdoctoral fellowship](https://github.com/protocol/research-grants/tree/master#protocol-labs-postdoctoral-fellowship)**.

To be notified of future grants, please [subscribe to our newsletter](https://mailchi.mp/protocol/research-newsletter-signup). You can view our current and past grant offerings in our [GitHub repository](https://github.com/protocol/research-grants#protocol-labs-research-grants) or apply for research funding at [grants.protocol.ai](http://grants.protocol.ai).


# RFP-X

## Analyzing and Improving Filecoin's Expected Consensus
### Team:
- [Tong Cao](https://wwwen.uni.lu/snt/people/tong_cao), Kunyao Academy
- Xin Li, Kunyao Academy

**Abstract:** In the past few years, we have witnessed the fast development of blockchains. As more and more communication protocols, voting mechanisms, and cryptographic primitives are involved in building consensus, conducting a formal analysis to evaluate the security and performance of novel consensus is becoming increasingly difficult.

In this project, we aim at providing a comprehensive study on Filecoin’s Expected Consensus (EC). Our objectives are: 1), to deconstruct EC and analyze all sub-protocols of EC theoretically, and then highlight EC’s novelty and dis/advantages; 2), to define EC’s properties regarding to the ledger extension (e.g., chain quality, common prefix, chain growth, and so on); 3), to build the theoretical model and design simulator to evaluate EC’s security and performance; 4), to provide feasible schemes to enhance EC’s security and optimize the transaction throughput.


## Rhizome
### Team:
- [Jacky Zhao](https://github.com/jackyzha0), Verses

**Abstract:** In an ideal world, there is data-neutrality. Much like how net neutrality strives to maintain separation of provider and content markets, data neutrality strives to maintain the separation of data and application markets. Single purpose apps backed by general purpose data. My main research question is about how we can enable data-neutrality on a web dominated by data moats. If we can create separate markets for data and applications, it creates competition based on service quality rather than on data ownership. I’m tentatively calling this project Rhizome, a data-persistence and identity layer for the distributed web. It is made up of two major components:

1. A personal data pod that _you_ own. Think iCloud or Dropbox but you have agency over how much storage you want, who has access to it, and what you want to do with it.
2. A framework for easily developing cohesive peer-to-peer applications on top of data from the previous layer

As a whole, it forms the basis for a model of the internet where people own their own data.

# RFP-011: [Changing the Internet](https://github.com/protocol/research-grants/blob/master/RFPs/rfp-011-changing-the-internet.md)

## Easing Access To Web 3.0 Services

### Team:
- [Scott Shenker](https://www2.eecs.berkeley.edu/Faculty/Homepages/shenker.html), ICSI and UC Berkeley
- [Arvind Krishnamurthy](https://www.cs.washington.edu/people/faculty/arvind), University of Washington
- [James McCauley](https://www.mtholyoke.edu/people/james-mccauley), Mount Holyoke College
- [Aurojit Panda](https://cs.nyu.edu/~apanda/), New York University


# Summer Research Grant

### [Matthew Akamatsu](https://www.biology.washington.edu/people/profile/matthew-akamatsu?qt-related_content=0), University of Washington

### [Yevgeniy Dodis](https://cs.nyu.edu/~dodis/), New York University

**Abstract:** We live in the age where massive amounts of data need to be stored and manipulated efficiently. In particular, it quickly becomes untenable by organizations to store all this data in-house, and they have to increasingly rely on various cloud solutions for data store and access. Additionally, companies must quickly adapt to new technologies, such as the emerging blockchain technology, to keep up with the competition. This creates unprecedented challenges for privacy, security, integrity and availability. For example, since a lot of this data is very sensitive, it must be stored in an encrypted format. Moreover, data often comes from various untrusted sources, and it is paramount that the data integrity is guaranteed, even if the cloud provider colludes with some of the data sources. Finally, especially in the financial sector, data is often subject to various audits and regulations, making it challenging to perform such audits without revealing unnecessary sensitive information about the data. In this proposal we suggest using tools of modern cryptography and algorithm design to address some of these challenges.


# Doctoral Fellowships

### [Abhiram Kothapalli](https://csd.cmu.edu/people/graduate-student/abhiram-kothapalli), Carnegie Mellon University

- **Advisor:** [Bryan Parno](https://www.andrew.cmu.edu/user/bparno/)

**Abstract:** Zero-knowledge proofs are a powerful cryptographic technique for demonstrating the correctness of computations without revealing any secret inputs. Modern applications are beginning to employ recursive zero-knowledge proofs (proofs that demonstrate the existence of other proofs) due to their distinct ability to handle stateful computation with dynamic control flow. For instance, one can efficiently prove large statements such as "the current state of the blockchain is valid" by proving that "there exists a proof for the previous state of the blockchain and the most recent update is valid". However, new challenges arise when reasoning about the security of recursive proofs, which inductively rely on the security of the proofs underlying them. Traditional theoretical frameworks strain to iron out complications that arise in the recursive regime. As such, we are working to develop better frameworks and security models to help design and reason about recursive proofs.

### [Cornelius Ihle](https://gipplab.org/team/cornelius-ihle/), University of Göttingen

- **Advisor:** [Prof. Dr. Bela Gipp](https://gipplab.org/)

**Abstract:** Peer-to-peer networks and applications must provide sufficient privacy to compete with the established client-server model. This project focuses on advancing anonymity for IPFS/Libp2p to protect user privacy. Time-tested anonymity tools like proxy servers or onion routing provide anonymity and plausible deniability, as long as identities are not unmasked. The project aims to reinforce anonymity by preventing the mapping of specific content to user identities. Providing content in IPFS/Libp2p places a provider record at a peer with an ID close to the content’s CID. Theoretically, the peer ID is a pseudonym, and a peer’s identity is not immediately apparent. In practice, a peer ID can be mapped to revealing information like an IP address or revealing content, especially if personal files are pinned and shared. For a system like IPFS, with exbibytes of data, state-of-the-art private information retrieval solutions are unbearable. Fortunately, the linkability of retrieval operations and identity is weaker than in content providing. Theoretically, a peer could generate a new peer ID for every retrieval operation at the cost of high churn. In this project, such methods, tools, and protocol extensions are devised, evaluated, and applied to find effective and efficient solutions for anonymity in IPFS/Libp2p.

### [Ioanna Karantaidou](https://sites.google.com/view/ioannakarantaidou), George Mason University 

- **Advisor:** [Foteini Baldimtsi](https://volgenau.gmu.edu/profiles/foteini)

**Abstract:** In this project we will explore and develop different approaches to the Proof of Storage problem. The currently proposed approach is roughly as follows: after breaking the file into blocks, one can use a Vector Commitment (VC) and prove possession by providing openings to random positions picked by the verifier. The soundness of this approach is relatively low and depends on the number of blocks. Storage of pre-computed proofs is highly possible, as the total number of proofs equals the number of blocks and hitting one of them by random happens with non-negligible probability. Therefore, multiple positions have to be opened.

We propose an alternative approach. Instead of using a VC, one can commit to blocks using an accumulator and prove membership/non-membership of random blocks picked by the verifier. We believe that this solution can lead to better soundness with less queries. However, as such an approach is expected to be computationally heavy for the prover, as part of this project we will explore solutions with trade-offs between storage and computation that come with rigorous soundness guarantees.

### [Simona Ramos](https://www.linkedin.com/in/simona-ramos-50834ba6/), Universitat Pompeu Fabra

- **Advisor:** [Vanesa Daza](https://www.upf.edu/web/vanesa-daza)

**Abstract:** With this research we aim to suggest a shift from traditionally centralized markets to a decentralized (blockchain-based) economy of community shared infrastructure and peer-to-peer services for Distributed Power Systems for small to medium size communities. We believe this to be a two-fold solution for mitigating the high socio-economic impact of increasing energy prices and fostering environmental sustainability. Alluding to the concept of ‘social energy’ - as a system run by and for the community, we propose to use a multidisciplinary perspective that merges economic governance theories with the technological affordances of blockchain technology - to model a community that uses a blockchain-based platform to produce, use and govern a decentralized and distributed energy system. To do so, we aim to explore the opportunities and constraints of application of blockchain (as a governance tool) for the migration of traditionally centralized markets into blockchains based horizontal systems while avoiding over-exploitation and/or under-provision of resources. In addition, we aim to apply Commons based economic theories to explore bottom-up economic governance structures across multiagent systems that can foster decentralization of blockchains in the long run. Overall, we hope that our research will facilitate the implementation of new blockchain projects specifically designed to support peer-to-peer production in (commons-oriented) communities, while fostering socio-economic policies in direction towards decentralization.

### [Weijie Wang](https://cpsc.yale.edu/people/weijie-wang), Yale University

- **Advisor:** [Charalampos Papamanthou](https://www.cs.yale.edu/homes/cpap/)

**Abstract:** A vector commitment (VC) allows one to commit to a vector of n positions so that later verifiable openings to a particular set of positions can be performed. We propose to construct a new maintainable vector commitment with aggregation algorithms that do not require black-box use of argument systems. Our initial work, supported by Protocol Labs, is a compiler that transforms an existing VC scheme with efficient aggregation to another one that balances update and query costs, while maintaining efficient aggregation. The main challenge of this method is that the update complexity is still large, compared with state-of-the-art maintainable vector commitments. With the help of the fellowship, we plan to work on aggregating maintainable log-size individual proofs such as AMT proofs in order to reduce update costs. We also plan to explore some other log-size aggregated proofs with different structures, such as ones based on lattices.


# Postdoctoral Fellowships

### [Kelsey Melissaris](https://www.kelseymelissaris.com/), PhD, The City University of New York

- **PI:** [Claudio Orlandi](https://cs.au.dk/~orlandi/), Aarhus University

**Abstract:** Proxy cryptography provides a method by which one party, the delegator, can securely delegate cryptographic tasks requiring a secret key to another party, the delegatee. A proxy re-encryption scheme enables the delegator to derive a key for a designated third party, the proxy, that can translate any ciphertext encrypted to the delegator into a ciphertext encrypted to the delegatee. Similarly, a proxy re-signature scheme enables the proxy to transform the delegatee’s signature into the delegator’s signature. All parties involved are mutually distrustful so these computations must be securely performed in a way that preserves privacy for each party.

Many proxy protocols have been proposed for both encryption and signature schemes from various assumptions but existing protocols do not enable fully flexible delegation. The proposed research generalizes the existing primitives of proxy re-encryption and re-signatures to the witness-based setting, specifically witness encryption and signatures of knowledge. In this setting NP statements replace public keys and witnesses to those statements function as secret keys. The proposed research will be the most general and flexible method for fine-grained delegation of these tasks and has applications in smart contracts, sharing encrypted outsourced data, updating encryption to comply with changing standards, and distributed signing protocols.


# Congratulations!

PL Research is excited to support these talented researchers as they continue driving progress in tandem with Protocol Labs. To learn more about our grant offerings visit our [grants repo](https://github.com/protocol/research-grants), and you can apply for funding at https://grants.protocol.ai/. Please reach out to research-grants@protocol.ai with any questions or feedback.

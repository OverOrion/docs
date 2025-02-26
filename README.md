# 1 Introduction

### Short Intro

Integritee is a highly scalable, privacy-enabling network in the Polkadot ecosystem with parachains on Polkadot and Kusama. We seek to become the leading Web3 privacy solution - a blockchain network for developers and relevant to enterprises to build (decentralized) applications that benefit from unrivaled speed, verifiable confidentiality/privacy, and interoperability. At scale.

Our solution combines the security and trust of Polkadot, the scalability of second-layer solutions, and the confidentiality of Trusted Execution Environments (TEEs) - a special-purpose hardware inside which computations run securely, confidentially, and verifiably. Our technology is relevant to both Web3 developers and enterprises who would like to benefit from verifiable privacy and public auditability.

For Web3 developers, we offer powerful tools to build strong decentralized solutions for multiple use cases: From decentralized gaming providers who require low latencies and scalability to compete with traditional gaming, to decentralized exchanges (DEXs) wanting to avoid front-running, and identity protocols seeking to keep sensitive information private, the scope is ample. Integritee also bridges the gap between Web3 and Web2 with a trusted oracle framework to ensure interoperability with real-world data.

Through our technology, we solve pressing challenges that blockchain solutions currently face, namely performance, privacy, scalability issues, and a lack of interoperability. While this enhanced blockchain value proposition is highly relevant to Web3 projects seeking to overcome these challenges, we truly believe that we can greatly increase blockchain adoption also for enterprise stakeholders by enabling totally new and improved use cases for decentralized applications.

Apart from our strong Web3 value proposition, enterprises can leverage our unique solution for verifiable privacy and public auditability. Data is processed and applications run in a secure TEE. The integrity and genuineness of the TEE and the hash of the binary it is executing are subsequently verified and a respective proof registered on our public ledger, making it transparent to any third party. This combination of verifiable privacy and public auditability provides a significant benefit, e.g., for institutions that want to prove data security and sovereignty to their customers or in case of data sharing collaborations between multiple parties.

### Overview

In the following chapters, we will offer insight into the fundamentals of the Integritee network, and its benefits for developers, companies, and users. We will also highlight and explain our main goals.

Further down, you will find Dev and DevOps-oriented content to guide those who wish to build on our platform.



### **Table of Contents**

* [1 Introduction](https://app.gitbook.com/o/IfmmCiczozKCKDF9gzvK/s/qncIgZuFR1dSzRfnz9LM/)
* [2 Integritee Network](2-integritee-network/)
  * [2.1 What is the function of the Integritee network?](2-integritee-network/2.1-what-is-the-function-of-the-integritee-network/)
    * [2.1.1 A public registry of remote attestation](2-integritee-network/2.1-what-is-the-function-of-the-integritee-network/2.1.1-a-public-registry-of-remote-attestation.md)
    * [2.1.2 Why not just use the Intel Attestation Service (IAS)?](2-integritee-network/2.1-what-is-the-function-of-the-integritee-network/2.1.2-why-not-just-use-the-intel-attestation-service-ias.md)
  * [2.2 Polkadot](2-integritee-network/2.2-polkadot/)
    * [2.2.1 Shared security for parachains](2-integritee-network/2.2-polkadot/2.2.1-shared-security-for-parachains.md)
    * [2.2.2 Auctions](2-integritee-network/2.2-polkadot/2.2.2-auctions.md)
    * [2.2.3 Slot Lease periods](2-integritee-network/2.2-polkadot/2.2.3-slot-lease-periods.md)
    * [2.2.4 Crowdloans](2-integritee-network/2.2-polkadot/2.2.4-crowdloan.md)
  * [2.3 Integritee Network Architecture](2-integritee-network/2.3-integritee-network-architecture.md)
  * [2.4 TEER token](2-integritee-network/2.4-teer-token/)
    * [2.4.1 How to Set Up a Wallet](2-integritee-network/2.4-teer-token/2.4.1-how-to-set-up-a-wallet.md)
    * [2.4.2 Which wallets are supported?](2-integritee-network/2.4-teer-token/2.4.2-which-wallets-are-supported.md)
    * [2.4.3 How to get TEER ?](2-integritee-network/2.4-teer-token/2.4.3-how-to-get-teer.md)
    * [2.4.4 How to check the transaction history?](2-integritee-network/2.4-teer-token/2.4.4-how-to-check-the-transaction-history.md)
    * [2.4.5 Tokenomics](2-integritee-network/2.4-teer-token/2.4.5-tokenomics.md)
  * [2.5 Governance](2-integritee-network/2.5-governance/)
    * [2.5.1 Council](2-integritee-network/2.5-governance/2.5.1-council.md)
    * [2.5.2 Technical Committee](2-integritee-network/2.5-governance/2.5.2-technical-committee.md)
    * [2.5.3 Treasury](2-integritee-network/2.5-governance/2.5.3-treasury.md)
    * [2.5.4 Democracy](2-integritee-network/2.5-governance/2.5.4-democracy.md)
  * [2.6 Infrastructure](2-integritee-network/2.6-infrastructure/)
    * [2.6.1 What are Collators and who runs them?](2-integritee-network/2.6-infrastructure/2.6.1-what-are-collators-and-who-runs-them.md)
    * [2.6.2 What are Sidechain Validators?](2-integritee-network/2.6-infrastructure/2.6.2-what-are-sidechain-validators.md)
  * [2.7 Privacy Technology: Trusted Execution Environments](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/)
    * [2.7.1 What is a TEE?](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.1-what-is-a-tee.md)
    * [2.7.2 What is remote attestation?](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.2-what-is-remote-attestation.md)
    * [2.7.3 How we use the technology to make confidential computation publicly verifiable](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.3-how-we-use-the-technology-to-make-confidential-computation-publicly-verifiable.md)
    * [2.7.4 Intel SGX](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.4.-intel-sgx/)
      * [2.7.4.1 Why SGX and not other technologies](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.4.-intel-sgx/2.7.4.1-why-sgx-and-not-other-technologies.md)
      * [2.7.4.2 Intel SGX Security Design](2-integritee-network/2.7-privacy-technology-trusted-execution-environments/2.7.4.-intel-sgx/2.7.4.2-intel-sgx-security-design.md)
  * [2.8 History](2-integritee-network/2.8-history.md)
  * [2.9 Roadmap](2-integritee-network/2.9-roadmap.md)
* [3 Our Technology](3-our-technology/)
  * [3.1 Software Development Kit](3-our-technology/3.1-software-development-kit/)
    * [3.1.1 Sidechains](3-our-technology/3.1-software-development-kit/3.1.1-sidechains.md)
    * [3.1.2 Trusted Off-Chain Computing](3-our-technology/3.1-software-development-kit/3.1.2-trusted-off-chain-computing.md)
    * [3.1.3 Oracle Framework](3-our-technology/3.1-software-development-kit/3.1.3-oracle-framework.md)
  * [3.2 Attesteer](3-our-technology/3.2-attesteer.md)
  * [3.3 Deployment Options](3-our-technology/3.3-deployment-options.md)
  * [3.4 Scalable Secure Kubernetes Cluster for TEEs](3-our-technology/3.4-scalable-secure-kubernetes-cluster-for-tees.md)
  * [3.5 Use cases](3-our-technology/3.5-use-cases/)
    * [3.5.1 Sidechains](3-our-technology/3.5-use-cases/3.5.1-sidechains.md)
    * [3.5.2 Trusted Off-Chain Computing](3-our-technology/3.5-use-cases/3.5.2-trusted-off-chain-computing.md)
    * [3.5.3 TEEracle - Oracle Framework](3-our-technology/3.5-use-cases/3.5.3-teeracle-oracle-framework.md)
    * [3.5.4 Attesteer](3-our-technology/3.5-use-cases/3.5.4-attesteer.md)
* [4 Development](4-development/)
  * [4.1 High-level overview of components](4-development/4.1-high-level-overview-of-repositories.md)
  * [4.2 SDK Versioning](4-development/4.2-sdk-versioning.md)
  * [4.3 Design](4-development/4.3-design/)
    * [4.3.1 L2 Sidechain](4-development/4.3-design/4.3.1-l2-sidechain/)
      * [4.3.1.1 Motivation & Introduction](4-development/4.3-design/4.3.1-l2-sidechain/4.3.2.1-motivation-and-introduction.md)
      * [4.3.1.2 Multi-validateer setup](4-development/4.3-design/4.3.1-l2-sidechain/4.3.2.2-multi-validateer-setup.md)
      * [4.3.1.3 Block production](4-development/4.3-design/4.3.1-l2-sidechain/4.3.2.3-block-production.md)
      * [4.3.1.4 Validateer components](4-development/4.3-design/4.3.1-l2-sidechain/4.3.2.4-validateer-components.md)
      * [4.3.1.5 On-boarding of new validateers](4-development/4.3-design/4.3.1-l2-sidechain/4.3.2.5-on-boarding-of-new-validateers.md)
    * [4.3.2 System and Networking Overview](4-development/4.3-design/4.3.2-system-and-networking-overview.md)
  * [4.4 SDK](4-development/4.4-sdk/)
    * [4.4.1 Sidechain SDK](4-development/4.4-sdk/4.4.1-sidechain-sdk.md)
    * [4.4.2 Trusted Off-chain Worker](4-development/4.4-sdk/4.4.2-trusted-off-chain-worker.md)
    * [4.4.3 TEEracle - Oracle Framework](4-development/4.4-sdk/4.4.3-teeracle-oracle-framework.md)
    * [4.4.4 Custom Business Logic / STF](4-development/4.4-sdk/4.4.4-custom-business-logic-stf/)
      * [4.4.4.1 Example: Encointer](4-development/4.4-sdk/4.4.4-custom-business-logic-stf/4.4.4.1-example-encointer.md)
    * [4.4.5 How To Access On-chain Storage](4-development/4.4-sdk/4.4.5-how-to-access-l1-parentchain-storage.md)
    * [4.4.6 RPC Interface](4-development/4.4-sdk/4.4.6-rpc-interface.md)
    * [4.4.7 Integritee Parachain Integration](4-development/4.4-sdk/4.4.7-integritee-parachain-integration.md)
  * [4.5 Attesteer](4-development/4.5-attesteer.md)
  * [4.6 Demos](4-development/4.6-demos/)
    * [4.6.1 Sidechain demo](4-development/4.6-demos/4.6.1-sidechain-demo.md)
    * [4.6.2 TOCW demo](4-development/4.6-demos/4.6.2-tocw-demo.md)
    * [4.6.3 TEEracle demo](4-development/4.6-demos/4.6.3-teeracle-demo.md)
    * [4.6.4 Attesteer demo](4-development/4.6-demos/4.6.4-attesteer-demo.md)
  * [4.7  Performance Benchmarking](4-development/4.7-performance-benchmarking.md)
  * [4.8 Hardware Diversification](4-development/4.8-hardware-diversification/)
    * [4.8.1 Distributor-Level Remote Attestation](4-development/4.8-hardware-diversification/4.8.1.-distributor-level-remote-attestation.md)
    * [4.8.2 Concept](4-development/4.8-hardware-diversification/4.8.2-concept.md)
    * [4.8.3 Roles](4-development/4.8-hardware-diversification/4.8.3-roles/)
      * [4.8.3.1 Hardware Manufacturer](4-development/4.8-hardware-diversification/4.8.3-roles/4.8.3.1-hardware-manufacture.md)
      * [4.8.3.2 Trusted Software Source](4-development/4.8-hardware-diversification/4.8.3-roles/4.8.3.2-trusted-software-source.md)
      * [4.8.3.3 Provision Entity](4-development/4.8-hardware-diversification/4.8.3-roles/4.8.3.3-provision-entity.md)
      * [4.8.3.4 Member](4-development/4.8-hardware-diversification/4.8.3-roles/4.8.3.4-member.md)
      * [4.8.3.5 Verifier](4-development/4.8-hardware-diversification/4.8.3-roles/4.8.3.5-verifier.md)
* [5 Nodes & Infrastructure](5-nodes-and-infrastructure/)
  * [5.1 How to set up and run Integritee Nodes](5-nodes-and-infrastructure/5.1-how-to-set-up-and-run-integritee-network-nodes/)
    * [5.1.1 Full Node](5-nodes-and-infrastructure/5.1-how-to-set-up-and-run-integritee-network-nodes/5.1.1-full-node/)
      * [5.1.1.1 Parachain on Kusama](5-nodes-and-infrastructure/5.1-how-to-set-up-and-run-integritee-network-nodes/5.1.1-full-node/5.1.1.1-parachain-on-kusama.md)
      * [5.1.1.2 Parachain on Polkadot](5-nodes-and-infrastructure/5.1-how-to-set-up-and-run-integritee-network-nodes/5.1.1-full-node/5.1.1.2-parachain-on-polkadot.md)
    * [5.1.2 Collator Node](5-nodes-and-infrastructure/5.1-how-to-set-up-and-run-integritee-network-nodes/5.1.2-collator-node.md)
  * [5.2 How to set up and run a Sidechain Validator Node](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/)
    * [5.2.1 Hardware Requirements](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.1-hardware-requirements.md)
    * [5.2.2 Intel SGX Licences](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.2-intel-sgx-licences.md)
    * [5.2.3 Software requirements](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.3-software-requirements/)
      * [5.2.3.1 Ansible](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.3-software-requirements/5.2.3.1-ansible.md)
      * [5.2.3.2 Docker](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.3-software-requirements/5.2.3.2-docker.md)
      * [5.2.3.3 Enabling SGX Hardware support in Docker](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.3-software-requirements/5.2.3.3-enabling-sgx-hardware-support-in-docker.md)
    * [5.2.4 Build the binaries](5-nodes-and-infrastructure/5.2-how-to-set-up-and-run-a-sidechain-or-tocw-node/5.2.4-build-the-binaries.md)
  * [5.3 How to deploy](5-nodes-and-infrastructure/5.3-how-to-deploy/)
    * [5.3.1 Why deploy on Integritee Network](5-nodes-and-infrastructure/5.3-how-to-deploy/5.3.1-why-deploy-on-integritee-network.md)
    * [5.3.2 Why use bare-metal cloud for TEE instances?](5-nodes-and-infrastructure/5.3-how-to-deploy/5.3.2-why-use-bare-metal-cloud-for-tee-instances.md)
    * [5.3.3 Securitee Offering](5-nodes-and-infrastructure/5.3-how-to-deploy/5.3.3-securitee-offering.md)
  * [6. Misc](6-misc/)
    * [6.1 Glossary](6-misc/6.1-glossary.md)
    * [6.2 Visual Materials](6-misc/6.2-visual-materials.md)
    * [6.3 Community Info & Links](6-misc/6.3-community-info-and-links.md)

&#x20;

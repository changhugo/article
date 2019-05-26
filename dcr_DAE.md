# Decred as a DAE Infrastructure Provider

![logo](img/header.png )

This article is a follow up on the [2108 Decred roadmap](https://blog.decred.org/2018/02/28/2018-Decred-Roadmap/) in which Decentralized Autonomous Entities (DAE) was mentioned. I am not a developer, so there could be many factual errors in this article, but I hope to spark discussions by describing how I think Decred can evolve. If my envisioning future is feasible, there will be massive demand to use the Decred blockchain, and will further establish Decred as a superior store of value (SoV).

Decred was created to be a better version of Bitcoin, and this vision can be ultimately realized by setting up an ecosystem that allows the creation of DAEs on the Decred blockchain. Such an ecosystem can be used to store value, make payment and co-ordinate workforces. To realize such a vision, Decred has to first completely transform itself into a DAE and set as an example to convince people the value of such an innovative organizational structure. At this moment, Decred is the most successful project working towards this goal. The recently passed proposal to [decentralize treasury spending](https://proposals.decred.org/proposals/c96290a2478d0a1916284438ea2c59a1215fe768a87648d04d45f6b7ecb82c3f) is a key step towards a DAE. After the proposal is implemented, Decred would be the first DAE working prototype. 

 ### Decred as a true DAE
After being established as a DAE prototype, Decred still has some items to implement to become a true DAE that I envision:
1. After each proposal is approved, there needs to be a system to track implementation status.  It can be an extension of the [contractor management system](https://github.com/decred/contractor-mgmt) (CMS) that helps the community to easily track project status. Such a system will serve as the foundation of budget planning.
2. [Decentralizing treasury spending]((https://proposals.decred.org/proposals/c96290a2478d0a1916284438ea2c59a1215fe768a87648d04d45f6b7ecb82c3f)) has to be implemented.
3. We need to create a special kind of address that can only be spent by a smart contract controlled by Politeia. I call this new address as “treasury address”, which I will explain later. 
4. We need to make sure [VSPs](https://docs.decred.org/faq/proof-of-stake/voting-service-providers/) are not allowed to change the votes selected by PoS stakers.  This can further decentralize Decred and protect the system against attacks. 
5. We need to further decentralize Politeia by setting up multiple instances that are managed by different contractors who govern each other. Decentralizing Politeia can make sure there is no single point of failure. 3-5 Politeia operators can be elected by stakeholders and they will be funded by the treasury. 

### Decred as a DAE Infrastructure Provider
After Decred becomes a true DAO/DAE, the next step is to help other suitable organizations to transform into DAE. Which organizations are suitable DAE candidates? Charities, NGOs, and non-profit organizations. These entities do not compete for profits, so they can afford to be less efficient. In contrast, openness, transparency, and fairness are much more important. A DAE structure can effectively help these non-profit entities to save operational expenses associated with keeping themselves transparent and to enable a global team structure that can easily scale.

### DAE built on Decred
We can develop an open source DAE module based on the Decred system to help organizations transform to DAE. It doesn’t make sense for these organizations to create their own blockchains because of the huge overhead associated with maintaining a blockchain. What they need is a DAE token system that can be anchored on a secure and permissionless blockchain, such as Decred. 

Decred can potentially allow the creation of DAE tokens based on OP_Return. A set of DAE tokens is needed for each DAE, and they are solely used as vehicles for voting within the DAE. DAE tokens are needed because DCR is a store of value, not an utility token. The amount of DAE token a person owns is directly proportional to his/her voice in the DAE. Each DAE will operate its own proposal system similar to Politeia. Decisions making and treasury management will be done in a transparent and decentralized manner similar to how Decred operates. 

The creation of a new DAE can be done by depositing DCR funds of the DAE into a Decred treasury address. The treasury address is responsible for managing funds for the DAE, and it does not have a seed phrase so that it cannot be restored by any wallet. The only way to spend from the treasury address is through a smart contract that is controlled by the proposal system. After depositing DCR into the treasury address, a new set of DAE tokens will be created, and employees of the DAE can earn DAE tokens based on their contributions to the DAE. Contractors of the DAE can vote through a DAE token wallet similar to Decrediton.   

A human resource system similar to the Decred Contractor Management System (CMS) will also be needed. Each DAE will need their own contractor clearance process based on their needs. We can integrate token incentive and punishment as part of the clearance process to ensure the quality of contractors. For example, 3 existing contractors can lock up numerous DAE tokens as collateral to approve a new person to join the DAE as a contractor. The collateral will be unlocked with some extra tokens as reward after the new contractor completes work that earns DAE token. On the other hand, the collateral will be taken away if the new contractor is kicked out from the DAE for whatever reasons supported by other 5 contractors. 

After a contractor has completed work contributing to the DAE, he/she can submit invoices to the CMS and claim DCR rewards. All invoices will be aggregated into a treasury spend proposal on the proposal system for every contractor to vote using their DAE tokens. If the proposal is approved, a smart contract is triggered to pay contractors DCRs from the treasury address. 

### Benefits to the Decred ecosystem
This use case of Decred serving as a DAE infrastructure provider (DIP) has multiple benefits.
1. Strengthen DCR's store of value property because non-profits entities would need to store their funds in DCR in order to use the Decred blockchain to create a DAE. 
2. Create demand to use the Decred blockchain because DAE's transactions will be stored on the Decred blockchain. This will certainly increase Decred's network value.
3. Consistent with Decred's current roadmap. The two major projects on the horizon are decentralizing treasury spending and the [DEX](https://blog.decred.org/2018/06/05/A-New-Kind-of-DEX/). The former is the prerequisite for Decred to become a DIP, and the later will greatly help providing liquidity for DAE to acquire DCR to store value.

### Discussions are welcomed
This article is written solely to encourage discussions around the possibility of Decred serving as the leader to provide infrastructure for DAE. This is a future I envision for Decred, but I would not be surprised if Decred takes a different route if stakeholders have something else in mind. The reason why I hold Decred is the possibility of stakeholders to shape the future of the project, which is not possible elsewhere. I had lengthy discussions with the Chinese community, and I hope to engage in discussions with the rest of the community.



Arthor: neil_nie <br/>
Editor & Translator: changhugo <br/>
[Original article](https://blog.dcrclub.org/chapter_05/dcr_DAE.html) 
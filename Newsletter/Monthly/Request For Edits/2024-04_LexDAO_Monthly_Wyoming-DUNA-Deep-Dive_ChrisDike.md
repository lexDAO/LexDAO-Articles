# A Deep Dive into the Wyoming DUNA
## Introduction
> DAOs are to Corporations what Democracy was to Monarchy — Paulo Fonseca.[1][1]

[Decentralized Autonomous Organizations (DAOs)](https://ethereum.org/en/dao/) are web3 primitives that enables people to coordinate towards a common purpose without a [centralized](https://www.blockchain-council.org/blockchain/decentralized-vs-centralized/) governance structure. However, in order for DAOs to thrive in the real world, they require a legal structure (or “[wrapper](https://docs.daobox.io/dao-legal-wrapper-design-and-creation/legal-wrappers-for-daos-definition-types-jurisdictions-and-use-cases)”) that cements their legitimacy.

This article is a dive into the Decentralized Unincorporated Nonprofit Association (DUNA), a DAO-specific legal structure established by the state of Wyoming.

We cover why DAOs may need a legal structure and more importantly, a DAO-specific one. We examine the traditional legal structures adopted by DAOs, alongside previous attempts at creating a DAO-specific legal structure. Finally, we take a closer look at the DUNA, its features, how it compares with traditional legal wrappers, and its potential advantages and disadvantages.

## What is the Need for DAO-Specific Legal Structures?
To understand why DAOs require DAO-specific legal structures or legal structures at all, it is necessary to first of all understand three key challenges faced by DAOs:

* **Legal Personhood**: A DAO needs a legal structure in order to become a legal entity and gain [legal personhood](https://en.wikipedia.org/wiki/Corporate_personhood). Without a legal existence, a DAO cannot enter into contracts, own property, sue persons in its own name, and exercise other legal rights.

* **Tax/Regulatory Compliance**: Without a legal existence, a DAO has no ability to pay taxes or effectively comply with regulations. Further, a DAO may be ascribed a structure by a court or regulator and then be determined to have failed to comply or pay appropriate taxes as in the case of [Ooki DAO](https://www.cftc.gov/PressRoom/PressReleases/8715-23).

* **Limited Liability of Members**: A legal existence allows a DAO to become separate from its members so that their personal liability in relation to debts and obligations of the DAO and judgments against the DAO can be [limited](https://www.sumup.com/en-gb/invoices/dictionary/limited-liability/).

DAOs generally address these challenges in three ways:
1. **Entityless structure**: Many DAOs operate without any legal structure or as a non-legal entity. Not adopting any structure can leave DAOs exposed to all three of the aforementioned challenges.

2. **"Partially Wrapped"**: DAOs have been known to, and may utilize development companies, "SPV" (Single/Special Purpose Vehicle) entities, trusts, and other forms to separately partially "wrap" portions of the DAO, holdings, or DAO functions. This can allow for "tax advantage" and tailored liability limitation, but can require significant legal engineering and administrative work, in addition to adding layers of complexity and frustrating DAO transparency.

3. **"Fully Wrapped"**: This entails adopting an established legal structures that confer DAOs with legal existence. These structures range from US structures such as the [Corporation](https://corporatefinanceinstitute.com/resources/accounting/what-is-corporation-overview/), [Unincorporated Nonprofit Associations (UNAs)](https://ballotpedia.org/Unincorporated_nonprofit_association), and [Limited Liability Companies (LLCs)](https://www.nolo.com/legal-encyclopedia/what-is-a-limited-liability-company.html), to slightly more exotic offshore options including the Marshall Islands DAO LLC, Cayman and Panama foundation structures, the Guernsey trust, and others. Perhaps the most vaunted is the ["Cayman Sandwich"](https://blogs.law.ox.ac.uk/oblb/blog-post/2023/11/venture-capital-latin-america-critical-look-cayman-sandwich-structure). The Foundation structure combines features of a corporation and a Trust and provides DAOs with several benefits: legal existence, limited liability for members, the ability to engage in profit and nonprofit activities, and even no taxes. 

While DAOs can adopt any one or combination of these legal entity structures, there is no one-size fits all solution, and adopting any structure may lead to additional required human input, complexity, cost, and uncertainty for DAOs in terms of reporting requirements and tax/regulatory compliance. Most of these legal structures are not DAO-specific and the legislation allowing them and case law guiding how the laws apply to them does not envision their use in web3. 

## What were Previous Attempts at Creating DAO-Specific Legal Structures?
### DAO LLCs
In the US, prior to the DUNA, a few versions of the DAO LLC have been the only significant attempt at creating a legal structure tailored for DAOs.

A [limited liability company (LLC)](https://www.nolo.com/legal-encyclopedia/what-is-a-limited-liability-company.html) is similar to a corporation in the sense that it establishes a business as a separate legal entity, thereby shielding its members from personal liability for the business. However, like an unincorporated entity, an LLC can act as a [pass-through entity](https://www.nolo.com/legal-encyclopedia/should-you-form-a-pass-through-entity.html) for tax purposes. The profits of an LLC may be [attributed](https://www.wolterskluwer.com/en/expert-insights/how-are-profits-split-in-an-llc) to its members who are then individually taxed, with the LLC itself not being taxable. The laws of certain jurisdictions allow DAOs to adopt the LLC structure, with some additional features. Under [Wyoming’s DAO Supplement](https://sos.wyo.gov/Forms/WyoBiz/DAO_Supplement.pdf), in addition to the general LLC features, DAO LLCs cannot not be [manager-managed](https://www.nolo.com/legal-encyclopedia/member-managed-llcs-versus-manager-managed-llcs.html), and the [fiduciary duties](https://uk.practicallaw.thomsonreuters.com/1-107-5744?transitionType=Default&contextData=(sc.Default)&firstPage=true) of members to the DAO can be waived. DAO LLCs and their equivalents are similarly available under the laws of [Tennessee](https://www.capitol.tn.gov/Bills/112/Amend/HA0748.pdf), [Utah](https://le.utah.gov/~2023/bills/static/HB0357.html#48-5-406), [Vermont](https://legislature.vermont.gov/statutes/section/11/025/04173) and [Marshall Islands](https://rmiparliament.org/cms/images/LEGISLATION/PRINCIPAL/202/2022-050/DecentralizedAutonomousOrganizationAct2022_1.pdf).  

The DAO LLC structure, despite representing a forward leap in DAO-specific legislation, has garnered little adoption. The structures have been [criticized](https://substack.com/inbox/post/38187682) [repeatedly](https://thedefiant.io/news/research-and-opinion/starting-a-dao-in-the-usa-steer-clear-of-dao-legislation) because of the tradeoffs it requires of DAOs and its general lack of suitability to DAO operations. Pass-through taxation, paperwork requirements, restrictions on manager-management, and the requirement of state representatives are all features of DAO LLCs that are considered to be against the notions of pseudonymity and flexibility that are fundamental to DAOs. They also appear to offer little to no benefit over non-DAO LLCs and impose additional restrictions.

## What is a DUNA?
A Decentralized Unincorporated Nonprofit Association (DUNA) is a type of legal structure specifically designed for DAOs. DUNAs are established under [Wyoming’s DUNA Act](https://www.wyoleg.gov/Legislation/2024/SF0050) which comes into effect on July 1, 2024. It represents the most recent leap towards creating a DAO-specific legal structure.  While the DUNA idea may seem novel, we here at LexDAO think there may be a better name, and we would like to take at least a little bit of credit for [pushing the idea forward](https://hackmd.io/@lex-dao/tuna-aug2022). Regardless, we still prefer the name DUNA to what the Wyoming Legislature appears to be supporting in its [titling](https://www.wyoleg.gov/Legislation/2024/SF0050) of the act "Unincorporated Non-Profit DAOs" which clearly would be abbreviated "UNDAOs".

DUNAs are an iteration of [UNAs](https://www.uniformlaws.org/committees/community-home?CommunityKey=40227d3a-8b5d-47c2-8cd0-b0ec12da97f9) with slight modifications tailored to DAOs. The DUNA, as currently written, mostly envisions a "Protocol DAO", and DAO focused around a single protocol or set of dApps (Decentralized Applications).

## What are the Key Features of a DUNA?
Pursuant to the Wyoming DUNA Act, DUNAs are legal entities with the following features and structure:
* **Separate Legal Entity**: DUNAs provide DAOs with legal existence, allowing them to exercise rights as a legal entity.[17-32-105](https://www.wyoleg.gov/Legislation/2024/SF0050);[108](https://www.wyoleg.gov/Legislation/2024/SF0050). Importantly, this enables DAOs to comply with tax and regulatory requirements. 

* **Limited Liability**: As a separate legal entity, a DUNA is distinct from its members. Therefore, the members of a DAO under the DUNA structure cannot be held liable for the actions of the DAO. [17-32-107](https://www.wyoleg.gov/Legislation/2024/SF0050). This protection also extends to persons who are authorized to manage certain affairs of the DAO, referred to as Administrators. [17-32-102(a)(i)](https://www.wyoleg.gov/Legislation/2024/SF0050).

* **Nonprofit Purpose**: DUNAs are [nonprofit organizations](https://corporatefinanceinstitute.com/resources/management/npo-non-profit-organization/). This means that they must possess a nonprofit purpose.[17-32-104(a)](https://www.wyoleg.gov/Legislation/2024/SF0050). This conveniently aligns with the ethos of many DAOs who set out to promote [public goods](https://support.gitcoin.co/gitcoin-knowledge-base/gitcoin-grants/general-questions/what-are-public-goods) or benefits. The specific purpose(s) of a DUNA is governed by its Governing principles. [17-32-102(a)(vii)](https://www.wyoleg.gov/Legislation/2024/SF0050). This is distinct from IRS designations of nonprofit ([26 CFR 1.501](https://www.ecfr.gov/current/title-26/chapter-I/subchapter-A/part-1/subject-group-ECFR062882ac6495890/section-1.501(c)(3)-1)), in that a DUNA does not necessarily need to qualify for 501c nonprofit taxation status, but there is significant overlap.

* **Distribution of Profits**: Despite their nonprofit status, and similar to UNAs, DUNAs can engage in profit-making activities to the extent that its profits are channeled into its nonprofit purpose. As a result, DAOs cannot distribute profits to members under the DUNA structure. However, DAOs can pay “reasonable compensation” to members, administrators or third parties for services rendered. [17-32-104(c)(i)](https://www.wyoleg.gov/Legislation/2024/SF0050). “Services” is not exhaustively defined in the DUNA Act and can range from voting on governance proposals to general participation in DAO activities. Profits can also be distributed to members in conformity with the DAO's nonprofit purpose. [17-32-104(c)(ii)](https://www.wyoleg.gov/Legislation/2024/SF0050). Both these provisions have a broad interpretation to the advantage of DAOs, as the Act fails to provide any strict definitions. DAOs can potentially leverage these provisions to effectively distribute profits to its members. This transforms what appears to be one of the loopholes of the Act into one of its more appealing features.

* **Governing Principles**: As [articles](https://corporatefinanceinstitute.com/resources/equities/articles-of-association/) are to a corporation, Governing principles are to a DUNA. The Governing principles govern the purpose, operations, rights, duties in a DUNA. It is determined by the members, it doesn’t need to be contained in a single document and can be implied from practice. This is suitable to the modus operandi of DAOs who make operational decisions through governance proposals, forums, and discord channels. It allows DAOs operational flexibility without the hassle of formal documentation. [17-32-102(a)(vii)](https://www.wyoleg.gov/Legislation/2024/SF0050).

* **Management Structure**: As [Directors](https://www.cgincorporations.com/blog/what-is-a-company-director/) are to a corporation, Administrators are to DUNAs, with the major difference being that Administrators are optional in DUNAs.[17-32-123](https://www.wyoleg.gov/Legislation/2024/SF0050). Otherwise, members generally drive the operations of a DUNA.


## What Gives DUNAs an Edge Over Other Legal Structures?
### DUNAs vs The Corporation
Corporations require a centralized management body with fiduciary duties (i.e. Directors). This is antithetical to the “D” in “DAO”. Only Administrators come close to resembling Directors in a DUNA, and even so, the use of Administrators is merely optional. Additionally, DUNAs are largely free from the burdensome compliance procedures that corporations are subject to, allowing them a great deal of flexibility.

### DUNAs vs Foundations
Foundations require governance bodies such as a Board of Directors, Foundation Council or Guardians. This compromises decentralization for DAOs. There is no required governance body for a DUNA. Furthermore, setting up and maintaining offshore Foundations is expensive and requires filings - the opposite is true for DUNAs.

### DUNAs vs UNAs
DUNAs are quite literally decentralized UNAs. A DUNA being a DAO-specific legal structure may make it better for a DAO than the ordinary UNA structure. This is because tailored legislation provides DAOs with clarity and allows for unique interpretation of rules with the legislature showing clear intention to create special categorization and rules.  

### DUNAs vs DAO LLCs
DAO LLCs can distribute profits to members while DUNAs cannot. However, DUNAs can compensate members, and the language and provisions of the DUNA Act is sufficiently wide enough to allow this to be done to a great degree. Additionally, membership arrangements (regarding transfer of rights, admission, removal, etc.) are flexible in a DUNA with no paperwork or filing requirements. A DUNA may align much better with the decentralized ethos of DAOs. Also, DUNAs are not currently required to report under the Corporate Transparency Act.

## What are the Pros and Cons of DUNAs?
### Pros
* **Decentralization**: DUNAs offer a way for DAOs to gain legal existence without compromising on decentralization and autonomy. DUNAs do not envisage a centralized management structure and it is up completely up to its members to steer the operations of the DUNA by defining its governing principles.

* **Regulatory Certainty**: By bringing DAOs under the laws of a state, the DUNA structure provides much-needed regulatory clarity and certainty. This is especially beneficial for DAOs that interact with the US economy. This approach may be superior to adopting offshoring strategies (such as the Foundation structure) which can ultimately expose DAOs to US laws and unforeseen legal challenges. 

* **Simplicity**: When compared to other legal entity structures, DUNAs are exponentially cheaper to set up and maintain, requiring no state filings or registration fees. DUNAs also have an easy to understand structure. This allows DAOs to maintain flexibility and smooth operations without cumbersome requirements.

### Cons
* **Novelty**: The DUNA is a new type of legal entity. This comes with its own risks. For all their undesirable features, traditional legal entity structures have been firmly established through years of judicial precedents, which gives them a degree of reliability and predictability which DUNAs cannot yet boast of.

* **Ambiguity**: The Wyoming DUNA Act contains some ambiguities that could lead to legal dispute in the future. For example, the Act does not define “reasonable compensation” for members or what it means for a DUNA to “confer benefits to members in conformity with its nonprofit purpose”.[17-32-104(c)](https://www.wyoleg.gov/Legislation/2024/SF0050). These provisions are open to wide interpretation and require clearer definitions. This is key to prevent DAOs from being found in violation of the Act due to wrong application of these provisions.

* **Taxation Concerns**: There is some ambiguity as to what is the tax treatment of DUNA revenue even if it is transferred to members as reasonable compensation. Here is at least a resource of some of the related concenrs from [thecryptotaxguy.eth](https://x.com/CryptoTaxGuyETH/status/1767977080644383099).

## Conclusion
The DUNA is a new kind of legal structure that represents a step forward from traditional DAO legal wrappers. DUNAs provide DAOs with legal existence, the ability to comply with tax and regulatory requirements, and limited liability for DAO members. DUNAs confer these benefits on DAOs while allowing them maintain their ethos of decentralization and permissionlessness by empowering members as the driving force of DAOs. In contrast to conventional legal wrappers, DUNAs offer DAOs regulatory certainty especially within the United States and are much simpler to establish and manage. DUNAs therefore hold a lot of potential as the go-to legal wrapper for DAOs and DAOs can leverage on the DUNA structure to establish their legal status.

## Sources	
[Legal Wrappers and DAOs](http://dx.doi.org/10.2139/ssrn.4123737) by Brummer, Christopher J. and Seira, Rodrigo

[Legal Wrappers For DAOs & Their Importance](https://medium.com/@atambobby/legal-wrappers-for-daos-their-importance-4b8fb430d24c) by Barnabas Atam	

[Wyoming built a home for DAOs, but they won't come](https://substack.com/inbox/post/38187682) by Joshua Durham 

[Decentralized Unincorporated Nonprofit Associations (DUNAs): Empowering Web3 Ecosystems](https://www.linkedin.com/pulse/decentralized-unincorporated-nonprofit-po0wc?utm_source=share&utm_medium=member_ios&utm_campaign=share_via) by Adilah Holivay 

[The DUNA: An Oasis For DAOs](https://a16zcrypto.com/posts/article/duna-for-daos/) by David Kerr and Miles Jennings

[Legal Framework for DAOs](https://api.a16zcrypto.com/wp-content/uploads/2022/06/dao-legal-framework-part-1.pdf) by David Kerr and Miles Jennings

[Legal Framework for DAOs - Pt II - Entity Selection Framework](https://api.a16zcrypto.com/wp-content/uploads/2022/06/dao-legal-framework-part-2.pdf) by David Kerr and Miles Jennings

[A Legal Framework for Decentralized Autonomous Organizations - Part III: Model Decentralized Unincorporated Nonprofit Association Act](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4749245)  by David Kerr and Miles Jennings 

[The Rise of Decentralized Autonomous Organizations: Opportunities and Challenges](https://stanford-jblp.pubpub.org/pub/rise-of-daos/release/1) by Aaron Wright 

[Limited Liability Company (LLC): What is it, Advantages and Disadvantages](https://www.nolo.com/legal-encyclopedia/what-is-a-limited-liability-company.html) by Nolo

[Should You Form a Pass-Through Entity?](https://www.nolo.com/legal-encyclopedia/should-you-form-a-pass-through-entity.html) by Nolo 

[Wyoming passes law to give DAOs a nonprofit legal framework](https://blockworks.co/news/wyoming-non-profit-dao-legislation) by Blockworks

[1]: <https://x.com/paulofonseca__/status/1572682226881662977?s=46> "Tweet by Paulo Fonseca"

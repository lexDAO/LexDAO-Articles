# ERC Standard Taxonomy [living document]

*by LexDAO Clinic => students: DanB (lead), Oatmilk and Kyler56; supervisor: bestape.*

## taxomomy graph

![ERC Standard Taxonomy](https://i.imgur.com/GxPiXTL.png)

*Click* *[here](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=ERCtaxonomy.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1IHetq9_FwYsIxZLBSRET0n19membqRmi%26export%3Ddownload)* *to explore the taxonomy in full detail*.

## introduction

ERC standards form the building blocks of the Ethereum user ecosystem and govern everything from NFTs to wallet formats and name registries. But what are ERCs and where do they come from? How does a post on [GitHub](https://github.com/ethereum/EIPs/pull/841) evolve into a monkey picture selling for 3 million dollars? 

In order to gain a better understanding of the ERC landscape, we created a taxonomy in the LexDAO Clinic that gives a bird's eye view of the evolution and interrelation of ERC standards. 

## a brief history of ERC/EIP

ERC stands for Ethereum Request for Comments. A subset of Standards Track Ethereum Improvement Proposals, or [EIPs](https://eips.ethereum.org/EIPS/eip-1), ERCs were inspired by the Request for Comments (RFCs) used by the Internet Engineering Task Force, one of the standards-setting bodies of the internet. 

ERCs, like RFCs, are canonical technical specifications that provide uniform frameworks for developers to build on. Ideally technical standards make smart contracts more reliable and interoperable. For example, if a smart contract follows the ERC-20 token standard it should contain certain functions like `balanceOf` or `totalSupply`, allowing developers to seamlessly plug it into other smart contracts that support that standard. 

The availability of plug-and-play standards makes dApps more composable by allowing people to build complex smart contracts using the same simple building blocks that everyone else uses.

## insights from creating the taxonomy

The standard setting process is not always a clean and orderly one, especially in a decentralized community spread across the globe. Anyone can propose a standard, usually on the Ethereum Magician's Forum or Github, and if it proves useful, after lots of lively debate, the community will adopt it. 

Standards compete with and improve upon other standards, and social consensus determines which ones are used. For example, ERC-1155 builds upon the ideas of ERC-20 and ERC-721 by allowing multiple fungible and non-fungible tokens to be represented by a single contract. Although some may consider ERC-1155 a more useful or efficient standard, an entire ecosystem has already sprung up around ERC-721, and four additional ERCs have already been finalized on top of it, which may make it more difficult for ERC-1155 to gain traction. 

Some standards, like ERC-712 and ERC-2612, haven't even been finalized but have proven so useful they have already gained widespread adoption. Although groups like the Ethereum Cat Herders and the Ethereum Magicians do an excellent job of stewarding the orderly development of standards, ultimately developers and their end users decide which ones actually become canonical and which fade into oblivion. 

As the ecosystem continues to evolve, many standards will be replaced and improved. Some will surely stagnate, and others, like ERC-721, will explode in popularity and form their own branches on the evolutionary tree. 

## conclusion 

Hopefully this taxonomy proves a useful way to visualize the ERC standards and how they have changed over time. 

The chart is meant to be a living document, one that we at LexDAO hope to update and improve upon as the landscape changes. 

Some things in the taxonomy might be wrong, or we might be missing a connection here or there. 

If you have any comments or suggestions, or if you're interested in helping us continue the project, stop by the LexDAO [Discord](https://discord.com/invite/QA75Zw4VTZ) and let us know!

Moreover, feel free to submit a pull request with your changes to https://github.com/lexdao/LexDAO-Articles . Documentation about how to make a pull requests [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork). 


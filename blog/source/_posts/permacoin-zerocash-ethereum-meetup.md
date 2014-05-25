title: 'SV Ethereum Meetup Writeup: Permacoin & Zerocash'
date: 2014-05-25 00:01:07
tags: bitcoin, ethereum, cryptocurrency, cryptography
---

Last Sunday, I attended the [Silicon Valley Ethereum Meetup](http://www.meetup.com/EthereumSiliconValley/events/175527242/) in Mountain View for a presentation on Permacoin by Andrew Miller and Zerocash by Eran Tromer. Both were thoughtful presentations that sought to push forward the field of research around novel applications for Satoshi Nakamoto's blockchain. Below is my summary of each presentation.

###Permacoin

Andrew & his collaborators' research is based on the premise is mining Bitcoin is only useful for securing the network; and this massive amount of computing power could be more useful for additional applications, like a massive distributed database of the world's information.

Andrew used interesting terminology to describe the process of mining: "a scratch-off puzzle \(SOP)." This makes for a useful analogy to to begin to explain what Bitcoin mining is to non-technologists. I've often heard people explain the computations done for hashing as "solving math problems"; when in reality, discovering new blocks is much more like playing the lottery billions of times looking for that next block.

Permacoin would modify the Bitcoin protocol \(or perhaps create a merged mined protocol?) to include a *Proof of Retrievability* \(POR)

>By building a POR-based SOP into Bitcoin, our scheme creates a system of highly distributed, peer-to-peer file storage suitable for storing a large, publicly valuable digital archive F. Specifically, our aim is to dis- tribute F to protect it against data losses associated with a single entity, e.g., the outages or wholesale data losses al- ready incurred by cloud providers [21].

>In contrast to existing peer-to-peer schemes [9, 23], our scheme doesn’t require an identity or reputation system to ensure storage of F , nor does it require that F be a popular download. We achieve file recoverability based strictly on clients’ incentives to make money (mine Bitcoins).

[Link to Permacoin Whitepaper](http://cs.umd.edu/~amiller/permacoin.pdf)

###Zerocash

Eran Tromer definitely won the award for longest journey to speak at a Meetup; having just flown in from Tel Aviv to present his team's whitepaper on Zerocash to the [IEEE Symposium on Security and Privacy](http://www.ieee-security.org/TC/SP2014/) held last week in San Jose. 

Zerocash's goal is to fix the intrinsic lack of privacy in Bitcoin. 

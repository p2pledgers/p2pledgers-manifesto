---
lang: en
title: Peer-to-Peer Ledgers
subtitle: A Manifesto for Sovereign Trade
author: Denis de Bernardy
date: June 24, 2026
abstract: |
  The upending of finance won't emerge from a global consensus. It will instead come from a multitude of local ones. Whereas cryptocurrencies merely replace payment rails, this protocol bypasses them and hollows out the institutions. That makes it a far greater threat to central banks and central governments.

  And they need to be neutered, to ensure they can no longer administer you out of your assets, retirement, or liberty---like they are doing right now.
---


# The Protocol

In the interest of clearing potential confusions upfront, this protocol is not a cryptocurrency. As such, none of the dogmas and threat models you might have in mind apply. It is not trustless. There is no cryptographic finality. There is no blockchain, global consensus, or global state. There is no native token to mine or stake. There is not even a distributed hash table.

Rather, there are peers signing Ricardian contracts and holding them in private local-first ledgers as triple-entry bookkeeping records. That is to say, peers privately exchanging and storing cryptographically signed contracts of the kind you'd sign at a law office, but interspersed with machine-readable instructions.

The protocol is currency-agnostic. Ledgers can bridge currencies or different blockchains as they see fit, including bank notes, metals, cryptos, CBDCs, or any other unit.

Transactions between ledgers are unapologetically private. Money flowing in comes out elsewhere like cash on a hawala. Only ledgers being traversed know how they relate with one another, and a dense enough network ensures ledgers don't always know who they're transacting with.

Trust is at the heart of the protocol, because ledgers secure the transactions they're involved in and cannot see the rest. Trustworthiness builds on signals that you and counterparties you've trusted enough to transact with have---and that only. This heuristic mirrors asking who you trust about people you don't. These signals build on bilateral records of settlements. These preclude Sybil attacks and money printing, since no one will trust a fake ledger that no real ledger has transacted with, much less transact with one without guarantees.

Any ledger can bridge trust gaps by guaranteeing the transactions of another: you for your relatives, your community for its members or nearby communities, or indeed a commercial ledger that monetizes its trustworthiness for profit. The protocol can thereby scale beyond immediate circles of trust via chains of intermediaries---exactly like commerce did in pre-modern times, when merchants carried letters of credit around with them, or for that matter today, when you use bank notes, credit cards, and wire transfers.

Intermediaries create monetization opportunities, but also a risk: a cartel can become all-seeing and thus all-powerful. Ledgers can set up new intermediaries at will, so the onus is on communities to prevent that outcome. Locally, it is a simple matter of spawning community-run intermediaries. Globally, it depends on community clusters becoming more autonomous and self-sufficient---to make global chains of intermediaries unnecessary. It is thus a social problem, not a protocol one.

The protocol is infrastructure-independent and transport-agnostic---and thereby suppression-resistant. It enables sending and receiving transactions using HTTP on the web or a LAN, Bluetooth, email, file drops, notifications, and so forth. This simply mirrors how contracts change hands off-graph.

Gossip ensures transactions are eventually finalized. The protocol mirrors what would happen offline if a contract's parties could exchange wet ink signatures with one another until they all hold each other's signature. The triple-entry bookkeeping records and idempotent responses mean duplicate contract signatures are just that---signatures for the same contract. The lack of polling makes it lightweight and scalable.

As a side-effect of mundane broadcasts like key rotations, the protocol allows running private serverless chat groups. Imagine couriers passing on letters as they interact, and ciphers ensuring only the intended recipients can read them. This is the digital equivalent: infrastructure-independent, transport-agnostic, gossip-based, end-to-end encrypted messaging.

The protocol supports programmatic scripting. Conceptually, triggers are like smart contracts. The difference is that assignees contractually execute logic on edge devices upon finalizing transactions. That removes the need for global consensus, unpredictable gas fees, trusted oracles, and deterministic logic on third-party servers. Async/await patterns let participants orchestrate complex workflows on their own schedule. Triggers enable bridging peer-to-peer ledgers with blockchains, holochains, traditional finance, internal backends, and more.

What makes this all possible is that this protocol is ledger-based, not bearer note-based. Ledgers manage contractual claims to the thing instead of holding the thing in custody like cryptographic wallets do. Because there is no Golden Calf to hold onto, there are no double-spending bugs, money-printing exploits, or bank runs to worry about on this graph. Further, credit is bounded at the edge, so there are no liquidity constraints beyond recipient risk tolerances, and unresponsive intermediaries simply remove options to offload that risk.

Claims propagate on the graph by consolidating triple-entry bookkeeping records between ledgers. Picture medieval communities using pen and paper to book tabs and periodically settling balances after netting them out. This protocol does the same with cryptographic signatures, authorizations, and anonymization. It is, in fact, nothing more.

This setup greatly empowers users, because they get to create their own credit and issue their own chargebacks. On-graph reputation limits their ability to do either. Trustworthiness heuristics flag ledgers that are locally overextended. The decision to accept credit risk is on the counterparties, like when a shop lets regulars book tabs. And recipients can use intermediaries to offload that risk, like when a shop accepts notes or credit cards. The protocol's teeth lie in binding dispute resolution with off-graph collection.

On-graph dispute resolution works by having participants sign authorizations that mirror a power of attorney when signing contracts. These enable a trusted peer serving as arbitrator to sign a decision that binds the affected parties whether they consent to it or not. This differs from an off-graph judge only in that the authorization makes the consent to an arbitrator's authority explicit. Moreover, peers can formalize an appeals process to impose checks and balances on the arbitration, just like with off-graph courts.

Trusted intermediaries take care of on-graph collection. This mirrors medieval tithing, whereby a community took responsibility for its members' obligations, with reputations at stake if either defaults. Any intermediary can fulfill this role, community-run or not. This reflects a legal lineage that modern banking obscures: _Black's Law_ defines a "Bank" as the bench, which is where judges sit. Money is ultimately a promise of future value. Denoting and enforcing such claims are, and always have been, two sides of the same coin. At the same time, this on-graph collection is just triple-entry bookkeeping.

The protocol's salient trick, then, is off-graph collection. Cryptographically signed contracts like those executed within this protocol are fully recognized legal instruments. It follows that traditional courts can adjudicate disputes over them if participants prefer that recourse, or enforce arbitral awards if needed. This protocol therefore delivers off-graph adjudication _and_ on-graph arbitration---both with off-graph enforceability.

One corollary is ledger recovery. With typical cryptocurrencies, cryptographic finality and stolen keys are big deals, since one false move can cost you your life savings. In this protocol, finality is socio-cryptographic. Transactions are triple-entry bookkeeping records held by all signing ledgers, so a balance cannot be lost or wiped clean. A ledger's claims and obligations can be rebuilt through its counterparties via the usual dispute resolution process and its associated broadcasting directives, which mirror off-graph legal notices. That ledger's balance can then be inherited or liquidated as needed.

Another corollary is that a community's members can create a contract with one another---a _social_ contract. That allows managing local-first asset ledgers and tort claims, like communities do today where central governments are weak. Such contracts make clear that individual rights, like property, are socially enforced---since power flows from the barrel of a gun. Each side's rights are the other's obligations, with individual sovereignty interwoven into collective sovereignty. Social contracts ought to make _both_ rights and obligations clear at the outset, because the last thing you'd ever want is a government making up rules you don't consent to.

To wit, this protocol sidesteps the scope of custodial-related statutes on the basis of being mere accounting. Regulating it requires burdening bookkeeping, Quickbooks, and Excel with red tape. Yet you can bet that propaganda rags will gaslight you over why lending to relatives should now land you on a watchlist, even as LLMs pitch financial surveillance as community care, schools unteach accounting out of existence, and shrinks rebrand autonomy as a pathology.

In sum, this protocol does more than merely disrupt payment rails. By enabling peers to issue and clear credit outside the financial system and resolve the associated claims and disputes without its government alter-ego, peer-to-peer ledgers hollow out the institutions. They pave a path forward for communities to reduce banks to bearing risk and governments to enforcing arbitrations.


# The Backstory

This protocol came about while considering what a currency rooted in abundance might look like. I was learning permaculture at the time. A currency rooted in abundance would need to be food-based, but any specific commodity re-introduces potential control on the supply and thus scarcity. It soon occurred to me that meals were the unit I was looking for. Everyone needs meals, and almost every adult can prepare one, so meals are universally valued and preclude monopolies.

A meal is a promise by its issuer to deliver a meal upon request. And by meal, I mean the unit of account, in a "colleagues taking turns buying lunch" kind of way; not perishable foods that require storing, shipping, or assessing using unredeemable notes that masquerade as superior. A fancy dinner could still cost several meals. I won't try to further define what a proper meal is, because we all know one when we eat one.

What makes meals unique as a currency unit is that they're a globally relatable yardstick that acquires meaning locally. Your meals are tastier than others, no doubt. What matters for our sake is that only your circles would ever redeem a meal from you. The odd exceptions are opportunities to have lunch with someone you interact with enough that you owe them a meal. Contrast that sociable event with the barrenness of bank notes. Further, meals would only ever get redeemed locally, if ever, since debt loops get cleared between and within communities. Locals trade in meals like in any other currency, and a London tourist who buys Akara in Makoko would go through intermediaries that book meals owed in London and the local economy respectively. This establishes that a meal in London has the same (social) value as one in the floating slums of Lagos.

Meals are thus universal, culture-aware promises. Because they transcend prices expressed in fiat, meals are fungible across communities, make a great store of value, and highlight the rigging that makes African money worthless despite the continent holding the riches. Meals are also community-serving---contrast local gardens with a mine or a data center. So why not use meals as a unit of account?

The question matters because control revolves around scarcity. Recovering abuse victims all know this intuitively---they've been withheld money, choices, love, attention, and more. Economists have led us to believe that currencies _need_ scarcity, and that we _must_ adapt to it---even as, behind the scenes, banks abuse fractional reserves, miners corner metals, and tech, energy, and finance cartels hijack cryptocurrencies to control the supply of scarce money. Breaking "their" control, then, requires breaking with scarcity.

It later occurred to me, while arriving at solutions that echoed Paul Grignon's work, that bearer notes structurally drive scarcity and usury---they make it so hard to consolidate debt loops that it's easier to just hoard excess notes and loan them to others. Following Ian Grigg's path on triple-entry bookkeeping and Ricardian contracts, by contrast, makes netting out debt loops immediate.

Cryptocurrencies don't break with scarcity---rather the opposite, if anything. And I don't mean to pick on the fact that most of them are bearer token-based. The fact that blockchains allow monitoring and controlling transactions is so well understood it's almost cliché. Agustin Carstens's infamous drooling over CBDCs giving Central Banks absolute control over your spending is unequivocal. My sense is that other cryptocurrencies are proving Thomas Pynchon's quip that they don't have to worry about answers if they can get you asking the wrong questions.

Fractional reserves are a case in point. We've all heard that cryptocurrencies strip bankers of their ability to print money. But Wall Street is mutualizing cryptocurrency pools held in custody already. They are going to leverage those out the wazoo by selling derivative products built around them. So that claim was financially illiterate. There are so many misconceptions about how money creation works, in fact, that dispelling them is in order.

The textbook economic notion that central bankers control the money supply by lending to commercial banks so they can lend to you is so risible that the Bank of England itself called out that myth. As Steve Keen had long been arguing by then, M0 trails M1 because banks lend first and worry about reserves later. The two things central banks do in practice are provide liquidity at the public's expense to private banks that would go bankrupt without, and extract a fee on selling government debt that treasuries could sell (or print) instead.

Moreover, the notion that banks create money by lending is just a parlor trick that obscures money's true source of value. What banks exchange at the Federal Reserve's window are promissory notes. Those are your promises to pay back your mortgage or your car loan. Your signature is what gives those notes value. What gives the Federal Reserve's (promissory) notes value is the U.S. government's ability to collect taxes. And your promise to pay those was in the fine print of your tax return. That one is a promissory note too. So in truth, _you_ were creating that money all along. The act of money creation is and always was your signature.

Cryptocurrencies take that creation power away from you, if anything. Worse, cryptographic finality robs you of your legitimate recourse in case of fraud, coercion, or error. To call this "trustless" is a lie. It is recourse-less. It forces you to trust a system where bugs are features, theft is irreversible, and the only 'law' is the cold logic of a smart contract that doesn't care if you were scammed. So in this respect, cryptocurrencies solve less than nothing. They institutionalize helplessness.

Most scathingly, cryptocurrencies overlook demand. Liabilities fuel demand for currency, because you must work for those who hold the unit of account if you cannot produce it yourself. Your control over access to liquidity becomes your relative power over others. Financiers know this intimately: interest-carrying loans, payment commissions, and dividends are funneling wealth to BlackRock and Vanguard. And they influence the legal environment to saddle communities with the consequences of their plunder. Units like meals, which anyone can produce, address this directly. Cryptocurrencies do not.

Cryptocurrencies let you bypass banks---but that is a meager consolation when militarized Rambos show up to clear out your community. That sight is routine to make room for mines, nature reserves, and industrial facilities when locals refuse to leave. The process is well oiled: claim land using the government, clear out the locals, dump them out of sight, and use the land for the greater good of a private pocket---under the complicit watch of a public kept in check with a bone. Conquest is too overt today, but eminent domain laws get support for national priorities, national obligations, and national emergencies.

These land grabs are possible only because governments took away managing asset ledgers and disputes from communities. The pretense of legality would fly out the window had they not, and land grabs would involve conquest like before the modern era. Communities would not tolerate polluters like mines near them were it not for central governments making them suck it up and cope. Managing asset ledgers and disputes is a government's _only_ purpose. The rest is bread and circus to distract from their abuse. By showing how peers could manage these directly, this protocol makes this corrupt reality self-evident.


# The Stakes

Peer-to-peer ledgers expose the machinery of modern finance for what it rests upon: peers who have collectively forgotten that they can just book their own tabs, and that money's actual source of value is their own signature. They also make transparent that finance and governments are two sides of the same coin.

Marginalized communities leave no doubt that peer-to-peer ledgers are viable. The shanty towns around Lima and elsewhere did not wait for government-issued land titles. They created them through occupation and peer-recognition. What is more, exchanges across the cash and informal economies are often tab-based. You don't even need a digital protocol---pen and paper work fine. What "legitimate" deeds and payments actually do is ratify government land grabs and bank fees.

Furthermore, any doubt that this protocol can scale is cleared by just looking around: you are living in the hyper-centralized, bearer-note version of this protocol---with layers of propaganda warping that reality, and the soon-to-be all-seeing and all-powerful cartel this protocol warns about. The latter boasts of running what amounts to a _Jones Plantation_ in books like Carroll Quigley's _Tragedy and Hope_, so this should be news to no one. What might is that CBDCs are just the tip of the iceberg. They are lightning rods that distract from the real threats, which are the ongoing asset grabs and judicial capture.

Legal ownership is in the process of becoming illusory for most people. Too few asset holders understand that their pensions and savings are in shares held in custody with senior creditor claims on them, as David Rogers Webb's _The Great Taking_ exposes. What is more, tokenized assets are making ownership partial and conditional. The concept of ownership is being redrawn before our eyes. Algorithms will soon dictate how you can use assets you nominally "own." These developments should give you pause, as should the missing trillions from the U.S. balance sheet uncovered by Mark Skidmore and Catherine Austin Fitts, land grabs like the 30x30 plan, and the ongoing technocratic coup. But the kicker is less this abuse of power than the judiciary rubber-stamping it.

In a well-functioning judiciary, the adjudicator considers the facts _and_ the law, and _may_ ignore the law. This is an essential check to prevent enforcing illegitimate statutes. Judges have abdicated that responsibility. Judges also suppress jury nullification. That is _your_ right---and duty---to do the same. Your minority vote as a juror is the _only vote_ you'll ever cast that makes a difference. Any juror can annul a law by refusing to apply it. Everything else is two wolves and a sheep voting on what's for dinner. Governments predictably fear jury nullification, so they push for plea deals and limit jury use. Most damning, however, is judges not even hearing an argument if a law or an expert tells them not to. This judiciary is flatly unfit for purpose.

The social contract, in sum, has been broken. The executive is out of control, and has stopped even pretending it ever worked for us. The other branches are packed with courtiers. This was always the case when you dig deeper---and there is no fixing a system that is working as intended. This is transparent to more people than ever. Many of them are incensed. The E.U. parliament held an event in early 2026 to discuss the risk of civil war. Efforts like the WHO pandemic treaty, which grants emergency powers to unelected experts to place people in camps without consent or judicial oversight, presage nothing good.

Going by the cartel's writings, that ominous future is not set. Jacques Attali explains in _A Brief History of the Future_ that peace is possible if enough of us reject the logic of empire. They're like bullfighters. They will fight the bull if they need to, but would also take a deal that lets them walk out alive. They'd no doubt want an amnesty, since wars always end with one. The question is if you'd grant it---and give up depending on taking another's land, life, or freedom. The latter matters, because "they" are the price of having someone do that dirty work.

But I digress. As noted earlier, this problem calls for a social solution, not a protocol one. Many will complain while doing nothing, but we can all choose to do something about it. By this I do not mean sanctioned performances like voting or peaceful protests. Those only legitimize whoever you beg for a longer leash, and peaceful is a euphemism for harmless anyway. Nor do I mean violence that would delegitimize you instead. In the words of Bill Mollison:

> "The greatest change we need to make is from consumption to production, even if on a small scale, in our own gardens. If only 10% of us do this, there is enough for everyone. Hence the futility of revolutionaries who have no gardens, who depend on the very system they attack, and who produce words and bullets, not food and shelter."


# Help Out

This project needs your support. The hard parts of the protocol are sketched out in the specs I've been writing, including the instruction syntax with a PEG grammar, the uses of cryptography, the transmissions and payloads, the gossip and trust APIs, the on-graph disputes and arbitration enforcement, and the master-slave and multi-master synchronization.

CBDCs are looming, as you no doubt know, so time is of the essence. I'm able to complete the open-source library, but I need backing to work on it full time.

If you're a like-minded engineer, the finalized specs and the reference library will be at `https://github.com/p2pledgers`. Give the project a follow.

If you'd like to contribute to, build on, or help promote the project, get in touch: `ddebernardy@proton.me`.

And if you're a concerned individual who simply wants to share this or chip in, thank you! Your contribution makes a world of difference. The funds will be used to support my family while building the library and launching apps built around it.

* Bank Wire: Email `ddebernardy@proton.me` for my details.
* Monero: `41oExK A8wJWM pN9ccE HiwbgX ko5oTR KLEBPX gwGYve Qg6Jzx Aqkzvh DPb9Ed xYTARA 6RK3NV Ug3ZoY wdcDHB baJRFP CptGx`
* Bitcoin: `bc1qvqlm8ena3sd536k0erpvxmwqzsw9t9k8spzgql`
* Lightning: `ddebernardy@cake.cash`
* Ethereum: `0x9d77b0721367CB7d818B09148D2C8332268D59A6`
* Litecoin: `ltc1q0fmrgenmx8vrh9n0hsnefj26kwy5dg0jt6mkwe`

And yes, the irony of depending on payment rails to build their replacement is not lost on me.

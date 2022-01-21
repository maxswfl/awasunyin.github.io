---
layout: post
title: The Web I Want to Use
subtitle: The web should be a good for the public, not an industry that turns the public into a good. Sadly, the web today is the other way round.
image: /assets/web3/0-spectrum-of-control-in-web3.jpeg
tags: [web3, privacy]
---

The web today (some call it Web2) is one that gives its users no control. It is a place that obfuscates the trade-offs that they are unconsciously accepting whenever they interact with it, where the users gain fleeting benefits in the present, while their true costs are shifted into the future. The price is not an amount of a fiat currency, but a loss of one's basic rights as a human. The web today is a place that is weak to the capture by the few, who seek to leverage its deficiencies for their private benefit, sometimes manifested in profits in a balance sheet, other times as enforcement of their political, economic, and arbitrary agendas.

The web should be a good for the public, not an industry that turns the public into a good. Sadly, the web today is the other way round.

The web I want to use (some call it Web3) is an ecosystem of instruments that can be entirely operated by its own users. This repertoire of tools forms the infrastructure that serves the people: individuals and communities[^1]. Its users are able to carry out their diverse everyday functions without requiring them to exchange any of their human rights. Whenever such trade-offs are necessary, this web not only offers enough optionality, but also offers options which are transparent, articulated, and understandable by anyone- so that users are able to make conscious and informed decisions.

## Principles of Web3

To avoid replicating the deficiencies of Web2, Web3 must be designed from first principles: *control*, *utility*, *flexibility*, and *expressivity*. These principles must apply to as many parts of the Web3 stack as possible, from the lowest level, such as cryptographic primitives, to the highest level parts such as the end-user interfaces. In this article, I focus on the principle of *control*, which I consider paramount for Web3.
![A taxonomy of components of Web3 from lowest to highest level with example subcategories & projects](/assets/web3/0-spectrum-of-control-in-web3.jpeg "A taxonomy of components of Web3 from lowest to highest level with example subcategories & projects")

### The illusion of control in Web2

One of the most dangerous characteristics of Web2 is its tendency to lure its into a false sense of control. This sense of control is often achieved by deploying end-user interfaces that excel at fulfiling the *de jure* requirements (e.g. cookie policies, terms and condition pages, checkboxes, etc.), but *de facto* results in the users feeling that they have control over Web2, omitting the fact that they cannot verify anything. Users often feel like they have a choice, a sense of transparency due to the increasing amount of information available (e.g. reports, hundred-page long T&Cs, etc)– this information overload ends up obfuscating the trade-offs that Web2 users are assuming for short term benefits.

An example where an end-user interface gives an illusion of choice is the way cookie settings are presented. In most cases they enable users to customize their cookie settings, thereby creating an illusion of choice. In reality, there is no way for its users to verify nor enforce that their preferences are respected. Sometimes they provide lots of granularity in options, but intentionally make UIs that are significantly more inconvenient than "accepting the defaults" or "enabling all". 
![Screenshot of the cookies pop-up screen from facebook.com, accessed on 2022–01–16 at 08:34 UTC](/assets/web3/facebook-cokies-popup.png "Screenshot of the cookies pop-up screen from facebook.com, accessed on 2022–01–16 at 08:34 UTC")

*Terms & Conditions* in Web2 are the a strong example of Web2's tendency to use theatre of transparency and information overload to distract users from the many trade-offs they're accepting. They are usually lengthy and the intefaces are programmed in a way that it records a form of shallow proof that the user has read them (e.g. you can only move forward after you've scrolled until the bottom of the T&Cs). These interfaces are great exercise in minimum viable compliance and they are also great in showing that they're transparent (see the screenshot below where Facebook even displays the list of third party companies that leverage cookies on Facebook users).
![Screenshot of the list of third party companies that Facebook’s Cookie Policy involves accessed on 2022–01–16 at 8:32 UTC](/assets/web3/list-of-third-party-companies-involved-in-facebook-cookies.png "Screenshot of the list of third party companies that Facebook’s Cookie Policy involves accessed on 2022–01–16 at 8:32 UTC")

### Control in Web3

Web3 should be designed to grant as much **control** to its users as they prefer in every part of the stack, from the lowest level as the *primitives* to the highest level such as the *end-user interfaces*. Control in Web3 is a spectrum and there are primarily three roles which are not mutually exclusive: designers & builders, operators, and users.

![The spectrum of control that Web3 is designed to enable](/assets/web3/0-spectrum-of-control-in-web3.jpeg "The spectrum of control that Web3 is designed to enable")

In one extreme, the set of people using the web overlap perfectly with the ones operating, enforcing, and verifying its properties and processes. A step further would be that the people operating and using the web are also the ones who design and build the web[^2]. This overlap grants the highest degree of control possible, because there is an alignment of incentives for the designers and builders and operators (who are also the end users) to not adopt exploitative paradigms when architecting the system and verifying that the properties are the ones that they expect while operating it. Without this overlap, the interests and incentives of the three groups can diverge.
![The state of highest control in Web3 where designers & builders, operators, and users overlap](/assets/web3/2-state-of-highest-control-in-web3.jpeg "The state of highest control in Web3 where designers & builders, operators, and users overlap")

Nonetheless, Web3 must also facilitate the extreme where users who only want to use the web can do so. In this case, they must be practically able verify that the web they use does nothing else but what they expect. In order to do so, end-to-end verification for all the users must be attainable.

![The state of lowest control in Web3 where the three groups do not overlap but users are still able to control and verify all parts of the stack](/assets/web3/3-state-of-lowest-control-in-web3.jpeg "The state of lowest control in Web3 where the three groups do not overlap but users are still able to control and verify all parts of the stack")

In order to enable the different degrees of control, this design principle must apply to all parts of the stack– in particular integration & developer intefaces and end-user interfaces, which are parts of the stack that are often forgotten.

* An example of the former is when **integration and developer tooling** is offered as a service, which provides short term benefits (good developer experience via easy-to-integrate APIs to a platform), but obfuscates the cost that might not be palpable in the immediate term (given that the written data on the distributed ledger platform is public, the tooling could be programmed to actively collect and monetizatize users' read data).
* An example of the latter is when Web2 **end-user interfaces** are combined with Web3 application protocols, often leading to a mismatch of expectations among Web3 users who do not have control over the interface as they are not operating it. Thus, they are susceptible to the decisions of the operators, such as censorship.

There are many ways to enable as much control for end-users as possible in Web3 (in the case that they do not wish to be involved with the design & building and/or the operation of parts of the stack), such as integrating an end-to-end verification process that starts with the entire stack being open-source (including the dependencies, tooling, and interfaces).Ideally, end-user interfaces are designed with the principle of control at its core, so that users can completely ignore everything else besides the UI they see and interact with. 

The two screens below show a Web3 wallet in the setup phase, where the user can directly control the underlying parts of the stack by selecting and customizing a profile:
![Example screens of an end-user interface and experience in Web3, a wallet that allows the user to control all parts of the stack by only interacting with the interface](/assets/web3/4-example-web3-end-user-interface.jpeg "Example screens of an end-user interface and experience in Web3, a wallet that allows the user to control all parts of the stack by only interacting with the interface")

- **Private**: by selecting this profile, the default properties of every interaction (transactions in this case) are shielded. Under the hood, the user is choosing the usage of elliptic curve cryptography (primitive) and zk-SNARKs (universal protocol) to enable shielded transactions. The user could even choose the degrees of privacy in other layers such as the peer-to-peer network, in this case where the user picks the most private option, the end user interface will be interacting with a [mixnet](https://en.wikipedia.org/wiki/Mix_network) (information carrying protocol).
- **Green**: this profile comes with the default property of minizing the carbon footprint of every interaction. In this case, the user would be picking the features in the protocol that by default are carbon neutral (a portion of the fees is dedicated to offset the carbon footprint of this transaction) and even in some cases are carbon negative, as in the protocol is programmed to spend a portion of the fees in purchasing enough [carbon dioxide removal](https://en.wikipedia.org/wiki/Carbon_dioxide_removal) credits to cause a net positive impact in the environment.
- **Trusted**: this profile's main property is minimization of transaction fees at the cost of trusting intermediaries. The UI in this case will articulate explicitly that the user is assuming the cost of loss of control (reliance on intermediaries) and privacy (transactions are by default transparent), but in return transactions will be the cheapest possible. In this case, while the technical properties are not so different from the average Web2 interface, it is the fact that the user retained the control and was made a choice based on their preferences and on explicitly articulated tradeoffs.

## Final remarks
To prevent the replication of the drawbacks of Web2, every part of the Web3 stack must be designed and built from first principles, which are *control*, *utility*, *flexibility*, and *expressivity*. In this article I dive deep into the principle of *control*, starting with the drawbacks of Web2, going through the spectrum of control in Web3, and ending with a few examples of how end-user interfaces could embody this design principle.

## Acknowledgements
The very first draft of this article had nothing to do with what you just read. I'm immensely grateful to James Kuo, Christopher Goes, Ismail Khoffi, and Adrian Brink for their questions, comments, and suggestions that inspired and helped me in shapping this article to the way it is now.

## Footnotes

[^1]: A community is a unit of two or more individuals who have a shared interest and therefore an inherent motive to coordinate with each other.

[^2]: And a step even further would be that they also build and operate the physical infrastructure required to access the web, from ISPs to open-source hardware in order to enable true full stack and end end-to-end verifiability.
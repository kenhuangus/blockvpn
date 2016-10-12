
                                        Peer to Peer VPN Sharing Using Blockchain Technology
                                                        White Paper
                                         
Table of Content

1: Introduction

2: VPN token: the approach to VPN token and conversion rate between VPN token and ether or bitcoin.

3: VPN smart Contract: conditions, payment method, security, oracle, auditing, etc.

4: Use Cases: personal uses case (for example, travel from USA to China), Business to Business use case (low cost site to site VPNs), more ambitious use case (established global peer to peer secure VPN network)


 Introduction

A Virtual Private Network (VPN) is a private network that extends across a public network or internet. A VPN is created by establishing a virtual point-to-point connection through the use of dedicated connections, virtual tunneling protocols with traffic encryption. Corporate employee can use VPN to access corporation's internal resource remotely and securely via internet if the VPN server is deployed inside the cooperation. Business to Business data exchange can be accomplished by establishing VPN connections between two companies. In the cloud environment, VPN is widely used for extend the private on premise data center to public cloud such as Amazon AWS (using Virtual Private Cloud which is based on VPN). Individuals can use VPN to access the web content from another countries even if the content is blocked by the firewall.

The peer to peer VPN project such as Social VPN was created to allow people to share VPN access. SocialVPN is an open-source IPOP-based virtual network that connects your computers privately to your friends’ computers (http://ipop-project.org/socialvpn/). 

There are two main issues limiting the wide use of social VPN. First, if A connects to B via VPN. A and B need to trust each other such that A can make sure to B is not eavesdropping on A's VPN connection, and B needs to trust A such that A will not use the VPN connection to try to gain unauthorized access to B's computing resource. Second, there needs to be incentives for people to share the VPN. Blockchain technology comes into play to make peer to peer VPN a reality.

To incentivize the VPN sharing, the VPN blockchain can be built on top of Bitcoin or Etherium Blockchain, the VPN token can be issued for sharing and paying of VPN service. To enable fast payment, Ripple (https://ripple.com) or Radient (http://raiden.network/), lightning (https://lightning.network) payment protocol or technology can be leveraged. 

For security, each sharing transaction (start time, stop time, public address of VPN parites) is recorded on the blockchain, and such record cannot be altered. This allows auditing of the VPN transactions and server as compensating security control such that VPN parties can reach a level of minimum trust needed for transaction. 

Furthermore, more restrictive security conditions of sharing can be codified into smart contract and deployed to the Blockchain. For example, one such condition could be A cannot use VPN to access B’s hard driver. An oracle can be elected by VPN parties, if such violation does occur to judge who has violated the contract conditions.  



 


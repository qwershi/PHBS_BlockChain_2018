# Research on the application of blockchain in logistics
## Overview
### 1. Problem in logistics
The supply chain involves many different parties. There exist a lot of interaction and collaboration between different parties, and all kinds of information generated during the entire supply chain operation are seperatedly stored in their own systems. The information flow also lacks transparency.
#### 1.1 Low efficiency
Because the information is seperated, it is difficult for the participating entities on the supply chain to accurately understand the status and existing problems of the related items. That reduces the efficiency of the system.
#### 1.2 High trust cost
The opaque information flow leads to time-consuming of acountability and burdensome proof when there is a dispute between the various different parties in the supply chain.
### 2. What can Blockchain change?
Blockchain technology as a large-scale collaboration tool is naturally suitable for supply chain management.
#### 2.1 Improve efficiency
Blockchain technology enables data to be made public between parties. That forms a complete and smooth flow of information throughout the supply chain, which ensures that all parties involved find problems and find solutions to problems in real time.
#### 2.2 Better acountability and dispute resolution
Blockchain has the characteristics of data immutability and proof of the existence of timestamps.
## Examples
### 1. Hazardous material transportaiton
Transportation of hazardous material should consider not only cost and efficiency, but also security. Secuirity is the most important.
* Blockchains can be used to monitor the flow and status of hazardous material in the whole logistics in real time, accurately and effectively, so that the regulatory authorities can conduct pre-regulation rather than accountability after the accident.
* All the information of agencies, suppliers, and transporters in the supply chain are written into the blockchain. The information will be permanently stored in the blockchain. Once accident happens, it is convenient to inqure.
### 2. Decentralized brokerage shipping
In the process of shipping, `brokers` coordinate `carriers` (provide transportation service) to organize orders and get payment from `shippers` (customers). Brokers charge a high middle-man markup, sometimes 30-50%. Traditionally, it is hard to get rid of `brokers` because establishing trust between `shippers` and `carriers` is difficult.
* By using the token as incentive, `carriers` can organize themselves to find shipments and intelligently route their team under the constrain of smart contract.
* The whole transportation process is clear. The status of the shipment can be obtained in real time by `shippers`.
* The link between online and offline is difficult to achieve. Stricter constrain in smart contract is needed.
### 3. Signing for express delivery
The final link of logistics natrually has a signing process. It is easy to come up an idea to use `private key` to make digital signature and use `public key` to verify identity when signing for express delivery.
* Secuirity. It is impossible for to received others' express delivery maliciously if everyone keep his `private key` a secret.
* Privacy. What exposed to the public is only the user's `public key`. No personal information can be read from Blockchain, even including phone numbers.
* Requirement is not enough. Blockchain increase the cost of the whole system if the accuracy and efficeny are high. Customers would not have such strong requirement to protect their privacy when the cost is too much. 
### 4. Charity in logistics
Some logistics companies claim that they will donate to charity every time they complete a single delivery. However, the customers do not know whether the company does it or not, and which donation is generated from their own delivery.
* In Blockchain, each donation has real delivery to support. It can make sure the whole donated amount is accurate.
* For each customer, he will exactly know how much donation is generated from his delivery, and where the moeny go to. 

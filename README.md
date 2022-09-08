Why is the audit result “Secured” and not “Well-Secured”?

The EtherAuthority team states that to reach the level of "well-secured", the contract must not have any human influence, meaning fully decentralized with no owner control.

Contract owners should decide for themselves whether or not to retain ownership of contracts based on their own business rules and the nature of the smart contracts. In some cases it is not advisable at all to renounce ownership of the contracts.

Ownership

The audit report of the Stakes contracts (Ube and Almond) states that "the owner can set critical values like interest rate, penalization, maturity, etc. If the admin wallet private key would be compromised, then it would create trouble, also the owner itself can change the ownership to any arbitrary account"

The audit results are correct, but we strongly recommend that contract owners DO NOT RENOUNCE ownership of their Ube and Almond smart contracts. Doing so renders the contracts unusable because the "owner" of the contract is responsible for approving the funds for the contract and thus paying interest to the Stakers. If the owner renounces, then no one will be able to pay interests.

In this way Ube and Almond contracts are centralized in nature, and cannot be decentralized.

Author: https://wpsmartcontracts.com/audits/ 

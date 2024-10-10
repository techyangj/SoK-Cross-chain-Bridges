
# Pay attention
This repository contains the code implementation related to the paper ***"SoK: Security of Cross-chain Bridges: Attack Surfaces, Defenses, and Open Problems."*** It provides implementations of most of the attack contracts and test contracts discussed in the paper, helping developers and researchers gain deeper insights into the security issues surrounding cross-chain bridges. The repository covers attack surfaces, existing defense mechanisms, and unresolved security challenges. Through these implementations, users can reproduce the attack models described in the paper, aiding in the security research and testing of cross-chain bridges.

A key feature of this repository is its use of the Foundry framework for testing, which is a highly efficient framework designed specifically for auditing smart contracts. The Foundry framework simplifies and speeds up the testing process, allowing developers to easily simulate and execute various attack scenarios on cross-chain bridges and analyze the security vulnerabilities in contracts. This makes the repository a powerful testing platform, not only suitable for security research but also for validating defense mechanisms in a practical testing environment.

Moreover, the repository includes not just basic attack contracts but also a complete testing framework and test cases. This allows developers to extend or customize tests for different attack methods. The repository is valuable in several areas:

- Security Research: Researchers can use the code and its Foundry testing framework to explore and verify potential security vulnerabilities in cross-chain bridges, performing audits and risk assessments.
- Defense Mechanism Development: Developers can simulate various attack scenarios and design and validate new defense strategies using the testing framework.
- Education and Training: The attack and defense examples in the repository are ideal for security education and developer training, allowing users to quickly grasp the security challenges of cross-chain bridges.

# How to use
## Requirement
Rust and Foundry 
**Rust Install**: https://www.rust-lang.org/tools/install
**Foundry Install**: https://book.getfoundry.sh/getting-started/installation
## Run Test
After entering each folder,
```
    forge test
```




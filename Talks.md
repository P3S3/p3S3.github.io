## Talks
More information about the program [here](https://p3s3.github.io/program).


**Monday from 9:30 to 10:45; then from 11:15 to 12:45** :
* **<ins>Title</ins>**: The future of security protocol analysis: Towards provable guarantees for apps? <br>
 **Cremers Cas**, *CISPA Helmholtz Center for Information Security* <br>


<ins>Abstract</ins>: There exist a range of modern methodologies in the domain of formal security analysis for protocols, together with decades of research into real-world applications, including TLS 1.3, EMV (Chip and pin), Wifi, 5G, Signal, iMessage, MLS, SPDM, and Matrix. These developments have helped to improve real-world security mechanisms and caught many potential attacks early. However, we are far from done. Using an example from secure messaging we show that users may get weaker guarantees from their apps than they might expect. However, we also show that some of these guarantees, such as PCS, fundamentally cannot be achieved in robust real-world applications. These two observations highlight the need for methodology that can analyze security of not just protocols, but also of larger systems.
We will show some recent developments that try and tackle these challenges, and how we might be able to move forward as a scientific community, to ultimately improve the security and privacy guarantees for end-users. <br>
<ins>Biography</ins>: Prof. Dr. Cas Cremers is faculty member at the CISPA Helmholtz Center for Information Security in Saarbruecken, Germany. He obtained his PhD in 2006 from Eindhoven University of Technology in the Netherlands. From 2006 to 2013 he was a postdoctoral researcher, and senior researcher and lecturer, at ETH Zurich in Switzerland. In 2013 he moved to the University of Oxford as an Associate Professor, and became full Professor at the University of Oxford in 2015. In 2018 he joined CISPA in Germany. His work includes co-developing the Scyther tool and the Tamarin prover for the analysis of security protocols, and working on provable foundations for secure messaging, including the first proofs of the Signal protocol. He contributed to the development of IETF's TLS 1.3 and MLS, and many other protocols. He served as PC co-chair of ACM CCS 2022 and 2023. He was awarded the 2026 IACR Levchin Prize for Real-World Cryptography as part of the Tamarin team. <br>




**Monday from 2:00 PM to 4:00 PM and Wednesday from 9:00 to 10:30 AM.** :
* **<ins>Title</ins>**: Introduction to Fully Homomorphic Encryption <br>
  **Izabachène Malika**, *ETIS, CY Cergy Paris Université, ENSEA, CNRS* <br>


<ins>Abstract</ins>: Fully homomorphic encryption is an advanced techniques that allows computations to be performed on encrypted data without having to decrypt it. Thus, data confidentiality remains guaranteed, even when the data is processed in encrypted form by a third party.This course will provide an introduction to fully homomorphic encryption, with a particular focus on schemes based on the Learning With Errors problem. We will present the algorithmic mechanisms used to control the noise inherent to most of the FHE schemes, as well as the techniques that enable different types of computations to be carried out on encrypted data. <br>
<ins>Biography</ins>: Malika Izabachene is an Associate Professor with the ICI team at ETIS laboratory and with the Department of Computer Science at Cergy Paris University.
Her research focuses on cryptography, with emphasis on homomorphic encryption, post-quantum cryptography, and privacy-preserving protocols, aiming to develop secure and practical solutions for privacypreserving applications. From 2020 to 2023, she served as Chief Cryptographer at Cosmian, a Paris-based start-up, overseeing the design of post-quantum cryptographic primitives and secure multi-party computation frameworks.  Prior to that, she was a researcher at CEA, and held postdoctoral positions focusing on electronic voting systems, anonymous credential schemes, and advanced post-quantum cryptography. She received her PhD in 2009 from Université Paris 7, where she conducted her doctoral research on anonymity in cryptographic protocols at ENS Paris.


**Tuesday from 9:00 to 10:30 AM and then from 11:00 to 12:30** :
* **<ins>Title</ins>**: Zero-Knowledge Proofs <br>
**Faonio Antonio**, *EURECOM, Sophia Antipolis*  <br>


<ins>Abstract</ins>: This class provides an introduction to modern zero-knowledge proof systems, starting from the fundamental concepts and progressing toward modern constructions. We begin “from zero,” covering the basic definitions of proof systems and argument systems, proofs and arguments of knowledge, and the formal notion of zero knowledge. Classical examples such as the Schnorr protocol will be used to build intuition and illustrate the core ideas behind interactive cryptographic proofs. The second part of the class focuses on modern proof systems. We introduce interactive oracle proofs (IOPs), with particular emphasis on polynomial interactive oracle proofs (PIOPs), which form the foundation of many contemporary zk-SNARK constructions. We will then discuss commitment schemes, and in particular polynomial commitment schemes, highlighting that several different cryptographic assumptions and constructions can be used to realize them.Finally, the class presents a simplified view of Plonk and its underlying PIOP. We will explain how statements expressed as arithmetic circuits can be transformed into systems of polynomial equations, and we will introduce the main building blocks of the Plonk protocol. The goal of the class is to provide participants with both the theoretical foundations and the conceptual tools needed to understand modern zero-knowledge proof systems. <br>

* **<ins>Title</ins>**: Beyond SNARKs: Hash-Based Zero-Knowledge for Post-Quantum Signatures  <br>
 **Feneuil Thibauld**, *CryptoExperts* <br>


<ins>Abstract</ins>: Zero-knowledge proof systems are a central tool in modern cryptography, enabling the verification of statements without revealing the underlying witness. While many efficient constructions rely on algebraic assumptions such as elliptic curves or pairings, hash-based alternatives provide an attractive route toward post-quantum security, relying only on well-established symmetric primitives.
Although hash-based proof systems have been studied for nearly a decade, primarily in the context of designing efficient SNARKs, their use for zero-knowledge proofs targeting small statements -where both the witness size and statement complexity are minimal- has only recently gained attention. This line of work was notably initiated by the VOLE-in-the-Head and TC-in-the-Head frameworks, which led to highly compact post-quantum signature schemes derived from MPC-in-the-Head techniques. These constructions introduced efficient methods for committing to and evaluating small polynomials using only symmetric cryptography, relying on structures such as GGM trees and Merkle trees.
In this lecture, we provide an overview of hash-based proof systems and explain how they can be leveraged to construct efficient post-quantum signature schemes based on a broad range of conservative security assumptions. We then explore how these techniques extend naturally to richer cryptographic functionalities, including ring signatures and blind signatures. Such advanced primitives play a central role in many privacy-enhancing technologies, highlighting the broader potential of hash-based zero-knowledge proofs beyond the traditional SNARK setting.

* **<ins>Title</ins>**: <br>
 **Boudguiga Aymen**, *CEA LIST, Université Paris-Saclay* <br>
<ins>Abstract</ins>: <br>

* **<ins>Title</ins>**: Legal aspects of the European Union Digital Identity Wallets <br>
  **Levallois-Barth Claire**, *IMT Atlantique* <br>


<ins>Abstract</ins>: To address the challenges posed by identity theft, fraud, and cyberattacks such as phishing, the European Union adopted the eIDAS 2 Regulation in 2024. By the end of 2026, every citizen and resident of the EU will be able to have access to a European Digital Identity Wallet, interoperable across all the EU Member States. In France, this wallet will take the form of France Identité. It will enable users to store on their smartphones their digital identity data (such as surname, first name, date of birth, nationality …), electronic attestations of attributes (including a driving license, passport, medical prescription, transport tickets, and others), and even to sign electronically. The so-called qualified electronic signature will thereby have the same legal value as a handwritten signature.
The wallet is intended to allow users to maintain control over their identity and personal data, and to access cross-border public and private digital services. The implementation of this pan-European infrastructure requires overcoming a substantial number of obstacles, both with respect to the wallets themselves and to the services provided through them. In particular, personal data must be processed in accordance with the GDPR. This entails, among other things, the implementation of privacy-enhancing technologies and the assurance of the security of the entire system. In that sense, each wallet must obtain a cybersecurity certification before its launch.     
<ins>Biography</ins>: Claire Levallois-Barth, professor of Public law at IMT Atlantique, Holder of the Research Chairs Values and Policies of Personnel Information and Data Common, Work Package Leader in the EU project APTITUDE on EU Digital Identity Wallet, WP 7 Compliance, European Values and Civil Society.

* **<ins>Title</ins>**: How to design a secure electronic voting protocol?  <br>
  **Debant Alexandre**, *Inria, Nancy* <br>


<ins>Abstract</ins>: Electronic voting is becoming a standard practice in our digital societies. It is employed for low-stakes elections, such as those held in schools, sports associations, and other similar contexts. However, it is also utilized in more critical settings, including professional elections and politically binding elections in numerous countries, such as Switzerland, Estonia, the United States, and France.
During this lecture, we try to answer the question: how to design a secure electronic voting protocol?
To achieve this, we will first recall what an electronic voting scheme is and define the security properties that are desirable for it.
Then, we will review the state-of-the-art techniques commonly employed to attain these objectives and explore how to combine them to design an electronic voting scheme.
Throughout the lecture, we will allocate time to analyze the security of real-world systems. These concrete exercises will provide us to a deeper understanding of the security concepts involved, uncover common design mistakes made when designing an electronic voting scheme, and understand the actual security provided by current electronic voting schemes.

* **<ins>Title</ins>**: Navigating the Privacy-Utility Trade-off: An Introduction to Privacy-Enhancing Technologies (PETs) <br>
  **Belguith Sana**, *School of Computer Science, the University of Bristol, UK* <br>


<ins>Abstract</ins>: As our digital infrastructure becomes increasingly decentralized and data-driven, the traditional perimeter-based approach to personal data protection is no longer sufficient to ensure individual privacy. This talk explores the paradigm shift toward Privacy-Enhancing Technologies (PETs), a suite of mathematical and computational tools designed to protect sensitive information.The session will bridge the gap between theory and practice by discussing PETS real-world deployments in various domains, while also addressing the inherent trade-offs in privacy preservation, computational overhead, data accuracy and data utility. Participants will leave with a clear framework for evaluating which PETs are most suitable for specific data-sharing challenges. We will also discuss interdisciplinary approaches to privacy while exploring the legal frameworks such as GDPR, in addition to discussing emergent privacy challenges such as privacy preservation in machine learning applications.

* **<ins>Title</ins>**: Information Flow - static analysis, dynamic monitoring and compiler preservation  <br>
  **Besson Frédéric**, *Inria, Univ Rennes, CNRS, IRISA* <br>


<ins>Abstract</ins>: Confidentiality is a fundamental security property which can be rephrased as an information flow property - intuitively secret information should not leak. We will focus on the strongest property,non-interference, which states that there should be no flow of information from secret data to public data.  Starting from the seminal work of Bell and LaPadula, we will investigate how to state and verify non-interference using  type systems. We will then consider dynamic information flow tracking and ways to combine static and dynamic information flow tracking. We will also cover the preservation of information flow properties through compilation and study the case of constant-time programming. This programming discipline can be formalised as a non-interference property and is essential to protect cryptographic implementations from timing attacks.
                                            
* **<ins>Title</ins>**: Foundations and Frontiers of Quantitative Information Flow <br>
  **Palamidessi Catuscia**, *INRIA* <br>


<ins>Abstract</ins>: Traditional Information Flow treats security as a binary property: a system is either secure or it isn't. However, in modern computing, some leakage is often inevitable. Quantitative Information Flow (QIF) provides the mathematical rigor to move beyond "if" a system leaks to "how much" it leaks, using information-theoretic tools to bound the threat. This tutorial introduces the g-leakage framework, a generalized approach that models adversary threats through diverse gain functions. We will explore the field's most celebrated results, specifically the Miracle Theorem, which reveals a surprising upper bound for the leakage of any system in terms of the Bayes risk, and the validation of the Coriaceous Conjecture via the McIver-Morgan-Smith theorem. The latter establishes a bridge between the operational security of a system and the structural properties of its information-theoretic representation, and can be considered a significant extension of the Blackwell-Sherman-Stein Theorem. Beyond theory, we demonstrate QIF’s utility in evaluating privacy-preserving technologies, including the leakage of searchable encryption and the protections of Differential Privacy (DP). A highlight of the session will be the recent result by Fernandes, Parastoo, and McIver, establishing a formal correspondence between max-leakage and DP, effectively unifying computer security and statistical privacy.

  
More information about the program [here](https://p3s3.github.io/program).

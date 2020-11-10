# Blockchain-based Systems Engineering – Lecture Slides
[Ulrich Gallersdörfer](https://ulig.io/research), [Patrick Holl](https://wwwmatthes.in.tum.de/pages/ocm83pu8nbkc/Patrick-Holl), and [Florian Matthes](https://wwwmatthes.in.tum.de/pages/88bkmvw6y7gx/Prof.-Dr.-Florian-Matthes) <br>
Department of Informatics <br>
Technical University of Munich <br>
{ulrich.gallersdoerfer, patrick.holl, matthes}@tum.de <br>
[https://wwwmatthes.in.tum.de/](https://wwwmatthes.in.tum.de/)

For citation, please use [the provided .bib file](references.bib).

## Introduction

This GitHub-repository contains all contents of the lecture _Blockchain-based Systems Engineering (IN2359)_, held regularly in the summer term at the [Technical University of Munich](https://www.tum.de), starting in 2018. About 500 students regularly enroll in the course. 

- Lecture: Prof. Dr. Florian Matthes
- Exercises / Tutorials: Ulrich Gallersdörfer
- Contact: Please open an issue / pull requests for comments. If you are interested in the .pptx-files, drop us an email. 

Slide deck 13 (Corda) created with support of Gonzalo Munilla Garrido and Susanne Stahnke.

## Module description
In this lecture, we provide an overview about Blockchain systems and systems engineering, focusing on technical details and applications of blockchain systems. We introduce cryptographic hash functions, and present their properties. Then the data structure and the working principles of the Bitcoin blockchain are investigated in detail. We analyze the Proof of Work consensus mechanism of Bitcoin and illustrate the mining scheme. Following this, we demonstrate the system architecture of the Ethereum blockchain with a focus on the Ethereum Virtual Machine and smart contracts. Subsequently, the Solidity language is explained in terms of syntax, types, and design. Ethereum decentralized applications(dApps) are illustrated with current standards and frameworks, and specifics to dApp developments are introduced. Alternative approaches to distributed ledger technologies in the enterprise space are also discussed. Accordingly, the concepts and architecture of Hyperledger Fabric and Corda are explained. We inspect the risks, challenges, and limitations of distributed ledger technologies and present an overview of the current state of the blockchain ecosystem.

## Contents

### Lecture and Exercise (+ Videos)

| Content of Lecture                                                            | Lecture Recording           | Content of Exercise                                                                           | Exercise Recording           |
|-------------------------------------------------------------------------------|-----------------------------|-----------------------------------------------------------------------------------------------|------------------------------|
| 0 & 1: Organization & Introduction                                            |                             | -                                                                                            | -                           |
| 2: [Cryptographic Basics](slides/02_Cryptographic_Basics.pdf)          | [Lecture Rec. 2](https://www.youtube.com/watch?v=3xt4HCXhj2M) | 2: [Cryptographic Basics](exercises/ex1.pdf) & [Solution](exercises/ex1_sol.pdf)     | [Exercise Rec. 1](https://youtu.be/J05SCM90rWk) |
| 3: [Bitcoin Basics](slides/03_Bitcoin_Basics.pdf)                      | [Lecture Rec. 3](https://www.youtube.com/watch?v=G8pxSaa4GTo) | 3: [Bitcoin 1](exercises/ex2.pdf) & [Solution](exercises/ex2_sol.pdf)                | [Exercise Rec. 2](https://youtu.be/S92FMcJ507o) |
| 4: [Bitcoin Script](slides/04_Bitcoin_Script.pdf)                      | [Lecture Rec. 4](https://youtu.be/ywg9dQH21Yo) | 4: [Bitcoin 2](exercises/ex3.pdf) & [Solution](exercises/ex3_sol.pdf)                | [Exercise Rec. 3](https://youtu.be/RsDqwdsbKiE) |
| 5: [Consensus in Bitcoin](slides/05_Consensus_in_Bitcoin.pdf)         | [Lecture Rec. 5](https://www.youtube.com/watch?v=0f-tw7RcCrI) | 5: [Bitcoin 3](exercises/ex4.pdf) & [Solution](exercises/ex4_sol.pdf)                | [Exercise Rec. 4](https://youtu.be/6BfPFGomtJA) |
| 6: [Bitcoin Assessment](slides/06_Bitcoin_Assessment.pdf)              | [Lecture Rec. 6](https://www.youtube.com/watch?v=2ot5ms2--8g) | 6: [Bitcoin 4](exercises/ex5.pdf) & [Solution](exercises/ex5_sol.pdf)                | [Exercise Rec. 5](https://youtu.be/ksxxssLXh-k) |
| 7: [Ethereum Basics](slides/07_Ethereum_Basics.pdf)                    | [Lecture Rec. 7](https://www.youtube.com/watch?v=piglsv8Guq8) | 7: [Ethereum 1](exercises/ex6.pdf) & [Solution](exercises/ex6_sol.pdf)               | [Exercise Rec. 6](https://youtu.be/KT_zD92A1Rs) |
| 8: [Ethereum Smart Contracts](slides/08_Ethereum_Smart_Contracts.pdf) | [Lecture Rec. 8](https://www.youtube.com/watch?v=-ToWLHGdl84) | 8: [Ethereum 2](exercises/ex7.pdf) & [Solution](exercises/ex7_sol.pdf)               | [Exercise Rec. 7](https://youtu.be/SmR668Wh2XA) |
| 9: [Ethereum Design Patterns](slides/09_Ethereum_Design_Patterns.pdf) | [Lecture Rec. 9](https://www.youtube.com/watch?v=AVJfRUgnZLM) | 9: [Ethereum 3](exercises/ex8.pdf) & [Solution](exercises/ex8_sol.pdf)               | [Exercise Rec. 8](https://youtu.be/ddrftGKK8fI) |
| 10: [Ethereum Dapps](slides/10_Ethereum_dApps.pdf)                     | [Lecture Rec. 10](https://www.youtube.com/watch?v=mPlBTMBdRQI) | 10: [Ethereum 4](exercises/ex9.pdf) (optional) & [Solution](exercises/ex9_sol.pdf) | - |
| 11: [Hyperledger I](slides/11_Hyperledger_I.pdf)                       | [Lecture Rec. 11](https://www.youtube.com/watch?v=oOKwTVPijd4&t=589s) | -                                                                                            | -                           |
| 12: [Hyperledger II](slides/12_Hyperledger_II.pdf)                     | [Lecture Rec. 12](https://www.youtube.com/watch?v=RQMWjZuXV-k) | -                                                                                            | -                           |
| 13: [Corda](slides/13_Corda.pdf)                                        | [Lecture Rec. 13](https://www.youtube.com/watch?v=Yw3HIAdtO_4) | -                                                                                            | -                           |


### Guest Lectures
| Title                      | Speaker             | Slides | Video Rec. |
|----------------------------|---------------------|--------|-----------------|
| Bringing DLT into Practice | Thilo Keber         | [Slides](slides/GuestLecture1.pdf)       |   [Rec.](https://www.youtube.com/watch?v=IAGEBu9C6i0) |
| Zero-Knowledge Proofs      | Alexander Esslinger | [Slides](slides/GuestLecture2.pdf)        |  [Rec.](https://www.youtube.com/watch?v=id2dzUCSvrI) |

We thank both speakers Thilo Keber and Alexander Esslinger for providing the material and talk as well as allowing us to share this material within this repository.

### Exams

- [2018 version](exams/exam18.pdf) (4 ECTS, 60 minutes)
- [2019 version](exams/exam19.pdf) (5 ECTS, 90 minutes)
- [2020 version](exams/exam20.pdf) (5 ECTS, 90 minutes)


## License
[![Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under [Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). 

## Acknowledgements
We wish to thank our students Alexander Hefele, Kaan Uzdogan, Christian Ziegler, and Konstantin Kuchenmeister for supporting the lecture and all others which provided valuable feedback!


## Other information
Symbols used from [FontAwesome](https://fontawesome.com/).
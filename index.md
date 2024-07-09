Probabilistic programs are a structured way to describe computations or models with access to some source of randomness. They appear naturally in various safety-, security-, and privacy-critical applications, including randomized algorithms, security protocols, and autonomous systems working in uncertain environments, e.g., due to imprecise sensors. 

The behavior of probabilistic programs is often counterintuitive — a consequence of the well-known fact that humans have difficulties reasoning about stochastic processes. In combination with their importance in emerging safety-critical domains, the counterintuitive nature of probabilistic programs means that ensuring their correctness must be based on verification and analysis techniques that are rigorous, tool-supported, and, ideally, largely automated. However, such tools have not kept up with the increasing usage and popularity of probabilistic programs.

In part, the lack of tool support can be explained by the fact that research on probabilistic programs is spread over multiple fields. In addition to the classical understanding of probabilistic programs as randomized algorithms, probabilistic programs have received rapidly increasing attention as a modeling formalism for complex probability distributions in machine learning, artificial intelligence, and cognitive science.

This workshop will provide a forum for research on the automated verification of probabilistic systems that are in some way described by a programming language, with a particular focus on both symbolic methods and compositional approaches.

# Invited Speakers

- [Mirco Giacobbe](https://mircogiacobbe.github.io)
    * Model checking with Neural Networks
    * Abstract: Model checking aims to derive rigorous proofs for the correctness of systems and has traditionally relied on purely symbolic methods. In this talk, I will show that model checking can be effectively addressed using machine learning too. I will present a realm of approaches for formal verification that leverage neural networks to represent certificates for the correctness of systems, known as "neural certificates." This approach trains certificates from synthetic executions of the system and then checks their validity using symbolic reasoning. Building upon the observation that checking a certificate is much simpler than finding one, and that neural networks are an appropriate representation for such certificates, this results in a machine learning approach to model checking that is entirely unsupervised, formally sound, and practically effective. I will show the principles and experimental results of this approach in correctness assurance of software, probabilistic systems, and control. 

- [Jan Hoffmann](https://www.cs.cmu.edu/~janh/)
    * Sound Probabilistic Inference with Guide Programs

- [Steven Holtzen](https://www.khoury.northeastern.edu/home/sholtzen/)
    * Decomposing Probability Distributions
 
      


# Program

| Time  | Author(s)                                                                                                   | Title                                                                                              |
|-------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| 9:00  |                                                                                                             | Opening                                                                                            |
| **9:10**  | **Jan Hoffmann**                                                                                        | **Sound Probabilistic Inference with Guide Programs**                                              |
| **9:50**  | **Steven Holtzen**                                                                                      | **Decomposing Probability Distributions**                                                                                            |
| 10:30 |                                                                                                             | Coffee break                                                                                       |
| 11:00 | Krishnendu Chatterjee, Ehsan Kafshdar Goharshady, Petr Novotný and Đorđe Žikelić                            | Disproving Equivalence of Probabilistic Programs                                                   |
| 11:16 | Kazuki Watanabe, Sebastian Junges, Jurriaan Rot and Ichiro Hasuo                                            | A Unifying Approach to Product Constructions for Quantitative Temporal Inference                   |
| 11:32 | Muqsit Azeem, Jan Křetínský and Maximilian Weininger                                                        | Sound Value Iteration for Simple Stochastic Games                                                  |
| **11:50** | **Mirco Giacobbe**                                                                                      | **Model checking with Neural Networks**                                                                                            |
| 12:30 |                                                                                                             | Lunch break                                                                                        |
| **14:00** |                                                                                                         | **Open Problems and Lightning Talks Session**                                                      |
| 15:30 |                                                                                                             | Closing                                                                                            |


# Call for Presentations

VeriProP 2024, co-located with CAV, aims to bring together researchers interested in the tool-supported verification of probabilistic programs, models, and systems. This includes probabilistic model checking, program verification in the presence of a source of randomness, or formal guarantees for statistical machine learning algorithms and artificial intelligence systems.

We solicit contributed short presentations. Topics of interest include, but are not limited to:

- Symbolic approaches to the verification of Markov models
- Exact inference techniques
- Abstract interpretation for probabilistic programs
- Domain-specific probabilistic programming languages
- Verification of inference algorithms
- Automation of deductive approaches to verifying probabilistic programs-
- Probabilistic program reasoning in safety, security, or privacy
- Synthesis of probabilistic programs

We call for extended abstracts (1-2 pages in pdf format) describing either ongoing research or an overview of past research in the workshop’s scope. We welcome abstracts covering work that has been previously published or is currently under review. There will be no formal proceedings.


### Submission

**Submission date**: May 24th, AoE

**Submission link**: [https://easychair.org/conferences/?conf=veriprop2024](https://easychair.org/conferences/?conf=veriprop2024)

### Attending

The workshop will take place on July 23rd, the day before CAV. Please register via the [official CAV website](http://www.i-cav.org/2024/).


# Organization

The workshop is chaired by:

- Michele Chiari, TU Wien
- Fredrik Dahlqvist, Queen Mary University of London
- Sebastian Junges, Radboud University
- Benjamin Kaminski, Saarland University and University College London
- Christoph Matheja, Technical University of Denmark

# Previous Editions
- [VeriProP 2023](https://veriprop.github.io/2023/)
- [VeriProP 2022](https://veriprop.github.io/2022/)
- [VeriProP 2021](https://veriprop.github.io/2021/)

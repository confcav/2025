---
layout: page
title: Keynotes
---
### Through the Looking Glass: Semantic Analysis of Neural Networks

[Corina Păsăreanu](https://www.andrew.cmu.edu/user/pcorina/), Carnegie Mellon University, USA

<img src="https://conferences.i-cav.org/2025/assets/img/corina.png" alt="Corina" width="200">

**Abstract:** Neural networks are known for their lack of transparency, making them difficult to understand and analyze. In this talk, we explore methods designed to interpret, formally analyze, and even shape the internal representations of neural networks using human-understandable abstractions. We review recent techniques including the use of vision-language models to investigate perception modules, the application of probing and steering vectors to identify vulnerabilities in code models, and an axiomatic approach for validating mechanistic interpretation of transformer models.

**Bio:** Corina Pasareanu is an ACM Fellow working at NASA Ames. She is
affiliated with KBR and Carnegie Mellon University's CyLab. Her
research interests include model checking, symbolic execution,
compositional verification, AI safety, autonomy, and security. She is
the recipient of several awards, including an ETAPS Test of Time Award
and an ACM Impact Paper Award.  She has been serving as
Program/General Chair for several conferences, including CAV in 2015
and more recently, ICSE in 2025. More information can be found on her
website: [https://www.andrew.cmu.edu/user/pcorina/](https://www.andrew.cmu.edu/user/pcorina/)

### Cedar: A New Language for Expressive, Fast, Safe, and Analyzable Authorization

[Emina Torlak](https://emina.github.io/), AWS and University of Washington, USA

<img src="https://conferences.i-cav.org/2025/assets/img/emina-high-res.jpg" alt="Emina" width="200">

**Abstract:** Authorization is the problem of deciding who has access to what in a multi-user system. Every cloud-based application has to solve this problem, from photo sharing to online banking to health care. This talk presents Cedar, a new language for authorization that is designed to be ergonomic, fast, safe, and analyzable by reduction to SMT. Cedar’s simple and intuitive syntax supports common authorization use-cases with readable policies, naturally expressing concepts from role-based, attribute-based, and relation-based access control models. Cedar’s policy structure enables authorization requests to be decided quickly. Its policy validator uses optional typing to help policy writers avoid mistakes, but not get in their way. Cedar’s design has been finely balanced to allow for a sound, complete, and decidable logical encoding, which enables precise policy analysis, e.g., to ensure that policy refactoring preserves existing permissions. We have implemented Cedar in Rust and used Lean to formally verify important properties of its design. Cedar is used at scale in Amazon Verified Permissions and Amazon Verified Access, and it is freely available at [https://github.com/cedar-policy](https://github.com/cedar-policy).

**Bio:** Emina Torlak is a Senior Principal Scientist at Amazon Web Services and an Affiliate Professor at the University of Washington. Emina works on new languages and tools for program verification and synthesis. She received her Bachelors (2003), Masters (2004), and Ph.D. (2009) degrees from MIT. Emina is the creator of Rosette and Kodkod, and leads the development of Cedar. Rosette is a solver-aided language that powers verification and synthesis tools for all kinds of systems, from radiation therapy control to Linux JIT compilers. Kodkod is a solver for relational logic, used widely in tools for software analysis and design. Cedar is an expressive, fast, and analyzable language for authorization, used at scale at Amazon Web Services and beyond. Emina is a recipient of the Robin Milner Young Researcher Award (2021), NSF CAREER Award (2017), Sloan Research Fellowship (2016), and the AITO Dahl-Nygaard Junior Prize (2016).

### Side Channel Secure Software: A Hardware Question

[Roderick Bloem](https://www.iaik.tugraz.at/person/roderick-bloem/), Graz University of Technology, Austria

<img src="https://conferences.i-cav.org/2025/assets/img/Roderick.jpg" alt="Roderick" width="200">

 **Abstract:** We will present a method to prove the absence of power side channels in systems that are protected using masking. Power side channels may allow attackers to discover secret information by measuring electromagnetic emanations from a chip. Masking is a countermeasure to hide secrets by duplication and addition of randomness. We will discuss how to formally prove security against power side channel techniques for circuits. We will then move on to software running on a CPU, where hardware details can have surprising effects. We will present some vulnerabilities on a small CPU and how to fix them, and we will talk about contracts that take side channels into account.

**Bio:** Roderick Bloem is a professor at Graz University of Technology. He received his M.Sc. degree in Computer Science from Leiden University, the Netherlands, in 1996, and his Ph.D. degree in Computer Science from the University of Colorado at Boulder in 2001.  From 2002 until 2008, he was an Assistant at Graz University of Technology, Graz, Austria. From 2008, he has been a full professor of Computer Science at the same university. He is a co-editor of the Handbook of Model Checking and has published over 140 peer reviewed papers in formal verification, reactive synthesis, Safe AI, and security.
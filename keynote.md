---
layout: page
title: Keynotes
---
### Title: TBA

[Corina Păsăreanu](https://www.andrew.cmu.edu/user/pcorina/), Carnegie Mellon University, USA

<img src="https://conferences.i-cav.org/2025/assets/img/corina.png" alt="Corina" width="200">

**Abstract:** TBA

**Bio:** Corina Pasareanu is an ACM Fellow working at NASA Ames. She is
affiliated with KBR and Carnegie Mellon University's CyLab. Her
research interests include model checking, symbolic execution,
compositional verification, AI safety, autonomy, and security. She is
the recipient of several awards, including an ETAPS Test of Time Award
and an ACM Impact Paper Award.  She has been serving as
Program/General Chair for several conferences, including CAV in 2015
and more recently, ICSE in 2025. More information can be found on her
website: [https://www.andrew.cmu.edu/user/pcorina/](https://www.andrew.cmu.edu/user/pcorina/)

### Title - Cedar: A New Language for Expressive, Fast, Safe, and Analyzable Authorization

[Emina Torlak](https://emina.github.io/), AWS and University of Washington, USA

<img src="https://conferences.i-cav.org/2025/assets/img/emina-high-res.jpg" alt="Emina" width="200">

**Abstract:** Authorization is the problem of deciding who has access to what in a multi-user system. Every cloud-based application has to solve this problem, from photo sharing to online banking to health care. This talk presents Cedar, a new language for authorization that is designed to be ergonomic, fast, safe, and analyzable by reduction to SMT. Cedar’s simple and intuitive syntax supports common authorization use-cases with readable policies, naturally expressing concepts from role-based, attribute-based, and relation-based access control models. Cedar’s policy structure enables authorization requests to be decided quickly. Its policy validator uses optional typing to help policy writers avoid mistakes, but not get in their way. Cedar’s design has been finely balanced to allow for a sound, complete, and decidable logical encoding, which enables precise policy analysis, e.g., to ensure that policy refactoring preserves existing permissions. We have implemented Cedar in Rust and used Lean to formally verify important properties of its design. Cedar is used at scale in Amazon Verified Permissions and Amazon Verified Access, and it is freely available at [https://github.com/cedar-policy](https://github.com/cedar-policy).

**Bio:** Emina Torlak is a Senior Principal Scientist at Amazon Web Services and an Affiliate Professor at the University of Washington. Emina works on new languages and tools for program verification and synthesis. She received her Bachelors (2003), Masters (2004), and Ph.D. (2009) degrees from MIT. Emina is the creator of Rosette and Kodkod, and leads the development of Cedar. Rosette is a solver-aided language that powers verification and synthesis tools for all kinds of systems, from radiation therapy control to Linux JIT compilers. Kodkod is a solver for relational logic, used widely in tools for software analysis and design. Cedar is an expressive, fast, and analyzable language for authorization, used at scale at Amazon Web Services and beyond. Emina is a recipient of the Robin Milner Young Researcher Award (2021), NSF CAREER Award (2017), Sloan Research Fellowship (2016), and the AITO Dahl-Nygaard Junior Prize (2016).
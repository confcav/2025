---
layout: page
title: Program
---
<style>
    .workshop {
        text-align: center;
    }
    .workshop th {
        background: white;
        word-wrap: break-word;
        text-align: center;
    }

</style>

### July 21st (Monday Workshops)
<div class="workshop">
    <table>
        <tr>
            <th>Verification Mentoring Workshop (VMW)</th>
        </tr>
        <tr>
            <th>Workshop on Verification of Quantum Computing (VQC)</th>
        </tr>
        <tr>
            <th>International Workshop on Trustworthy Cyber-Physical Systems (TACPS)</th>
        </tr>
        <tr>
            <th>Workshop on Hyperproperties: Advances in Theory and Applications (HYPER)</th>
        </tr>
        <tr>
            <th>Allen Emerson Memorial</th>
        </tr>
        <tr>
            <th>Symposium on AI Verification (SAIV), Both Days</th>
        </tr>
    </table>
</div>

### July 22nd (Tuesday Workshops)

<div class="workshop">
    <table>
        <tr>
            <th>Workshop on Automated Reasoning for Tensor Compilers (AR4TC)</th>
        </tr>
        <tr>
            <th>Meeting on String Constraints and Applications (MOSCA)</th>
        </tr>
        <tr>
            <th>14th Workshop on Synthesis (SYNT)</th>
        </tr>
        <tr>
            <th>12th Workshop on Horn Clauses for Verification and Synthesis (HCVS)</th>
        </tr>
        <tr>
            <th>Workshop on Verification of Probabilistic Programs (VeriProP)</th>
        </tr>
        <tr>
            <th>Ken McMillan Celebration</th>
        </tr>
        <tr>
            <th>Symposium on AI Verification (SAIV), Both Days</th>
        </tr>
    </table>
</div>

### July 23rd (Wednesday)
<style>
    .schedule {
        text-align: center;
    }
    .schedule th {
        word-wrap: break-word;
        text-align: center;
    }
    .schedule td {
        word-wrap: break-word;
        text-align: center;
    }
    .schedule tr:nth-child(1) { background: white; }
    .schedule tr:nth-child(2) { background: white; }
    .schedule tr:nth-child(3) { background: yellow; }
    .schedule tr:nth-child(4) { background: white; }
    .schedule tr:nth-child(5) { background: green; }
    .schedule tr:nth-child(6) { background: white; }
    .schedule tr:nth-child(7) { background: yellow; }
    .schedule tr:nth-child(8) { background: white; }
    .schedule tr:nth-child(9) { background: yellow; }
    .schedule tr:nth-child(10) { background: white; }
    .schedule tr:nth-child(11) { background: red; }
    .schedule tr:nth-child(12) { background: white; }
</style>

<style>
    .gray-box {
        background-color: #f0f0f0; /* light gray */
        border-radius: 8px;
        padding: 5px;
        max-width: 730px;
        margin: 5px auto;
        color: #333;
        }
    .entry {
        display: grid;
        grid-template-columns: 120px 1fr; /* fixed width for time, rest for content */
        column-gap: 20px;
        padding: 10px 0;
        border-bottom: 1px solid #ccc;
    }
    .entry:last-child {
        border-bottom: none;
    }
    .time {
        font-weight: normal;
        font-size: 1em;
        /* align time to right for neatness */
        text-align: left;
        padding-right: 10px;
    }
    .details {
        /* no special styling needed here, just normal flow */
    }
    .title {
        font-weight: 600;
        font-size: 1em;
        margin-bottom: 6px;
    }
    .speakers {
        font-size: 0.9em;
        line-height: 1.3;
    }
</style>

<div class="schedule">
    <table>
        <tr>
            <th>Time</th>
            <th>Room A</th>
            <th>Room B</th>
        </tr>
        <tr>
            <th>8:30-9:00</th>
            <td colspan="2">Breakfast</td>
        </tr>
        <tr>
            <th>9:00-10:30</th>
            <td colspan="2">Opening Remarks; CAV Award</td>
        </tr>
        <tr>
            <th>10:30-11:00</th>
            <td colspan="2">Coffee break</td>
        </tr>
        <tr>
            <th>11:00-12:00</th>
            <td colspan="2">Keynote</td>
        </tr>
        <tr>
            <th>12:00-14:00</th>
            <td colspan="2">Lunch</td>
        </tr>
        <tr>
            <th>14:00-15:30</th>
            <th><a href="#hardware-model-checking"> Hardware Model Checking</a> </th>
            <th><a href="#probabilistic-reasoning-i"> Probabilistic Reasoning I</a> </th>
        </tr>
        <tr>
            <th>15:30-16:00</th>
            <td colspan="2" >Coffee break</td>
        </tr>
        <tr>
            <th>16:00-17:30</th>
            <th><a href="#synthesis-and-learning"> Synthesis and Learning</a></th>
            <th><a href="#concurrency-and-runtime"> Concurrency and Runtime Verification</a></th>
        </tr>
        <tr>
            <th>17:30-17:45</th>
            <td colspan="2" > </td>
        </tr>
        <tr>
            <th>17:45-18:45</th>
            <td colspan="2" > Industry Panel </td>
        </tr>
        <tr>
            <th>19:00</th>
            <td colspan="2" > Reception </td>
        </tr>
    </table>	
</div>

<div class="gray-box">
    <h4 id="hardware-model-checking">14:00-15:30 Hardware Model Checking</h4>
    <b>Room: A</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time">14:00-14:20</div>
      <div class="details">
        <div class="title">Infinite-state Liveness Checking with rlive</div>
        <div class="speakers">
            Alessandro Cimatti, Alberto Griggio (Fondazione Bruno Kessler), Christopher Johannsen, Kristin Yvonne Rozier (Iowa State University), Stefano Tonetta (FBK) </div>
      </div>
    </div>
    <div class="entry">
        <div class="time">14:20-14:40</div>
        <div class="details">
          <div class="title">Deeply Optimizing the SAT Solver for the IC3 Algorithm
              </div>
          <div class="speakers">
              Yuheng Su (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Qiusong Yang (Institute of Software, Chinese Academy of Sciences, Beijing, China); Yiwei Ci (Institute of Software, Chinese Academy of Sciences); Yingcheng Li, Tianjun Bu (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Ziyu Huang (Beijing Forestry University) </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">14:40-15:00</div>
        <div class="details">
          <div class="title">Property Directed Reachability with Extended Resolution</div>
          <div class="speakers">
            Yakir Vizel, Andrew Luka (Technion - Israel Institute of Technology)</div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:00-15:20</div>
        <div class="details">
          <div class="title">Introducing Certificates to the Hardware Model Checking Competition</div>
          <div class="speakers">
            Nils Froleyks (JKU Linz), Emily Yu (Institute of Science and Technology Austria), Mathias Preiner (Stanford University), Armin Biere (University of Freiburg), Keijo Heljanko (University of Helsinki)</div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:20-15:30</div>
        <div class="details">
          <div class="title">Btor2-Select: Machine Learning Based Algorithm Selection for Hardware Model Checking</div>
          <div class="speakers">
            Zhengyang Lu (University of Waterloo), Po-Chun Chien (LMU Munich), Nian-Ze Lee (National Taiwan University), Arie Gurfinkel (University of Waterloo), Vijay Ganesh (Georgia Institute of Technology)</div>
        </div>
      </div>
</div>
    
<div class="gray-box">
    <h4 id="probabilistic-reasoning-i">14:00-15:30 Probabilistic Reasoning I</h4>
    <b>Room: B</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time">14:00-14:20</div>
      <div class="details">
        <div class="title">Quantitative Supermartingale Certificates</div>
        <div class="speakers">
        Alessandro Abate (University of Oxford); Mirco Giacobbe, Diptarko Roy (University of Birmingham) </div>
      </div>
    </div>
    <div class="entry">
        <div class="time">14:20-14:40</div>
        <div class="details">
          <div class="title">Supermartingale Certificates for Quantitative Omega-regular Verification and Control
              </div>
          <div class="speakers">
          Thomas A. Henzinger (IST Austria); Kaushik Mallik (IMDEA Software Institute); Pouya Sadeghi (University of Tehran); Djordje Zikelic (Singapore Management University) </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">14:40-15:00</div>
        <div class="details">
          <div class="title">Approximate Probabilistic Bisimulation for Continuous-Time Markov Chains</div>
          <div class="speakers">
          Timm Spork, Christel Baier (Technische Universität Dresden); Joost-Pieter Katoen (RWTH Aachen University); Sascha Klüppelholz (Technische Universität Dresden); Jakob Piribauer (Technische Universität Dresden; Universität Leipzig) </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:00-15:20</div>
        <div class="details">
          <div class="title">On the Almost-Sure Termination of Probabilistic Counter Programs</div>
          <div class="speakers">
          Sergei Novozhilov (Zhejiang University; The Hong Kong University of Science and Technology); Mingqi Yang, Mingshuai Chen, Zhiyang Li, Jianwei Yin (Zhejiang University) </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:20-15:30</div>
        <div class="details">
          <div class="title">POPACheck: A Model Checker for Probabilistic Pushdown Automata</div>
          <div class="speakers">
          Francesco Pontiggia, Ezio Bartocci, Michele Chiari (TU Wien) </div>
        </div>
      </div>
</div>

<div class="gray-box">
    <h4 id="synthesis-and-learning">16:00-17:30 Synthesis and Learning</h4>
    <b>Room: A</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time">16:00-16:20</div>
      <div class="details">
        <div class="title">Deductive Synthesis of Reinforcement Learning Agents for Infinite Horizon Tasks</div>
        <div class="speakers">
        Yuning Wang, He Zhu (Rutgers) 
        </div>
      </div>
    </div>
     <div class="entry">
      <div class="time">16:20-16:40</div>
      <div class="details">
        <div class="title">Automata Learning from Preference and Equivalence Queries</div>
        <div class="speakers">
        Eric Hsiung, Joydeep Biswas, Swarat Chaudhuri (University of Texas at Austin) 
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">16:40-17:00</div>
      <div class="details">
        <div class="title">Branching Bisimulation Learning</div>
        <div class="speakers">
        Alessandro Abate (University of Oxford); Mirco Giacobbe (University of Birmingham); Christian Micheletti (University of Padua); Yannik Schnitzer (University of Oxford)
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">17:00-17:10</div>
      <div class="details">
        <div class="title">Extending AALpy with Passive Learning: A Generalized State-Merging Approach</div>
        <div class="speakers">
        Benjamin von Berg, Bernhard Aichernig (TU Graz)
        </div>
      </div>
    </div>
        <div class="entry">
      <div class="time">17:10-17:20</div>
      <div class="details">
        <div class="title">LearnLib: 10 years later</div>
        <div class="speakers">
        Markus Frohme (Technische Universität Dortmund); Falk Howar (Technische Universität Dortmund, Fraunhofer ISST); Bernhard Steffen (Technische Universität Dortmund) 
        </div>
      </div>
    </div>
        <div class="entry">
      <div class="time">17:20-17:30</div>
      <div class="details">
        <div class="title">A Misconception-Driven Adaptive Tutor for Linear Temporal Logic</div>
        <div class="speakers">
        Siddhartha Prasad (Brown University); Ben Greenman (University of Utah, USA); Tim Nelson, Shriram Krishnamurthi (Brown University) 
        </div>
      </div>
    </div>
   
</div>

<div class="gray-box">
    <h4 id="concurrency-and-runtime">16:00-17:30 Concurrency and Runtime Verification</h4>
    <b>Room: B</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time">16:00-16:20</div>
      <div class="details">
        <div class="title">GPUMC: A Stateless Model Checker for GPU Weak Memory Concurrency</div>
        <div class="speakers">
        Soham Chakraborty (TU Delft); S. Krishna (IIT Bombay); Andreas Pavlogiannis (Aarhus University); Omkar Tuppe (IIT Bombay) 
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">16:20-16:40</div>
      <div class="details">
        <div class="title">Counterexample-Guided Commutativity</div>
        <div class="speakers">
        Marcel Ebbinghaus, Dominik Klumpp, Andreas Podelski (University of Freiburg) 
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">16:40-17:00</div>
      <div class="details">
        <div class="title">Scaling Up Proactive Enforcement</div>
        <div class="speakers">
        François Hublet (ETH Zürich); Leonardo Lima (University of Copenhagen); David Basin, Srdjan Krstic (ETH Zürich); Dmitriy Traytel (University of Copenhagen) 
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">17:00-17:10 </div>
      <div class="details">
        <div class="title">An Intermediate Program Representation for Optimizing Stream-Based Languages</div>
        <div class="speakers">
        Frederik Scheerer, Jan Baumeister, Bernd Finkbeiner, Arthur Correnson (CISPA Helmholtz Center for Information Security)
        </div>
      </div>
    </div>
    <div class="entry">
      <div class="time">17:10-17:20</div>
      <div class="details">
        <div class="title">PyCaliper: Python-embedded Infrastructure for RTL Verification and Specification Synthesis</div>
        <div class="speakers">
        Adwait Godbole (University of California, Berkeley); Brian Huffman (Intel Labs); Fangfei Liu (Intel); Carlos V Rozas (Intel Labs); Sanjit A. Seshia (University of California, Berkeley) 
        </div>
      </div>
    </div>

</div>

### July 24th (Thursday)
<div class="schedule">

<table>
    <tr>
        <th>Time</th>
        <th>Room A</th>
        <th>Room B</th>
    </tr>
    <tr>
        <th>8:30-9:00</th>
        <td colspan="2" >Breakfast</td>
    </tr>
    <tr>
        <th>9:00-10:30</th>
        <th><a href="#neural-networks">Neural Networks</a></th>
        <th><a href="#models-and-fol">Model Counting and First-Order Logic</a></th>
    </tr>
    <tr>
        <th>10:30-11:00</th>
        <td colspan="2" >Coffee break</td>
    </tr>
    <tr>
        <th>11:00-12:00</th>
        <td colspan="2" >Keynote</td>
    </tr>
    <tr>
        <th>12:00-14:00</th>
        <td colspan="2" >Lunch</td>
    </tr>
    <tr>
        <th>14:00-15:30</th>
        <th><a href="#data-structures">Data Structures</a></th>
        <th><a href="#reactive-synthesis">Reactive Synthesis</a></th>
    </tr>
    <tr>
        <th>15:30-16:00</th>
        <td colspan="2" >Coffee break</td>
    </tr>
    <tr>
        <th>16:00-17:30</th>
        <th><a href="#cryptography-and-security">Cryptography and Security</a></th>
        <th><a href="#model-checking">Model Checking</a></th>
    </tr>
    <tr>
        <th>17:30-18:45</th>
        <td colspan="2" > </td>
    </tr>
    <tr>
        <th>19:00</th>
        <td colspan="2"> Banquet </td>
    </tr>
</table>	

</div>

<div class="gray-box">
    <h4 id="neural-networks">9:00-10:30 Neural Networks</h4>
    <b>Room: A</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 9:00-9:20 </div>
      <div class="details">
        <div class="title"> Floating-Point Neural Networks Are Provably Robust Universal Approximators </div>
        <div class="speakers">
            Geonho Hwang (GIST); Wonyeol Lee (POSTECH); Yeachan Park (Sejong University); Sejun Park (Korea University); Feras Saad (Carnegie Mellon University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 9:20-9:40 </div>
      <div class="details">
        <div class="title"> A Formally Verified Robustness Certifier for Neural Networks </div>
        <div class="speakers">
             James Tobler (University of Queensland); Hira Taqdees Syeda, Toby Murray (University of Melbourne)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 9:40-10:00 </div>
      <div class="details">
        <div class="title"> Policy Verification in Stochastic Dynamical Systems Using Logarithmic Neural Certificates </div>
        <div class="speakers">
            Thom Badings (University of Oxford); Wietze Koops (Lund University); Sebastian Junges (Radboud University); Nils Jansen (Ruhr-University Bochum)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 10:00-10:10 </div>
      <div class="details">
        <div class="title"> StarV: A Qualitative and Quantitative Verification Tool for Learning-enabled Systems </div>
        <div class="speakers">
            Hoang-Dung Tran (University of Nebraska Lincoln); SungWoo Choi (University of Nebraska, Lincoln, School of Computing); Yuntao Li, Qing Liu (University of Nebraska-Lincoln); Hideki Okamoto (Toyota NA R&D); Bardh Hoxha (Toyota Research Institute North America); Georgios Fainekos (Toyota Motor North America)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 10:10-10:20 </div>
      <div class="details">
        <div class="title"> ModelVerification.jl: a Comprehensive Toolbox for Formally Verifying Deep Neural Networks </div>
        <div class="speakers">
            Tianhao Wei, Hanjiang Hu (Carnegie Mellon University); Luca Marzari (University of Verona); Kai S. Yun, Peizhi Niu, Xusheng Luo, Changliu Liu (Carnegie Mellon University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 10:20-10:30 </div>
      <div class="details">
        <div class="title"> NeuralSAT: A High-Performance Verification Tool for Deep Neural Networks </div>
        <div class="speakers">
             Hai Duong, ThanhVu (Vu) Nguyen (George Mason University); Matthew B Dwyer (University of Virginia)  </div>
      </div>
    </div>

</div>

<div class="gray-box">
    <h4 id="models-and-fol">9:00-10:30 Model Counting and First-Order Logic</h4>
    <b>Room: B</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 9:00-9:20 </div>
      <div class="details">
        <div class="title"> Polyregular Model Checking </div>
        <div class="speakers">
             Aliaume Lopez, Rafał Stefański (University of Warsaw)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 9:20-9:40 </div>
      <div class="details">
        <div class="title"> Engineering an Efficient Probabilistic Exact Model Counter </div>
        <div class="speakers">
             Mate Soos (University of Toronto); Kuldeep S. Meel (Georgia Institute of Technology and University of Toronto)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 9:40-9:50 </div>
      <div class="details">
        <div class="title"> Decision Heuristics in MCSat </div>
        <div class="speakers">
             Thomas Hader (TU Wien); Ahmed Irfan, Stephane Graham-Lengrand (SRI International)  </div>
      </div>
    </div>
        <div class="entry">
      <div class="time"> 9:50-10:00 </div>
      <div class="details">
        <div class="title"> Veil: A Framework for Automated and Interactive Verification of Transition Systems </div>
        <div class="speakers">
            George Pîrlea, Vladimir Gladshtein (National University of Singapore); Elad Kinsbruner (Technion); Qiyuan Zhao, Ilya Sergey (National University of Singapore)  </div>
      </div>
    </div>
        <div class="entry">
      <div class="time"> 10:00-10:10 </div>
      <div class="details">
        <div class="title"> The Vampire Diary </div>
        <div class="speakers">
            Filip Bartek (Czech Technical University in Prague); Ahmed Bhayat (University of Manchester); Robin Coutelier, Marton Hajdu, Matthias Hetzenberger (TU Wien); Petra Hozzova (Czech Technical University in Prague); Laura Kovacs, Jakob Rath (TU Wien); Michael Rawson (University of Southampton); Giles Reger (The University of Manchester); Martin Suda (Czech Technical University in Prague); Johannes Schoisswohl (TU Wien); Andrei Voronkov (The University of Manchester)  </div>
      </div>
    </div>
        <div class="entry">
      <div class="time"> 10:10-10:20 </div>
      <div class="details">
        <div class="title"> Panini: An Efficient and Flexible Knowledge Compiler </div>
        <div class="speakers">
            Yong Lai (Jilin Univeristy); Kuldeep S. Meel (Georgia Institute of Technology); Roland H. C. Yap (National University of Singapore)  </div>
      </div>
    </div>

</div>

<div class="gray-box">
    <h4 id="data-structures">14:00-15:30 Data Structures</h4>
    <b>Room: A</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 14:00-14:20 </div>
      <div class="details">
        <div class="title"> Verifying Tree-Manipulating Programs via CHCs </div>
        <div class="speakers">
             Marco Faella (University of Naples Federico II); Gennaro Parlato (University of Molise)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 14:20-14:40 </div>
      <div class="details">
        <div class="title"> Automated Verification of Monotonic Data Structure Traversals in C </div>
        <div class="speakers">
            Matthew Sotoudeh (Stanford University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 14:40-15:00 </div>
      <div class="details">
        <div class="title"> Arithmetizing Shape Analysis </div>
        <div class="speakers">
            Sebastian Wolff, Ekanshdeep Gupta (New York University); Zafer Esen (Uppsala University); Hossein Hojjat (TeIAS, Khatam University); Philipp Rümmer (University of Regensburg); Thomas Wies (New York University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 15:00-15:20 </div>
      <div class="details">
        <div class="title"> Raven: An SMT-Based Concurrency Verifier </div>
        <div class="speakers">
             Ekanshdeep Gupta, Nisarg Patel, Thomas Wies (New York University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 15:20-15:30 </div>
      <div class="details">
        <div class="title"> Fifteen Years of Viper </div>
        <div class="speakers">
            Marco Eilers, Malte Schwerhoff (ETH Zurich); Alexander J. Summers (University of British Columbia); Peter Müller (ETH Zurich)  </div>
      </div>
    </div>

</div>

<div class="gray-box">
    <h4 id="reactive-synthesis">14:00-15:30 Reactive Synthesis</h4>
    <b>Room: B</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 14:00-14:20 </div>
      <div class="details">
        <div class="title"> Scaling GR(1) Synthesis via a Compositional Framework for LTL Discrete Event Control </div>
        <div class="speakers">
            Hernán Gabriel Gagliardi (Universidad de Buenos Aires); Victor Braberman (Universidad de Buenos Aires/CONICET); Sebastian Uchitel (Universidad de Buenos Aires, CONICET, Imperial College London)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 14:20-14:40 </div>
      <div class="details">
        <div class="title"> Counter Example Guided Reactive Synthesis for LTL Modulo Theories </div>
        <div class="speakers">
            Andoni Rodriguez (IMDEA Software Institute and Universidad Politecnica de Madrid, Spain); Felipe Gorostiaga, Cesar Sanchez (IMDEA Software Institute)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 14:40-15:00 </div>
      <div class="details">
        <div class="title"> Automatic Synthesis of Smooth Infinite Horizon Paths Satisfying Linear Temporal Logic Specifications </div>
        <div class="speakers">
            Samuel Williams, Jyotirmoy Deshmukh (University of Southern California)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 15:00-15:20 </div>
      <div class="details">
        <div class="title"> Full LTL Synthesis over Infinite-state Arenas </div>
        <div class="speakers">
            Shaun Azzopardi (N/A); Luca Di Stefano (TU Wien); Nir Piterman, Gerardo Schneider (University of Gothenburg and Chalmers University of Technology)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 15:20-15:30 </div>
      <div class="details">
        <div class="title"> Issy: A Comprehensive Tool for Specification and Synthesis of Infinite-State Reactive Systems </div>
        <div class="speakers">
            Philippe Heim, Rayna Dimitrova (CISPA Helmholtz Center for Information Security)  </div>
      </div>
    </div>

</div>

<div class="gray-box">
    <h4 id="cryptography-and-security">16:00-17:30 Cryptography and Security</h4>
    <b>Room: A</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 16:00-16:20 </div>
      <div class="details">
        <div class="title"> Automated Verification of Consistency in Zero-Knowledge Proof Circuits </div>
        <div class="speakers">
            Jon Stephens (University of Texas at Austin); Shankara Pailoor (Veridise Inc); Isil Dillig (University of Texas at Austin)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 16:20-16:40 </div>
      <div class="details">
        <div class="title"> Integer Reasoning Modulo Different Constants in SMT </div>
        <div class="speakers">
            Elizaveta Pertseva, Alex Ozdemir (Stanford); Shankara Pailoor, Alp Bassa (Veridise); Sorawee Porncharoenwase (Amazon); Işil Dillig (UT Austin); Clark Barrett (Stanford)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 16:40-17:00 </div>
      <div class="details">
        <div class="title"> Structural operational semantics for functional and security verification of pipelined processors </div>
        <div class="speakers">
             Robert Colvin (University of Queensland); Roger Su (Australian National University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 17:00-17:20 </div>
      <div class="details">
        <div class="title"> Relational Hoare Logic for Realistically Modelled Machine Code </div>
        <div class="speakers">
            Denis Mazzucato (Carnegie Mellon University); Abdalrhman Mohamed (Stanford University); Juneyoung Lee (Amazon Web Services); Clark Barrett (Stanford University); Jim Grundy, John Harrison (Amazon Web Services); Corina Pasareanu (NASA Ames and Carnegie Mellon University)  </div>
      </div>
    </div>

</div>

<div class="gray-box">
    <h4 id="model-checking">16:00-17:30 Model Checking</h4>
    <b>Room: B</b><br>
    <b>Session Chair: TBD</b>
    <div class="entry">
      <div class="time"> 16:00-16:20 </div>
      <div class="details">
        <div class="title"> Efficient Probabilistic Model Checking for Relational Reachability </div>
        <div class="speakers">
            Lina Gerlach (RWTH Aachen Univsersity); Tobias Winkler, Erika Ábrahám (RWTH Aachen University); Borzoo Bonakdarpour (Michigan State University); Sebastian Junges (Radboud University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 16:20-16:30 </div>
      <div class="details">
        <div class="title"> Verifying PETSc Vector Components Using CIVL </div>
        <div class="speakers">
            Venkata Narayana Sarma Dhavala, Stephen F. Siegel (University of Delaware); Jan Hueckelheim, Paul Hovland (Argonne National Laboratory)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 16:30-16:50 </div>
      <div class="details">
        <div class="title"> Compositional Abstraction for Timed Systems with Broadcast Synchronization </div>
        <div class="speakers">
             Hanyue Chen (Tongji University); Miaomiao Zhang (Tongji Uniersity); Frits Vaandrager (Radboud University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 16:50-17:00 </div>
      <div class="details">
        <div class="title"> The rIC3 Hardware Model Checker </div>
        <div class="speakers">
            Yuheng Su (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Qiusong Yang, Yiwei Ci (Institute of Software, Chinese Academy of Sciences, Beijing, China); Tianjun Bu (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Ziyu Huang (Beijing Forestry University)  </div>
      </div>
    </div>
    <div class="entry">
      <div class="time"> 17:00-17:10 </div>
      <div class="details">
        <div class="title"> HornStr: Invariant Synthesis for Regular Model Checking as Constrained Horn Clauses </div>
        <div class="speakers">
            Hongjian Jiang, Anthony W. Lin (RPTU and MPI-SWS); Oliver Markgraf (RPTU); Philipp Rümmer (University of Regensburg); Daniel Stan (LRE, Epita)  </div>
      </div>
    </div>

</div>



### July 25th (Friday)
<div class="schedule">

<table>
    <tr>
        <th>Time</th>
        <th>Room A</th>
        <th>Room B</th>
    </tr>
    <tr>
        <th>8:30-9:00</th>
        <td colspan="2" >Breakfast</td>
    </tr>
    <tr>
        <th>9:00-10:30</th>
        <th>Decision Procedures</th>
        <th>MDPs and Probabilistic Reasoning</th>
    </tr>
    <tr>
        <th>10:30-11:00</th>
        <td colspan="2" >Coffee break</td>
    </tr>
    <tr>
        <th>11:00-12:00</th>
        <td colspan="2" >Keynote</td>
    </tr>
    <tr>
        <th>12:00-14:00</th>
        <td colspan="2" >Lunch, Logic Lounge</td>
    </tr>
    <tr>
        <th>14:00-15:30</th>
        <th>Quantum Computing</th>
        <th>Probabilistic Reasoning II</th>
    </tr>
    <tr>
        <th>15:30-16:00</th>
        <td colspan="2" >Coffee break</td>
    </tr>
    <tr>
        <th>16:00-17:30</th>
        <th>Applications</th>
        <th>Networks and Protocols</th>
    </tr>
    <tr>
        <th>17:30-17:45</th>
        <td colspan="2" > </td>
    </tr>
    <tr>
        <th>17:45-18:45</th>
        <td colspan="2" > Business Meeting </td>
    </tr>
    <tr>
        <th>19:00</th>
        <td colspan="2" > PC Dinner </td>
    </tr>
</table>	

</div>
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
            <th><a href="#probabilistic-reasoning-i"> Probabilistic Reasoning I </th>
        </tr>
        <tr>
            <th>15:30-16:00</th>
            <td colspan="2" >Coffee break</td>
        </tr>
        <tr>
            <th>16:00-17:30</th>
            <th><a href="#synthesis-and-learning"> Synthesis and Learning</th>
            <th><a href="#concurrency-and-runtime"> Concurrency and Runtime Verification</th>
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
            Alessandro Cimatti, Alberto Griggio (Fondazione Bruno Kessler), Christopher Johannsen, Kristin Yvonne Rozier (Iowa State University), Stefano Tonetta (FBK)
        </div>
      </div>
    </div>
    <div class="entry">
        <div class="time">14:20-14:40</div>
        <div class="details">
          <div class="title">Deeply Optimizing the SAT Solver for the IC3 Algorithm
              </div>
          <div class="speakers">
              Yuheng Su (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Qiusong Yang (Institute of Software, Chinese Academy of Sciences, Beijing, China); Yiwei Ci (Institute of Software, Chinese Academy of Sciences); Yingcheng Li, Tianjun Bu (University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences); Ziyu Huang (Beijing Forestry University)
          </div>
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
        Alessandro Abate (University of Oxford); Mirco Giacobbe, Diptarko Roy (University of Birmingham) 
        </div>
      </div>
    </div>
    <div class="entry">
        <div class="time">14:20-14:40</div>
        <div class="details">
          <div class="title">Supermartingale Certificates for Quantitative Omega-regular Verification and Control
              </div>
          <div class="speakers">
          Thomas A. Henzinger (IST Austria); Kaushik Mallik (IMDEA Software Institute); Pouya Sadeghi (University of Tehran); Djordje Zikelic (Singapore Management University) 
          </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">14:40-15:00</div>
        <div class="details">
          <div class="title">Approximate Probabilistic Bisimulation for Continuous-Time Markov Chains</div>
          <div class="speakers">
          Timm Spork, Christel Baier (Technische Universität Dresden); Joost-Pieter Katoen (RWTH Aachen University); Sascha Klüppelholz (Technische Universität Dresden); Jakob Piribauer (Technische Universität Dresden; Universität Leipzig) 
            </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:00-15:20</div>
        <div class="details">
          <div class="title">On the Almost-Sure Termination of Probabilistic Counter Programs</div>
          <div class="speakers">
          Sergei Novozhilov (Zhejiang University; The Hong Kong University of Science and Technology); Mingqi Yang, Mingshuai Chen, Zhiyang Li, Jianwei Yin (Zhejiang University) 
            </div>
        </div>
      </div>
      <div class="entry">
        <div class="time">15:20-15:30</div>
        <div class="details">
          <div class="title">POPACheck: A Model Checker for Probabilistic Pushdown Automata</div>
          <div class="speakers">
          Francesco Pontiggia, Ezio Bartocci, Michele Chiari (TU Wien) 
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
        <th>Neural Networks</th>
        <th>Model Counting and First-Order Logic</th>
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
        <th>Data Structures</th>
        <th>Reactive Synthesis</th>
    </tr>
    <tr>
        <th>15:30-16:00</th>
        <td colspan="2" >Coffee break</td>
    </tr>
    <tr>
        <th>16:00-17:30</th>
        <th>Cryptography and Security</th>
        <th>Model Checking</th>
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
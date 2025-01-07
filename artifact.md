---
layout: page
title: Artifact Evaluation
---
		
The purpose of the artifact evaluation is to support authors to provide more substantial supplements to their papers so future researchers can more effectively build on and compare with previous work. The Artifact Evaluation Committee (AEC) will read the paper and explore the artifact to give the authors third-party feedback about how well the artifact supports the paper and how easy it is for future researchers to use the artifact.

We will be attributing 3 badges, according to [ACM’s artifact guidelines](https://www.acm.org/publications/policies/artifact-review-and-badging-current)

1. Artifact available: available on a publicly accessible archival repository with a DOI
2. Artifact functional: documented, consistent, complete, exercisable
3. Artifact reusable: artifacts are of a quality that significantly exceeds functional; see below

Authors of provisionally accepted tool papers are *required* to submit an artifact at least at the functional level. Acceptance of tool papers is conditional on successful artifact evaluation. Authors of accepted regular papers and Industrial Experience Reports and Case Studies are *invited* (but not required) to submit an artifact.

Members of the artifact evaluation committee and the program committee are asked to use submitted artifacts for the sole purpose of evaluating the contribution associated with the artifact.

Note: artifact evaluation will be single-blind, but paper reviews (except for tool and case-study papers) are double-blind: in the case of the regular papers, do not add identifying information to your paper submission.


### IMPORTANT DATES

All deadlines are AoE (Anywhere on Earth).

* Artifact submission: Monday, April 14, 2025 (mandatory for tool papers)
* Completion/notification of the smoke-test: Sunday, April 27, 2025 (see below)
* Artifact revision: Wednesday, April 30, 2025
* Artifact notification: Monday, May 19, 2025

### SUBMISSION SITE

TBA

### PROCESS

The artifact evaluation consists of two phases: the smoke-test phase and the full-review phase.

In the smoke-test phase, reviewers will download artifacts, read the artifact instructions, and attempt to run the experiments. However, they will not yet verify any claims during this phase. Any technical difficulties (e.g., the image does not start up, experiment script crashes) are documented in a smoke-test review. The authors will be notified about the outcome of the smoke-test by April 25th (AoE). After the smoke-test phase is completed, the artifact submission will be reopened to allow authors to address identified issues. Please keep in mind that the smoke-test phase is solely for resolving technical issues and will involve a dialogue between reviewers and authors. In particular, authors can only make revisions if there are technical issues. If all reviewers agree that there are no issues, they will proceed with the full-review phase.

In the full-review phase, reviewers will evaluate artifacts according to the [evaluation criteria](#evaluation-criteria) and decide on the badge(s) awarded to each submission.

### SUBMISSION GUIDELINES

A final artifact submission should consist of:

1. An **abstract**
    * that summarizes the artifact and explains its relation to the paper including
    * a URL from which your artifact package (a **.zip** file described below) can be downloaded – we encourage you to provide a DOI (which is required for the Available badge) – and
    * the **SHA256** checksum of the .zip file (on submission), and,
    * if applicable, a description of any special requirements beyond a Docker or virtual machine image (e.g., cloud-computing resources, certain hardware, etc.), and,
    * a list of badges that are claimed for the artifact, and
2. A **.pdf** file of the submitted paper.

When uploading your artifact to the URL, please update the **SHA256** checksum of the .zip file in the abstract. You can generate the checksum using the following command-line tools.

* Linux: `sha256sum <file>`
* Windows: `CertUtil -hashfile <file> SHA256`
* MacOS: `shasum -a 256 <file>`


### PACKAGING GUIDELINES

Your artifact .zip file must contain the following elements.

1. The **artifact**, i.e., data, software, libraries, scripts, etc. required to replicate the results of your paper. We encourage the authors to use a Docker image. Alternatively, a virtual machine (VM) image that is compatible with [https://www.virtualbox.org](https://www.virtualbox.org) can be used (please choose a commonly used OS). In this case, save the image as an Open Virtual Appliance (OVA) file.
    * Please include all components required to replicate the results of your paper. If you use material (e.g., source code, benchmarks, etc.) published elsewhere, please include the DOI in your artifact.
    * Please test your artifact on a machine different from the one used for preparing the artifact, to ensure that reviewers will not experience problems installing or executing your artifact.
    * The artifact evaluation is single blind. Please make sure that you do not (accidentally) learn the identity of the reviewers (e.g., through analytics, logging).
    * Please prepare your artifact in such a way that any computer science expert without dedicated expertise in your field can use your artifact, especially to replicate your results. In particular, provide easy-to-use scripts and a detailed README document (see below).
    * If possible, the artifact should include log files that report the results that were presented in the paper. README should then point to the relevant log files.
    * When possible, include source code within your virtual machine image, and point to the most relevant and interesting parts of the source code tree in the README.

2. A **LICENSE** file. Your license needs to allow the artifact evaluation chairs to download and distribute the artifact to the artifact evaluation committee members and the artifact evaluation committee members must be allowed to evaluate the artifact, e.g., use, execute, and modify the artifact for the purpose of artifact evaluation.

3. A **README** text file that introduces the artifact to the user and guides the user through the replication of your results. It should describe:
    * the **structure** and **content** of your artifact.
    * the steps to **set up** your artifact, i.e., how to start the Docker container or how to boot the VM image.
        - Please provide dedicated instructions for installation and a test suit that allows the reviewer to detect any technical difficulties during the smoke test (it must run for only a few minutes).
    * the details on how to **replicate** your results of the paper.
        - Please document which claims or results of the paper can be replicated with the artifact and how (e.g., which experiment must be performed). Please also explain which claims and results cannot be replicated and why.
        - Describe in detail how to replicate the results in the paper, especially describe the steps that need to be performed to replicate the results in the paper. To simplify the reviewing process, we recommend providing **evaluation scripts** (where applicable).
        - Precisely state the **resource requirements** (RAM, number of cores, CPU frequency, etc.) needed to test your artifact. Your resource requirements should be modest and allow replication of results even on laptops.
        - Please provide for each task/step of the replication (an estimate) how long it will take to perform it or how long it took for you and what exact machine(s) you used.
        - For tasks that require a large amount of resources (hardware or time), we recommend providing the additional possibility to replicate a subset of the results with reasonably modest resource and time limits, e.g., within 8 hours on a reasonable personal computer. In this case, please also include a script to replicate only a subset of the results, and explain the relation of the subset to the entire set of results in your paper and why the subset of results supports your claims. If this is not possible, please contact the AE chairs early, but no later than before submission.
        
    * at least basic information on how the correctness of the artifact (i.e. the presented tool/method) has been **tested** (e.g. a comparison of the outputs against other tools or baselines).

If you are not in a position to prepare the artifact as above, please contact AE chairs for an alternative arrangement. For instance, if you cannot provide us with a VM/Docker that contains licensed software (e.g., Matlab), please contact us so we can find a solution.

### EVALUATION CRITERIA

All artifacts are evaluated by the artifact evaluation committee. Each artifact will be reviewed by at least two committee members. Reviewers will read the paper and explore the artifact to evaluate how well the artifact supports the claims and results of the paper.


#### Criteria for the “available” badge

To get the available badge, please upload your Docker or VM image to a repository that provides a DOI, such as Zenodo, figshare, or Dryad and use this DOI link in your artifact submission.


#### Criteria for the “functional” badge

Artifacts seeking the “functional” badge will be evaluated based on the following questions.

* Is the artifact well-documented?
* Is the artifact complete, i.e., are all the results reported in the paper replicable?
* Is the artifact consistent with the paper and the claims made by the paper?
* Does the artifact document how the correctness of the artifact (i.e. the presented tool/method) was tested?

#### Additional criteria for the “reusable” badge

Artifacts seeking the “reusable” badge need to clear a significantly higher bar than functional artifacts. First, they must be available, i.e., receive an “available” badge. Second, we expect a higher level of quality during the evaluation of the functional level. Third, in addition to the criteria from the functional level, they are evaluated against the following criteria.

* Does the artifact have a license which allows reuse, repurposing, and is easy to use?
* Are all dependencies and used libraries well documented and up to date?
* Does the artifact README explain how the artifact can be used beyond the paper in sufficient detail?
* Does the artifact provide documented interfaces for extensions or is the artifact open source?
* Can the artifact be used in a different environment (e.g., built on another system, used outside of the Docker or VM image, etc.)?

An artifact README template from last year's CAV can be found at [https://zenodo.org/doi/10.5281/zenodo.10679817](https://zenodo.org/doi/10.5281/zenodo.10679817)


### BADGE PLACEMENT

If your artifact passed the evaluation successfully, you can place one or two badges on your camera-ready version.

1. Download the appropriate badges [Available](https://github.com/danieldietsch/ae-badges/raw/main/pdf/cav-alt/1-available.pdf), [Functional](https://github.com/danieldietsch/ae-badges/raw/main/pdf/cav-alt/2-functional.pdf), or [Reusable](https://github.com/danieldietsch/ae-badges/raw/main/pdf/cav-alt/3-reusable.pdf) and place them beside your LaTeX files.
2. Add the LaTeX snippet from below to your document and remove all the blocks that do not apply.
3. Add your DOI link to the “Available” badge if you received it.

Because LNCS does not provide a standard placement for the badges, you need to experiment a little to find a good place for them. They should be on the first page and not inside the margins (because the margins will be cut by Springer before publication).

You can start with the following Latex snippet.

```
\documentclass{lncs}
\usepackage{showframe} % print page margins, remove when positioning is satisfying
\usepackage{graphicx} % necessary for inserting .pdfs
\usepackage{hyperref} % "available" badge is a link to the actual DOI
\usepackage[firstpage]{draftwatermark} % free badge placement

\SetWatermarkAngle{0}
%%%%%%%%% Use only one of the four following blocks
% use this block if you received the the "reusable" badge
\SetWatermarkText{\raisebox{12.5cm}{
\hspace{0.1cm}
\href{https://doi.org/10.1109/5.771073}{\includegraphics{1-available}}
\hspace{9cm}
\includegraphics{3-reusable}
}}

% use this block if you received the "available" and the "functional" badge
\SetWatermarkText{\raisebox{12.5cm}{
\hspace{0.1cm}
\href{https://doi.org/10.1109/5.771073}{\includegraphics{1-available}}
\hspace{9cm}
\includegraphics{2-functional}
}}

% use this block if you received only the "functional" badge
\SetWatermarkText{\raisebox{12.5cm}{
\hspace{10.62977cm}
\includegraphics{2-functional}
}}

% use this block if you received only the "available" badge
\SetWatermarkText{\raisebox{12.5cm}{
\hspace{0.1cm}
\includegraphics{1-available}
}}
%%%%%%%%%%%%%%%%%% 
```

An example of the resulting paper is this [.pdf](https://github.com/danieldietsch/ae-badges/blob/main/examples/lncs/samplepaper.pdf).


### CHAIRS OF ARTIFACT EVALUATION COMMITTEE

For any questions, please contact the two AE chairs:

[Matthias Heizmann](https://www.iste.uni-stuttgart.de/institute/team/Heizmann/)[ (matthias.heizmann@iste.uni-stuttgart.de)](mailto:matthias.heizmann@iste.uni-stuttgart.de) <br>
[Tanja Schindler](https://ai.dmi.unibas.ch/people/schindler/)[ (tanja.schindler@unibas.ch)](mailto:tanja.schindler@unibas.ch)
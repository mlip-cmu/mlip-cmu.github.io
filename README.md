# Machine Learning in Production / AI Engineering (17-445/17-645/17-745/11-695)



<span style="font-weight:bold; background-color:rgb(46, 125, 50);    transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms, box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms, border-color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms, color 250ms cubic-bezier(0.4, 0, 0.2, 1) 0ms; color:white; box-shadow: rgba(0, 0, 0, 0.2) 0px 3px 1px -2px, rgba(0, 0, 0, 0.14) 0px 2px 2px 0px, rgba(0, 0, 0, 0.12) 0px 1px 5px 0px; padding: 6px 16px;border-radius:4px ; text-decoration: none;"><a href="https://mlip-cmu.github.io/s2024/" style="color:white">Spring 2024 website</a></span>



*CMU course and corresponding book that covers how to build, deploy, assure, and maintain software products with machine-learned models. Includes the entire lifecycle from a prototype ML model to an entire system deployed in production. Covers also **responsible AI** (safety, security, fairness, explainability) and **MLOps**.* 

***

![Course topics overview](overview.svg "Course topics overview")

In 2024, the course will be offered in the spring and probably also in the fall. In all offerings since 2021, the class does not have formal prerequisites, but expects some familiarity with machine learning concepts and basic programming skills. 

See the specific offering of the course you are interested in:

* Fall 2019: [F2019 website](https://ckaestne.github.io/seai/F2019) and [F2019 GitHub branch](https://github.com/ckaestne/seai/tree/F2019).
* Summer 2020 (with video recordings):  [S2020 website](https://ckaestne.github.io/seai/S2020) and [S2020 GitHub branch](https://github.com/ckaestne/seai/tree/S2020)
* Fall 2020: [F2020 website](https://ckaestne.github.io/seai/F2020) and [F2020 GitHub branch](https://github.com/ckaestne/seai/tree/F2020)
* Spring 2021: [S2021 website](https://ckaestne.github.io/seai/S2021) and [S2021 GitHub branch](https://github.com/ckaestne/seai/tree/S2021)
* Spring 2022: [S2022 website](https://ckaestne.github.io/seai/S2022) and [S2022 GitHub branch](https://github.com/ckaestne/seai/tree/S2022)
* Fall 2022: [F2022 website](https://ckaestne.github.io/seai/F2022) and [F2022 GitHub branch](https://github.com/ckaestne/seai/tree/F2022)
* Spring 2023: [S2023 website](https://mlip-cmu.github.io/s2023/) and [S2023 on GitHub](https://github.com/mlip-cmu/s2023)
* Spring 2024: [S2024 website](https://mlip-cmu.github.io/s2024/) and [S2024 on GitHub](https://github.com/mlip-cmu/s2024)

For researchers, educators, or others interested in this topic, we share all course material, including slides and assignments, under a creative commons license on GitHub (see above) and have recently completed a [textbook](https://ckaestne.medium.com/machine-learning-in-production-book-overview-63be62393581) complementing the course, soon to be published by MIT Press. A while ago, we also published an article describing the rationale and the design of the first iteration of the course: [Teaching Software Engineering for AI-Enabled Systems](https://arxiv.org/abs/2001.06691). Video recordings of the Summer 2020 offering, now somewhat dated, are online on the [course page](https://ckaestne.github.io/seai/S2020/#course-content). We would be happy to see this course or a similar version taught at other universities.  See also an [annotated bibliography](https://github.com/ckaestne/seaibib) on the topic.


## Course content

For a description of topics covered and course structure, see [learning goals](https://github.com/mlip-cmu/s2023/blob/main/learning_goals.md).

The course content evolves from semester to semester. Below is the schedule from the Fall 2022 offering. See the webpages for specific semesters above.

<table>
<thead>
<tr>
<th>Date</th>
<th>Topic</th>
<th>Reading</th>
<th>Assignment due</th>
</tr>
</thead>
<tbody><tr>
<td>Mon, Aug 29</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/01_introduction/intro.html">Introduction and Motivation</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/01_introduction/intro.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/01_introduction/intro.pdf">pdf</a>, <a href="https://ckaestne.medium.com/introduction-to-machine-learning-in-production-eef7427426f1">book chapter</a>)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Wed, Aug 31</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/02_systems/systems.html">From Models to Systems</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/02_systems/systems.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/02_systems/systems.pdf">pdf</a>, <a href="https://ckaestne.medium.com/machine-learning-in-production-from-models-to-systems-e1422ec7cd65">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 5, 7, 8</td>
<td></td>
</tr>
<tr>
<td>Fri, Sep 02</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/blob/F2022/recitations/01_git_and_ml_apis/">Git &amp; ML APIs</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Sep 05</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Labor day, no classes</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Wed, Sep 07</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/03_modelaccuracy/modelquality1.html">Model Quality</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/03_modelaccuracy/modelquality1.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/03_modelaccuracy/modelquality1.pdf">pdf</a>, <a href="https://ckaestne.medium.com/model-quality-defining-correctness-and-fit-a8361b857df">book chapter 1</a>, <a href="https://ckaestne.medium.com/model-quality-measuring-prediction-accuracy-38826216ebcb">chapter 2</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 19</td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/I1_mlproduct.md">I1: ML Product</a></td>
</tr>
<tr>
<td></td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/03a_teamwork/teams.html">Teamwork Primer</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/03a_teamwork/teams.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/03a_teamwork/teams.pdf">pdf</a>)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Fri, Sep 09</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/tree/F2022/recitations/02_kafka">Stream processing: Apache Kafka</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Sep 12</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/04_modeltesting/modelquality2.html">Model Testing Beyond Accuracy</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/04_modeltesting/modelquality2.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/04_modeltesting/modelquality2.pdf">pdf</a>, <a href="https://ckaestne.medium.com/model-quality-slicing-capabilities-invariants-and-other-testing-strategies-27e456027bd">book chapter</a>)</td>
<td><a href="https://homes.cs.washington.edu/~wtshuang/static/papers/2020-acl-checklist.pdf">Behavioral Testing of NLP Models with CheckList</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Sep 14</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/05_goals/goals.html">Goals and Measurement</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/05_goals/goals.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/05_goals/goals.pdf">pdf</a>, <a href="https://ckaestne.medium.com/when-to-use-machine-learning-83fe9be1b8e1">book chapter 1</a>, <a href="https://ckaestne.medium.com/setting-and-measuring-goals-for-machine-learning-projects-c887bc6ab9d0">book chapter 2</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 2, 4</td>
<td></td>
</tr>
<tr>
<td>Fri, Sep 16</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/tree/F2022/recitations/03_measurements_and_teamwork">Measurement and Teamwork</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Sep 19</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/06_requirements/requirements.html">Gathering and Untangling Requirements</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/06_requirements/requirements.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/06_requirements/requirements.pdf">pdf</a>, <a href="https://ckaestne.medium.com/gathering-requirements-for-ml-enabled-systems-4f0a7a23730f">book chapter</a>)</td>
<td><a href="http://mcs.open.ac.uk/mj665/icse17kn.pdf">The World and the Machine</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Sep 21</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/07_mistakes/mistakes.html">Planning for Mistakes</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/07_mistakes/mistakes.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/07_mistakes/mistakes.pdf">pdf</a>, <a href="https://ckaestne.medium.com/planning-for-machine-learning-mistakes-2574f4fcf529">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 6, 7, 24</td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/project.md#milestone-1-recommendation-model-and-first-deployment">M1: Modeling and First Deployment</a></td>
</tr>
<tr>
<td>Fri, Sep 23</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/blob/F2022/recitations/04_requirements_and_risk_analysis/Recitation%204%20-%20Requirements%20and%20Risk%20Analysis.pptx.pdf">Requirements and Risk Analysis</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Sep 26</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/08_architecture/tradeoffs.html">Toward Architecture and Design</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/08_architecture/tradeoffs.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/08_architecture/tradeoffs.pdf">pdf</a>, <a href="https://ckaestne.medium.com/architectural-components-in-ml-enabled-systems-78cf76b29a92">book chapter 1</a>, <a href="https://ckaestne.medium.com/thinking-like-a-software-architect-121ea6919871">chapter 2</a>, <a href="https://ckaestne.medium.com/quality-drivers-in-architectures-for-ml-enabled-systems-836f21c44334">chapter 3</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 18 &amp; <a href="https://hackernoon.com/choosing-the-right-machine-learning-algorithm-68126944ce1f">Choosing the right ML alg.</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Sep 28</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/09_deploying_a_model/deployment.html">Deploying a Model</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/09_deploying_a_model/deployment.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/09_deploying_a_model/deployment.pdf">pdf</a>, <a href="https://ckaestne.medium.com/deploying-a-model-f0b7ffefd06a">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 13 and <a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/1feg4j8/alma991019735160604436">Machine Learning Design Patterns</a>, Ch. 16</td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/I2_requirements.md">I2: Requirements</a></td>
</tr>
<tr>
<td>Fri, Sep 30</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/tree/F2022/recitations/05_architecture">Architecture &amp; Midterm Questions</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Oct 03</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/10_qainproduction/qainproduction.html">Testing in Production</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/10_qainproduction/qainproduction.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/10_qainproduction/qainproduction.pdf">pdf</a>, <a href="https://ckaestne.medium.com/quality-assurance-in-production-for-ml-enabled-systems-4d1b3442316f">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 14, 15</td>
<td></td>
</tr>
<tr>
<td>Wed, Oct 05</td>
<td><img src="https://img.shields.io/badge/-midterm-blue.svg" alt="Midterm"> <strong><a href="https://github.com/ckaestne/seai/tree/F2022/exams">Midterm</a></strong></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Fri, Oct 07</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/blob/F2022/recitations/06_docker/Recitation%206%20Docker.pdf">Containers: Docker</a> (<a href="https://github.com/ckaestne/seai/tree/F2022/recitations/06_docker">Code</a>)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Oct 10</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/11_infrastructurequality/infrastructurequality.html">Infrastructure Quality and MLOps</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/11_infrastructurequality/infrastructurequality.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/11_infrastructurequality/infrastructurequality.pdf">pdf</a>, <a href="https://ckaestne.medium.com/quality-assurance-basics-6ce1eca9921">book chapter 1</a>, <a href="https://ckaestne.medium.com/quality-assurance-for-machine-learning-pipelines-d495b8e5ad6a">book chapter 2</a>, <a href="https://ckaestne.medium.com/integration-and-system-testing-bc4db6650d1">book chapter 3</a>, <a href="https://ckaestne.medium.com/planning-for-operations-of-ml-enabled-systems-a3d18e07ef7c">operations chapter</a>)</td>
<td><a href="https://research.google.com/pubs/archive/46555.pdf">The ML Test Score</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Oct 12</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/12_dataquality/dataquality.html">Data Quality</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/12_dataquality/dataquality.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/12_dataquality/dataquality.pdf">pdf</a>, <a href="https://ckaestne.medium.com/data-quality-for-building-production-ml-systems-2e0cc7e6113f">book chapter</a>)</td>
<td><a href="https://dl.acm.org/doi/abs/10.1145/3411764.3445518">Data Cascades in High-Stakes AI</a></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/I3_architecture.md">I3: Architecture</a></td>
</tr>
<tr>
<td>Fri, Oct 14</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://drive.google.com/file/d/1trLB68hSuh8MIpCdTLEvjyog0CPy7ILp/view?usp=sharing">Unit Tests and Continuous Integration</a> (<a href="https://drive.google.com/file/d/1vQITq_DrriAg-_eVn6NUR0qsU7luxTgm/view?usp=share_link">PDF</a>, <a href="https://github.com/ranadeepsingh/CI_Tutorial">Code</a>, <a href="https://youtu.be/1jbvVuOSNHA">Video</a>)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Oct 17</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Fall break, no classes</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Wed, Oct 19</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Fall break, no classes</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Fri, Oct 21</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Fall break, no classes</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Oct 24</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/13_dataatscale/dataatscale.html">Scaling Data Storage and Data Processing</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/13_dataatscale/dataatscale.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/13_dataatscale/dataatscale.pdf">pdf</a>, <a href="https://ckaestne.medium.com/scaling-ml-enabled-systems-b5c6b1527bc">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019577936304436">Big Data</a>, Ch. 1</td>
<td></td>
</tr>
<tr>
<td>Wed, Oct 26</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/14_process/process.html">Process &amp; Technical Debt</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/14_process/process.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/14_process/process.pdf">pdf</a>, <a href="https://ckaestne.medium.com/data-science-and-software-engineering-process-models-ea997ea53711">book chapter 1</a>, <a href="https://ckaestne.medium.com/technical-debt-in-machine-learning-systems-62035b82b6de">chapter 2</a>)</td>
<td><a href="http://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf">Hidden Technical Debt in Machine Learning Systems</a></td>
<td></td>
</tr>
<tr>
<td>Fri, Oct 28</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Tartan community day, no classes</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Oct 31</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/15_intro_ethics_fairness/intro-ethics-fairness.html">Responsible ML Engineering</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/15_intro_ethics_fairness/intro-ethics-fairness.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/15_intro_ethics_fairness/intro-ethics-fairness.pdf">pdf</a>, <a href="https://ckaestne.medium.com/responsible-ai-engineering-c97e44e6c57a">book chapter 1</a>, <a href="https://ckaestne.medium.com/fairness-in-machine-learning-and-ml-enabled-products-8ee05ed8ffc4">chapter 2</a>)</td>
<td><a href="https://datasociety.net/wp-content/uploads/2018/04/Data_Society_Algorithmic_Accountability_Primer_FINAL-4.pdf">Algorithmic Accountability: A Primer</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Nov 02</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/16_model_fairness/model_fairness.html">Measuring Fairness</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/16_model_fairness/model_fairness.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/16_model_fairness/model_fairness.pdf">pdf</a>, <a href="https://ckaestne.medium.com/fairness-in-machine-learning-and-ml-enabled-products-8ee05ed8ffc4">book chapter</a>)</td>
<td><a href="http://users.umiacs.umd.edu/~hal/docs/daume19fairness.pdf">Improving Fairness in Machine Learning Systems</a></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/project.md#milestone-2-model-and-infrastructure-quality">M2: Infrastructure Quality</a></td>
</tr>
<tr>
<td>Fri, Nov 04</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/tree/F2022/recitations/08_monitoring">Monitoring: Prometheus, Grafana</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Nov 07</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/17_system_fairness/system_fairness.html">Building Fairer Products</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/17_system_fairness/system_fairness.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/17_system_fairness/system_fairness.pdf">pdf</a>, <a href="https://ckaestne.medium.com/fairness-in-machine-learning-and-ml-enabled-products-8ee05ed8ffc4">book chapter</a>)</td>
<td><a href="https://dl.acm.org/doi/pdf/10.1145/3290607.3310433?casa_token=xg_kkiUWskIAAAAA:BPhrPLhkHNgAeggGjWw0NBmCi93Rp3TaOX2ZCb54v7m3WfLmf-O5K5F1ogrBmTHFWUH3SfvJdhoMkg">A Mulching Proposal</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Nov 09</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/18_explainability/explainability.html">Explainability &amp; Interpretability</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/18_explainability/explainability.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/18_explainability/explainability.pdf">pdf</a>, <a href="https://ckaestne.medium.com/interpretability-and-explainability-a80131467856">book chapter</a>)</td>
<td><a href="https://dataskeptic.com/blog/episodes/2020/black-boxes-are-not-required">Black boxes not required</a> or <a href="https://arxiv.org/abs/1811.10154">Stop Explaining Black Box ML Models…</a></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/I4_mlops_tools.md">I4: MLOps Tools</a></td>
</tr>
<tr>
<td>Fri, Nov 11</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/tree/F2022/recitations/09_fairness">Fairness</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Nov 14</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/19_transparency/transparency.html">Transparency &amp; Accountability</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/19_transparency/transparency.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/19_transparency/transparency.pdf">pdf</a>, <a href="https://ckaestne.medium.com/transparency-and-accountability-in-ml-enabled-systems-f8ed0b6fd183">book chapter</a>)</td>
<td><a href="https://pair.withgoogle.com/chapter/explainability-trust/">People + AI, Ch. Explainability and Trust</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Nov 16</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/20_provenance/provenance.html">Versioning, Provenance, and Reproducability</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/20_provenance/provenance.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/20_provenance/provenance.pdf">pdf</a>, <a href="https://ckaestne.medium.com/versioning-provenance-and-reproducibility-in-production-machine-learning-355c48665005">book chapter</a>)</td>
<td><a href="https://www.buildingintelligentsystems.com/">Building Intelligent Systems</a>, Ch. 21 &amp; <a href="http://research.google.com/pubs/archive/45390.pdf">Goods: Organizing Google's Datasets</a></td>
<td></td>
</tr>
<tr>
<td>Fri, Nov 18</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://docs.google.com/presentation/d/13BCWL35LM2DXv5Hxj_aKBpdEP4CQhabc9mbUIWJDLm4/edit?usp=sharing">Model Explainability &amp; Interpretability</a> (<a href="https://drive.google.com/file/d/1ZoFXFO5MkDxHvu9h4qB7xrvUXjslt3wP/view?usp=sharing">PDF</a>, <a href="https://colab.research.google.com/drive/1ZiawXPUplLVVTAjz-734dChjyxII0XZO?usp=sharing">Code</a>, <a href="https://youtu.be/tYRWFSIc2IM">Video</a>)</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Nov 21</td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/lectures/guest_lecture/debugging-sherry-tongshuang-wu.pdf">Debugging</a> (Guest lecture by <a href="https://www.cs.cmu.edu/~sherryw/">Sherry Tongshuang Wu</a>)</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>Wed, Nov 23</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Thanksgiving break</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Fri, Nov 25</td>
<td><img src="https://img.shields.io/badge/-break-red.svg" alt="Break"> Thanksgiving break</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Nov 28</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/21_security/security.html">Security and Privacy</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/21_security/security.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/21_security/security.pdf">pdf</a>, <a href="https://ckaestne.medium.com/security-and-privacy-in-ml-enabled-systems-1855f561b894">book chapter</a>)</td>
<td><a href="https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/6lpsnm/alma991019649190004436">Building Intelligent Systems</a>, Ch. 25 &amp; <a href="https://ieeexplore.ieee.org/document/9107290">The Top 10 Risks of Machine Learning Security</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Nov 30</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/22_safety/safety.html">Safety</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/22_safety/safety.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/22_safety/safety.pdf">pdf</a>, <a href="https://ckaestne.medium.com/safety-in-ml-enabled-systems-b5a5901933ac">book chapter</a>)</td>
<td><a href="http://ceur-ws.org/Vol-2560/paper40.pdf">Practical Solutions for Machine Learning Safety in Autonomous Vehicles</a></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/project.md#milestone-3-monitoring-and-continuous-deployment">M3: Monitoring and CD</a></td>
</tr>
<tr>
<td>Fri, Dec 02</td>
<td><img src="https://img.shields.io/badge/-rec-yellow.svg" alt="Recitation"> <a href="https://github.com/ckaestne/seai/blob/F2022/recitations/11_threat%20modeling/Recitation%2011%20Threat%20Modelling.pdf">Threat modeling</a></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Mon, Dec 05</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/23_teams/teams.html">Fostering Interdisciplinary Teams</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/23_teams/teams.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/23_teams/teams.pdf">pdf</a>, <a href="https://ckaestne.medium.com/building-machine-learning-products-with-interdisciplinary-teams-a1fdfbf49e81">book chapter</a>)</td>
<td><a href="https://arxiv.org/abs/2110.10234">Collaboration Challenges in Building ML-Enabled Systems</a></td>
<td></td>
</tr>
<tr>
<td>Wed, Dec 07</td>
<td><a href="https://ckaestne.github.io/seai/F2022/slides/24_summary/all.html">Summary and Reflection</a> (<a href="https://github.com/ckaestne/seai/blob/F2022/lectures/24_summary/all.md">md</a>, <a href="https://ckaestne.github.io/seai/F2022/slides/24_summary/all.pdf">pdf</a>)</td>
<td></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/project.md#milestone-4-fairness-security-and-feedback-loops">M4: Fairness, Security and Feedback Loops</a></td>
</tr>
<tr>
<td>Sun, Dec 18 (9:30-11:30am)</td>
<td><strong>Final Project Presentations</strong></td>
<td></td>
<td><a href="https://github.com/ckaestne/seai/blob/F2022/assignments/project.md#final-report-and-presentation">Final report</a></td>
</tr>
</tbody></table>



## Course Syllabus and Policies

See the web pages for the specific semester for details.


Students taking the PhD version of this class (17-745) will replace two individual assignments with a research project instead, resulting in a draft of a paper of at least workshop quality.

## Related Courses at CMU

* 17-649 Artificial Intelligence for Software Engineering: This course focuses on how AI techniques can be used to build better software engineering tools and goes into more depth with regard to specific AI techniques, whereas we focus on how software engineering techniques can be used to build AI-enabled systems. Our application scenarios are typical web-based systems for end users, rather than tools for software developers.
* [05-318 Human-AI Interaction](http://www.humanaiclass.org/): Focuses on the HCI angle on designing AI-enabled products. Overlaps in some coverage on fairness, covers in much more detail user interface design and how to involving humans in ML-supported decisions, whereas this course focuses more on architecture design, requirements engineering, and deploying systems in production. Both courses are complementary.
* [17-646 DevOps: Modern Deployment](https://mse.isri.cmu.edu/applicants/course-offerings.html), [17-647 Engineering Data Intensive Scalable Systems](https://mse.isri.cmu.edu/applicants/course-offerings.html), and similar: These course cover techniques to build scalable, reactive, and reliable systems in depth. We will survey DevOps, and big data systems in the context of designing and deploying systems, but will not explore them in as much detail as a dedicated course can. We will look at MLOps as a ML-specific variant of DevOps.
* [10-601 Machine Learning](https://www.cmu.edu/mits/curriculum/core/10-601.html), [15-381 Artificial Intelligence: Representation and Problem Solving](https://www.cs.cmu.edu/~15381-f17/), [05-834  Applied Machine Learning](https://www.cmu.edu/mits/curriculum/core/05-834.html), [95-865 Unstructured Data Analytics](https://www.andrew.cmu.edu/user/georgech/95-865/), [10-718: Machine Learning in Practice](https://github.com/dssg/MLinPractice), and many others: CMU offers many course that teach how machine learning and artificial intelligence techniques work internally or how to apply them to specific problems (including feature engineering and model evaluation), often on static data sets. We assume a basic understanding of such techniques and processes (see prerequisites) but focus on the engineering process for production ML systems.
* 17-691 Machine Learning in Practice: Applied machine learning with an focus on deployment and monitoring of models.
* [15-884 Machine Learning Systems](https://catalyst.cs.cmu.edu/15-884-mlsys-sp21/), [10-714 Deep Learning Systems](https://dlsyscourse.org): Courses that focus on the systems aspect of building ML libraries, such as distributed learning and using hardware acceleration. 
* [17-630 Prompt Engineering](https://www.cs.cmu.edu/~breaux/prompting/): Course focused specifically on prompt engineering for large language models.
* [10-613 Machine Learning, Ethics and Society](https://www.cs.cmu.edu/~hheidari/mles-fall-21.html), [16-735 Ethics and Robotics](), [05-899 Fairness, Accountability, Transparency, & Ethics (FATE) in Sociotechnical Systems], and others dive much deeper into ethical issues and fairness in machine learning, in some cases diving deeper into statistical notions or policy. We will cover these topics in a two-week segment among many others. 

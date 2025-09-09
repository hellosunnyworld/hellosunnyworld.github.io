---
layout: page
title: My Research
sitemap: false
permalink: /research/
---

## Current Work
<div class="project">
  <div class="project-image">
    <img src="/assets/img/overview_agent_training.svg" alt="Project Image" class="project-logo">
  </div>
  <div class="project-content">
    <h2>Enhance RL with Noisy LLM Feedback</h2>

    <!-- EMNLP 2024 Entry -->
    <div class="publication-entry">
      <h3>[EMNLP 2024]</h3>
      <p class="publication-title" style="font-size: 16px;"><a href="https://arxiv.org/pdf/2410.17389"><em>Navigating Noisy Feedback: Enhancing Reinforcement Learning with Error-Prone Language Models</em></a></p>
      <p class="authors" style="font-size: 13px;">
        <strong>Muhan Lin</strong>, Shuyang Shi, Yue Guo, Behdad Chalaki, Vaishnav Tadiparthi, Ehsan Moradi Pari, Simon Stepputtis, Joseph Campbell, Katia Sycara
      </p>
    </div>

    <!-- RLBrew Workshop, RLC 2024 Entry -->
    <div class="publication-entry">
      <h3>[RLBrew Workshop, RLC 2024]</h3>
      <p class="publication-title" style="font-size: 16px;"><a href="https://rlbrew-workshop.github.io/papers/39_a_reward_analysis_of_reinforce.pdf"><em>A Reward Analysis of Reinforcement Learning from Large Language Model Feedback</em></a></p>
      <p class="authors" style="font-size: 13px;">
        <strong>Muhan Lin</strong>, Shuyang Shi, Yue Guo, Behdad Chalaki, Vaishnav Tadiparthi, Simon Stepputtis, Joseph Campbell, Katia Sycara
      </p>
    </div>

    <!-- Keywords -->
    <div class="keywords">
      <span class="keyword">Reward Design</span>
      <span class="keyword">Reinforcement Learning</span>
      <span class="keyword">LLM</span>
    </div>

    <!-- Description -->
    <p class="description" style="font-size: 14px;">
      Extended <em>RL from LLM Feedback</em> to work well with small language models which may produce incorrect rankings:
    </p>
    <ul style="font-size: 14px;">
      <li>Proposed a potential-based reward specification method to scale down rewards based on LLM feedback uncertainty.</li>
      <li>Theoretically and empirically showed that uncertain LLM feedback leads to uninformative potential-based rewards, avoiding misleading rewards and enabling efficient training even with small error-prone LLMs.</li>
    </ul>


    <!-- Links -->
    <div class="links" style="display: inline;">
      <a href="https://arxiv.org/pdf/2410.17389"><strong style="color: skyblue;">Paper</strong></a> /
      <a href="https://youtu.be/jKKUqB-nf7Y"><strong style="color: skyblue;">Video</strong></a> /
      <a href="https://github.com/sy-shi/RLAIF_ScoreDiff"><strong style="color: skyblue;">Code</strong></a>
    </div>
  </div>
</div>

<div class="project">
  <div class="project-image">
    <img src="/assets/img/credit-assign.svg" alt="Project Image" class="project-logo">
  </div>
  <div class="project-content">
    <h2>AI-based Credit Assignment</h2>

    <div class="publication-entry">
      <p class="publication-title" style="font-size: 16px;"><em>Speaking the Language of Teamwork: LLM-Guided Credit Assignment in Multi-Agent Reinforcement Learning</em></p>
      <p class="authors" style="font-size: 13px;">
        <strong>Muhan Lin</strong>, Shuyang Shi, Yue Guo, Vaishnav Tadiparthi, Behdad Chalaki, Ehsan Moradi Pari, Simon Stepputtis, Woojun Kim, Joseph Campbell, Katia Sycara
      </p>
    </div>
    <p class="description" style="font-size: 14px;"> In submission </p>

    <!-- Keywords -->
    <div class="keywords">
      <span class="keyword">Multi-agent Reinforcement Learning</span>
      <span class="keyword">Reward Design</span>
      <span class="keyword">LLM</span>
    </div>

    <!-- Description -->
    <p class="description" style="font-size: 14px;">
      Extended the error-tolerant RLAIF to multiagent collaboration tasks for credit assignment, decomposing team rewards to individual ones with LLM feedback.
    </p>


    <!-- Links -->
    <!-- <div class="links" style="display: inline;">
      <a href="https://arxiv.org/pdf/2410.17389"><strong style="color: skyblue;">Paper</strong></a> /
      <a href="https://youtu.be/jKKUqB-nf7Y"><strong style="color: skyblue;">Video</strong></a> /
      <a href="https://github.com/sy-shi/RLAIF_ScoreDiff"><strong style="color: skyblue;">Code</strong></a>
    </div> -->
  </div>
</div>

<div class="project">
  <div class="project-image">
    <img src="/assets/img/ad hoc team.svg" alt="Project Image" class="project-logo">
  </div>

  <div class="project-content">
    <h2>Action Advising for Efficient RL in Ad Hoc Teaming</h2>
    <div class="publication-entry">
      <p class="publication-title" style="font-size: 16px;"><em>Enhancing Multi-Agent Teaming Efficiency Through Experience-Based Action Advising</em></p>
      <p class="authors" style="font-size: 13px;">
        Shuyang Shi, Yue Guo, <strong>Muhan Lin</strong>, Vaishnav Tadiparthi, Behdad Chalaki, Ehsan Moradi Pari, Simon Stepputtis, Woojun Kim, Joseph Campbell, Katia Sycara
      </p>
    </div>
    <p class="description" style="font-size: 14px;"> In submission </p>
    <!-- <a href="link_to_paper" class="paper-link">Paper</a> -->
    <div class="keywords">
      <a class="keyword">Transfer Learning</a>
      <a class="keyword">Multi-agent Reinforcement Learning</a>
      <!-- Add more keywords as needed -->
    </div>
    <p class="description" style="font-size: 14px;"> Accelerated multiagent RL by enabling agents with different levels of prior competency to cooperate effectively in solving a shared task: </p>
    <ul style="font-size: 14px;">
      <li>Using a multi-armed bandit algorithm, the most experienced agent evaluated teammates' skills, assigned suitable sub-tasks, and adapted agents to these tasks via a policy advising algorithm, improving team learning and task efficiency.</li>
    </ul>
  </div>
</div>

<div class="project">
  <div class="project-image">
    <video autoplay loop muted class="project-logo">
      <source src="/assets/video/painting demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  <div class="project-content">
    <h2>Creative Mobile Robot Wall Painting</h2>
    <!-- <a href="link_to_paper" class="paper-link">Paper</a> -->
    <div class="keywords">
      <!-- <a href="link_to_related_content" class="keyword">Paper</a> -->
      <a class="keyword">ROS</a>
      <a class="keyword">Mobile Manipulator</a>
      <a class="keyword">VLM</a>
      <!-- Add more keywords as needed -->
    </div>
    Implemented a mobile manipulator navigation framework for large-scale wall-painting. Integrated VLM models to enable image-to-stroke creative painting.
  </div>
</div>
---
## Past Work
<div class="project">
  <div class="project-image">
    <img src="/assets/img/STPG.png" alt="Project Image" class="project-logo">
  </div>
  <div class="project-content">
    <h2>Addressing Unexpected Delays in Multi-agent Path Plan Execution</h2>
    <div class="publication-entry">
      <h3>[AAAI 2025 (Oral)]</h3>
      <p class="publication-title" style="font-size: 16px;"><a href="https://arxiv.org/pdf/2412.15908"><em>Speedup Techniques for Switchable Temporal Plan Graph Optimization</em></a></p>
      <p class="authors" style="font-size: 13px;">
        He Jiang, <strong>Muhan Lin</strong>, Jiaoyang Li
      </p>
    </div>
    <div class="keywords">
      <a class="keyword">Multi-agent Systems</a>
      <a class="keyword">Path Planning</a>
      <!-- Add more keywords as needed -->
    </div>
    <p style="font-size: 14px;"> Optimizing a Switchable Temporal Plan Graph (STPG) is a common approach to handling unexpected delays in multi-agent path plan execution. We proposed acceleration techniques for this procedure, including stronger admissible heuristics, edge grouping, prioritized branching and incremental implementation.</p>
    <ul style="font-size: 14px;">
      <li>Achieved over 100% improvement in STPG reconstruction success rates within 0.5 seconds across maps with varying agent densities, outperforming <em>Mixed-Integer Linear Programming</em> and <em>naive graph-based methods</em>.</li>
    </ul>
    <div class="links" style="display: inline;">
      <a href="https://arxiv.org/pdf/2412.15908"><strong style="color: skyblue;">Paper</strong></a> /
      <!-- <a href="https://youtu.be/jKKUqB-nf7Y"><strong style="color: skyblue;">Video</strong></a> / -->
      <a href="https://github.com/DiligentPanda/STPG"><strong style="color: skyblue;">Code</strong></a>
    </div>
  </div>
</div>

<div class="project">
  <div class="project-image">
    <img src="/assets/img/2robot.png" alt="Project Image" class="project-logo">
  </div>
  <div class="project-content">
    <h2>Multi-robot Relative Pose Estimation with Distance-measuring Units and Odometry Information</h2>
    <div class="publication-entry">
      <h3>[Transactions on Mechatronics (TMECH) 2023]</h3>
      <p class="publication-title" style="font-size: 16px;"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10142210"><em>Asymptotically Efficient Estimators for Range‑based Robot Relative Localization</em></a></p>
      <p class="authors" style="font-size: 13px;">
        Yue Wang, <strong>Muhan Lin</strong>, Xinyi Xie, Yuan Gao, Fuqin Deng, Tin Lun Lam
      </p>
    </div>
    <div class="keywords">
      <a class="keyword">Multi-agent Systems</a>
      <a class="keyword">Pose Estimation</a>
      <!-- Add more keywords as needed -->
    </div>
    <p style="font-size: 14px;"> Enhanced localization accuracy in multiagent systems, where robots communicated their odometry trajectories and relative distance with each other and then estimated their initial relative poses. Reduced the estimation residuals to the Cramer-Rao Lower Bound.</p>
    <div class="links" style="display: inline;">
      <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10142210"><strong style="color: skyblue;">Paper</strong></a> /
      <a href="https://www.youtube.com/watch?v=kd_uIMl4f6I"><strong style="color: skyblue;">Video</strong></a>
    </div>
  </div>
</div>

<div class="project">
  <div class="project-image">
    <img src="/assets/img/active-feature.jpg" alt="Project Image" class="project-logo">
  </div>
  <div class="project-content">
    <h2>Active Feature Selection for Pose Estimation of Visual Odometry</h2>
    <div class="publication-entry">
      <h3>[RISS Journal 2022]</h3>
      <p class="publication-title" style="font-size: 16px;"><a href="https://riss.ri.cmu.edu/wp-content/uploads/2023/08/CMU-RISS_Working_Papers_Journal-2022-PAPERS.pdf"><em>Less Is More: A Robust Visual Inertial Odometry with Active Feature Selection</em></a></p>
      <p class="authors" style="font-size: 13px;">
        <strong>Muhan Lin</strong>, Shibo Zhao, Sebastian Scherer
      </p>
    </div>
    <div class="keywords">
      <a class="keyword">Computer Vision</a>
      <a class="keyword">SLAM</a>
      <!-- Add more keywords as needed -->
    </div>
    <p style="font-size: 14px;"> Developed a quality measurement metric to select visual feature points for the multi-spectral odometry:</p>
    <ul style="font-size: 14px;">
      <li>Improved the accuracy of visual odometry pose estimation and efficiency (13.036% of the original residuals, 58.832% of the original CPU usage) with filtered visual feature points in dark environments.</li>
    </ul>
    <div class="links" style="display: inline;">
      <a href="https://riss.ri.cmu.edu/wp-content/uploads/2023/08/CMU-RISS_Working_Papers_Journal-2022-PAPERS.pdf"><strong style="color: skyblue;">Paper</strong></a>
    </div>
  </div>
</div>

<!-- **Mechanism Design** -->

<!-- - [Integrated quadruped-hexarotor system: design](/research/hexarotor/#system-design) -->

<!-- <html>
<div>
  <div>
  <img src="hexarotor/assets/img/flight_1.png" style="zoom:5%;" />
  <img src="hexarotor/assets/img/flight_1.png" style="zoom:5%;" />
  <div>
</div>
</html> -->

<!-- **Control and Planning** -->
<!-- - [Path Planning for mobile robots](/research/path-plan/)
<!-- - [Integrated quadruped-hexarotor system: control](/research/hexarotor/#control) -->
<!-- - [Navigation for UR-10 manipulators](/research/ur10-nav/#navigation) -->

<!-- **Collaborative Systems** -->
<!-- - [Large-scale collective behavior manipulation](/research/large_scale/) -->
<!-- - [Active vision scheduling of multi-UGV systems](/research/active_vision/) (dissertation) -->
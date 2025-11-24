---
layout: single
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---

I have explored diverse research domains and topics throughout my academic journey: evaluation, dataset benchmarks, AI4SE (AI for software engineering), AI4Edu (AI for Education), agents, mechanistic interpretability, transportation...

Below are some of my works tagged by theme. 

**(\* equal contribution; \*\* core member and sub-team lead)**

---

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/terminal-bench.png" alt="Terminal-Bench">
  </div>
  <div class="research-entry__content">
    <strong>Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces</strong><br>
    <span style="background-color: #E8F4FD; color: #1565C0; padding: 2px 8px; border-radius: 4px; border: 1px solid #1565C0; font-size: 0.85em; margin-right: 5px;">Evaluation</span>
    <span style="background-color: #FFF3E0; color: #E65100; padding: 2px 8px; border-radius: 4px; border: 1px solid #E65100; font-size: 0.85em; margin-right: 5px;">Agent</span>
    <span style="background-color: #F3E5F5; color: #7B1FA2; padding: 2px 8px; border-radius: 4px; border: 1px solid #7B1FA2; font-size: 0.85em;">Dataset Benchmark</span><br>
    <span style="color: #8B0000;"><em>Stanford University & Laude Institute</em></span><br>
    <em>Mike Merrill*, Alex Shaw*, Nicholas Carlini**, Boxuan Li**, Harsh Raj**, Ivan Bercovich**, <strong>Lin Shi**</strong>, et al.</em><br>
    <strong style="color: #00008B;">Terminal Bench 1.5 under review; Adapters paper planning for submission to ICML 2026 </strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">I am a <strong>core contributor</strong> in Terminal Bench and <a href="https://harborframework.com/docs">Harbor</a>. I lead the <a href="https://harborframework.com/docs/adapters">Registry and Adapter Team</a> to adapt other benchmarks into Terminal-Bench / Harbor format that aim to make agent evaluation uniform, convenient, and easy. I managed 50+ benchmark adapters covering 5000+ tasks by coordinating 100+ contributors and directed adapter standardization, benchmark screening, and code quality control. <strong>We are still recruiting open-source community contributors to get more adapters onboard - feel free to reach out!</strong></p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/deveval.png" alt="DevEval">
  </div>
  <div class="research-entry__content">
    <strong>Prompting Large Language Models to Tackle the Full Software Development Lifecycle: A Case Study</strong><br>
    <span style="background-color: #E8F4FD; color: #1565C0; padding: 2px 8px; border-radius: 4px; border: 1px solid #1565C0; font-size: 0.85em; margin-right: 5px;">Evaluation</span>
    <span style="background-color: #F3E5F5; color: #7B1FA2; padding: 2px 8px; border-radius: 4px; border: 1px solid #7B1FA2; font-size: 0.85em;">Dataset Benchmark</span><br>
    <span style="color: #8B0000;"><em>Shanghai AI Lab</em></span><br>
    <em>Bowen Li*, Wenhan Wu*, Ziwei Tang*, <strong>Lin Shi*</strong>, et al.</em><br>
    <strong style="color: #00008B;">COLING 2025</strong> | <a href="https://aclanthology.org/2025.coling-main.502/">ACL Anthology</a><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">DevEval, a dataset and evaluation framework for assessing LLMs across software development lifecycle (software design, environment setup, implementation, unit testing, acceptance testing); released on <a href="https://github.com/open-compass/DevEval">OpenCompass</a>.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/judging-judges.png" alt="Judging the Judges">
  </div>
  <div class="research-entry__content">
    <strong>Judging the Judges: A Systematic Study of Position Bias in LLM-as-a-Judge</strong><br>
    <span style="background-color: #E8F4FD; color: #1565C0; padding: 2px 8px; border-radius: 4px; border: 1px solid #1565C0; font-size: 0.85em;">Evaluation</span><br>
    <span style="color: #8B0000;"><em>Dartmouth College</em></span><br>
    <em><strong>Lin Shi</strong>, Chiyu Ma, Wenhua Liang, Weicheng Ma, Soroush Vosoughi</em><br>
    <strong style="color: #00008B;">AACL-IJCNLP 2025 Main</strong> | <a href="https://arxiv.org/abs/2406.07791">arXiv</a><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">A systematic framework for evaluating position bias of LLM judges by repetition stability, position consistency, and preference fairness; investigated key factors driving position bias.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/many-minds.png" alt="Judging with Many Minds">
  </div>
  <div class="research-entry__content">
    <strong>Judging with Many Minds: Do More Perspectives Mean Less Prejudice?</strong><br>
    <span style="background-color: #E8F4FD; color: #1565C0; padding: 2px 8px; border-radius: 4px; border: 1px solid #1565C0; font-size: 0.85em; margin-right: 5px;">Evaluation</span>
    <span style="background-color: #FFF3E0; color: #E65100; padding: 2px 8px; border-radius: 4px; border: 1px solid #E65100; font-size: 0.85em;">Agent</span><br>
    <span style="color: #8B0000;"><em>Dartmouth College</em></span><br>
    <em>Chiyu Ma, Enpei Zhang, Yilun Zhao, Wenjun Liu, Yaning Jia, Peijun Qing, <strong>Lin Shi</strong>, et al.</em><br>
    <strong style="color: #00008B;">EMNLP 2025 Findings</strong> | <a href="https://aclanthology.org/2025.findings-emnlp.941/">ACL Anthology</a><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Multi-Agent-Debate exacerbates biases; LLM-as-meta-judges resist them.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/msra.png" alt="Microsoft Research Asia">
  </div>
  <div class="research-entry__content">
    <strong>SAILRTS: Multimodal Multi-Agent System for Automated Software Issue Resolution</strong><br>
    <span style="background-color: #FFF3E0; color: #E65100; padding: 2px 8px; border-radius: 4px; border: 1px solid #E65100; font-size: 0.85em;">Agent</span><br>
    <span style="color: #8B0000;"><em>Microsoft Research Asia</em></span><br>
    <em>Informal Research Intern</em><br>
    <strong style="color: #00008B;">In preparation for ICML 2026</strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Designed SAILRTS, a multimodal multi-agent system for automated real-world software-issue resolution through context isolation, enhanced codebase analysis, and bidirectional code–image localization.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/ai-education-cmu.png" alt="AI Education CMU">
  </div>
  <div class="research-entry__content">
    <strong>Learning Path Optimization by Agent-simulated Students</strong><br>
    <span style="background-color: #E8F5E9; color: #2E7D32; padding: 2px 8px; border-radius: 4px; border: 1px solid #2E7D32; font-size: 0.85em; margin-right: 5px;">AI Education</span>
    <span style="background-color: #FFF3E0; color: #E65100; padding: 2px 8px; border-radius: 4px; border: 1px solid #E65100; font-size: 0.85em;">Agent</span><br>
    <span style="color: #8B0000;"><em>CMU-OAK Lab</em></span><br>
    <em>Visiting Researcher, supervised by Professor Paulo Carvalho</em><br>
    <strong style="color: #00008B;">In progress</strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Developed a reinforcement-learning-inspired framework to identify learning segments and knowledge components to construct, evaluate, and optimize personalized learning paths.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/adaptive-learning.png" alt="Adaptive Learning Platform">
  </div>
  <div class="research-entry__content">
    <strong>Adaptive Learning Platform for CS Education</strong><br>
    <span style="background-color: #E8F5E9; color: #2E7D32; padding: 2px 8px; border-radius: 4px; border: 1px solid #2E7D32; font-size: 0.85em;">AI Education</span><br>
    <span style="color: #8B0000;"><em>Dartmouth College</em></span><br>
    <em>Senior Thesis, supervised by Professor Soroush Vosoughi</em><br>
    <strong style="color: #00008B;">November 2023 – August 2025</strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">AI-powered adaptive learning platform deployed for Dartmouth CS1 courses to personalize practice problems, learning progress, and feedback loop. Try it <a href="https://cs1-helper.dartmouth.edu/">here</a> (only available to Dartmouth students with password)!</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/educational-game.png" alt="Educational Game">
  </div>
  <div class="research-entry__content">
    <strong>Universal Matching Game</strong><br>
    <span style="background-color: #E8F5E9; color: #2E7D32; padding: 2px 8px; border-radius: 4px; border: 1px solid #2E7D32; font-size: 0.85em;">AI Education</span><br>
    <span style="color: #8B0000;"><em>Dartmouth College</em></span><br>
    <em>Neukom Scholar Project</em><br>
    <strong style="color: #00008B;">Deployed at Dartmouth</strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">A full-stack multiplayer matching-game. Learn by matching and for fun! Use AI to translate materials into pairs, learn them by matching, and play against others. Try it <a href="https://universalmatching.com/">here</a>.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/mechanistic.png" alt="Mechanistic Insights">
  </div>
  <div class="research-entry__content">
    <strong>Mechanistic Insights: Circuit Transformations Across Input and Fine-Tuning Landscapes</strong><br>
    <span style="background-color: #FCE4EC; color: #C2185B; padding: 2px 8px; border-radius: 4px; border: 1px solid #C2185B; font-size: 0.85em;">Mechanistic Interpretability</span><br>
    <span style="color: #8B0000;"><em>Dartmouth College</em></span><br>
    <em>Chiyu Ma*, <strong>Lin Shi*</strong>, Ollie Liu, Wenhua Liang, Jiaqi Gan, Ming Cheng, Willie Neiswanger, Soroush Vosoughi</em><br>
    <strong style="color: #00008B;">Under review at TMLR</strong><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Investigated how ablated inputs and fine-tuning methods (e.g., LoRA, Bitfit) modify circuits of LLMs; proposed efficient framework to explore model component functionalities.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/transport-pm25.png" alt="Built Environment">
  </div>
  <div class="research-entry__content">
    <strong>Built Environment, Car Ownership and PM2.5: Stronger Causal Estimates from a Quasi-Experiment</strong><br>
    <span style="background-color: #EFEBE9; color: #4E342E; padding: 2px 8px; border-radius: 4px; border: 1px solid #4E342E; font-size: 0.85em;">Transportation</span><br>
    <span style="color: #8B0000;"><em>Harvard University</em></span><br>
    <em><strong>Lin Shi*</strong>, Yiliang Jiang*, Faan Chen*, et al.</em><br>
    <strong style="color: #00008B;">Journal of Transport Geography</strong> | <a href="https://doi.org/10.1016/j.jtrangeo.2025.104301">DOI</a><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Applied Structural Equation Modeling (SEM) to estimate the causal impact of built environment on resident travel behavior, providing valuable insights for urban planning and transportation research.</p>
  </div>
</div>

<div class="research-entry">
  <div class="research-entry__image">
    <img src="/images/research/road-safety.png" alt="Road Safety">
  </div>
  <div class="research-entry__content">
    <strong>Measuring Road Safety Achievement Based on EWM-GRA-SVD: A Decision-Making Support System for APEC Countries</strong><br>
    <span style="background-color: #EFEBE9; color: #4E342E; padding: 2px 8px; border-radius: 4px; border: 1px solid #4E342E; font-size: 0.85em;">Transportation</span><br>
    <span style="color: #8B0000;"><em>Harvard University</em></span><br>
    <em>Faan Chen*, <strong>Lin Shi*</strong>, et al.</em><br>
    <strong style="color: #00008B;">Knowledge-Based Systems</strong> | <a href="https://doi.org/10.1016/j.knosys.2022.109373">DOI</a><br>
    <p style="margin-top: 10px; color: #555; margin-bottom: 0;">Proposed multi-criteria decision making (MCDM) frameworks for transportation and environmental policy analysis, providing road-safety policymaking support for APEC countries.</p>
  </div>
</div>

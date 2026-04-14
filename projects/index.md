---
layout: default
title: Projects
---

<div class="hero-section" style="margin-bottom: 40px;">
  <h1>Archive</h1>
  <p class="hero-tagline">Research & Engineering &mdash; <span>SISSA & Area Science Park</span></p>
</div>

<div class="featured-projects">

  <!-- LLaVA Representations -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/llava_representations.png' | relative_url }}" alt="LLaVA Architecture and Representations">
    </div>
    <div class="project-content">
      <span class="project-tag" style="background: rgba(195, 142, 255, 0.1); color: var(--accent-purple);">Active Research</span>
      <a href="https://github.com/luisfpal/LLaVA_Representations_Analysis" class="project-title">VLM Interpretability & Geometry</a>
      <p class="project-desc">Ongoing research investigating how visual instruction tuning reshapes internal geometry. Identified that early-mid layers learn to "see" while late layers handle decoding. Serving as the foundation for current VLM interpretability work.</p>
      <div class="project-tech">
        <span class="tech-tag">PyTorch</span>
        <span class="tech-tag">HuggingFace</span>
        <span class="tech-tag">LLaVA / Llama2</span>
      </div>
    </div>
  </div>

  <!-- Emu3 / NLP -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/nlp_emu3.png' | relative_url }}" alt="Emu3 Generated Image Quintuplet">
    </div>
    <div class="project-content">
      <span class="project-tag">Generative AI</span>
      <a href="https://github.com/luisfpal/NLP-UniTS" class="project-title">Emu3 Generation Quality</a>
      <p class="project-desc">Evaluated the impact of vision-understanding fine-tuning on image generation quality. Benchmarked Emu3 models using MSCOCO and FID metrics on A100 clusters.</p>
      <div class="project-tech">
        <span class="tech-tag">Emu3</span>
        <span class="tech-tag">MSCOCO</span>
        <span class="tech-tag">FID</span>
        <span class="tech-tag">NVIDIA A100</span>
      </div>
    </div>
  </div>

  <!-- XAI / Robustness -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/xai_robustness.png' | relative_url }}" alt="Grad-CAM explanations of adversarial attacks">
    </div>
    <div class="project-content">
      <span class="project-tag">Reliable AI</span>
      <a href="https://github.com/luisfpal/XAI-RAI-UniTS" class="project-title">Model Robustness & XAI</a>
      <p class="project-desc">Analyzed the robustness of ResNet, ViT, and Swin backbones against adversarial attacks. Evaluated XAI explanations (Grad-CAM, Captum) under noise perturbations.</p>
      <div class="project-tech">
        <span class="tech-tag">Vision Transformers</span>
        <span class="tech-tag">Grad-CAM</span>
        <span class="tech-tag">Adversarial ML</span>
      </div>
    </div>
  </div>

  <!-- Diffusion Models -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/diffusion_anomaly.svg' | relative_url }}" alt="Diffusion Anomaly Correction">
    </div>
    <div class="project-content">
      <span class="project-tag">Probabilistic ML</span>
      <a href="https://github.com/luisfpal/ProbabilisticMachineLearningAndDeepLearning-UniTS" class="project-title">Diffusion Anomaly Correction</a>
      <p class="project-desc">Developed an anomaly correction pipeline for categorical data. Combined classifier gradients with data distributions learned via diffusion models to refine predictions.</p>
      <div class="project-tech">
        <span class="tech-tag">Diffusion Models</span>
        <span class="tech-tag">Anomaly Detection</span>
        <span class="tech-tag">JAX/PyTorch</span>
      </div>
    </div>
  </div>

  <!-- Cloud Computing -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/cloud_computing.svg' | relative_url }}" alt="Distributed Systems Observability">
    </div>
    <div class="project-content">
      <span class="project-tag">Distributed Systems</span>
      <a href="https://github.com/luisfpal/CloudComputing-UniTS" class="project-title">Cloud Observability & Testing</a>
      <p class="project-desc">Implemented a containerized Nextcloud deployment with a robust observability pipeline. Evaluated system scalability using Prometheus, Grafana, and Locust load testing.</p>
      <div class="project-tech">
        <span class="tech-tag">Docker</span>
        <span class="tech-tag">Prometheus/Grafana</span>
        <span class="tech-tag">Locust</span>
      </div>
    </div>
  </div>

  <!-- Optimization -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/evolutionary_game_theory.png' | relative_url }}" alt="Iterated Prisoner's Dilemma Results">
    </div>
    <div class="project-content">
      <span class="project-tag">Evolutionary AI</span>
      <a href="https://github.com/luisfpal/OptimizationForArtificialIntelligence-UniTS" class="project-title">Evolutionary Game Theory</a>
      <p class="project-desc">Evolved adaptive strategies for the Iterated Prisoner’s Dilemma using Genetic Algorithms. Benchmarked against Axelrod’s classic tournament strategies.</p>
      <div class="project-tech">
        <span class="tech-tag">Genetic Algorithms</span>
        <span class="tech-tag">Game Theory</span>
        <span class="tech-tag">Python</span>
      </div>
    </div>
  </div>

  <!-- ADL -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/equivariant_cnns.svg' | relative_url }}" alt="Group Equivariant CNN Symmetry">
    </div>
    <div class="project-content">
      <span class="project-tag">Geometric Deep Learning</span>
      <a href="https://github.com/luisfpal/AdvancedDeepLearning-UniTS" class="project-title">Equivariant Networks & Frame Theory</a>
      <p class="project-desc">Designed architectures that exploit inherent data symmetries. Implemented Group Equivariant CNNs (G-CNNs) and Low Coherence MLPs to enhance training efficiency.</p>
      <div class="project-tech">
        <span class="tech-tag">PyTorch</span>
        <span class="tech-tag">Symmetry</span>
        <span class="tech-tag">Frame Theory</span>
      </div>
    </div>
  </div>

  <!-- RL -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/rl_control.png' | relative_url }}" alt="Soft Actor-Critic Control in Gymnasium">
    </div>
    <div class="project-content">
      <span class="project-tag">Reinforcement Learning</span>
      <a href="https://github.com/luisfpal/ReinforcementLearning-UniTS" class="project-title">Soft Actor-Critic Control</a>
      <p class="project-desc">Implemented Soft Actor-Critic (SAC) and TD3 algorithms for continuous control tasks. Evaluated performance across complex Gymnasium environments.</p>
      <div class="project-tech">
        <span class="tech-tag">Gymnasium</span>
        <span class="tech-tag">SAC</span>
        <span class="tech-tag">TD3</span>
      </div>
    </div>
  </div>

  <!-- Multi-Fidelity -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/inverse_pdes.png' | relative_url }}" alt="Multi-fidelity Inverse PDE Results">
    </div>
    <div class="project-content">
      <span class="project-tag">Physics-Informed ML</span>
      <a href="https://github.com/luisfpal/SimulationIntelligenceAndLearningForAutonomousSystems-UniTS" class="project-title">Multi-Fidelity Inverse PDEs</a>
      <p class="project-desc">Combined composite neural networks for multi-fidelity data with Proximal Policy Optimization (PPO) for autonomous system control and inverse PDE solving.</p>
      <div class="project-tech">
        <span class="tech-tag">PDEs</span>
        <span class="tech-tag">PPO</span>
        <span class="tech-tag">PyTorch</span>
      </div>
    </div>
  </div>

  <!-- Statistical Methods -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/statistical_methods.svg' | relative_url }}" alt="Statistical Methods and Data Analysis">
    </div>
    <div class="project-content">
      <span class="project-tag">Statistical ML</span>
      <a href="https://github.com/luisfpal/StatisticalMethods-UniTS" class="project-title">Statistical Analysis & Modeling</a>
      <p class="project-desc">End-to-end statistical analysis project focusing on rigorous data processing, robust modeling, and reproducible research reporting.</p>
      <div class="project-tech">
        <span class="tech-tag">R</span>
        <span class="tech-tag">RMarkdown</span>
        <span class="tech-tag">Inference</span>
      </div>
    </div>
  </div>

  <!-- HPC -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/hpc.svg' | relative_url }}" alt="High Performance Computing OpenMP Execution">
    </div>
    <div class="project-content">
      <span class="project-tag">HPC & Optimization</span>
      <a href="https://github.com/luisfpal/HighPerformanceComputing-UniTS" class="project-title">High Performance Computing</a>
      <p class="project-desc">Parallel computing and hardware optimization for scientific simulations. Focused on C-based performance tuning and CMake-driven builds.</p>
      <div class="project-tech">
        <span class="tech-tag">C</span>
        <span class="tech-tag">OpenMP / MPI</span>
        <span class="tech-tag">CMake</span>
      </div>
    </div>
  </div>

  <!-- Advanced Programming -->
  <div class="project-card glass">
    <div class="project-image-container">
      <img class="project-image" src="{{ '/assets/img/projects/cpp_patterns.svg' | relative_url }}" alt="C++ Software Engineering Patterns">
    </div>
    <div class="project-content">
      <span class="project-tag">Software Eng</span>
      <a href="https://github.com/luisfpal/AdvancedProgramming-SISSA" class="project-title">Scientific C++ Engineering</a>
      <p class="project-desc">Advanced software engineering patterns for scientific applications at SISSA. Focused on memory management and high-performance design.</p>
      <div class="project-tech">
        <span class="tech-tag">C++</span>
        <span class="tech-tag">Design Patterns</span>
        <span class="tech-tag">Memory Ops</span>
      </div>
    </div>
  </div>

</div>
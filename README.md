# DisentTalk: Cross-lingual Talking Face Generation via Semantic Disentanglement Diffusion

<div align="center">

Anonymous Authors

Submitted to ICME 2025

<!-- [Paper](#) | [Project Page](#) | [Code](#)  -->

</div>

## Abstract
Existing diffusion-based audio-driven talking face generation methods often suffer from poor lip synchronization and unnatural facial expressions, with these issues being particularly pronounced in cross-lingual scenarios. These performance issues stem from two fundamental scientific challenges: the semantic entanglement of facial intermediate representations (e.g., 3DMM parameters) and the isolated processing of spatial-temporal features. To address these challenges, we present a novel framework with two key innovations: (1) a data-driven semantic disentanglement approach that decomposes 3DMM parameters into meaningful subspaces for fine-grained facial region control, and (2) a hierarchical diffusion architecture with region-aware attention that jointly models spatial-temporal features throughout generation. We further introduce CHDTF, a Chinese high-definition talking face dataset for cross-lingual evaluation. Extensive experiments demonstrate that our method outperforms existing approaches, achieving superior lip synchronization and natural expressions while maintaining temporal coherence.

## Method Overview
<div align="center">
<img src="framework.jpg" width="800px"/>
</div>

## Supplementary Video Materials

### Introduction Video in Different Languages
<div align="center">
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="Intro/art_intro_English.mp4" type="video/mp4">
    </video>
    <br>
    <em>Introduction Video in English</em>
    <br>
    <video width="80%" controls>
      <source src="Intro/art_intro_Chinese.mp4" type="video/mp4">
    </video>
    <br>
    <em>Introduction Video in Chinese</em>
    <br>
    <video width="80%" controls>
      <source src="Intro/art_intro_Japan.mp4" type="video/mp4">
    </video>
    <br>
    <em>Introduction Video in Japanese</em>
    <br>
    <video width="80%" controls>
      <source src="Intro/art_intro_Spanish.mp4" type="video/mp4">
    </video>
    <br>
    <em>Introduction Video in Spanish</em>
  </div>


### Comparison of Different Methods (HDTF dataset)
<div align="center">
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="HDTF/algorithm_comparison_rd_radio53_crop_256_000.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="HDTF/algorithm_comparison_wda_chrisvanhollen1_crop_256_000.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="HDTF/algorithm_comparison_wra_mikecrapo_crop_256_000.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="HDTF/algorithm_comparison_wra_vickyhartzler_crop_256_000.mp4" type="video/mp4">
    </video>
    <br>
    <em>Comparison of Different Methods (HDTF dataset)</em>
  </div>

### Comparison of Different Methods (CHDTF dataset)
<div align="center">
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="CHDTF/algorithm_comparison_baoxiaofeng_187_crop_0_260.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="CHDTF/algorithm_comparison_kanghui_18_crop_0_200.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="CHDTF/algorithm_comparison_lizimeng_169_crop_0_300.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="CHDTF/algorithm_comparison_yanyuxin_36_crop_0_300.mp4" type="video/mp4">
    </video>
    <br>
    <em>Comparison of Different Methods (CHDTF dataset)</em>
  </div>

### Comparison of Different Methods (Voxceleb2 dataset, multilingual)
<div align="center">
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00343.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00365.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00383.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00416.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00429.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="Vox2/algorithm_comparison_id00459.mp4" type="video/mp4">
    </video>
    <br>
    <em>Comparison of Different Methods (Voxceleb2 dataset, multilingual)</em>
  </div>

### Disentanglement Analysis of 3DMM Parameters
<div align="center">
<video width="80%" controls>
  <source src="show_disentangle/disentagle_videos_.mp4" type="video/mp4">
</video>
<br>
<em>Demonstration of Disentanglement of 3DMM Parameters</em>
</div>

### Weight Comparison Experiment
<div align="center">
<video width="80%" controls>
  <source src="ablation_weight/weight_comparison22.mp4" type="video/mp4">
</video>
<br>
<em>Demonstration of Different Weights Effects</em>
</div>


### Ablation Study on Different Components
<div align="center">
<div class="grid-container">
  <div class="grid-item">
    <video width="100%" controls>
      <source src="ablation_model/Components_comparison_222.mp4" type="video/mp4">
    </video>
    <br>
    <em>Ablation Study on Different Components</em>
  </div>
</div>
</div>
</div>

# Thanks for your attention! We will update the project page and code later.

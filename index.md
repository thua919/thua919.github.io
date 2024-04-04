<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
<tr style="padding:0px">
  <td style="padding:1% 1% 1% 0%;width:62%;vertical-align:middle">
    <h1>
      Tongyan Hua - 华 彤延
    </h1>
    <p>
      <!-- <a target="_blank" href=""></a>-->
      I am a Ph.D. student in the <a target="_blank" href="https://wufan-zhao.github.io/group/">AI 4D City (AI4City)</a> Lab
      at HKUST, Guangzhou, supervised by Prof. <a target="_blank" href="https://scholar.google.com/citations?user=SE267o4AAAAJ">Wufan Zhao</a>. 
      My current research interests focus on AI-based 3D computer vision. I have had the honour to collaborate with Prof. 
      <a target="_blank" href="https://scholar.google.com/citations?user=vsE4nKcAAAAJ&hl=zh-CN">Wenming Yang</a> at Tsinghua University and dear Prof. <a target="_blank" href="https://scholar.google.com/citations?user=SReb2csAAAAJ&hl=en">Addison Lin Wang</a> at HKUST, working on knowledge distillation and Neural Radiance Fields (NeRF), respectively. Before this, I had extensively explored various research areas, including biotechnology, operational research, and geography, driven by pure interest. I was also a robotics algorithm engineer at 
      <a target="_blank" href="https://en.bgy.com.cn/en/products/construction">Country Garden Group</a>, focusing on visual SLAM for indoor construction robots. 
    </p>
    <p>
I obtained my M.Sc. degree funded by three competitive scholarships at 
<a target="_blank" href="https://www.tudelft.nl/en/">TU Delft</a> and 
<a target="_blank" href="https://www.universiteitleiden.nl/en">Leiden University</a>. 
I completed my B.Sc. degree with the highest thesis score at 
<a target="_blank" href="https://english.jiangnan.edu.cn/">Jiangnan University</a>.

    </p>   
    <p style="text-align:center">
      <a target="_blank" href="mailto:t.hua.msc@outlook.com"> Email</a> &nbsp;/&nbsp;
      <a target="_blank" href="https://github.com/thua919">GitHub</a> &nbsp;/&nbsp;
      <a target="_blank" href="https://scholar.google.com/citations?user=rUGoZaMAAAAJ">Google Scholar</a>
      <!-- <a target="_blank" href="https://www.linkedin.com/in/lizuoyue"> LinkedIn </a> -->
    </p>
  </td>
  <td style="padding:2% 0% 1% 1%;width:38%;max-width:38%">
    <img style="width:100%;max-width:100%" alt="profile photo" src="fig/me_img.jpg">
  </td>
</tr>
</tbody>
</table>


<h1>Research</h1>
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>


<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="fig/cvpr24.png">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Benchmarking Implicit Neural Representation and Geometric Rendering in Real-Time RGB-D SLAM</strong>
      <br>
        <strong>Tongyan Hua</strong>, 
        <a target="_blank" href="https://vlislab22.github.io/vlislab/linwang.html">Lin Wang</a>.
      <br>
      CVPR 2024 &nbsp;/&nbsp; 
      <a target="_blank" href="https://arxiv.org/abs/2403.19473">Paper</a> &nbsp;/&nbsp; 
      <a target="_blank" href="https://vlis2022.github.io/nerf-slam-benchmark/">Project</a> 
    </p>
    <p>
      Implicit neural representation (INR), in combination with geometric rendering, has recently been employed in real-time dense RGB-D SLAM. In this work, we establish, to our knowledge, the first open-source benchmark framework to evaluate the performance of a wide spectrum of commonly used INRs and rendering functions for mapping and localization. 
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/square_placeholder.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>
        Hi-Map:Hierarchical Factorized Radiance Field for High-Fidelity Monocular Dense Mapping
      </strong>
      <br>
        <strong>Tongyan Hua*</strong>, 
        <strong>Haotian Bai*</strong>, 
        <strong>Zidong Cao</strong>, 
        <strong>Ming Liu</strong>, 
        <strong>Dacheng Tao</strong>, 
        <a target="_blank" href="https://vlislab22.github.io/vlislab/linwang.html">Lin Wang</a>.
      <br>
      Pre-print &nbsp;/&nbsp; 
      <a target="_blank" href="https://arxiv.org/abs/2401.03203">Paper</a> &nbsp;/&nbsp; 
      <a target="_blank" href="https://vlis2022.github.io/fmap/">Project</a> 
    </p>
    <p>
      In this paper, we introduce Hi-Map, a novel monocular dense mapping approach based on Neural Radiance Field (NeRF). Hi-Map is exceptional in its capacity to achieve efficient and high-fidelity mapping using only posed RGB inputs. 
    </p>
  </td>
</tr>



<tr onmouseout="sat2scene_stop()" onmouseover="sat2scene_start()">
  <td style="padding:1%;width:20%;max-width:20%;line-height:0;vertical-align:middle">
    <video id="sat2scene_video" style="width:100%;max-width:100%;left:5%;opacity:1" muted loop>
      <source src="assets/sat2scene.mp4" type="video/mp4">Your browser does not support the video tag.
    </video>
    <script type="text/javascript">
      function sat2scene_start() {
        document.getElementById("sat2scene_video").play();
      }
      function sat2scene_stop() {
        document.getElementById("sat2scene_video").pause();
      }
    </script>
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>3D Urban Scene Generation from Satellite Images with Diffusion</strong>
      <br>
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://www.linkedin.com/in/zhenqiangli">Zhenqiang Li</a>, 
        <a target="_blank" href="https://zhpcui.github.io">Zhaopeng Cui</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/marc.pollefeys">Marc Pollefeys</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/moswald">Martin R. Oswald</a>. 
      <br>
      CVPR 2024 &nbsp;/&nbsp; 
      <a target="_blank" href="https://arxiv.org/abs/2401.10786">Paper</a>
    </p>
    <p>
      Generalize diffusion models to 3D sparse space and perform urban scene generation on a given or predicted geometry, followed by neural rendering techniques to render arbitrary views with excellence in both single-frame quality and inter-frame consistency.
    </p>
  </td>
</tr>


</tbody>
</table>


<h1>Awards</h1>
<p>
<!-- <a target="_blank" href="https://www.datascience.ch/phd-fellows">Swiss Data Science Center (SDSC) Fellowship</a>, 2019 -->
Leiden Science China (LSC) scholarship, 2018
<br>
Leiden Science China (LSC) scholarship, 2017
<br>
China Scholarship Council (CSC) Scholarship, 2017
<br>
Academic Honoured Scholarship, 2016
<br>
AMANO Scholarship, 2016
<br>
YUAN XIANG Scholarship, 2016
</p>


<h1>Academic Service</h1>
<p>
<strong>Conference Reviewer</strong>: IROS
<!-- <br> -->
<!-- <strong>Journal Reviewer</strong>: TPAMI, TGRS. -->
</p>

<h1>Teaching</h1>

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>

<!-- <tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=178454&semkez=2024S&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2024
  </td>
</tr> -->

TBD.

</tbody>
</table>


<h1>Contact</h1>
<p>
<strong>Tongyan Hua</strong><br>
No.1 Du Xue Rd<br>
HKUST, Guangzhou<br>
China
</p>

<p align="right">Last update: 04 Apr 2024</p>

<script type="text/javascript">
  function setOpacity(elmId, targetOpacity, stepSize, stepTimeMs) {
    var elm = document.getElementById(elmId);
    var currentOpacity = parseFloat(elm.style.opacity);
    var numSteps = Math.ceil(Math.abs(targetOpacity - currentOpacity) / stepSize);
    stepSize = Math.abs(stepSize);
    if (targetOpacity < currentOpacity) {
      stepSize = -stepSize;
    }
    var i = 0;
    var k = window.setInterval(function() {
      if (i < (numSteps - 1)) {
        i++;
        elm.style.opacity = currentOpacity + i * stepSize;
      } else {
        elm.style.opacity = targetOpacity;
        clearInterval(k);
      }
    }, stepTimeMs);
  };
</script>

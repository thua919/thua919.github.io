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
<!-- <tr style="padding:0px">  
  <h1>Research</h1>
</tr> -->
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

<tr onmouseout="compnvs_stop()" onmouseover="compnvs_start()">
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <video id="compnvs_video" style="width:100%;max-width:100%;left:5%;opacity:1" muted loop>
      <source src="assets/compnvs.mp4" type="video/mp4">Your browser does not support the video tag.
    </video>
    <script type="text/javascript">
      function compnvs_start() {
        document.getElementById("compnvs_video").play();
      }
      function compnvs_stop() {
        document.getElementById("compnvs_video").pause();
      }
    </script>
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>CompNVS: Novel View Synthesis with Scene Completion</strong>
      <br>
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://scholar.google.com/citations?user=siv1RXUAAAAJ">Tianxing Fan</a>, 
        <a target="_blank" href="https://www.linkedin.com/in/zhenqiangli">Zhenqiang Li</a>, 
        <a target="_blank" href="https://zhpcui.github.io">Zhaopeng Cui</a>, 
        <a target="_blank" href="https://sites.google.com/ut-vision.org/ysato">Yoichi Sato</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/marc.pollefeys">Marc Pollefeys</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/moswald">Martin R. Oswald</a>. 
      <br>
      ECCV 2022 &nbsp;/&nbsp; 
      <a target="_blank" href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136610441.pdf">Paper</a>
    </p>
    <p>
      Synthesize novel views from RGB-D images with largely incomplete scene coverage. Perform generation on a sparse grid-based neural representation to complete unobserved scene parts. Extrapolate the missing area and render consistent photorealistic image sequences.
    </p>
  </td>
</tr>

<tr onmouseout="acmmm_stop()" onmouseover="acmmm_start()">
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <video id="acmmm_video" style="width:100%;max-width:100%;left:5%;opacity:1" muted loop>
      <source src="assets/acmmm.mp4" type="video/mp4">Your browser does not support the video tag.
    </video>
    <script type="text/javascript">
      function acmmm_start() {
        document.getElementById("acmmm_video").play();
      }
      function acmmm_stop() {
        document.getElementById("acmmm_video").pause();
      }
    </script>
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Factorized and Controllable Neural Re-rendering of Outdoor Scene for Photo Extrapolation</strong>
      <br>
        <a target="_blank" href="https://github.com/BoMingZhao">Boming Zhao</a>, 
        <a target="_blank" href="https://ybbbbt.com">Bangbang Yang</a>, 
        <a target="_blank" href="https://zhenyangli.github.io">Zhenyang Li</a>, 
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="http://www.cad.zju.edu.cn/home/gfzhang">Guofeng Zhang</a>, 
        <a target="_blank" href="https://www.wlu.ca/academics/faculties/faculty-of-science/faculty-profiles/jiashu-zhao/index.html">Jiashu Zhao</a>, 
        <a target="_blank" href="https://www.yindawei.com">Dawei Yin</a>, 
        <a target="_blank" href="https://zhpcui.github.io">Zhaopeng Cui</a>, 
        <a target="_blank" href="http://www.cad.zju.edu.cn/home/bao">Hujun Bao</a>. 
      <br>
      ACM Multimedia 2022 (<strong>Oral</strong>) &nbsp;/&nbsp; 
      <a target="_blank" href="https://dl.acm.org/doi/abs/10.1145/3503161.3548125">Paper</a> <!-- &nbsp;/&nbsp; 
      <a target="_blank" href="https://zju3dv.github.io/neural_outdoor_rerender">Project page</a> -->
    </p>
    <p>
      Expand tourist photos from a narrow field of view to a wider one while maintaining a similar visual style. Propose factorized neural re-rendering model to produce photorealistic novel views from cluttered outdoor Internet photo collections, which enables applications such as controllable scene re-rendering, photo extrapolation, and 3D photo generation.
    </p>
  </td>
</tr>

<tr onmouseout="sat2vid_stop()" onmouseover="sat2vid_start()">
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <video id="sat2vid_video" style="width:100%;max-width:100%;left:5%;opacity:1" muted loop>
      <source src="assets/sat2vid.mp4" type="video/mp4">Your browser does not support the video tag.
    </video>
    <script type="text/javascript">
      function sat2vid_start() {
        document.getElementById("sat2vid_video").play();
      }
      function sat2vid_stop() {
        document.getElementById("sat2vid_video").pause();
      }
    </script>
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Sat2Vid: Street-view Panoramic Video Synthesis from a Single Satellite Image</strong>
      <br>
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://www.linkedin.com/in/zhenqiangli">Zhenqiang Li</a>, 
        <a target="_blank" href="https://zhpcui.github.io">Zhaopeng Cui</a>, 
        <a target="_blank" href="https://u.osu.edu/qin.324">Rongjun Qin</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/marc.pollefeys">Marc Pollefeys</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/moswald">Martin R. Oswald</a>. 
      <br>
      ICCV 2021 &nbsp;/&nbsp; 
      <a target="_blank" href="https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Sat2Vid_Street-View_Panoramic_Video_Synthesis_From_a_Single_Satellite_Image_ICCV_2021_paper.pdf">Paper</a>
    </p>
    <p>
      Synthesize both temporally and geometrically consistent street-view panoramic video from a single satellite image and camera trajectory. Explicitly create a 3D point cloud representation of the scene and maintain dense 3D-2D correspondences across frames that reflect the geometric scene configuration inferred from the satellite view. Generation adopts GAN-based methods in the 3D sparse space.
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/nvsmonodep.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>NVS-MonoDepth: Improving Monocular Depth Prediction with Novel View Synthesis</strong>
      <br>
        <a target="_blank" href="https://zuriabauer.com">Zuria Bauer</a>, 
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://cvnet.cpd.ua.es/curriculum-breve/es/orts-escolano-sergio/7775">Sergio Orts Escolano</a>, 
        <a target="_blank" href="https://cvnet.cpd.ua.es/curriculum-breve/es/cazorla-quevedo-miguel-angel/18333">Miguel Cazorla</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/marc.pollefeys">Marc Pollefeys</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/moswald">Martin R. Oswald</a>. 
      <br>
      3DV 2021 &nbsp;/&nbsp; 
      <a target="_blank" href="https://ieeexplore.ieee.org/document/9665820">Paper</a>
    </p>
    <p>
      Application of novel view synthesis to improve monocular depth estimation, with a wrapping scheme using the estimated depth to an additional viewpoint. The same depth network is applied to the synthesized view and provides another supervision.
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/tcsvt.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
      <p>
      <strong>Spatio-Temporal Perturbations for Video Attribution</strong>
      <br>
        <a target="_blank" href="https://www.linkedin.com/in/zhenqiangli">Zhenqiang Li</a>, 
        <a target="_blank" href="https://wei-min.wang">Weimin Wang</a>, 
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://hyf015.github.io">Yifei Huang</a>, 
        <a target="_blank" href="https://sites.google.com/ut-vision.org/ysato">Yoichi Sato</a>. 
      <br>
      TCSVT 2021 &nbsp;/&nbsp; 
      <a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/9435317">Paper</a>
      <p>
        Take extra attention to the evaluation metrics for video attribution methods. Specifically, a new reliability measurement method is proposed, by which the reliable and objective metrics are screened. The effectiveness of the proposed attribution method is extensively investigated by both subjective and objective evaluation, and comparison with multiple significant baseline attribution methods.
      </p>
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/wacv.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Towards Visually Explaining Video Understanding Networks with Perturbation</strong>
      <br>
        <a target="_blank" href="https://www.linkedin.com/in/zhenqiangli">Zhenqiang Li</a>, 
        <a target="_blank" href="https://wei-min.wang">Weimin Wang</a>, 
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://hyf015.github.io">Yifei Huang</a>, 
        <a target="_blank" href="https://sites.google.com/ut-vision.org/ysato">Yoichi Sato</a>. 
      <br>
      WACV 2021 &nbsp;/&nbsp; 
      <a target="_blank" href="https://openaccess.thecvf.com/content/WACV2021/papers/Li_Towards_Visually_Explaining_Video_Understanding_Networks_With_Perturbation_WACV_2021_paper.pdf">Paper</a>
    </p>
    <p>
      Aim to provide an easy-to-use visual explanation method for video understanding networks with diversified structures. Propose a generic perturbation-based visual explanation method, enhanced by a novel spatiotemporal smoothness constraint. The method enables the comparison of explanation results between different video classification networks and avoids generating pathological adversarial explanations for video inputs.
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/s2g.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Geometry-Aware Satellite-to-Ground Image Synthesis for Urban Areas</strong>
      <br>
        <a target="_blank" href="https://xiaohulugo.github.io">Xiaohu Lu</a>*, 
        <strong>Zuoyue Li</strong>*, 
        <a target="_blank" href="https://zhpcui.github.io">Zhaopeng Cui</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/moswald">Martin R. Oswald</a>, 
        <a target="_blank" href="https://people.inf.ethz.ch/marc.pollefeys">Marc Pollefeys</a>, 
        <a target="_blank" href="https://u.osu.edu/qin.324">Rongjun Qin</a>. 
      <br>
      *Equal contribution. CVPR 2020 &nbsp;/&nbsp; 
      <a target="_blank" href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lu_Geometry-Aware_Satellite-to-Ground_Image_Synthesis_for_Urban_Areas_CVPR_2020_paper.pdf">Paper</a>
    </p>
    <p>
      Generate panoramic street-view images that are geometrically consistent with a given satellite image via a GAN-based network with the proposed geo-transformation layer that retains the physical satellite-to-ground relation. The synthesized images retain well-articulated and authentic geometric shapes, as well as the texture richness of the street view in various scenarios.
    </p>
  </td>
</tr>

<tr>
  <td style="padding:1%;width:20%;max-width:20%;vertical-align:middle">
    <img style="width:100%;max-width:100%" alt="profile photo" src="assets/topo.jpg">
  </td>
  <td style="padding:1%;width:80%;max-width:80%">
    <p>
      <strong>Topological Map Extraction from Overhead Images</strong>
      <br>
        <strong>Zuoyue Li</strong>, 
        <a target="_blank" href="https://www.ics.uzh.ch/en/research/research-groups/Jan-Dirk-Wegner.html">Jan Dirk Wegner</a>, 
        <a target="_blank" href="https://omls.dmi.unibas.ch/en/persons/aurelien-lucchi">Aurelien Lucchi</a>. 
      <br>
      ICCV 2019 &nbsp;/&nbsp; 
      <a target="_blank" href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Topological_Map_Extraction_From_Overhead_Images_ICCV_2019_paper.pdf">Paper</a>
      <br>
    </p>
    <p>
      Circumvent the conventional pixel-wise segmentation of aerial images and predict objects in a vector representation directly. Directly extracts the topological map of a city from overhead images as collections of building footprints and road networks.
    </p>
  </td>
</tr>
</tbody>
</table>


<h1>Awards</h1>
<p>
Outstanding Reviewer, <a target="_blank" href="https://cvpr2023.thecvf.com/Conferences/2023/OutstandingReviewers">CVPR 2023</a>
<br>
Outstanding Reviewer, <a target="_blank" href="https://eccv2022.ecva.net/program/outstanding-reviewers">ECCV 2022</a>
<br>
National Scholarship for Outstanding Students Abroad, 2022
<br>
<a target="_blank" href="https://www.jsps.go.jp/english/e-fellow/e-fellow-sp/outline_eth.html">Japan Society for the Promotion of Science (JSPS) Fellowships for Research in Japan</a>, 2020
<br>
<a target="_blank" href="https://www.datascience.ch/phd-fellows">Swiss Data Science Center (SDSC) Fellowship</a>, 2019
<br>
Graduate with Distinction (M.Sc.) at ETH Zürich, 2018
<br>
Second Runner-up (student teams) at Helvetic Coding Contest, 2017
<br>
Outstanding Graduates at Zhejiang University, 2015
</p>

<h1>Academic Service</h1>
<p>
<strong>Conference Reviewer</strong>: CVPR, ICCV, ECCV, NeurIPS, WACV.
<br>
<strong>Journal Reviewer</strong>: TPAMI, TGRS.
</p>

<h1>Teaching</h1>

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=178454&semkez=2024S&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2024
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=173300&semkez=2023W&lang=en">263-5902-00L Computer Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Autumn 2023
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=167257&semkez=2023S&lang=en">263-5904-00L Deep Learning for Computer Vision: Seminal Work</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2023
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vorlesungen.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?semkez=2023S&lerneinheitId=168741&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2023
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=162913&semkez=2022W&lang=en">252-0847-00L Computer Science</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Autumn 2022
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=157422&semkez=2022S&lang=en">263-5904-00L Deep Learning for Computer Vision: Seminal Work</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2022
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?semkez=2022S&lerneinheitId=158871&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2022
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?semkez=2021S&lerneinheitId=150524&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2021
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vorlesungen.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=140478&semkez=2020W&lang=en">263-5902-00L Computer Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Autumn 2020
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vorlesungen.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=136431&semkez=2020S&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2020
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=134908&semkez=2020S&lang=en">263-5904-00L Deep Learning for Computer Vision: Seminal Work</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2020
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=132284&semkez=2019W&lang=en">263-5902-00L Computer Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Autumn 2019
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=128451&semkez=2019S&lang=en">252-0579-00L 3D Vision</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2019
  </td>
</tr>

<tr style="padding:0px">
  <td style="padding:0%;width:85%;vertical-align:middle">
    Teaching Assistant, <a target="_blank" href="https://www.vvz.ethz.ch/Vorlesungsverzeichnis/lerneinheit.view?lerneinheitId=126900&semkez=2019S&lang=en">263-5904-00L Deep Learning for Computer Vision: Seminal Work</a>, ETH Zürich
  </td>
  <td style="padding:0%;width:15%;max-width:15%;text-align:right">
    Spring 2019
  </td>
</tr>

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

---
layout: default
---

<div class="grid-layout">
  <div class="card">
    <div class="card-header"> About </div>
    <div class="card-main">
      <div class="main-description">
      <p>
      The complete 3D reconstruction of neurons from high resolution Electron Microscopy (EM) is fundamental to high-resolution Connectomics and advancing the understanding of neural information processing. This is done by the complete delineation of neurons from their surroundings; a task which is so time-intensive that it is impossible for all but the most basic of organisms. Computer vision has been critical for speeding this workflow, with recent systems reporting superhuman performance <a href="https://arxiv.org/abs/1706.00120"> [1] </a> and an approximate 250-fold reduction in processing time for a 100 x 100 x 100 tissue volume <a href="https://www.biorxiv.org/content/early/2017/10/09/200675"> [2] </a>. This benchmark of over 400 man-hours of expert annotation nevertheless still represents a significant barrier in mapping neural circuits.
      </p>
      <p>
      Here, we target the poor generalization of computer vision systems in connectomics with a novel challenge for the Source and Tissue Agnostic Reconstruction of Neurons (STARN). This challenge presents a "training" dataset consisting of five publicly available annotated tissue volumes from a variety of organisms and imaging configurations for training computer vision systems (CREMI A/B/C, FIB-25, ISBI 2013); evaluation is performed on an independent volume <a href="https://www.nature.com/articles/nature09818"> [3] </a> annotated by our group. We will demonstrate that the SARN challenge defeats state-of-the-art systems for neuron reconstruction, which perform as poorly as models with only a fraction of their total number of free parameters.
      </p>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header"> Data </div>
    <div class="card-main">
      <div class="main-description"> The test volumes are not used in the training data at all and contain cell volumes from a different species. </div>
    </div>
    <div class="align-center">
      <a href="gs://sarn/data/briggman.npy" class="btn align-center"> Download Data </a>
    </div>
  </div>
  <div class="card">
    <div class="card-header"> Leaderboard </div>
    <div class="card-main">
      <div class="main-description"> The submissions having membrane segmentations for the test volume can be submitted to our Google Cloud Storage. We will evaluate the submissions and inrtoduce an entry in our leaderboard (which will be released in X amount of time). </div>
    </div>
    <div class="align-center">
      <a href="gs://sarn/submission" class="btn align-center"> Upload Submission </a>
    </div>
    <!-- table>
        <tr>
        <th> Submission Name </th>
        <th> Metric 1 </th>
        <th> Metric 2 </th>
        <th> Metric N </th>
        <th> Final score </th>
        </tr>
        <tr>
        <td> Name 1 </td>
        <td> Score 1 </td>
        <td> Score 2 </td>
        <td> Score N </td>
        <td> sum(scores[i]) </td>
        </tr>
    </table -->
  </div>
</div>

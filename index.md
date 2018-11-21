---
layout: default
---

<div class="grid-layout">
  <div class="card">
    <div class="card-header"> About </div>
    <div class="card-main">
      <div class="main-description">
      <p>
      Recent successes in deep learning have started to impact neuroscience. Of particular significance are claims that current segmentation algorithms achieve "super-human" accuracy in an area known as connectomics. However, as we will show, these algorithms do not effectively generalize beyond the particular source and brain tissues used for training -- severely limiting their usability by the broader neuroscience community. To fill this gap, we describe a novel connectomics challenge for source- and tissue-agnostic reconstruction of neurons (STAR), which favors broad generalization over fitting specific datasets. We first demonstrate that current state-of-the-art approaches to neuron segmentation perform poorly on the challenge. We further describe a novel convolutional recurrent neural network module that combines short-range horizontal connections within a processing stage and long-range top-down connections between stages. The resulting architecture establishes the state of the art on the STAR challenge -- improving the prospect for computer vision to allow for widespread fully-automated connectomics analysis.
      </p>
      <p>
      Here, we address the poor generalization of computer vision systems in connectomics with a novel challenge: the source- and tissue-agnostic reconstruction of neurons. This challenge presents a "training" dataset consisting of five publicly available and annotated tissue volumes representing a variety of organisms and imaging configurations (CREMI, FIB-25, and SNEMI3D); evaluation is performed on an independent volume <a href="https://www.nature.com/articles/nature09818"> [1] </a> annotated by our group. We will demonstrate that the STARN challenge defeats state-of-the-art systems for neuron reconstruction.
      </p>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header"> Data & Code </div>
    <div class="card-main">
      <div class="main-description"> <strong> Training Data:</strong> The instructions for getting training volumes can be found at the following links: </div>
      <div class="grid-layout pad-some">
        <a href="http://brainiac2.mit.edu/SNEMI3D/home" class="btn align-center"> SNEMI3D </a>
        <a href="https://github.com/google/ffn/#sample-data" class="btn align-center"> FIB-25 </a>
        <a href="https://cremi.org/" class="btn align-center"> CREMI </a>
      </div>
      <div class="main-description"> Download the test volume for measuring generalization capability (.h5 file). The HDF5 file has a dataset called "slices". The volume data is stored under this dataset. Below is the link for download: </div>
      <div class="align-center pad-some">
        <a href="https://doi.org/10.5281/zenodo.1490123" class="btn align-center"> Test Volume </a>
      </div>
    </div>
    <div class="align-center pad-some">
      <!--a href="https://doi.org/10.5281/zenodo.1490123" class="btn align-center"> Test Volume </a-->
      <div class="btn align-center"> Link to Code
        <div class="tooltip"> Code coming soon! </div>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header"> Leaderboard </div>
    <div class="card-main">
      <div class="main-description"> Upload your <strong> neuron segmentation </strong> results on the test volume provided. </div>
    </div>
    <div class="align-center">
      <!-- a href="#submission" class="btn align-center"> Submit Results </a -->
      <div class="btn align-center"> Submit Results
        <div class="tooltip"> Submissions currently disabled. Check back soon for the challenge kickoff! </div>
      </div>
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

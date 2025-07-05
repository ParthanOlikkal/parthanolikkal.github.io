---
title: "ParthanOlikkal"
layout: single
permalink: /
author_profile: true
classes: wide
sidebar:
  nav: false
---

I am a Ph.D. Candidate at the <a href="https://umbc.edu/" target="_blank"><strong>University of Maryland Baltimore County</strong></a>, advised by <a href="https://www.csee.umbc.edu/ramana-vinjamuri/" target="_blank">Dr. Ramana Vinjamuri</a>. My research lies at the intersection of **Brain-Computer Interfaces, Reinforcement Learning and Robotics**. I build real-time adaptive pipelines for motor intent decoding using EEG and EMG signals, with applications in assistive technologies, rehabilitation, and neuroadaptive gaming.

Before joining UMBC, I worked on gesture decoding systems for prosthetics and interactive virtual environments. My work emphasizes synergy-driven analysis, multimodal control, and human-in-the-loop reinforcement learning.

📄 Download my [**CV**](/assets/docs/Parthan_CV.pdf)

<hr>

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: flex-start; justify-content: space-between;">

  <div style="flex: 1; min-width: 250px;">
    <h3>Interests</h3>
    <ul>
      <li>Brain-Computer Interfaces</li>
      <li>Reinforcement Learning</li>
      <li>EMG and EEG-based motor decoding</li>
      <li>Human-Robot Interaction</li>
      <li>Motion & Synergy Analysis</li>
    </ul>
  </div>

<div style="flex: 1; min-width: 250px;">
  <h3>Education</h3>
  <ul>
    <li>🎓 <strong>Ph.D. in Computer Science</strong> (Present)<br>
        <span style="font-size: 0.8em;">
        University of Maryland, Baltimore County
        </span></li>
    <li>🎓 <strong>M.S. in Computer Science</strong>, 2021<br>
        <span style="font-size: 0.8em;">
        University of Maryland, Baltimore County
        </span></li>
    <li>🎓 <strong>B.Tech in Computer Science</strong>, 2017<br>
        <span style="font-size:0.8em;">
        Cochin University of Science and Technology
        </span></li>
  </ul>
</div>

</div>

---

## Publications

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: flex-start; margin-bottom: 2rem; border: 1px solid #e0e0e0; border-radius: 8px; padding: 1.5rem; background: #fafafa; font-size: 0.9em;">

  <!-- LEFT: Image -->
  <div style="flex: 1 1 300px; min-width: 250px;">
    <img src="/assets/images/EEG_EMG_Robot.png" alt="Paper teaser" style="width: 100%; border-radius: 8px;">
  </div>

  <!-- RIGHT: Text -->
  <div style="flex: 2 1 400px; min-width: 250px; font-size:0.8em">

    <p style="font-size: 0.9em; color: #555;">
      <strong>Parthan Olikkal</strong>, Branesh M. Pillai, Jackrit Suthakorn, Habib Ali, Ramana Vinjamuri  
      <br>2024 – <em>IEEE Robotics and Biomimetics</em>
    </p>

    <h3 style="margin-top: 0;">A Hybrid EEG-EMG Framework for Humanoid Control using Deep Learning Transformers</h3>

    <p style="color: #555;font-style:0.8em">
      This study presents a Transformer-based deep learning approach that integrates EEG and EMG signals to enhance upper limb motor control for rehabilitation. Ten able-bodied subjects performed center-out tasks of varying complexity, with simultaneous EEG, EMG, and 2D kinematic data collection. The fused signals enabled the model to achieve 87.27% accuracy across all levels and control a humanoid robot to replicate movements. The results demonstrate the effectiveness of EEG-EMG fusion in improving precision and performance in BCI-driven assistive and neurorehabilitation technologies.
    </p>

<!-- Button Group -->
<div class="btn-links" style="margin-top: 1rem; font-size:1em;">
  <button onclick="openBibModal('/assets/bib/Olikkal_2024_ROBIO.bib', 'bibModal-robio2024')" 
          class="btn btn-outline-primary btn-page-header btn-sm">Cite</button>
  <a class="btn btn-outline-primary btn-page-header btn-sm" href="https://doi.org/10.1109/ROBIO64047.2024.10907308" target="_blank" rel="noopener">DOI</a>
</div>

<!-- Modal -->
<div id="bibModal-robio2024" style="display:none; position: fixed; z-index: 9999; left: 0; top: 0; width: 100%; height: 100%;
     background-color: rgba(0,0,0,0.5); text-align: center;">
  <div style="background: #fff; margin: 10% auto; padding: 20px; border-radius: 10px; width: 90%; max-width: 700px; position: relative;">
    <h3>BibTeX Citation</h3>
    <textarea id="bibtexText-robio2024" readonly style="width: 100%; height: 300px; padding: 10px; font-family: monospace;
              border: 1px solid #ccc; border-radius: 6px;">Loading...</textarea>
    <div style="margin-top: 1rem;">
      <button onclick="copyBibTex('bibtexText-robio2024')" class="btn btn-sm" style="margin-right: 10px;">📋 Copy</button>
      <a href="/assets/bib/Olikkal_2024_ROBIO.bib" download class="btn btn-sm" style="margin-right: 10px;">⬇️ Download</a>
      <button onclick="document.getElementById('bibModal-robio2024').style.display='none'" class="btn btn-sm">❌ Close</button>
    </div>
  </div>
</div>

  </div>
</div>


<script>
function openBibModal(bibURL, modalID) {
  const modal = document.getElementById(modalID);
  const textarea = modal.querySelector("textarea");

  fetch(bibURL)
    .then(response => response.text())
    .then(data => {
      textarea.value = data;
      modal.style.display = 'block';
    })
    .catch(() => {
      textarea.value = "Failed to load BibTeX.";
      modal.style.display = 'block';
    });
}

function copyBibTex(textareaID) {
  const text = document.getElementById(textareaID);
  text.select();
  document.execCommand("copy");
  alert("BibTeX copied to clipboard!");
}
</script>

---
title: "Gesture-to-Robot Synergy Translation"
layout: single
permalink: /projects/mitra-gesture/
author_profile: true
classes: wide
---

## Humanoid Control using RGB camera
<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: flex-start;">

  <!-- LEFT: Video -->
  <div style="flex: 1 1 300px; min-width: 300px;">
    <video width="100%" controls poster="/assets/images/Mitra_Mirror.jpg">
      <source src="/assets/video/Mitra_Mirroring.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <!-- RIGHT: Text -->
  <div style="flex: 2 1 400px; min-width: 250px; font-size: 0.9em;">
    <p>
      This project demonstrates real-time control of a humanoid robot using synergy-based reconstruction of hand gestures.  
      Using a single RGB camera and the MediaPipe framework, 33 static hand gestures were captured and reduced to joint angular velocities.
      Kinematic synergies, derived using dimensionality reduction, were used to reconstruct and replay these gestures on the humanoid robot Mitra with high fidelity (95.7% accuracy).
    </p>
    <p>
      This work showcases how low-dimensional synergies can be leveraged for controlling high-dimensional robotic end-effectors in assistive and rehabilitation applications.
    </p>
  </div>

</div>

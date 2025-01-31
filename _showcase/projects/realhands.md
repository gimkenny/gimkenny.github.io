---
show: true
width: 12
date: 2025-1-1
group: Projects
---

<div class="p-3">
  <h3 class="mt-3">Real Hand Visualization in VR through Real-Time Video Matting</h3>
  <p>
    This project, stemming from my Bachelor's Thesis, refers to my development of a VR platform created  to visualize and interact with the user's egocentric  hands in VR. The implemented system visualizes real hands in augmented virtuality by utilizing a ZED Mini stereo camera for egocentric video input, processed through a Robust Video Matting (RVM) model for real-time alpha matte extraction and depth-based filtering of the user's upper limbs. The processed frames are transmitted via TCP to Unity, where they are rendered onto layered plane objects configured for binocular parallax, with a custom shader ensuring background transparency and adjustable edge detail. 
  
</p>

  <div class="row project-images">
    <div class="col-8 centered-img">
      <img src="{{ '/assets/images/projects/arduino/hands3.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="hands-conceptualization">
    </div>
    <div class="col-4 centered-img">
      <img src="{{ '/assets/images/projects/arduino/hands4.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="hands-conceptualization">
    </div>
    <div class="col-6 centered-img">
      <img src="{{ '/assets/images/projects/arduino/hands1.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="hands-occlusion">
    </div>
    <div class="col-6 centered-img">
      <img src="{{ '/assets/images/projects/arduino/hands2.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="hands-physical">
    </div>
  </div>


</div>

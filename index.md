## AVERtek's XR-NOW 

---

### Medical/Health Information

<!--[OSI Building Brands; Growing Business](/https://osicreative.com/)-->
<!--<img src="images/dummy_thumbnail.jpg?raw=true"/> -->



---
<!-- Loads <model-viewer> for old browsers like IE11: -->
  <script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->

<model-viewer loading="eager" id="paused-change-demo" camera-controls src="Models/Ch16_nonPBR@Shuffling.gltf" ar="" ar-modes="scene-viewer webxr quick-look" ios-src="usdz_ch16_nonpbr_shuffling__1614913944630.usdz" alt="Medical/Health Information" ar-scale="auto" camera-controls=""  style="width: 95%; height: 500px" exposure="0.5"> <button slot="ar-button" style="background-color: white; border-radius: 8px; border: 1 px solid black; position: absolute; top: 20px; right: 20px; ">
      👋 AR Click Here
  </button> 
</model-viewer>
<script>
(() => {
  const modelViewer = document.querySelector('#paused-change-demo');

  self.setInterval(() => {
    modelViewer.animationName = modelViewer.animationName === 'mixamo.com' ?
      'Static Pose': 'mixamo.com';
  }, 500.0);
})();
<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>



---

<!-- Remove above link if you don't want to attibute -->

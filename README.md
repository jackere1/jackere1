- 👋 Hi, I’m @jackere1
- 👀 I’m interested in Video games
- 🌱 I’m currently learning Cooking
- 💞️ I’m looking to collaborate on projects later
<img src="https://miro.medium.com/max/1000/1*XrEWAu1sgFkZ4IQtG3DMmg.gif" style="text-align: center"/>

<script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
<a-scene>
<a-assets>
    <img id="sky" src="panaroma.jpg"/>
</a-assets>
<a-sky
    src="#sky"
></a-sky>
<!-- Sun -->
<a-sphere 
  color="#F5C85D"
  position="-13 2 -10" 
  radius="4"></a-sphere>

<!-- Mercury -->
<a-sphere
  color="#AF886D"
  position="-7 2 -10"
  radius=".25"></a-sphere>

<!-- Venus -->
<a-sphere 
  color="#ECBFBF"
  position="-5 2 -10" 
  radius=".5"></a-sphere>

<!-- Earth -->
<a-sphere 
  color="#6DCBE7"
  position="-3 2 -10" 
  radius=".5"></a-sphere>

<!-- Mars -->
<a-sphere 
  color="#CF503A"
  position="-1 2 -10" 
  radius=".25"></a-sphere>

<!-- Jupiter -->
<a-sphere 
  color="#C9957A"
  position="1 2 -10"
  radius="1"></a-sphere>

<!-- Saturn -->
<a-sphere 
  color="#F8EC99"
  position="4 2 -10" 
  radius=".8"></a-sphere>

<!-- Uranus -->
<a-sphere 
  color="#73AAF8"
  position="7 2 -10"
  radius=".75"></a-sphere>

<!-- Neptune -->
<a-sphere 
  color="#3453BD"
  position="10 2 -10" 
  radius=".75"></a-sphere>

<!-- The other not-so-basic planets. These have rings around them. The rings are made of torii (singular torus) a shape that can be used to make donuts, tubes and yes, ring shapes -->
<a-entity id="saturn-container" position="4 2 -10">
  <a-sphere position="0 0 0 " radius=".8" color="#F8EC99" id="saturn"></a-sphere>
  <a-torus id="saturn-ring-1" color="#57524A" segments-tubular="50" radius="3.2" radius-tubular="0.1" rotation="90 0 0" scale=".44 .44 0.04"></a-torus>
  <a-torus id="saturn-ring-2" color="#A29A87" segments-tubular="50" radius="2.4" radius-tubular="0.2" rotation="90 0 0" scale=".44 .44 0.04"></a-torus>
</a-entity>

<a-entity id="uranus-container" position="7 2 -10">
  <a-sphere id="uranus" radius=".75" color="#73AAF8"></a-sphere>
  <a-torus id="uranus-ring" color="#FFFFFF" segments-tubular="50" radius="1.5" radius-tubular="0.01" rotation="-10 90 0" scale=".75 .75 0.075"></a-torus>
</a-entity>

</a-scene>

<!---
jackere1/jackere1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

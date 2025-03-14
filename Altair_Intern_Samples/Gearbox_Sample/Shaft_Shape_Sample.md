# Simple Demonstration of Shaft Shape Optimization

The goal of this shaft shape optimization is to determine the optimal hole radius (within the 10mm +/-3mm) along the shaft to reduce weight while satisfying specific constraints.<br><br>

## Full Demostration
<span style="color:black"><b> Before Optimization:Shaft_Shape_Result</b><br><br>
<img src="Shaft_Original_Model.png" alt="Shaft_Original_Model" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br>

<!--GC-->
<span style="color:black"> <b>Geometry Cleanup:</b>
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Shaft_GC_1.png" alt="Shaft_GC_1" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Define Center Points of Circles</p>
  <img src="Shaft_GC_2.png" alt="Shaft_GC_2" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Create Construction Cylinder Surface</p>
  <img src="Shaft_GC_3.png" alt="Shaft_GC_3" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Surface Cut</p>
  <img src="Shaft_GC_4.png" alt="Shaft_GC_4" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Delete Construction Surface</p>
  <img src="Shaft_GC_5.png" alt="Shaft_GC_5" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Delete Solid</p>
</div><br>

<!--Mesh-->
<span style="color:black"> <b>Mesh and Mesh Control:</b><br><br>
<img src="Shaft_Mesh.png" alt="Shaft_Mesh_Detail" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br><br>

<!--RBE-->
<span style="color:black"><b>RBE2s:<b><br><br>
<img src="Shaft_RBE2.png" alt="Shaft_RBE" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br><br>

<!--Contact-->
<span style="color:black"> <b>Contacts:</b>
<p style="font-size:0.8em;">Type: Freeze; Consolidate; Vicinity Tolerance: 1.0</p>
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Shaft_Contact_2.png" alt="Shaft_Contact_1" style="display: block; margin-bottom: 10px;">
  <img src="Shaft_Contact_1.png" alt="Shaft_Contact_2" style="display: block; margin-bottom: 10px;">
  <img src="Shaft_Contact_3.png" alt="Shaft_Contact_3" style="display: block; margin-bottom: 10px;">
  </div><br>
  
<!--Material-->
<span style="color:black"> <b>Material Setup: Skipped</b><br><br>

<!--Load Step-->
<span style="color:black"> <b>Load Steps:</b>
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Shaft_Load_Step_1.png" alt="Shaft_Load_Step_1" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Moment Applied</p>
  <img src="Shaft_Load_Step_2.png" alt="Shaft_Load_Step_2" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Single Point Constraint</p>
  <img src="Shaft_Load_Step_3.png" alt="Shaft_Load_Step_3" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Model Constraint</p>
  <img src="Shaft_Load_Result.png" alt="Shaft_Load_Result" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Load Result</p>
</div><br>

<!--Shape Optimization-->
<span style="color:black"> <b>Shape Optimization:</b><br><br>
<img src="Shaft_Design_Variable.png" alt="Shaft_Design_Variable" style="width: 100%; max-width: auto; display: block; margin: 0 auto;">
<p style="font-size:0.8em; text-align: center;">Define Variable Elements</p><br>
<img src="Shaft_Shape_Animation.gif" alt="Shaft_Shape_Amination" style="width: 100%; max-width: auto; display: block; margin: 0 auto;">
<p style="font-size:0.8em; text-align: center;">Optimization Processing</p><br>

<!--Result-->
<span style="color:black"> <b>Shape Optimization Result:</b><br><br>
<img src="Shaft_Shape_Result.png" alt="Shaft_Shape_Result" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br><br><br>

<span style="font-size:16px; color:blue">[Back to Gearbox Sample Page](https://shibojia98.github.io/Portfolio/Altair_Intern_Samples/Gearbox_Sample/Altair_1.html)</span><br>
<span style="font-size:16px; color:blue">[Back to the Home Page](https://shibojia98.github.io/Portfolio/)</span>

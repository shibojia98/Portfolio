# Simple Demonstration of Shaft Shape Optimization

<span style="color:black"> Before Optimization:<br><br>
<img src="Shaft_Original_Model.png" alt="Shaft_Original_Model" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br>

<!--GC-->
<span style="color:black"> Geometry Cleanup:
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
<span style="color:black"> Mesh and Mesh Control:
<img src="Shaft_Mesh.png" alt="Shaft_Mesh_Detail" style="width: 50%; max-width: auto; display: block; margin: 0 auto;"><br><br>

<!--RBE-->
<span style="color:black">RBE2s:
<img src="Shaft_RBE2.png" alt="Shaft_RBE" style="width: 100%; max-width: auto; display: block; margin: 0 auto;"><br><br>

<!--Contact-->
<span style="color:black"> Contacts:
<p style="font-size:0.8em;">Type: Freeze; Consolidate; Vicinity Tolerance: 1.0</p>
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Shaft_Contact_2.png" alt="Shaft_Contact_1" style="display: block; margin-bottom: 10px;">
  <img src="Shaft_Contact_1.png" alt="Shaft_Contact_2" style="display: block; margin-bottom: 10px;">
  <img src="Shaft_Contact_3.png" alt="Shaft_Contact_3" style="display: block; margin-bottom: 10px;">
  </div><br>
  
<!--Material-->
<span style="color:black"> Material Setup: Skipped<br><br>

<!--Load Step-->
<span style="color:black"> Load Steps:
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
<span style="color:black"> Shape Optimization:
<img src="Shaft_Design_Variable.png" alt="Shaft_Design_Variable" style="width: 100%; max-width: auto; display: block; margin: 0 auto;">
<p style="font-size:0.8em; text-align: center;">Define Variable Elements</p><br>
<img src="Shaft_Shape_Animation.gif" alt="Shaft_Shape_Amination" style="width: 100%; max-width: auto; display: block; margin: 0 auto;">
<p style="font-size:0.8em; text-align: center;">Optimization Processing</p><br>

<!--Result-->
<span style="color:black"> Shape Optimization Result:
<img src="Shaft_Shape_Result.png" alt="Shaft_Shape_Result" style="width: 100%; max-width: auto; display: block; margin: 0 auto;">

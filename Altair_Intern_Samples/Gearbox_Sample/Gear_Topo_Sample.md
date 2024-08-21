# Simple Demonstration of Gear Topology Optimization
The objective of this gear topology optimization is to optimize the material distribution of the design space between the root circle and the center to minimize weight.<br><br>
<a href="#target-position">*Click here to Comparsion Before & After </a><br><br>
## Full Demonstration:<br>
<span style="color:black"> <b>Before Optimization:</b><br><br>
<img src="Gear_Original_Model.png" alt="Gear_Original_Model" style="width: 50%; max-width: auto; display: block; margin: 0 auto;"><br>
<span style="color:black"> Geometry Cleanup:
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Gear_Topo_GC_1.png" alt="Gear_Topo_GC_1" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Remove Fillet</p>
  <img src="Gear_Topo_GC_2.png" alt="Gear_Topo_GC_2" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Define Center Points of Circles</p>
  <img src="Gear_Topo_GC_3.png" alt="Gear_Topo_GC_3" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Create Construction Surface</p>
  <img src="Gear_Topo_GC_4.png" alt="Gear_Topo_GC_4" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Surface Cut</p>
  <img src="Gear_Topo_GC_5.png" alt="Gear_Topo_GC_5" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Delete Construction Surface</p>
  <img src="Gear_Topo_GC_6.png" alt="Gear_Topo_GC_6" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Delete Solid</p>
  <img src="Gear_Topo_GC_7.png" alt="Gear_Topo_GC_7" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Create Surfaces from Lines</p>
  <img src="Gear_Topo_GC_8.png" alt="Gear_Topo_GC_8" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Create a Solid from Surfaces (Design Space)</p>
</div><br>


<span style="color:black"> <b>Mesh and Mesh Control:</b>
<div style="display: flex; overflow-x: auto; white-space: nowrap;">
  <img src="Gear_Mesh_Control_1.png" alt="Mesh_Control_1" style="margin-right: 10px;">
  <img src="Gear_Mesh_Control_2.png" alt="Mesh_Control_2" style="margin-right: 10px;">
  <img src="Gear_Mesh_Control_3.png" alt="Mesh_Control_3" style="margin-right: 10px;">
</div>
<img src="Gear_Mesh_Details.png" alt="Mesh_Detail" style="width: 50%; max-width: auto; display: block; margin: 0 auto;"><br><br>

  
  
<span style="color:black"> <b>RBE2 & RBE3 Setup:</b><br><br>
<img src="Gear_RBE2_3.png" alt="RBE" style="width: 90%; max-width: auto; display: block; margin: 0 auto;"><br><br>


<span style="color:black"> <b>Material Setup: Skipped</b><br><br>

<span style="color:black"> <b>Load Steps:</b>
<div style="max-height: 300px; overflow-y: auto;">
  <img src="Gear_Load_Step_1.png" alt="Gear_Load_Step_1" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Load Applied</p>
  <img src="Gear_Load_Step_2.png" alt="Gear_Load_Step_2" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Single Point Constraint</p>
  <img src="Gear_Load_Step_3.png" alt="Gear_Load_Step_3" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Model Constraint</p>
  <img src="Gear_Load_Step_4.png" alt="Gear_Load_Step_4" style="display: block; margin-bottom: 10px;">
  <p style="font-size:0.8em; text-align: center;">Load Steps</p>
</div><br>
<span style="color:black"> <b>Optimization Results:</b><br><br>
<img src="Gear_Topo_Result.gif" alt="Gear_Result"><br><br><br>

<h2 id="target-position">Comparsion Before & After</h2>

For one selected solution, Density Threshold: 0.3, Max Displacement: 0.025mm at teeth, Min Vol., Unidirectional Draft; Cyclic Symmetry #: 6：
| Topology | Before   | After    |
|----------|----------|----------|
| Stress   | 32171.992     | 36319.941     |
| Displacement    | 0.025     | 0.025     |
| Modal 1    | 1.649883E+03     | 2.185571E+03     |
| Modal 2    | 1.650395E+03     | 2.186073E+03     |
| Modal 3    | 1.757600E+03     | 2.305663E+03     |
| Modal 4    | 2.018013E+03     | 2.471020E+03     |
| Modal 5    | 2.018914E+03     | 2.471894E+03     |
| Modal 6    | 2.958553E+03     | 3.003110E+03     |
| Modal 7    | 3.598404E+03     | 3.747645E+03     |
| Modal 8   | 3.598753E+03     | 3.963651E+03     |




<span style="font-size:16px; color:blue">[Back to Gearbox Sample Page](https://shibojia98.github.io/Portfolio/Altair_Intern_Samples/Gearbox_Sample/Altair_1.html)</span><br>
<span style="font-size:16px; color:blue">[Back to the Home Page](https://shibojia98.github.io/Portfolio/)</span>

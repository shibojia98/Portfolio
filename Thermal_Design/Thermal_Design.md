<a href="https://shibojia98.github.io/Portfolio/">Back to the Home Page</a>

<h1>4kW Power Supply Baffle Airflow Design</h1>

<h2>Project Introduction</h2>

<p>
  This project presents the thermal-electrical-mechanical coupled design and airflow optimization of a 4kW power supply charging station using Siemens Flotherm.
  The study considered the interaction between heat-generating electrical components, mechanical chassis constraints, and forced-air cooling performance within a compact enclosure.
</p>

<p>
  A compact sheet-metal baffle was designed based on the chassis structure, electronic component layout, and CFD flow profiles.
  The baffle concentrates forced airflow and guides it through critical heat-generating components, improving convective heat transfer and overall heat dissipation performance.
</p>

<h2>MCAD Model Simplification</h2>

<p>
  The original mechanical and electrical assembly was simplified for CFD simulation. Non-critical small features were removed while preserving the major components,
  blockage regions, heat-generating parts, heat sinks, fans, and enclosure boundaries that directly affect airflow resistance and heat dissipation.
</p>

<img src="Model_Simplification.png" alt="Flotherm MCAD Simplified Model">

<h2>Baseline Airflow Analysis Before Optimization</h2>

<p>
  Before adding the baffle, the initial airflow simulation was performed to evaluate the baseline cooling behavior inside the enclosure.
  The result showed that the fan-driven airflow was not fully guided through the main thermal load areas.
</p>

<img src="Before_Optimization.gif" alt="Before Optimization Airflow Speed Distribution">

<h2>Problem Identification</h2>

<p>
  In the original design, two 100 mm cooling fans were positioned to direct airflow toward the main power semiconductor devices,
  including the PFC MOSFETs, boost diodes, SiC diodes, and IGBTs.
  The goal was to improve heat dissipation around the dominant heat sources.
</p>

<p>
  However, post-processing of velocity slice profiles and critical temperature monitors showed that airflow from both side intakes tended to bypass the targeted heat sink regions.
  Only limited airflow passed through the fin arrays and across the critical heat sources, causing insufficient convective cooling, low-velocity zones, recirculation, and stagnant air pockets.
  As hot air remained inside the enclosure longer, several monitored components exceeded their junction temperature limits after convergence.
</p>

<h2>Baffle Design Solution</h2>

<p>
  To address this issue, a custom sheet-metal baffle was designed to redirect and concentrate the airflow toward the critical heat-generating regions.
  The baffle was integrated within the limited internal space of the power supply enclosure while avoiding interference with existing components and assembly constraints.
</p>

<img src="Baffle_Design.png" alt="Sheet Metal Baffle Design">

<h2>Optimization Result Comparison</h2>

<p>
  After adding the baffle, the airflow path became more directed and uniform.
  The optimized design increased airflow coverage over the thermal load path and reduced inefficient bypass flow regions.
</p>

<h3>Before Optimization</h3>

<img src="Before_Optimization.gif" alt="Before Optimization Airflow Speed Distribution">

<h3>After Optimization</h3>

<img src="After_Optimization.gif" alt="After Optimization Airflow Speed Distribution">

<h2>Flow Trajectory Verification</h2>

<p>
  The flow trajectory result further verified that the baffle effectively guided the airflow from the cooling fans through the power electronics area.
  The airflow path became more organized, helping improve convective heat transfer across the main heat-generating components.
</p>

<img src="Flow_Traj.gif" alt="Optimized Flow Trajectory">

<h2>Engineering Contribution</h2>

<h2>Engineering Contribution</h2>

<ul>
  <li>Designed an airflow baffle based on chassis constraints, electronic component layout, and CFD flow profile analysis.</li>
  <li>Performed electro-thermal-fluid coupling analysis in Siemens Flotherm to evaluate thermal performance.</li>
  <li>Improved internal ventilation efficiency and reduced monitored temperatures by 3%–7.2%.</li>
  <li>Maintained semiconductor temperatures approximately 20–55°C below junction temperature limits after optimization.</li>
  <li>Converted the optimized baffle concept into manufacturable sheet-metal 3D parts.</li>
</ul>

<h2>Tools Used</h2>

<ul>
  <li>Siemens Flotherm</li>
  <li>MCAD model simplification</li> 
  <li>SolidWorks</li>

</ul>

<br>

<a href="https://shibojia98.github.io/Portfolio/">Back to the Home Page</a>

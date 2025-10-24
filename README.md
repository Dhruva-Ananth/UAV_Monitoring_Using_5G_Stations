# UAV_Monitoring_Using_5G_Stations
Code Base for Simulations and testing of UAV monitoring using 5G base stations are low altitude radars

3D Fused-Error Surfaces (by number of base stations)

Each row shows the 3D surface of expected 1-σ fused position error over the operational area for a given number of base stations (BS). Warmer colors indicate larger expected error.

1 BS
<p align="center"> <img src="./Images/3dmapbs1.jpg" width="95%" alt="3D fused error surface - 1 base station" /> </p> <p align="center"><sub><b>3D fused error surface (1 BS):</b> Error is lowest near the single site and grows rapidly away from boresight due to limited angular diversity.</sub></p>
2 BS
<p align="center"> <img src="./Images/3dmapbs2.jpg" width="95%" alt="3D fused error surface - 2 base stations" /> </p> <p align="center"><sub><b>3D fused error surface (2 BS):</b> Overlap between the two inward-facing sectors reduces error along the bisector; blind wedges remain.</sub></p>
3 BS
<p align="center"> <img src="./Images/3dmapbs3.jpg" width="95%" alt="3D fused error surface - 3 base stations" /> </p> <p align="center"><sub><b>3D fused error surface (3 BS):</b> Triangulation improves central region; gaps align with FOV edges.</sub></p>
4 BS
<p align="center"> <img src="./Images/3dmapbs4.jpg" width="95%" alt="3D fused error surface - 4 base stations" /> </p> <p align="center"><sub><b>3D fused error surface (4 BS):</b> Cross-view overlap yields markedly lower interior error.</sub></p>
6 BS
<p align="center"> <img src="./Images/3dmapbs6.jpg" width="95%" alt="3D fused error surface - 6 base stations" /> </p> <p align="center"><sub><b>3D fused error surface (6 BS):</b> Denser angular diversity flattens the error landscape over most of the area.</sub></p>
8 BS
<p align="center"> <img src="./Images/3dmapbs8.jpg" width="95%" alt="3D fused error surface - 8 base stations" /> </p> <p align="center"><sub><b>3D fused error surface (8 BS):</b> Multiple overlapping looks minimize fused uncertainty except at sector boundaries.</sub></p>
Coverage vs. Error Heatmaps (by number of base stations)

For each BS count we show (left) coverage/overlap and (right) absolute-error heatmap.

1 BS
<p align="center"> <img src="./Images/bs1coverage.jpg" width="49%" alt="Coverage map - 1 BS" /> <img src="./Images/bs1errormap.jpg" width="49%" alt="Error heatmap - 1 BS" /> </p> <p align="center"><sub><b>1 BS:</b> Single sector coverage; error grows quickly off-boresight.</sub></p>
2 BS
<p align="center"> <img src="./Images/bs2coverage.jpg" width="49%" alt="Coverage map - 2 BS" /> <img src="./Images/bs2errormap.jpg" width="49%" alt="Error heatmap - 2 BS" /> </p> <p align="center"><sub><b>2 BS:</b> Overlap along the mid-region reduces error; edges remain weakly constrained.</sub></p>
3 BS
<p align="center"> <img src="./Images/bs3coverage.jpg" width="49%" alt="Coverage map - 3 BS" /> <img src="./Images/bs3errormap.jpg" width="49%" alt="Error heatmap - 3 BS" /> </p> <p align="center"><sub><b>3 BS:</b> Three-way overlap stabilizes the center; error lobes track FOV gaps.</sub></p>
4 BS
<p align="center"> <img src="./Images/bs4coverage.jpg" width="49%" alt="Coverage map - 4 BS" /> <img src="./Images/bs4errormap.jpg" width="49%" alt="Error heatmap - 4 BS" /> </p> <p align="center"><sub><b>4 BS:</b> Robust interior coverage; lower errors where ≥3 sectors overlap.</sub></p>
6 BS
<p align="center"> <img src="./Images/bs6coverage.jpg" width="49%" alt="Coverage map - 6 BS" /> <img src="./Images/bs6errormap.jpg" width="49%" alt="Error heatmap - 6 BS" /> </p> <p align="center"><sub><b>6 BS:</b> High overlap density; residual warm zones align with residual sector boundaries.</sub></p>
8 BS
<p align="center"> <img src="./Images/bs8coverage.jpg" width="49%" alt="Coverage map - 8 BS" /> <img src="./Images/bs8errormap.jpg" width="49%" alt="Error heatmap - 8 BS" /> </p> <p align="center"><sub><b>8 BS:</b> Extensive joint visibility; error falls below target thresholds across most of the area.</sub></p>
Side-by-Side Comparisons
3D Surfaces — All BS Counts
<p align="center"> <img src="./Images/3dmapbs1.jpg" width="32%" alt="3D 1 BS" /> <img src="./Images/3dmapbs2.jpg" width="32%" alt="3D 2 BS" /> <img src="./Images/3dmapbs3.jpg" width="32%" alt="3D 3 BS" /> </p> <p align="center"> <img src="./Images/3dmapbs4.jpg" width="32%" alt="3D 4 BS" /> <img src="./Images/3dmapbs6.jpg" width="32%" alt="3D 6 BS" /> <img src="./Images/3dmapbs8.jpg" width="32%" alt="3D 8 BS" /> </p> <p align="center"><sub><b>Trend:</b> Increasing BS count flattens the error surface and improves uniformity.</sub></p>
Coverage Maps — All BS Counts
<p align="center"> <img src="./Images/bs1coverage.jpg" width="32%" alt="Coverage 1 BS" /> <img src="./Images/bs2coverage.jpg" width="32%" alt="Coverage 2 BS" /> <img src="./Images/bs3coverage.jpg" width="32%" alt="Coverage 3 BS" /> </p> <p align="center"> <img src="./Images/bs4coverage.jpg" width="32%" alt="Coverage 4 BS" /> <img src="./Images/bs6coverage.jpg" width="32%" alt="Coverage 6 BS" /> <img src="./Images/bs8coverage.jpg" width="32%" alt="Coverage 8 BS" /> </p> <p align="center"><sub><b>Trend:</b> More sites ⇒ more overlap ⇒ stronger observability in the interior.</sub></p>
Error Heatmaps — All BS Counts
<p align="center"> <img src="./Images/bs1errormap.jpg" width="32%" alt="Error 1 BS" /> <img src="./Images/bs2errormap.jpg" width="32%" alt="Error 2 BS" /> <img src="./Images/bs3errormap.jpg" width="32%" alt="Error 3 BS" /> </p> <p align="center"> <img src="./Images/bs4errormap.jpg" width="32%" alt="Error 4 BS" /> <img src="./Images/bs6errormap.jpg" width="32%" alt="Error 6 BS" /> <img src="./Images/bs8errormap.jpg" width="32%" alt="Error 8 BS" /> </p> <p align="center"><sub><b>Trend:</b> Absolute position error decreases and becomes more uniform as BS count increases.</sub></p>

# Spatio-Temporal Paradox of 2D Priors: Evidential
Feature Gating for Robust 3D Occupancy Prediction
Spatio-Temporal Paradox of 2D Priors: Evidential Feature Gating for Robust 3D Occupancy Prediction
(EAEEIE 2026 — Code updating soon)
We present the Evidential Feature Gate (EFG), a novel framework designed to resolve the "Spatio-Temporal Paradox" in vision-centric 3D semantic occupancy prediction
. While standard 2D pre-trained backbones excel at static noise penetration, they exhibit severe structural collapse under dynamic environmental anomalies (e.g., severe motion blur and heavy snow), triggering a cascading failure we formally identify as "Temporal Poisoning"
.
In contrast to standard deterministic architectures that blindly trust geometrically warped features, our approach explicitly models epistemic uncertainty directly at the intermediate spatial feature level using Evidential Deep Learning and Dirichlet subjective logic
. By dynamically quantifying this out-of-distribution uncertainty, the EFG mathematically suppresses corrupted spatial inputs toward zero, acting as an active protective firewall around the network's 3D temporal history buffer
.
Evaluated using the rigorous NuScenes-C robustness benchmark, our evidential architecture effectively restores clean-weather semantic accuracy (yielding 30.44 mIoU)
. More importantly, it yields up to an 804% relative improvement in structural retention under severe motion blur, and a 78.5% relative improvement under snow conditions
. Overall, we make a significant contribution towards highly reliable, uncertainty-aware 3D environment understanding for autonomous driving, introducing negligible overhead (+0.01M parameters) while maintaining real-time inference at 14.2 FPS
.
Code will be available soon!

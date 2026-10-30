Intergranular Cracking in Ni and Ni–10Cr Alloys

This repository contains files for preparing atomistic models and performing simulations of intergranular cracking in Ni and Ni–10 at.% Cr alloys.

File descriptions

deltamu.zip — Chemical potential difference calculation
Contains files for determining the chemical potential difference between Ni and Cr for the Ni–10 at.% Cr alloy. This step is performed before preparing the Cr-segregated models and provides the chemical potential difference used in the subsequent segregation simulations.

intergranular_model.zip — Intergranular crack model construction
Contains files for constructing atomistic models with a pre-existing crack along the grain boundary.

segregation_model.zip — Cr-segregated model preparation
Contains files for preparing grain-boundary Cr-segregated models using hybrid Monte Carlo/molecular dynamics simulations. After obtaining the segregated structures, follow the crack-construction procedure in intergranular_model.zip to prepare the corresponding intergranular crack models.

tension.zip — Uniaxial tensile loading example
Provides an example of uniaxial tensile loading for a specific grain-boundary crack model to investigate intergranular crack propagation. This example can be adapted to other grain boundaries by updating the model-specific inputs.

Workflow for Cr-segregated crack models

Determine the chemical potential difference using deltamu.zip.

Prepare the Cr-segregated structure using segregation_model.zip.

Introduce the intergranular crack following the procedure in intergranular_model.zip.

Apply uniaxial tensile loading using tension.zip as a reference.

Extract each ZIP archive before use.

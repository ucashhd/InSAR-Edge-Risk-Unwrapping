# Edge Ambiguity-Risk Learning for InSAR Phase Unwrapping

Project page for **A Solver-Aligned Hybrid Framework for InSAR Phase Unwrapping via Edge Ambiguity-Risk Learning**.

The method predicts ambiguity risk on horizontal and vertical image edges and
converts these predictions into weights for conventional phase-unwrapping
solvers. The same trained predictor is used with PUMA-style graph cuts, SNAPHU,
and MCF through solver-specific interfaces.

## Code availability

This repository currently contains project information only. Source code and
model files are not yet hosted here.

A separate reproduction package has been prepared for peer review. It includes
label generation, training and inference code, solver adapters, evaluation
scripts, environment specifications, configuration files, fixed training and
validation indices, and a pretrained model. Two InSAR-DLPU examples with
reference metrics and step-by-step instructions demonstrate the workflow.
SNAPHU and GAMMA MCF require separately installed solver software.

## Data

The examples are one simulated test pair and one real TanDEM-X test pair from
[InSAR-DLPU](https://github.com/zhoulifan/InSAR-DLPU). The full dataset is available
through the original dataset project. The two examples reproduce individual
sample results rather than the complete test-set statistics reported in the
paper.

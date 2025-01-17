Ika Han and Kassandra Jordan

# Introduction 
StressD is a machine learning-based tool designed to predict stress distributions in solid materials efficiently. This project evaluates the robustness and reliability of StressD by testing its adherence to key physical principles, including symmetry, boundary condition adherence, and physical constraints.

The primary goal of this project is to evaluate StressD against three critical physical principles:

Symmetry: Stress distributions should exhibit symmetry when input configurations are symmetric.

Boundary Condition Adherence: Stress predictions must align with defined boundary conditions.

Physical Constraints: Predicted stress values must remain finite and within realistic bounds.

The evaluation is split into two main components:

1. Property-Based Testing

Symmetry: Quantifies deviations in stress fields for symmetric input geometries.

Boundary Conditions: Ensures predictions respect specified loading and support conditions.

Physical Constraints: Monitors predictions to confirm stress values remain finite and valid.

2. Systematic Input Testing

Synthetic datasets were generated to simulate various input scenarios, including edge cases, to evaluate StressD's robustness and highlight limitations.

# Set-up:
To re-run this code, you need to pull the testing_data attached to the original StressD paper. Due to high lag when downloading and uploading these cases, we don't include the file here.

The /revsion, /testing_data, and /base_network are taken directly from the StressD project. This level of integration was with the intent to fork and make a PR. 
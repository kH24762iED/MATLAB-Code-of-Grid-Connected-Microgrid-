%% ========================================================================
%  HOW TO RUN THE CODE
%  ========================================================================
%
%  1. REQUIREMENTS
%     - MATLAB (a recent release is recommended).
%     - MATPOWER: must be installed and added to the MATLAB path. It supplies
%       the test-system data and performs the power flow (load flow) analysis.
%     - PlatEMO (version 4.16_SR): included in the "PlatEMO-4.16_SR" folder
%       of this package.
%
%  2. SETUP
%     - Set the MATLAB current folder to the root directory of this package.
%     - Make sure the "PlatEMO-4.16_SR" folder and MATPOWER are on the
%       MATLAB path (use "Set Path" or the addpath command).
%
%  3. RUNNING THE SIMULATION
%     - Execute "run_simulation.m". The script generates results in two parts:
%
%       Part 1 - Benchmark comparison of MOEAs
%           Compares all considered multi-objective evolutionary algorithms
%           (MOEAs), reporting the hypervolume indicator (HVI) and the
%           resulting Pareto fronts.
%
%       Part 2 - Proposed method
%           Presents the results of the proposed method, together with a
%           comparison table covering the different case studies.
%
%  4. CUSTOMIZING THE PROBLEM FORMULATION
%     - The proposed problem formulation is implemented in the "Problems"
%       folder, with "Dist_M_Paper1.m" as the main file.
%     - Modify this file to adapt the code to a different formulation,
%       objectives, or constraints.
%
%% ========================================================================
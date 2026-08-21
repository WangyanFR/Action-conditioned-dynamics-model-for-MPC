# Action-conditioned-dynamics-model-for-MPC

This repository accompanies the paper **“Action-Conditioned Dynamics Learning for Model Predictive Control of Flexible Fish Locomotion.”**

The project develops a data-driven framework for closed-loop control of flexible-fish locomotion, integrating CFD-resolved fish–fluid simulations, disagreement-guided trajectory data collection, action-conditioned dynamics learning, and model predictive control (MPC). The learned dynamics model is designed to efficiently predict the future motion of the flexible fish under candidate body-wave commands, enabling rapid action-sequence evaluation and closed-loop target-reaching control without repeatedly performing expensive CFD rollouts during the MPC planning process.

The repository is intended to include the main implementations used in this work, including the **IB–LBM-based flexible-fish simulation environment**, **trajectory generation and disagreement-guided active data collection**, **RR-RSSM dynamics-model training**, **baseline models including ARX, LSTM, and Baseline RSSM**, **learned-dynamics-based MPC planning and control**, as well as the corresponding **configuration, evaluation, and visualization scripts** required to reproduce the main numerical results.

The codebase and configuration files are currently being organized and prepared for public release. **Upon publication of the paper, we will make the complete source code and all relevant configuration files publicly available in this repository.**

For questions or further information, please contact **[1022201147@tju.edu.cn](mailto:1022201147@tju.edu.cn)**.

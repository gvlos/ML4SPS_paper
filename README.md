# State and Action Factorization in Power Grids

Paper presented at the [ML4SPS workshop](https://sites.google.com/view/ml4sps) during the [ECML 2024](https://ecmlpkdd.org/2024/) conference.

PDF ---> [here](https://github.com/gvlos/ML4SPS_paper/blob/main/_ML4SPS_camera_ready.pdf)

**Authors**: Gianvito Losapio, Davide Beretta, Marco Mussi, Alberto Maria Metelli, Marcello Restelli

**Abstract**: The increase of renewable energy generation towards the zero-emission target is making the problem of controlling power grids more and more challenging. The recent series of competitions Learning To Run a Power Network (L2RPN) have encouraged the use of Reinforcement Learning (RL) for the assistance of human dispatchers in operating power grids. All the solutions proposed so far severely restrict the action space and are based on a single agent acting on the entire grid or multiple independent agents acting at the substations level. In this work, we propose a domain-agnostic algorithm that estimates correlations between state and action components entirely based on data. Highly correlated state-action pairs are grouped together to create simpler, possibly independent subproblems that can lead to distinct learning processes with less computational and data requirements. The algorithm is validated on a power grid benchmark obtained with the Grid2Op simulator that has been used throughout the aforementioned competitions, showing that our algorithm is in line with domain-expert analysis. Based on these results, we lay a theoretically-grounded foundation for using distributed reinforcement learning in order to improve the existing solutions.

# :robot: awesome-generative-flows
![contributing-image](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

Awesome papers related to generative flow matching and its applications in bioinformatics.

**Please feel free to create a pull request if you would like to add other awesome papers.**

[![Star History Chart](https://api.star-history.com/svg?repos=amorehead/awesome-generative-flows&type=Date)](https://star-history.com/#amorehead/awesome-generative-flows&Date)
# Contributors

<!-- readme: collaborators,contributors -end -->

<a href="https://github.com/amorehead/awesome-generative-flows/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=amorehead/awesome-generative-flows" />
</a>

### Open-source Methods for Flow Matching Models

| Method Name                                                                                                                    | Year | Brief Description                                       | Source Code                                                           |
| ------------------------------------------------------------------------------------------------------------------------------ | ---- | ------------------------------------------------------- | --------------------------------------------------------------------- |
| Neural Autoregressive Flows ([Huang et al., 2018](https://github.com/CW-Huang/NAF/))                                           | 2018 | Foundational model                                      | [GitHub](https://github.com/CW-Huang/NAF/)                            |
| Neural (latent) ODE ([Chen et al., 2018](https://github.com/rtqichen/torchdiffeq))                                             | 2018 | Foundational model                                      | [GitHub](https://github.com/rtqichen/torchdiffeq)                     |
| GLOW ([Kingma et al., 2018](https://github.com/openai/glow))                                                                   | 2018 | Foundational generative flows                           | [GitHub](https://github.com/openai/glow)                              |
| FFJORD ([Grathwohl et al., 2019](https://github.com/rtqichen/ffjord))                                                          | 2019 | Improves computational efficiency of Neural ODE         | [GitHub](https://github.com/rtqichen/ffjord)                          |
| Augmented Neural ODEs ([Dupont et al., 2019](https://github.com/EmilienDupont/augmented-neural-odes))                          | 2019 | Foundational neural ODE                                 | [GitHub](https://github.com/EmilienDupont/augmented-neural-odes)      |
| Residual Flows ([Chen et al., 2019](https://github.com/rtqichen/residual-flows))                                               | 2019 | Invertible generative flows                             | [GitHub](https://github.com/rtqichen/residual-flows)                  |
| Graph Normalizing Flows ([Liu et al., 2019](https://github.com/jliu/graph-normalizing-flows))                                  | 2019 | Generative geometric flows                              | [GitHub](https://github.com/jliu/graph-normalizing-flows)             |
| Stochastic Normalizing Flows ([Wu et al., 2020](https://github.com/noegroup/stochastic_normalizing_flows))                     | 2020 | Generative stochastic flows                             | [GitHub](https://github.com/noegroup/stochastic_normalizing_flows)    |
| Equivariant Normalizing Flows ([Garcia Satorras et al., 2021](https://github.com/vgsatorras/en_flows))                         | 2021 | Generative equivariant flows                            | [GitHub](https://github.com/vgsatorras/en_flows)                      |
| Diffusion Normalizing Flow ([Zhang et al., 2021](https://github.com/qsh-zh/DiffFlow))                                          | 2021 | Generative stochastic flows                             | [GitHub](https://github.com/qsh-zh/DiffFlow)                          |
| Monte Carlo Flows ([Gabrie et al., 2022](https://github.com/marylou-gabrie/flonaco))                                           | 2022 | Flows for MCMC                                          | [GitHub](https://github.com/marylou-gabrie/flonaco)                   |
| Divergence-free Neural Conservation Laws ([Richter et al., 2022](https://github.com/facebookresearch/neural-conservation-law)) | 2022 | Flows with divergence-free neural networks              | [GitHub](https://github.com/facebookresearch/neural-conservation-law) |
| Rectified Flows ([Liu et al., 2022](https://github.com/gnobitab/RectifiedFlow))                                                | 2022 | Straight and fast flow trajectories                     | [GitHub](https://github.com/gnobitab/RectifiedFlow)                   |
| Flow Matching for Generative Modeling ([Lipman et al., 2022](https://github.com/facebookresearch/flow_matching))               | 2022 | Generative flows with Gaussian probability paths        | [GitHub](https://github.com/facebookresearch/flow_matching)           |
| Stochastic Interpolants (InterFlow) ([Albergo et al., 2022](https://github.com/malbergo/stochastic-interpolants))              | 2022 | Building flows with stochastic interpolants & diffusion | [GitHub](https://github.com/malbergo/stochastic-interpolants)         |
| RIVER ([Davtyan et al., 2022](https://github.com/araachie/river))                                                              | 2022 | Flow matching for video prediction                      | [GitHub](https://github.com/araachie/river)                           |
| Point Straight Flow ([Wu et al., 2022](https://github.com/klightz/PSF))                                                        | 2022 | Generating point clouds with straight and fast flows    | [GitHub](https://github.com/klightz/PSF)                              |
| Action Matching ([Neklyudov et al., 2023](https://github.com/necludov/jam))                                                    | 2023 | Generative optimal transport with arbitrary paths       | [GitHub](https://github.com/necludov/jam)                             |
| OT Conditional Flow Matching ([Tong et al., 2023](https://github.com/atong01/conditional-flow-matching))                       | 2023 | Generative (conditional) continuous flows               | [GitHub](https://github.com/atong01/conditional-flow-matching)        |

... *(List truncated for brevity — see original content for full list)*

### Application-Specific Flow Matching Models

| Research Area      | Applications                             | Method Name | Flow Conditioning         | Network Architecture          | Source Code                                                                                                    |
| ------------------ | ---------------------------------------- | ----------- | ------------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Molecular modeling | Protein sequence generation              | ProtFlow    | Conditioned               | Transformer                   | [GitHub](https://github.com/mabr3112/ProtFlow)                                                                 |
|                    | Protein structure generation             | FrameFlow   | Unconditioned             | SE(3)-equivariant transformer | [GitHub](https://github.com/microsoft/protein-frame-flow)                                                      |
|                    | Protein structure generation             | FoldFlow    | Unconditioned             | SE(3)-equivariant transformer | [GitHub](https://github.com/DreamFold/FoldFlow)                                                                |
|                    | Protein side-chain packing               | FlowPacker  | Conditioned               | SE(3)-equivariant transformer | [GitHub](https://gitlab.com/mjslee0921/flowpacker)                                                             |
|                    | Protein sequence & structure generation  | Multiflow   | Unconditioned             | SE(3)-equivariant transformer | [GitHub](https://github.com/jasonkyuyim/multiflow)                                                             |
|                    | Protein sequence & structure generation  | CoFlow      | Conditioned               | Transformer                   | [GitHub](https://github.com/LtECoD/CoFlow)                                                                     |
|                    | Protein sequence & structure generation  | OriginFlow  | Unconditioned/Conditioned | Transformer                   | [GitHub](https://github.com/JoreyYan/Originflow)                                                               |
|                    | Antibody sequence & structure generation | FlowDesign  | Conditioned               | SE(3)-equivariant transformer | -                                                                                                              |
|                    | Peptide sequence & structure generation  | D-Flow      | Conditioned               | Transformer                   | [GitHub](https://github.com/smiles724/PeptideDesign)                                                           |
|                    | Small molecule generation                | MolFM       | Unconditioned             | Geometric GNN                 | [GitHub](https://github.com/AlgoMole/MolFM)                                                                    |
|                    | Small molecule generation                | SemlaFlow   | Unconditioned             | Geometric GNN                 | [GitHub](https://github.com/rssrwn/semla-flow)                                                                 |
|                    | Small molecule generation                | FlowMol     | Unconditioned             | Geometric GNN                 | [GitHub](https://github.com/Dunni3/FlowMol)                                                                    |
|                    | Small molecule conformer prediction      | ET-Flow     | Conditioned               | Transformer                   | [GitHub](https://github.com/shenoynikhil/ETFlow)                                                               |
|                    | Small molecule & materials generation    | ADiT        | Unconditioned             | All-atom transformer          | \[GitHub]\([https://github.com/facebookresearch/all-atom-d](https://github.com/facebookresearch/all-atom-d)... |

... *(Table truncated for brevity — see original content for full list)*

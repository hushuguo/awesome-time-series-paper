# awesome-time-series-papers
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) ![Stars](https://img.shields.io/github/stars/hushuguo/awesome-time-series-papers
)


This repository is a comprehensive collection of recent research papers and resources in the field of time series analysis, spanning a wide range of topics including forecasting, anomaly detection, early classification, irregular time series learning, representation learning, and more.

## Some Additional Information

🚩 2025/2/12: **Add causal discovery Part**

🚩 2025/2/12: **Add ICLR 2025 Papers**

🚩 2025/1/23: **Add AAAI 2025 Papers**

🚩 2024/12/23: **Add ICDM 2025 Papers**

🚩 2024/12/8: **Add VLDB 2024 Papers**

🚩 2024/10/30: **Add NeurIPS 2024 Papers**

🚩 2024/10/11: **Add ICML 2024 Papers**

🚩 2024/9/4: **Add KDD 2024 Papers**

## Cateloge
<div align="center">

  [Time Series Forecasting](#time-series-forecasting)  
  
  [Time Series Anomaly Detection](#time-series-anomaly-detection)

  [Time Series Early Classification](#time-series-early-classification)

  [Irregular Time Series Learning](#irregular-time-series-learning)

  [Time Series Representation Learning](#time-series-representation-learning)
  
  [Time Series Causal Discovery](#time-series-causal-discovery)

  [Time Series Classification](#time-series-classification)

  [Theory Resource](#theory-resource)
  
  [Code Resource](#code-resource)

</div>



## Time Series Forecasting

### 2024

| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [Investigating Pattern Neurons in Urban Time Series Forecasting](https://openreview.net/forum?id=a9vey6B54y) | [Code](https://anonymous.4open.science/r/PN-Train) | ICLR 2025 |
| [Timer-XL: Long-Context Transformers for Unified Time Series Forecasting](https://openreview.net/forum?id=KMCJXjlDDr) | None | ICLR 2025 |
| [In-context Time Series Predictor](https://openreview.net/forum?id=dCcY2pyNIO) | None | ICLR 2025 |
| [TimeKAN: KAN-based Frequency Decomposition Learning Architecture for Long-term Time Series Forecasting](https://openreview.net/pdf?id=wTLc79YNbh) | [Code](https://github.com/huangst21/TimeKAN) | ICLR 2025 |
| [A Simple Baseline for Multivariate Time Series Forecasting](https://openreview.net/pdf?id=oANkBaVci5) | [Code](https://openreview.net/forum?id=oANkBaVci5) | ICLR 2025 |
| [Fast and Slow Streams for Online Time Series Forecasting Without Information Leakage](https://openreview.net/forum?id=I0n3EyogMi) | None | ICLR 2025 |
| [Root Cause Analysis of Anomalies in Multivariate Time Series through Granger Causal Discovery](https://openreview.net/forum?id=k38Th3x4d9)  | None  | ICLR 2025 |
| [Label Correlation Biases Direct Time Series Forecast](https://openreview.net/pdf/0fccc26b8bb98e9da2d0932820aa42c47e8ab9e0.pdf)  | None  | ICLR 2025 |
| [TimeMixer++: A General Time Series Pattern Machine for Universal Predictive Analysis](https://openreview.net/forum?id=1CLzLXSFNn)  | None  | ICLR 2025 |
| [CSformer: Combining Channel Independence and Mixing for Robust Multivariate Time Series Forecasting](https://arxiv.org/abs/2312.06220)  | None  | AAAI 2025 |
| [CALF: Aligning LLMs for Time Series Forecasting via Cross-modal Fine-Tuning](https://arxiv.org/pdf/2403.07300) | [Code](https://github.com/Hank0626/CALF) | AAAI 2025 |
| [Revisiting Attention for Multivariate Time Series Forecasting](https://arxiv.org/pdf/2407.13806) | [Code](https://github.com/Joeland4/FSatten-SOatten) | AAAI 2025 |
| [Battling the Non-stationarity in Time Series Forecasting via Test-time Adaptation](https://arxiv.org/pdf/2501.04970) | [Code](https://github.com/kimanki/TAFAS) | AAAI 2025 |
| [Unlocking the Power of LSTM for Long Term Time Series Forecasting](https://arxiv.org/abs/2408.10006) | None | AAAI 2025 |
| [Unlocking the Power of Patch: Patch-Based MLP for Long-Term Time Series Forecasting](https://arxiv.org/abs/2405.13575) | [Code](https://github.com/TangPeiwang/PatchMLP) | AAAI 2025 |
| [Adaptive Multi-Scale Decomposition Framework for Time Series Forecasting](https://arxiv.org/pdf/2406.03751) | [Code](https://github.com/TROUBADOUR000/AMD) | AAAI 2025 |
| [Neural Conformal Control for Time Series Forecasting](https://arxiv.org/pdf/2412.18144) | [Code](https://github.com/complex-ai-lab/ncc) | AAAI 2025 |
| [TimeCMA: Towards LLM-Empowered Multivariate Time Series Forecasting via Cross-Modality Alignment](https://arxiv.org/pdf/2406.01638) | [Code](https://github.com/ChenxiLiu-HNU/TimeCMA) | AAAI 2025 |
| [Hierarchical Classification Auxiliary Network for Time Series Forecasting](https://arxiv.org/pdf/2405.18975) | [Code](https://github.com/syrGitHub/HCAN) | AAAI 2025 |
| [Apollo-Forecast: Overcoming Aliasing and Inference Speed Challenges in Language Models for Time Series Forecasting	](https://arxiv.org/pdf/2412.12226) | None | AAAI 2025 |
| [Sequence Complementor: Complementing Transformers For Time Series Forecasting with Learnable Sequences](https://arxiv.org/pdf/2501.02735) | None | AAAI 2025 |
| [Auto-Regressive Moving Diffusion Models for Time Series Forecasting](https://arxiv.org/abs/2412.09328) | [Code](https://github.com/daxin007/ARMD) | AAAI 2025 |
| [xPatch: Dual-Stream Time Series Forecasting with Exponential Seasonal-Trend Decomposition](https://arxiv.org/abs/2412.17323) | [Code](https://github.com/stitsyuk/xpatch) | AAAI 2025 |
| [WPMixer: Efficient Multi-Resolution Mixing for Long-Term Time Series Forecasting](https://arxiv.org/abs/2412.17176) | [Code](https://github.com/Secure-and-Intelligent-Systems-Lab/WPMixer) | AAAI 2025 |
| [Cherry-Picking in Time Series Forecasting: How to Select Datasets to Make Your Model Shine](https://arxiv.org/abs/2412.14435) | [Code](https://github.com/luisroque/bench) | AAAI 2025 |
| [Multiple Time Series Forecasting with Dynamic Graph Modeling](https://www.vldb.org/pvldb/vol17/p753-zhao.pdf) | [Code](https://github.com/zhkai/MTSF-DG) | VLDB 2024|
| [TFB: Towards Comprehensive and Fair Benchmarking of Time Series Forecasting Methods](https://www.vldb.org/pvldb/vol17/p2363-hu.pdf) | [Code](https://github.com/decisionintelligence/TFB) | VLDB 2024|
| [Weakly Guided Adaptation for Robust Time Series Forecasting](https://www.vldb.org/pvldb/vol17/p766-cheng.pdf) | [Code](https://github.com/YunyaoCheng/DARF) | VLDB 2024|
| [Retrieval-Augmented Diffusion Models for Time Series Forecasting](https://arxiv.org/abs/2410.18712) | [Code](https://github.com/AdityaLab/FOIL) | NeurIPS 2024|
| [Attractor Memory for Long-Term Time Series Forecasting: A Chaos Perspective](https://arxiv.org/abs/2402.11463) | None | NeurIPS 2024|
| [Frequency Adaptive Normalization For Non-stationary Time Series Forecasting](https://arxiv.org/abs/2409.20371) | [Code](https://github.com/wayne155/FAN) | NeurIPS 2024|
| [Rethinking the Power of Timestamps for Robust Time Series Forecasting: A Global-Local Fusion Perspective](https://arxiv.org/pdf/2409.18696) | [Code](https://github.com/ForestsKing/GLAFF) | NeurIPS 2024|
| [AutoTimes: Autoregressive Time Series Forecasters via Large Language Models](https://arxiv.org/abs/2402.02370) | [Code](https://github.com/thuml/AutoTimes) | NeurIPS 2024|
| [BackTime: Backdoor Attacks on Multivariate Time Series Forecasting](https://arxiv.org/pdf/2410.02195) | [Code](https://github.com/xiaolin-cs/BackTime) | NeurIPS 2024|
| [Are Language Models Actually Useful for Time Series Forecasting?](https://arxiv.org/abs/2406.16964) | [Code](https://github.com/BennyTMT/LLMsForTimeSeries) | NeurIPS 2024|
| [Parsimony or Capability? Decomposition Delivers Both in Long-term Time Series Forecasting](https://arxiv.org/abs/2401.11929) | [Code](https://github.com/AdityaLab/FOIL) | NeurIPS 2024|
| [SOFTS: Efficient Multivariate Time Series Forecasting with Series-Core Fusion](https://arxiv.org/abs/2404.14197) | [Code](https://github.com/Secilia-Cxy/SOFTS) | NeurIPS 2024|
| [CycleNet: Enhancing Time Series Forecasting through Modeling Periodic Patterns](https://arxiv.org/abs/2409.18479) | [Code](https://github.com/ACAT-SCUT/CycleNet) | NeurIPS 2024|
| [CondTSF: One-line Plugin of Dataset Condensation for Time Series Forecasting](https://arxiv.org/abs/2406.02131) | [Code](https://github.com/RafaDD/CondTSF) | NeurIPS 2024|
| [Scaling Law for Time Series Forecasting](https://arxiv.org/pdf/2405.15124) | [Code](https://github.com/JingzheShi/ScalingLawForTimeSeriesForecasting) | NeurIPS 2024|
| [From News to Forecast: Integrating Event Analysis in LLM-Based Time Series Forecasting with Reflection](https://arxiv.org/abs/2409.17515) | [Code](https://github.com/ameliawong1996/From_News_to_Forecast) | NeurIPS 2024|
| [TimeXer: Empowering Transformers for Time Series Forecasting with Exogenous Variables](https://arxiv.org/pdf/2402.19072) | [Code](https://github.com/thuml/TimeXer) | NeurIPS 2024|
| [Are Self-Attentions Effective for Time Series Forecasting?](https://arxiv.org/abs/2405.16877) | [Code](https://github.com/dongbeank/CATS) | NeurIPS 2024|
| [Time-Series Forecasting for Out-of-Distribution Generalization Using Invariant Learning](https://arxiv.org/abs/2406.09130) | [Code](https://github.com/AdityaLab/FOIL) | ICML 2024|
| [Learning Optimal Projection for Forecast Reconciliation of Hierarchical Time Series](https://openreview.net/pdf?id=55HfvJ6lDB) | None | ICML 2024|
| [Irregular Multivariate Time Series Forecasting: A Transformable Patching Graph Neural Networks Approach](https://openreview.net/pdf?id=UZlMXUGI6e) | [Code](https://github.com/usail-hkust/t-PatchGNN) | ICML 2024|
| [SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters](https://arxiv.org/abs/2405.00946) | [Code](https://github.com/lss-1138/SparseTSF) | ICML 2024|
| [A decoder-only foundation model for time-series forecasting](https://arxiv.org/pdf/2310.10688) | [Code](https://github.com/google-research/timesfm) | ICML 2024|
| [SIN: Selective and Interpretable Normalization for Long-Term Time Series Forecasting](https://icml.cc/virtual/2024/poster/33594) | None | ICML 2024|
| [CATS: Enhancing Multivariate Time Series Forecasting by Constructing Auxiliary Time Series as Exogenous Variables](https://arxiv.org/pdf/2403.01673) | [Code](https://github.com/LJC-FVNR/CATS) | ICML 2024|
| [Unified Training of Universal Time Series Forecasting Transformers](https://arxiv.org/abs/2402.02592) | [Code](https://github.com/SalesforceAIResearch/uni2ts) | ICML 2024|
| [Transformers with Loss Shaping Constraints for Long-Term Time Series Forecasting](https://arxiv.org/pdf/2402.09373) | None | ICML 2024|
| [Deep Functional Factor Models: Forecasting High-Dimensional Functional Time Series via Bayesian Nonparametric Factorization](https://arxiv.org/abs//2403.14587) | [Code](https://github.com/yiruiliu110/df2m) | ICML 2024|
| [An Analysis of Linear Time Series Forecasting Models](https://arxiv.org/abs//2403.14587) | [Code](https://github.com/VEWOXIC/FITS/) | ICML 2024|
| [SAMformer: Unlocking the Potential of Transformers in Time Series Forecasting with Sharpness-Aware Minimization and Channel-Wise Attention](https://arxiv.org/pdf/2402.10198) | [Code](https://github.com/romilbert/samformer) | ICML 2024|
| [Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting](https://arxiv.org/abs/2405.10800) | [Code](https://github.com/XDZhelheim/HimNet) | KDD 2024|
| [STEMO: Early Spatio-temporal Forecasting with Multi-Objective Reinforcement Learning](https://arxiv.org/abs/2406.04035) | [Code](https://github.com/coco0106/MO-STEP) | KDD 2024|
| [Irregular Traffic Time Series Forecasting Based on Asynchronous Spatio-Temporal Graph Convolutional Networks](https://arxiv.org/abs/2308.16818) | None | KDD 2024|
| [UniST: A Prompt-empowered Universal Model for Urban Spatio-temporal Prediction](https://arxiv.org/abs/2402.11838) | [Code](https://github.com/tsinghua-fib-lab/UniST) | KDD 2024|
| [UniTS: Building a Unified Time Series Model](https://arxiv.org/pdf/2403.00131.pdf) | [Code](https://github.com/mims-harvard/units) | Arxiv |
| [TimeMachine: A Time Series is Worth 4 Mambas for Long-term Forecasting](https://arxiv.org/pdf/2403.09898.pdf) | [Code](https://github.com/Atik-Ahamed/TimeMachine) | ECAI 2024 |
| [Time Evidence Fusion Network: Multi-source View in Long-Term Time Series Forecasting](https://arxiv.org/abs/2405.06419) | [Code](https://github.com/ztxtech/Time-Evidence-Fusion-Network) | Arxiv |
| [E2Usd: Efficient-yet-effective Unsupervised State Detection for Multivariate Time Series](https://arxiv.org/pdf/2402.14041) | [Code](https://github.com/AI4CTS/E2Usd)| WWW 2024 |
| [UniTime: A Language-Empowered Unified Model for Cross-Domain Time Series Forecasting](https://arxiv.org/abs/2310.09751) | [Code](https://github.com/liuxu77/UniTime) | WWW 2024 |
| [Dynamic Multi-Network Mining of Tensor Time Series](https://arxiv.org/abs/2310.09751) | [Code](https://github.com/KoheiObata/DMM) | WWW 2024 |
| [CARD: Channel Aligned Robust Blend Transformer for Time Series Forecasting](https://openreview.net/forum?id=MJksrOhurE) | [Code](https://github.com/wxie9/card) | ICLR 2024 |
| [Pathformer: Multi-scale Transformers with Adaptive Pathways for Time Series Forecasting](https://openreview.net/forum?id=lJkOCMP2aW) | [Code](https://github.com/decisionintelligence/pathformer) | ICLR 2024 |
| [GAFormer: Enhancing Timeseries Transformers Through Group-Aware Embeddings](https://openreview.net/forum?id=c56TWtYp0W) | None | ICLR 2024 |
| [Transformer-Modulated Diffusion Models for Probabilistic Multivariate Time Series Forecasting](https://openreview.net/forum?id=qae04YACHs) | None | ICLR 2024 |
| [iTransformer: Inverted Transformers Are Effective for Time Series Forecasting](https://openreview.net/forum?id=JePfAI8fah) | [Code](https://github.com/thuml/iTransformer?utm_source=catalyzex.com) | ICLR 2024 |
| [TimeMixer: Decomposable Multiscale Mixing for Time Series Forecasting](https://openreview.net/pdf?id=7oLshfEIC2) | [Code](https://github.com/kwuking/TimeMixer) | ICLR 2024 |
| [Considering Nonstationary within Multivariate Time Series with Variational Hierarchical Transformer for Forecasting](#) | None | AAAI 2024 |
| [Latent Diffusion Transformer for Probabilistic Time Series Forecasting](#) | None | AAAI 2024 |

### 2023

| Method Name | Code | Source |
| ------- | ------ | -------- |
| [MICN: Multi-scale Local and Global Context Modeling for Long-term Series Forecasting](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/wanghq21/MICN) | ICLR 2023 |
| [Crossformer: Transformer Utilizing Cross-Dimension Dependency for Multivariate Time Series Forecasting](https://openreview.net/pdf?id=vSVLM2j9eie) | [Code](https://github.com/Thinklab-SJTU/Crossformer) | ICLR 2023 |
| [Scaleformer: Iterative Multi-scale Refining Transformers for Time Series Forecasting](https://openreview.net/pdf?id=sCrnllCtjoE) | [Code](https://github.com/BorealisAI/scaleformer) | ICLR 2023 |
| [SAITS: Self-Attention-based Imputation for Time Series](https://arxiv.org/abs/2202.08516) | [Code](https://github.com/WenjieDu/SAITS/) | Expert Systems with Applications |
| [A Time Series is Worth 64 Words: Long-term Forecasting with Transformers](http://arxiv.org/abs/2211.14730) | [Code](https://github.com/yuqinie98/PatchTST) | ICLR 2023 |

### 2022

| Method Name | Code | Source |
| ------- | ------ | ------ |
| [Non-stationary Transformers: Rethinking the Stationarity in Time Series Forecasting](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |
| [Generative Time Series Forecasting with Diffusion, Denoise and Disentanglement](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |
| [SCINet: Time Series Modeling and Forecasting with Sample Convolution and Interaction](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |
| [Learning Latent Seasonal-Trend Representations for Time Series Forecasting](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |
| [GT-GAN: General Purpose Time Series Synthesis with Generative Adversarial Networks](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |
| [FiLM: Frequency improved Legendre Memory Model for Long-term Time Series Forecasting](https://openreview.net/pdf?id=zt53IDUR1U) | [Code](https://github.com/user/repo) | NeurIPS 2022 |

### 2021

| Method Name | Code | Source |
| ------- | ------ | ------ |
| [Probabilistic Transformer For Time Series Analysis](https://openreview.net/forum?id=HfpNVDg3ExA) | [Code](https://github.com/user/repo) | NeurIPS 2021 |
| [Autoformer: Decomposition transformers with auto-correlation for long-term series forecasting](https://papers.nips.cc/paper/2021/file/bcc0d400288793e8bdcd7c19a8ac0c2b-Paper.pdf) | [Code](https://github.com/user/repo) | NeurIPS 2021 |
| [Whittle Networks: A Deep Likelihood Model for Time Series](https://www.ml.informatik.tu-darmstadt.de/papers/yu2021icml_wspn.pdf) | [Code](https://github.com/ml-research/WhittleNetworks) | ICML 2021 |
| [Z-GCNETs: Time Zigzags at Graph Convolutional Networks for Time Series Forecasting](https://arxiv.org/abs/2105.04100) | [Code](https://github.com/Z-GCNETs/Z-GCNETs) | ICML 2021 |
| [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://arxiv.org/abs/2012.07436) | [Code](https://github.com/zhouhaoyi/Informer2020) | AAAI 2021 |

### 2020

| Method Name | Code | Source |
| ------- | ------ | ------ |
| [Block Hankel Tensor ARIMA for Multiple Short Time Series Forecasting](https://ojs.aaai.org/index.php/AAAI/article/download/6032/5888) | [Code](https://github.com/huawei-noah/BHT-ARIMA) | AAAI 2020 |
| [Adversarial Sparse Transformer for Time Series Forecasting](https://proceedings.neurips.cc/paper/2020/file/c6b8c8d762da15fa8dbbdfb6baf9e260-Paper.pdf) | None | NeurIPS 2020 |
| [Benchmarking Deep Learning Interpretability in Time Series Predictions](https://arxiv.org/pdf/2010.13924) | [Code](https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark) | NeurIPS 2020 |

## Time Series Anomaly Detection
| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [Learn hybrid prototypes for multivariate time series anomaly detection](https://openreview.net/forum?id=8TBGdH3t6a) | None | ICLR 2025 |
| [Can LLMs Understand Time Series Anomalies?](https://openreview.net/forum?id=LGafQ1g2D2) | [Code](https://openreview.net/forum?id=LGafQ1g2D2) | ICLR 2025 |
| [CATCH: Channel-Aware Multivariate Time Series Anomaly Detection via Frequency Patching](https://openreview.net/pdf?id=m08aK3xxdJ) | [Code](https://anonymous.4open.science/r/CATCH-E535/README.md) | ICLR 2025 |
| [Multi-Resolution Decomposable Diffusion Model for Non-Stationary Time Series Anomaly Detection](https://openreview.net/pdf?id=eWocmTQn7H) | [Code](https://openreview.net/forum?id=eWocmTQn7H) | ICLR 2025 |
| [ImDiffusion: Imputed Diffusion Models for Multivariate Time Series Anomaly Detection](https://www.vldb.org/pvldb/vol17/p359-zhang.pdf) | [Code](https://github.com/17000cyh/IMDiffusion) | VLDB 2024|
| [An Experimental Evaluation of Anomaly Detection in Time Series](https://www.vldb.org/pvldb/vol17/p483-zhang.pdf) | [Code](https://github.com/zaqthss/experiment-tsad) | VLDB 2024|
| [AutoTSAD: Unsupervised Holistic Anomaly Detection for Time Series Data](https://www.vldb.org/pvldb/vol17/p483-zhang.pdf) | [Code](https://github.com/zaqthss/experiment-tsad) | VLDB 2024|
| [Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series](https://arxiv.org/abs/2401.03955) | [Code](https://github.com/ibm-granite/granite-tsfm/tree/main/tsfm_public/models/tinytimemixer) | NeurIPS 2024|
| [STONE: A Spatio-temporal OOD Learning Framework Kills Both Spatial and Temporal Shifts](https://dl.acm.org/doi/10.1145/3637528.3671680) | None | KDD 2024|
| [LARA: A Light and Anti-overfitting Retraining Approach for Unsupervised Time Series Anomaly Detection](https://arxiv.org/abs/2405.06419) | None | WWW 2024 |
| [Breaking the Time-Frequency Granularity Discrepancy in Time-Series Anomaly Detection](https://arxiv.org/abs/2405.06419) | [Code](https://dl.acm.org/doi/10.1145/3589334.3645556) | WWW 2024 |
| [Revisiting VAE for Unsupervised Time Series Anomaly Detection: A Frequency Perspective](https://arxiv.org/pdf/2402.02820) | [Code](https://github.com/CSTCloudOps/FCVAE)| WWW 2024 |
| [MEMTO: Memory-guided Transformer for Multivariate Time Series Anomaly Detection](https://openreview.net/forum?id=UFW67uduJd) | None | NeurIPS 2023 |
| [CAT: Beyond Efficient Transformer for Content-Aware Anomaly Detection in Event Sequences](https://dl.acm.org/doi/abs/10.1145/3534678.3539155) | [Code](https://github.com/mmichaelzhang/CAT) | KDD 2022 |
| [DCT-GAN: Dilated Convolutional Transformer-based GAN for Time Series Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/9626552) | None | TKDE 2022 |
| [Concept Drift Adaptation for Time Series Anomaly Detection via Transformer](https://link.springer.com/article/10.1007/s11063-022-11015-0) | None | Neural Processing Letters 2022 |
| [Anomaly Transformer: Time Series Anomaly Detection with Association Discrepancy](https://arxiv.org/abs/2110.02642) | [Code](https://github.com/thuml/Anomaly-Transformer) | ICLR 2022 |
| [TranAD: Deep Transformer Networks for Anomaly Detection in Multivariate Time Series Data](https://arxiv.org/abs/2201.07284) | [Code](https://github.com/imperial-qore/tranad) | VLDB 2022 |
| [Learning graph structures with transformer for multivariate time series anomaly detection in IoT](https://arxiv.org/abs/2104.03466) | [Code](https://github.com/ZEKAICHEN/GTA) | IEEE Internet of Things Journal 2021 |
| [Spacecraft Anomaly Detection via Transformer Reconstruction Error](http://www.utias.utoronto.ca/wp-content/uploads/2019/07/88-Spacecraft-anomaly-detection-via-transformer-reconstruction-error.pdf) | None | ICASSE 2019 |
| [Unsupervised Anomaly Detection in Multivariate Time Series through Transformer-based Variational Autoencoder](https://ieeexplore.ieee.org/abstract/document/9601669) | None | CCDC 2021 |
| [Variational Transformer-based anomaly detection approach for multivariate time series](https://www.sciencedirect.com/science/article/abs/pii/S0263224122000914) | None | Measurement 2022 |

## Time Series Early Classification
| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [Second-order Confidence Network for Early Classification of Time Series](https://dl.acm.org/doi/10.1145/3631531) | None | TIST 2023 |
| [CALIMERA: : A new early time series classification method](https://dl.acm.org/doi/10.1016/j.ipm.2023.103465) | [Code](https://github.com/JakubBilski/CALIMERA) | IPM 2023 |
| [TEASER: Early and Accurate Time Series Classification](https://arxiv.org/abs/1908.03405) | [Code](https://github.com/patrickzib/SFA) | DMKD 2020|
| [An Effective Confidence-Based Early Classification of Time Series](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8765556) | [Code](https://github.com/junweilvhfut/ECEC) | Access 2019|

## Irregular Time Series Learning
| Method Name | Code | Source |
| ------- | ------ | ---------- |
|[Amortized Control of Continuous State Space Feynman-Kac Model for Irregular Time Series]() | [Code](https://openreview.net/forum?id=8zJRon6k5v) | ICLR 2025 |
| [Probabilistic Forecasting of Irregularly Sampled Time Series with Missing Values via Conditional Normalizing Flows](https://arxiv.org/abs/2402.06293) | [Code](github.com/yalavarthivk/ProFITi) | AAAI 2025 |
| [TimeCHEAT: A Channel Harmony Strategy for Irregularly Sampled Multivariate Time Series Analysis](https://arxiv.org/abs/2412.12886) | None | AAAI 2025 |
| [EMIT - Event Based Masked Auto Encoding for Irregular Time Series](https://arxiv.org/abs/2409.16554) | [Code](https://github.com/hrishi-ds/EMIT) | ICDM 2024 |


## Time Series Representation Learning
| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [On the Identification of Temporal Causal Representation with Instantaneous Dependence](https://openreview.net/forum?id=2efNHgYRvM) | [Code](https://openreview.net/forum?id=2efNHgYRvM) | ICLR 2025 |
| [Shedding Light on Time Series Classification using Interpretability Gated Networks](https://openreview.net/pdf?id=n34taxF0TC) | None | ICLR 2025 |
| [requency-Masked Embedding Inference: A Non-Contrastive Approach for Time Series Representation Learning](https://arxiv.org/pdf/2412.20790) | [Code](https://github.com/USTBInnovationPark/Frequency-masked-Embedding-Inference) | AAAI 2025|
| [Cross-Domain Pre-training with Language Models for Transferable Time Series Representations](https://arxiv.org/abs/2403.12372) | [Code](https://github.com/anhduy0911/CoInception) | WSDM 2024|
| [Improving Time Series Encoding with Noise-Aware Self-Supervised Learning and an Efficient Encoder](https://arxiv.org/abs/2306.06579) | [Code](https://github.com/anhduy0911/CoInception) | ICDM 2024|
| [A Shapelet-based Framework for Unsupervised Multivariate Time Series Representation Learning](https://www.vldb.org/pvldb/vol17/p386-wang.pdf) | [Code](https://github.com/real2fish/CSL) | VLDB 2024|

## Time Series Causal Discovery
| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [DyCAST: Learning Dynamic Causal Structure from Time Series](https://link.zhihu.com/?target=https%3A//openreview.net/forum%3Fid%3DWjDjem8mWE) | None | ICLR 2025 |
| [CausalRivers - Scaling up benchmarking of causal discovery for real-world time-series](https://openreview.net/forum?id=wmV4cIbgl6) | [Code](https://openreview.net/forum?id=wmV4cIbgl6) | ICLR 2025 |

## Time Series Classification
| Method Name | Code | Source |
| ------- | ------ | ---------- |
| [PPT: Patch Order Do Matters In Time Series Pretext Task](https://openreview.net/forum?id=7zwIEbSTDy) | None | ICLR 2025 |
| [Advancing Time Series Classification with Multimodal Language Modeling](https://arxiv.org/abs/2403.12371) | [Code](https://github.com/Mingyue-Cheng/InstructTime) | WSDM 2024|

## Theory Resource

| Course Name | Link | Source |
| ----------- | ---- | ------ |
| [Time Series Analysis, MIT](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/) | [MIT OCW](https://ocw.mit.edu/) | MIT |
| [Time Series Forecasting, Udacity](https://www.udacity.com/course/time-series-forecasting--ud980) | [Udacity](https://www.udacity.com/) | Udacity |
| [Practical Time Series Analysis, Coursera](https://www.coursera.org/learn/practical-time-series-analysis) | [Coursera](https://www.coursera.org/) | Coursera |
| [Time Series Forecasting using Python](https://courses.analyticsvidhya.com/courses/creating-time-series-forecast-using-python) | [Analytics Vidhya](https://courses.analyticsvidhya.com/) | Analytics Vidhya |
| [Policy Analysis Using Interrupted Time Series, edX](https://www.edx.org/course/policy-analysis-using-interrupted-time-series) | [edX](https://www.edx.org/) | edX |

## Code Resource

| Repository Name | Link | Description |
| --------------- | ---- | ----------- |
| [PyPOTS: A Python Toolbox for Data Mining on Partially-Observed Time Series](https://github.com/WenjieDu/PyPOTS) | [GitHub](https://github.com/WenjieDu/PyPOTS) | Python toolbox for time series |
| [FOST from Microsoft](https://github.com/microsoft/FOST) | [GitHub](https://github.com/microsoft/FOST) | Forecasting toolbox |
| [PyTorch Forecasting](https://github.com/jdb78/pytorch-forecasting) | [GitHub](https://github.com/jdb78/pytorch-forecasting) | Time series forecasting with PyTorch |
| [A collection of time series prediction methods](https://github.com/LongxingTan/Time-series-prediction) | [GitHub](https://github.com/LongxingTan/Time-series-prediction) | Collection of methods |
| [Flow Forecast: A deep learning framework for time series forecasting](https://github.com/AIStream-Peelout/flow-forecast) | [GitHub](https://github.com/AIStream-Peelout/flow-forecast) | Deep learning framework |



## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hushuguo/awesome-time-series-papers&type=Timeline)](https://star-history.com/#hushuguo/awesome-time-series-papers&Timeline)

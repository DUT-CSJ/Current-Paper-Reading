# Current-Paper-Reading

List of recently read papers.

### Visual Correspondence and Few-Shot Segmentation using Foundation Models!!!
 - [ ] Emergent Correspondence from Image Diffusion (NIPS 2023)
 - [ ] Learning Robust Correlation with Foundation Model for Weakly-Supervised Few-Shot Segmentation (KBS 2024)
 - [ ] LANGUAGE-GUIDED FEW-SHOT SEMANTIC SEGMENTATION (ICASSP 2024)
 - [ ] ZERO-SHOT CO-SALIENT OBJECT DETECTION FRAMEWORK (ICASSP 2024)
 - [ ] Matcher: Segment Anything with One Shot Using All-Purpose Feature Matching (ICLR 2024)
 - [ ] A Tale of Two Features: Stable Diffusion Complements DINO for Zero-Shot Semantic Correspondence (NIPS 2023)
 - [ ] OmniGlue: Generalizable Feature Matching with Foundation Model Guidance (CVPR 2024)
 - [ ] Telling Left from Right: Identifying Geometry-Aware Semantic Correspondence (CVPR 2024)

### Matting
 - [x] MatteFormer: Transformer-Based Image Matting via Prior-Tokens (CVPR 2022)
    - Trimap Based Method
    - Tri-token and Memory Based on Swin Transformer
 - [x] Boosting Semantic Human Matting with Coarse Annotations (CVPR 2020)
    - Without any Prior
    - Prediction-Unification-Refinement
    - Promoting Matting from Coarse Data
 - [x] Mask Guided Matting via Progressive Refinement Network (CVPR 2021)
    - Mask Based Method
    - Progressive Refinement
 - [x] Real-Time High-Resolution Background Matting (CVPR 2021 Best Student Paper Honorable Mention)
    - Background Based Method
    - Two Stage: Base Network and Refin Network (Patch Based)
    - Two Datasets, High Speed
 - [x] Robust High-Resolution Video Matting with Temporal Guidance (WACV 2022)
    - Annotation Input Free, Without Pre-captured Background
    - Light Weight, High Speed
 - [ ] SketchEdit: Mask-Free Local Image Manipulation with Partial Sketches (CVPR 2022)
 - [x] ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation (CVPR 2022)
    - Deep-Shallow-Fusion Architecture (Different from Global Lightweight Model and Global Local Refinement)
    - RAF for Feature Fusion
    - Auxiliary Super-Resolution Task
 - [ ] TransMatting: Enhancing Transparent Objects Matting with Transformers (ECCV 2022)
 - [x] Human Instance Matting via Mutual Guidance and Multi-Instance Refinement (CVPR 2022 Oral)
    - Mask Generate (Mask R-CNN) -- Matting (MGMatting) -- Refine (Proposed in This Paper)
    - New Benchmark and Metric

Loss Function in Matting
 - L1 Regression Loss
 - Composition Loss
 - Laplacian Loss

### Super-Resolution (Steal for High-Resolution Image Segmentation)
 - [x] SwinIR: Image Restoration Using Swin Transformer (ICCV 2021)
    - Shallow and Deep Feature Extraction (3x3 Conv and Swin Transformer Block)
    - Reconstruction Decoder (Conv + PixelShuffle)

### Few-Shot Segmentation (Academic Struggle)
 - [x] PANet: Few-Shot Image Semantic Segmentation with Prototype Alignment (ICCV 2019)
 - [ ] GanOrCon: Are Generative Models Useful for Few-Shot Segmentation? (CVPR 2022)
 - [x] Learning What Not To Segment: A New Perspective on Few-Shot Segmentation (CVPR 2022 Oral)
 - [x] Self-support Few-Shot Semantic Segmentation (ECCV 2022)
 - Self-Support Matching (Foreground and Background)
 - SSL Loss
 - Performance is not Outstanding
 - [x] Adaptive Agent Transformer for Few-shot Segmentation (ECCV 2022)
 - [ ] Cost Aggregation with 4D Convolutional Swin Transformer for Few-Shot Segmentation (ECCV 2022)
 - [ ] Dense Gaussian Processes for Few-Shot Segmentation (ECCV 2022)
 - [ ] Doubly Deformable Aggregation of Covariance Matrices for Few-shot Segmentation (ECCV 2022)
 - [x] Dense Cross-Query-and-Support Attention Weighted Mask Aggregation for Few-Shot Segmentation (ECCV 2022)
 - self-attention (1-shot to n-shot easily)
 - [ ] Interclass Prototype Relation for Few-Shot Segmentation (ECCV 2022)
 - [ ] HM: Hybrid Masking for Few-Shot Segmentation (ECCV 2022)

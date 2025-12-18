## Table of contents
- [Blind Face Restoration](#blind-face-restoration)
- [Face Super-Resolution](#face-super-resolution)
- [Image Quality Assessment](#image-quality-assessment)
- [Benchmark Datasets](#benchmark-datasets)

## Blind Face Restoration 
|Year<div style="width:20px">|Venue<div style="width:60px">|Title<div style="width:600px">|Resources<div style="width:100px">|Introduction<div style="width:400px">|
|:---:|:----:|:----:|:----:|:----:|
|2021|CVPR|GAN Prior Embedded Network for Blind Face Restoration in the Wild|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_GAN_Prior_Embedded_Network_for_Blind_Face_Restoration_in_the_CVPR_2021_paper.html)\]\[[code](https://github.com/yangxy/GPEN)\]|GAN|
|2021|CVPR|Towards Real-World Blind Face Restoration With Generative Facial Prior|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_Towards_Real-World_Blind_Face_Restoration_With_Generative_Facial_Prior_CVPR_2021_paper.html)\]\[[code](https://github.com/TencentARC/GFPGAN)\]|GAN|
|2021|CVPR|Progressive Semantic-Aware Style Transformation for Blind Face Restoration|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Progressive_Semantic-Aware_Style_Transformation_for_Blind_Face_Restoration_CVPR_2021_paper.html)\]\[[code](https://github.com/chaofengc/PSFRGAN)\]|GAN/Geo-Prior|
|2022|TPAMI|Face Restoration via Plug-and-Play 3D Facial Priors|\[[paper](https://ieeexplore.ieee.org/document/9591403)\]\[~~code~~]|CNN/Geo-Prior|
|2022|AAAI|Panini-Net: GAN Prior Based Degradation-Aware Feature Interpolation for Face Restoration|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/20159)\]\[[code](https://github.com/jianzhangcs/panini)\]|GAN|
|2022|CVPR|Rethinking Deep Face Restoration|\[[paper](https://doi.org/10.1109/CVPR52688.2022.00750)\]\[~~code~~]|GAN/Codebook|
|2022|CVPR|Blind Face Restoration via Integrating Face Shape and Generative Priors|\[[paper](https://doi.org/10.1109/CVPR52688.2022.00751)\]\[[code](https://github.com/TencentYoutuResearch/FaceRestoration-sgpn)\]|GAN/Geo-Prior|
|2022|CVPR|RestoreFormer: High-Quality Blind Face Restoration from Undegraded Key-Value Pairs|\[[paper](https://doi.org/10.1109/CVPR52688.2022.01699)\]\[[code](https://github.com/wzhouxiff/RestoreFormer)\]|ViT/Codebook|
|2022|CVPR|GCFSR: a Generative and Controllable Face Super Resolution Method Without Facial and GAN Priors|\[[paper](https://doi.org/10.1109/CVPR52688.2022.00193)\]\[[code](https://github.com/hejingwenhejingwen/GCFSR)\]|GAN|
|2022|ECCV|VQFR: Blind Face Restoration with Vector-Quantized Dictionary and Parallel Decoder|\[[paper](https://arxiv.org/abs/2205.06803)\]\[[code](https://github.com/TencentARC/VQFR)\]|CNN/Codebook|
|2022|NeurIPS|Towards Robust Blind Face Restoration with Codebook Lookup Transformer|\[[paper](https://papers.nips.cc/paper_files/paper/2022/hash/c573258c38d0a3919d8c1364053c45df-Abstract-Conference.html)\]\[[code](https://github.com/sczhou/CodeFormer)\]|ViT/Codebook|
|2023|TCSVT|DEAR-GAN: Degradation-Aware Face Restoration With GAN Prior|\[[paper](https://doi.org/10.1109/TCSVT.2023.3244786)\]\[~~code~~]|GAN|
|2023|TPAMI|Learning Dual Memory Dictionaries for Blind Face Restoration|\[[paper](https://ieeexplore.ieee.org/document/9921338)\]\[[code](https://github.com/csxmli2016/DMDNet)\]|ViT/Codebook/Ref|
|2023|TPAMI|RestoreFormer++: Towards Real-World Blind Face Restoration From Undegraded Key-Value Pairs|\[[paper](https://doi.org/10.1109/TPAMI.2023.3315753)\]\[[code](https://github.com/wzhouxiff/RestoreFormerPlusPlus)\]|ViT/Codebook|
|2023|CVPR|DR2: Diffusion-Based Robust Degradation Remover for Blind Face Restoration|\[[paper](https://ieeexplore.ieee.org/document/10204963)\]\[[code](https://github.com/Kaldwin0106/DR2_Drgradation_Remover)\]|Diffusion|
|2023|IJCAI|Analyzing and Combating Attribute Bias for Face Restoration|\[[paper](https://www.ijcai.org/proceedings/2023/128)\]\[[code](https://github.com/Seeyn/DebiasFR)\]|GAN|
|2023|ICCV|Towards Authentic Face Restoration with Iterative Diffusion Models and Beyond|\[[paper](https://ieeexplore.ieee.org/document/10376857)\]\[~~code~~]|Diffusion|
|2023|MM|Exploring Correlations in Degraded Spatial Identity Features for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/10.1145/3581783.3611782)\]\[~~code~~]|GAN|
|2023|MM|DiffBFR: Bootstrapping Diffusion Model for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/10.1145/3581783.3611731)\]\[~~code~~]|Diffusion|
|2023|NeurIPS|PGDiff: Guiding Diffusion Models for Versatile Face Restoration via Partial Guidance|\[[paper](https://papers.nips.cc/paper_files/paper/2023/hash/661c37f3b098bdee53fd7d9c4ef6964a-Abstract-Conference.html)\]\[[code](https://github.com/pq-yang/PGDiff)\]|Diffusion|
|2024|TCSVT|Blind Face Restoration for Under-Display Camera via Dictionary Guided Transformer|\[[paper](https://ieeexplore.ieee.org/abstract/document/10339338)\]\[~~code~~]|ViT|
|2024|TCSVT|Toward Real-World Blind Face Restoration With Generative Diffusion Prior|\[[paper](https://ieeexplore.ieee.org/abstract/document/10486984)\]\[[code](https://github.com/chenxx89/BFRffusion)]|Diffusion|
|2024|TPAMI|DifFace: Blind Face Restoration With Diffused Error Contraction|\[[paper](https://ieeexplore.ieee.org/document/10607954)\]\[[code](https://github.com/zsyOAOA/DifFace)\]|Diffusion|
|2024|AAAI|Blind Face Restoration under Extreme Conditions: Leveraging 3D-2D Prior Fusion for Superior Structural and Texture Recovery|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/27889)\]\[[code](https://github.com/zhengrchan/FREx)\]|GAN/Geo-Prior|
|2024|ICLR|Dual Associated Encoder for Face Restoration|\[[paper](https://openreview.net/forum?id=gwDuW7Ok5f)\]\[[code](https://github.com/LIAGM/DAEFR)\]|ViT/Codebook|
|2024|CVPR|WaveFace: Authentic Face Restoration with Efficient Frequency Recovery|\[[paper](https://ieeexplore.ieee.org/document/10656674)\]\[[code](https://github.com/yoqim/waveface)]|Diffusion|
|2024|CVPR|Learning Degradation-Unaware Representation with Prior-Based Latent Transformations for Blind Face Restoration|\[[paper](https://ieeexplore.ieee.org/document/10655585)\]\[~~code~~]|Diffusion|
|2024|CVPR|PFStorer: Personalized Face Restoration and Super-Resolutionn|\[[paper](https://ieeexplore.ieee.org/document/10657576)\]\[~~code~~]|Diffusion/Ref|
|2024|IJCAI|CLR-Face: Conditional Latent Refinement for Blind Face Restoration Using Score-Based Diffusion Models|\[[paper](https://www.ijcai.org/proceedings/2024/143)\]\[~~code~~]|Diffusion|
|2024|MM|3D Priors-Guided Diffusion for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/10.1145/3664647.3681611)\]\[[code](https://github.com/Xiaobin-Lu/3Diffusion)\]|Diffusion/Geo-Prior|
|2024|MM|LD-BFR: Vector-Quantization-Based Face Restoration Model with Latent Diffusion Enhancement|\[[paper](https://dl.acm.org/doi/10.1145/3664647.3680853)\]\[[code](https://github.com/YuzhenD/LD-BFR.git)\]|Diffusion/Codebook|
|2024|NeurIPS|ReF-LDM: A Latent Diffusion Model for Reference-based Face Image Restoration|\[[paper](https://papers.nips.cc/paper_files/paper/2024/hash/88be023075a5a3ff3dc3b5d26623fa22-Abstract-Conference.html)\]\[[code](https://github.com/ChiWeiHsiao/ref-ldm)\]|Diffusion/Ref|
|2025|PR|Visual Style Prompt Learning Using Diffusion Models for Blind Face Restoration|\[[paper](https://doi.org/10.1016/j.patcog.2024.111312)\]\[[code](https://github.com/LonglongaaaGo/VSPBFR)\]|Diffusion|
|2025|TCSVT|FaceGCN: Structured Priors Inspired Graph Convolutional Networks for Face Restoration With Unknown Degradations|\[[paper](https://ieeexplore.ieee.org/document/10830527)\]\[[code](https://github.com/yanwd628/FaceGCN)\]|GCN/Geo-Prior|
|2025|TIFS|Multi-Scale Semantic-Guidance Networks: Robust Blind Face Restoration Against Adversarial Attacks|\[[paper](https://ieeexplore.ieee.org/document/11006147)\]\[~~code~~]|CNN/Geo-Prior|
|2025|TNNLS|Multiprior Learning Via Neural Architecture Search for Blind Face Restoration|\[[paper](https://ieeexplore.ieee.org/document/10355907)\]\[[code](https://github.com/YYJ1anG/MFPSNet)\]|CNN/Geo-Prior|
|2025|AAAI|FaceMe: Robust Blind Face Restoration with Personal Identification|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32593)\]\[[code](https://github.com/modyu-liu/FaceMe)\]|Diffusion/Ref|
|2025|ICLR|InterLCM: Low-Quality Images as Intermediate States of Latent Consistency Models for Effective Blind Face Restoration|\[[paper](https://openreview.net/forum?id=rUxr9Ll5FQ)\]\[[code](https://github.com/sen-mao/InterLCM)\]|Diffusion|
|2025|ICLR|MGFR: Overcoming False Illusions in Real-World Face Restoration with Multi-Modal Guided Diffusion Model|\[[paper](https://openreview.net/forum?id=m9RNBZewW2)\]\[[code](https://github.com/KD-TAO/MGFR)\]|Diffusion/Ref|
|2025|CVPR|OSDFace: One-Step Diffusion Model for Face Restoration|\[[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_OSDFace_One-Step_Diffusion_Model_for_Face_Restoration_CVPR_2025_paper.html)\]\[[code](https://github.com/jkwang28/OSDFace)\]|Diffusion/Codebook|
|2025|ICML|Feature out! Let Raw Image as Your Condition for Blind Face Restoration|\[[paper](https://openreview.net/pdf?id=vwIjp2751u)\]\[~~code~~]|Diffusion|
|2025|IJCAI|Unleashing the Potential of Transformer Flow for Photorealistic Face Restoration|\[[paper](https://www.ijcai.org/proceedings/2025/234)\]\[~~code~~]|Diffusion|
|2025|MM|AuthFace: Towards Authentic Blind Face Restoration withFace-oriented Generative Diffusion Prior|\[[paper](https://dl.acm.org/doi/epdf/10.1145/3746027.3755165)\]\[[code](https://github.com/EthanLiang99/AuthFace)\]|Diffusion|


## Face Super-Resolution 
|Year<div style="width:20px">|Venue<div style="width:60px">|Title<div style="width:600px">|Resources<div style="width:100px">|Introduction<div style="width:400px">|
|:---:|:----:|:----:|:----:|:----:|
|2021|TIP|Learning Spatial Attention for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/9293182)\]\[[code](https://github.com/chaofengc/Face-SPARNet)]|CNN/Attention|
|2021|TIP|Features Guided Face Super-Resolution via Hybrid Model of Deep Learning and Random Forests|\[[paper](https://ieeexplore.ieee.org/document/9395386)\]\[~~code~~]|CNN/Geo-Prior|
|2021|TMM|Learning Face Image Super-Resolution Through Facial Semantic Attribute Transformation and Self-Attentive Structure Enhancement|\[[paper](https://ieeexplore.ieee.org/document/9055090)\]\[~~code~~]|CNN/Geo-Prior|
|2021|TMM|Supervised Pixel-Wise GAN for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/9132630)\]\[[code](https://github.com/Merle314/Supervised-Pixel-Wise-GAN)]|GAN|
|2021|MM|Face Hallucination via Split-Attention in Split-Attention Network|\[[paper](https://dl.acm.org/doi/abs/10.1145/3474085.3475682)\]\[[code](https://github.com/mdswyz/SISN-Face-Hallucination)]|CNN/Attention|
|2022|NN|Multi-level landmark-guided deep network for face super-resolution|\[[paper](https://www.sciencedirect.com/science/article/pii/S0893608022001587?via%3Dihub)\]\[[code](https://github.com/zhuangcheng31/MLG_Face)]|CNN/Geo-Prior|
|2022|TCSVT|Propagating Facial Prior Knowledge for Multitask Learning in Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/9792407)\]\[[code](https://github.com/wcy-cs/KDFSRNet)]|CNN/Geo-Prior|
|2022|TIP|Attention-Driven Graph Neural Network for Deep Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/9916123)\]\[~~code~~]|GCN/Attention|
|2022|IJCAI|IDPT: Interconnected Dual Pyramid Transformer for Face Super-Resolution|\[[paper](https://www.ijcai.org/proceedings/2022/182)\]\[~~code~~]|ViT|
|2023|NN|Self-attention learning network for face super-resolution|\[[paper](https://www.sciencedirect.com/science/article/pii/S0893608023000060?via%3Dihub)\]\[~~code~~]|CNN/Attention|
|2023|PR|A Composite Network Model for Face Super-Resolution with Multi-Order Head Attention Facial Priors|\[[paper](https://www.sciencedirect.com/science/article/pii/S0031320323002030?via%3Dihub)\]\[~~code~~]|CNN/ViT/Geo-Prior|
|2023|TIP|CTCNet: A CNN-Transformer Cooperation Network for Face Image Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10087319)\]\[[code](https://github.com/IVIPLab/CTCNet)]|CNN/ViT|
|2023|TIP|Semi-Cycled Generative Adversarial Networks for Real-World Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10036448)\]\[[code](https://github.com/HaoHou-98/SCGAN)]|GAN|
|2023|TMM|SCTANet: A Spatial Attention-Guided CNN-Transformer Aggregation Network for Deep Face Image Super-Resolution|\[[paper](https://www.sciencedirect.com/science/article/pii/S0893608023000060?via%3Dihub)\]\[~~code~~]|CNN/ViT|
|2023|TMM|JDSR-GAN: Constructing an Efficient Joint Learning Network for Masked Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10032643)\]\[~~code~~]|GAN/Geo-Prior|
|2023|CVPR|Spatial-Frequency Mutual Learning for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10205328)\]\[[code](https://github.com/wcy-cs/SFMNet)]|CNN/Attention|
|2023|IJCAI|Learning Attention from Attention: Efficient Self-Refinement Transformer for Face Super-Resolution|\[[paper](https://www.ijcai.org/proceedings/2023/115)\]\[[code](https://github.com/Guanxin-Li/LAA-Transformer)]|ViT|
|2024|TCSVT|PLGNet: Prior-Guided Local and Global Interactive Hybrid Network for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10535972)\]\[[code](https://github.com/lil808/PLGNet)]|CNN/ViT/Geo-Prior|
|2024|TMM|An Efficient Latent Style Guided Transformer-CNN Framework for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10145603)\]\[[code](https://github.com/FVL2020/ELSFace)]|CNN/ViT|
|2024|TMM|Exploiting Multi-Scale Parallel Self-Attention and Local Variation via Dual-Branch Transformer-CNN Structure for Face Super-Resolution|\[[paper](https://ieeexplore.ieee.org/document/10207832)\]\[[code](https://github.com/jingang-cv/DBTC)]|CNN/ViT|
|2024|TNNLS|Rethinking Prior-Guided Face Super-Resolution: A New Paradigm With Facial Component Prior|\[[paper](https://ieeexplore.ieee.org/document/9875217)\]\[~~code~~]|CNN/ViT/Geo-Prior|
|2024|AAAI|Low-Light Face Super-resolution via Illumination, Structure, and Texture Associated Representation|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/28339)\]\[[code](https://github.com/wcy-cs/IC-FSRDENet)]|Diffusion|
|2024|MM|Efficient Face Super-Resolution via Wavelet-based Feature Enhancement Network|\[[paper](https://dl.acm.org/doi/10.1145/3664647.3681088)\]\[[code](https://github.com/PRIS-CV/WFEN)]|ViT|
|2025|PR|SANet: Face super-resolution based on self-similarity prior and attention integration|\[[paper](https://www.sciencedirect.com/science/article/pii/S0031320324006058?via%3Dihub)\]\[~~code~~]|CNN|
|2025|PR|CMANet: A CNN-Mamba aggregation network for face super-resolution|\[[paper](https://www.sciencedirect.com/science/article/pii/S0031320325005199?via%3Dihub)\]\[~~code~~]|CNN/Mamba|
|2025|TIFS|FDNet: A Frequency-Aware Decomposition Network for Robust Face Super-Resolution Against Adversarial Attacks|\[[paper](https://ieeexplore.ieee.org/document/11018135)\]\[~~code~~]|CNN|
|2025|AAAI|Diffusion Prior Interpolation for Flexibility Real-World Face Super-Resolution|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32997)\]\[[code](https://github.com/JerryYann/DPI)]|Diffusion|




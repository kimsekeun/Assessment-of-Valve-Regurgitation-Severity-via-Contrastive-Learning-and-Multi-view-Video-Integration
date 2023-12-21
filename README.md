# Assessment of Valve Regurgitation Severity via Contrastive Learning and Multi-view Video Integration


[![Framework: PyTorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org/) 

This repo contains the code for our paper **Assessment of Valve Regurgitation Severity via Contrastive Learning and Multi-view Video Integration**  </a>.

![Intuition](intuition.png?raw=true "Intuition")

Acquisition of various color Doppler imaging in standard echocardiographic views from varying probe positions. The white region of interest (ROI) within the image represents a specific area that has been selected for analysis. The color represents both the speed and direction of blood flow within the ROI Blood flow towards the probe is visualized in red, while flow away from the probe is depicted in blue. 

![Overview of framework](Methods.png?raw=true "Method")
Overall architecture of the proposed method. A supervised contrastive learning to learn representations using a contrastive loss but uses label information to sample positives and negative pairs. A feature extractor which employs a pre-trained encoder shared across all input video. The optimization step involves the use of inter-intra contrastive loss in conjunction with classification loss. 

## Execution Instructions
- Envrionment Setting

```
pip install -r requirements.py
```
  
## Citation

If you found our paper is contributed to your research, please consider starring ⭐ us on GitHub and citing 📚 us in your research!

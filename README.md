<!-- PROJECT LOGO -->
<br />
<div align="center">




  <h3 align="center">HyCoSNet: A Hybrid ConvNeXt-Swin Transformer Network for Glioma Overall Survival Prediction </h3>
  <img width="1057" height="476" alt="The structure of HyCoSNet" src="https://github.com/user-attachments/assets/ee44f051-75b1-492f-bf96-0e7a61981c19" />
  <p align="justify">
    Glioma prognosis is highly heterogeneous, underscoring the need for accu-rate, preoperative prediction of overall survival from Magnetic Resonance Imaging (MRI). Reliable overall survival (OS) stratification is essential for tailoring treatment strategies and improving patient outcomes. However, most existing studies rely on symmetric network designs or naïve fusion methods, which fail to capture the complementary and modality-specific in-formation embedded in different MRI sequences. To address this limitation, we propose HyCoSNet, an asymmetric hybrid network tailored for modali-ty-aware feature learning. Unlike symmetric backbones, HyCoSNet em-ploys a Swin Transformer to capture long-range contextual information from Fluid-Attenuated Inversion Recovery (FLAIR) sequences, and a Con-vNeXt to model fine-grained local structures in contrast-enhanced T1-weighted (T1c) images. To further stabilize 3D training, we design a chan-nel-first LayerNorm variant that avoids reliance on framework-specific im-plementations. The modality-specific features are projected into a common space and progressively aligned through a cross-attention fusion block, en-suring effective interaction rather than naïve concatenation. This strategy produces a compact, discriminative embedding that balances representa-tional richness and computational efficiency. We evaluate HyCoSNet on the University of California San Francisco Preoperative Diffuse Glioma MRI (UCSF-PDGM) dataset for binary OS classification. The model achieves an area under the receiver operating characteristic curve (AUC) of 0.7139, outperforming baseline methods while requiring fewer computa-tional resources. By establishing a new paradigm for modality-aware feature learning, HyCoSNet provides a reliable and clinically valuable framework for preoperative glioma survival prediction. 
    <br />
    <br />
    The source code of HyCoSNet will be made public after the paper is accepted.
    <br />
  </p>
   <h3 align="lift">Dataset </h3>
  <p align="lift">
    UCSF-PDGM | The University of California San Francisco Preoperative Diffuse Glioma MRI (https://www.cancerimagingarchive.net/collection/ucsf-pdgm/)
     </p>
</div>




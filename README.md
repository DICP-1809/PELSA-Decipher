# PELSA-Decipher: a software tool for the processing and interpretation of ligand-protein interaction dataset acquired by PELSA

## PELSA-Decipher

![PELSA](https://github.com/user-attachments/assets/5364f36d-4d7a-4bb2-94e1-5cb655051986)

## Overview

**PELSA-Decipher** is a software tool specifically designed to streamline the processing and analysis of PELSA data.  It is an efficient and user-friendly software that offers the following key functionalities:

- **Differential Analysis (DA):** Quantitative comparison of differences between samples to facilitate the identification of target proteins.
- **Protein Local Stability Analysis (ProLSA):** Exploration of stability characteristics across different regions of a protein allowing the determination of binding regions.
- **Concentration-Dependent Analysis (CDA):** Analysis of the concentration-dependent curves at peptide level to enable the calculation of both local and global affinities of ligands for their target proteins.

The software supports importing domain information from the UniProt database, enabling precise analysis of ligand-protein binding regions. Users can also define custom regions for targeted analysis. In addition, it provides flexible image customization options, supports multiple output formats, and allows batch export of result reports and images.

Beyond PELSA-specific data, **PELSA-Decipher** is also compatible with certain other data types, further enhancing its versatility and functionality.

Developed in Python, the software’s graphical user interface (GUI) is built using PySide6. The tool is available as a packed `.exe` application, which can be directly downloaded and executed. Detailed instructions on installation, operation, troubleshooting, and additional resources are provided in the accompanying documentation.

## Cite

1)A peptide-centric local stability assay enables proteome-scale identification of the protein targets and binding regions of diverse ligands, Kejia Li, Shijie Chen, Keyun Wang, Yan Wang, Lianji Xue, Yuying Ye,Zheng Fang , Jiawen Lyu, Haiyang Zhu, Yanan Li, Ting Yu, Feng Yang, Xiaolei Zhang, Siqi Guo, Chengfei Ruan, Jiahua Zhou, Qi Wang, Mingming Dong , Cheng Luo, Mingliang Ye, Nature Methods, 2025;22:278-282.

2)PELSA-Decipher: A Software Tool for the Processing and Interpretation of Ligand–Protein Interaction Data Sets Acquired by PELSA, Haiyang Zhu, Keyun Wang, Kejia Li, Zheng Fang, Jiahua Zhou, Lianji Xue, Mingliang Ye, Journal of Proteome Research, 10.1021/acs.jproteome.5c00365.


## Download

It is recommended to use PELSA-Decipher of the latest version, which could be downloaded [here](https://github.com/DICP-1809/PELSA-Decipher/releases), where previous version can also be acquired. The user manual is also included.

## Computer System Requirements

+ Operating System: Windows 10/11, x64

## License Application

PELSA-Decipher is a free software, and the license is requested solely for the purpose of understanding how the software is used and to provide better service. We assure you that all information collected will be used for statistical purposes only and will not be disclosed to any third party. Users are mainly distinguished as academic or industrial based on their institutional email address, so please apply for the license using your institution-affiliated email.

When PELSA-Decipher is launched for the first time, a temporary license valid for 3 days is automatically generated. This license grants full access to all features of the software. During the temporary license period, users may apply for and update to a long-term license through the Info page. Once the temporary license expires, restarting the application will directly open the license application window.

PELSA is a patented technology. Industrial users are required to obtain a license to use PELSA in advance by contacting PELSA_Decipher@163.com. Upon approval, we will send you the license to use PELSA-Decipher.

![演示文稿_1](https://github.com/user-attachments/assets/b16a8f2b-c404-4194-bbbd-038e99509588)


## Module Introduction：

### Differential Analysis (DA)


 The DA module in PELSA-Decipher uses a statistical model to identify differential proteins between experimental and control groups based on predefined thresholds. By integrating peptide-level quantitative data, the module enables differential analysis at both the peptide and protein levels. It also provides visualization of the differential analysis results, such as boxplots and volcano plots.

### Protein Local Stability Analysis (ProLSA)

The protein local stability analysis module is designed to assess and visualize information associated with changes in protein local stability after the ligand binding. 

### Concentration-Dependent Analysis (CDA)

The CDA module in PELSA-Decipher models the concentration dependence of peptides and proteins, enabling the calculation of both local and global affinities of ligands for their target proteins. 

## Other Software

For other software developed by the Mingliang Ye's Lab, please see https://github.com/DICP-1809.

## Contact Us

Group leader: Mingliang Ye

E-mail: mingliang@dicp.ac.cn

Developer: Haiyang Zhu

E-mail: zhyemqww@dicp.ac.cn

# MV-TransReid:  3D Multi-view Transformer Network for Occluded Person Re-Identification

Thanks for your attention. In this repo, we provide the code and dataset for the paper "MV-TransReID: 3D Multi-view Transformer Network for Occluded Person Re-Identification".



# Open-source  schedule

**07 Oct 2022.** Open source the query of multi-view-market1501, multi-view-DukeMTMC and  multi-view-Occluded-duke. You can directly download my generated 3D multi-view dataset at  Google drive.

[Occluded-Duke-query.zip](https://drive.google.com/file/d/1cF_ozpjsbaFEa9tku1Kf_cTgkRNAozdy/view?usp=sharing)

[Market1501-query.zip](https://drive.google.com/file/d/1K2oqkP84ql5abFkp8V8vCvnR1b5N-VzM/view?usp=sharing)

[DukeMTMC-query.zip](https://drive.google.com/file/d/1iZgPoJ5dQKAcxjfKG2bvCSftoAbEoK3H/view?usp=sharing)

These Multi-view datasets not only give Multi-view formats but also the point cloud format, allowing future study to examine 3D person ReID using view-based as well as point-based methodologies.

**15 Nov 2022.** Open source the gallery of multi-view-market1501. 

**15 Dec 2022.** Open source the pre-processing code of  multi-view-Occluded-duke dataset. 

**15 Jan 2023.** Open source the evaluation code and model weights on multi-view-Occluded-duke dataset. 

The rest of  source code and dataset will be open source after this paper is accepted.



# Dataset introduction

A reconstruct algorithm SMPL and a rendering engine blender are adopted to generate multi-view dataset from input images in this work. Exactly, we presents three large scale 3D multi-view person ReID datasets, Multi-view-Market1501, Multi-view-duke and  Multi-view-Occluded-duke, which are derived from Market1501, Dukemtmc and Occluded-duke, respectively. Our datasets provide new ways of thinking to resolve occluded person ReID.

The scale of Multi-view-Market1501, Multi-view-duke and  Multi-view-Occluded-duke  as shown:

| Dataset          |              | #ID   | #3D model | #Multi-view image |
| ---------------- | ------------ | ----- | --------- | ----------------- |
| MV-Market-1501   | Training     | 751   | 129,36    | 155,232           |
| Gallery          |              | 752   | 197,32    | 236,784           |
| Query            |              | 750   | 3368      | 40,416            |
| MV-duke          | Training Set | 702   | 15,618    | 187,146           |
| Gallery          |              | 1,110 | 17,661    | 211,932           |
| Query            |              | 519   | 2210      | 26,520            |
| MV-Occluded-duke | Training     | 702   | 15,618    | 187,146           |
| Gallery          |              | 1,110 | 17,661    | 211,932           |
| Query            |              | 519   | 2210      | 26,520            |

Note that because the Occluded-duke derived from the Dukemtmc, so the scale of Multi-view-duke is equal to Multi-view-Occluded-duke. 

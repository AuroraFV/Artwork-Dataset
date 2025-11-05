## Dataset Details
- **Wikiart**
  - Source: Paper - *Large-scale classification of fine-art paintings: Learning the right metric on the right feature*.
  - The **WikiArt** dataset, containing over 80,000 artworks across various styles and artists. 
  - We refined it for experiments by selecting 1–2 representative works from each of 366 21st-century artists. To ensure relevance, we filtered out non-illustrative artworks, such as photography, and excessively explicit pieces, yielding a final test set of **234** images.
- **Conllustration**
  - Source: Paper - *FedStyle: Style-Based Federated Learning Crowdsourcing Framework for Art Commissions*.
  - Upon obtaining permission from the **Conllustration** dataset owners,  we have showed 237 images used in our experiments. The Conllutration dataset was collected by experienced artists with over 10 years of experience, includes 3,238 illustrations from 18 contemporary illustrators. 
  - After excluding pure line drawings, we sampled an average of 13 images per artist, resulting in a final test set of **237** images.
- **Finedge**
  - We manually collected 200 artworks published by contemporary illustrators online, forming a new dataset named it **Finedge**.
  - For objective experiments, we selected **128** test cases with clear edges and suitable for the Linear Watermark pattern.

## Dataset Usage in Experiments
- The experiments without explicit specification are conducted on Conllutration (Table 1 & 4), as contemporary illustrations can better reflect the real-world use cases of our system compared to historical paintings in Wikiart, and the former is collected by experienced artists.
- Two case images presented in Figure 3 are sourced from the Finedge dataset.

## Showcase of Representative Watermarked Images
![image](https://github.com/AuroraFV/Artwork-Dataset/blob/main/watermarked%20cases/1.png)
![image](https://github.com/AuroraFV/Artwork-Dataset/blob/main/watermarked%20cases/Frame%206-1.png)
![image](https://github.com/AuroraFV/Artwork-Dataset/blob/main/watermarked%20cases/3.png)

## Citation
If you use this dataset, please cite our paper:

```bibtex
@inproceedings{10.1145/3746027.3754738,
  author    = {Ran, Changjuan and Liu, Fang and Fang, Runqi and Meng, Xiangyu and Cui, Shenglan and Ye, Yunfan},
  title     = {Where Watermark Meets Beauty: Expert-Guided Aesthetic Visible Watermarking for Digital Artworks},
  year      = {2025},
  isbn      = {9798400720352},
  publisher = {Association for Computing Machinery},
  address   = {New York, NY, USA},
  url       = {https://doi.org/10.1145/3746027.3754738},
  doi       = {10.1145/3746027.3754738},
  booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
  pages     = {6605--6614},
  numpages  = {10},
  location  = {Dublin, Ireland},
  series    = {MM '25}
}

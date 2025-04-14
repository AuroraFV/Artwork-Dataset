## Dataset Details
- **Wikiart**
  - The **WikiArt** dataset, containing over 80,000 artworks across various styles and artists. We refined it for experiments by selecting 1–2 representative works from each of 366 21st-century artists. To ensure relevance, we filtered out non-illustrative artworks, such as photography, and excessively explicit pieces, yielding a final test set of **234** images.
- **Conllustration**
  - Upon obtaining permission from the **Conllustration** dataset owners,  we have showed 237 images used in our experiments. The Conllutration dataset was collected by experienced artists with over 10 years of experience, includes 3,238 illustrations from 18 contemporary illustrators. After excluding pure line drawings, we sampled an average of 13 images per artist, resulting in a final test set of **237** images.
- **Finedge**
  - We manually collected 200 artworks published by contemporary illustrators online, forming a new dataset named it **Finedge**.
  - For objective experiments, we selected **128** test cases with clear edges suitable for the Linear Watermark pattern.

## Dataset Usage in Experiments
- The experiments without explicit specification are conducted on Conllutration (Table 1 & 4), as contemporary illustrations can better reflect the real-world use cases of our system compared to historical paintings in Wikiart, and the former is collected by experienced artists.
- Two case images presented in Figure 3 are sourced from the Conllustration and Finedge datasets, respectively.
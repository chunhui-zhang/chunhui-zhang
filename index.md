## Biography

I received his B.S. degree from the School of Mathematics and Computational Science at Hunan University of Science and Technology. I am currently a Master student at the Institute of Information Engineering at Chinese Academy of Sciences and the School of Cyber Security at the University of Chinese Academy of Sciences. My major research interests include machine learning and visual tracking.

**News** 

One paper accepted in ACM MM 2020.

We the first prize in Anti-UAV 2020 challenge, CVPRW 2020.

## Research

### MM 2020: [Accurate UAV Tracking with Distance-Injected Overlap Maximization](https://2020.acmmm.org/)

UAV tracking is usually challenged by the dual-dynamic disturbances that arise from not only diverse moving target but also motion camera, leading to a more serious model drift issue than traditional visual tracking. In this work, we propose to alleviate this issue with distance-injected overlap maximization. Our idea is improving the accuracy of target localization by deriving a conceptually simple target localization loss and a global feature recalibration scheme in a mutual reinforced way. In particular, the target localization loss is designed by simply incorporating the normalized distance of target offset and generic semantic IoU loss, resulting in the distance-injected semantic IoU loss, and its minimal solution can alleviate the drift problem caused by camera motion. Moreover, the deep feature extractor is reconstructed and alternated with a feature recalibration network, which can leverage the global information to recalibrate significant features and suppress negligible features. Following by multi-scale feature concat, the proposed tracker can improve the discriminative capability of feature representation for UAV targets on the fly. Extensive experimental results on four benchmarks, \ie~UAV123, UAVDT, DTB70, and VisDrone, demonstrate the superiority of the proposed tracker against existing state-of-the-arts on UAV tracking.
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/chunhui-zhang/Chunhui-Zhang/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

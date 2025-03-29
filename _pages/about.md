---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a final year PhD candidate at the Department of Computer Science, Rutgers University. My advisor is the distinguished professor Dimitris N. Metaxas. I received my B.E. degree from North China Electric Power University and M.E. degree from Tsinghua University, both in Beijing, China. I also spent three years working in China, including the one-year wonderful experience in the Radiology Department of Peking University Cancer Hospital and Institute. I have a solid technical background in [Cardiac MRI](https://cardiacmri.com/tech-guide/imaging-sequences).  

My research interests mainly focus on computer vision, medical image analysis and medical imaging. Current research projects are: 
- Cardiac MR image analysis: motion estimation, image segmentation and strain analysis on cardiac cine MRI and [myocardial tagging MRI](https://drive.google.com/file/d/19_KQq7y0uHBfTBLO72yykKKsjXfTkyXF/view).
- MRI pulse sequences and image reconstruction.
- 3D shape modeling and dynamic analysis.

# PhD Students Recruitment 
I am looking for multiple self-motivated PhD students to work on machine learning, computer vision and AI for healthcare applications. Students with a background in Computer Science, Biomedical Engineering (especially for MRI), Electrical Engineering, Automation, or related fields are welcome to drop me an email (meng.ye@rutgers.edu) with your CV and publications (if any). Please note I may not be able to respond to every message due to limited time.

# 🔥 News
- *2025.03*: &nbsp;🎉🎉 I will be an Assistant Professor of Computer Science Engineering at The University of Texas at Arlington. 

# 📝 Publications 
[18] VerSe: Integrating Multiple Queries as Prompts for Versatile Cardiac MRI Segmentation. 
Bangwei Guo, Meng Ye, Yunhe Gao, Bingyu Xin, Leon Axel, Dimitris N. Metaxas. In Information Processing in Medical Imaging (IPMI), 2025. (Oral) [[Code](https://github.com/bangwayne/verse)]

[17] Learning Volumetric Neural Deformable Models to Recover 3D Regional Heart Wall Motion from Multi-Planar Tagged MRI. 
Meng Ye, Bingyu Xin, Bangwei Guo, Leon Axel, Dimitris N. Metaxas. arXiv preprint, 2025. [[Paper](https://arxiv.org/abs/2411.15233)][[Project page](https://github.com/DeepTag/VolumetricNeuralDeformableModels)]

[16] Continuous Spatio-Temporal Memory Networks for 4D Cardiac Cine MRI Segmentation. 
Meng Ye, Bingyu Xin, Leon Axel, Dimitris N. Metaxas. In IEEE Winter Conference on Applications of Computer Vision (WACV), 2025. [[Paper](https://arxiv.org/abs/2410.23191)] [[Project page](https://github.com/DeepTag/CSTM)]

[15] Rethinking Deep Unrolled Model for Accelerated MRI Reconstruction.
Bingyu Xin, Meng Ye, Leon Axel, Dimitris N. Metaxas. In European Conference on Computer Vision (ECCV), 2024. (Oral) (Double winner solution of the CMRxRecon2024 challenge) [[News](https://www.cs.rutgers.edu/news-events/news/news-item/cs-ph-d-students-bingyu-xin-and-meng-ye-win-first-place-at-miccai-2024)] [[Code](https://github.com/hellopipu/PromptMR-plus)]

[14] Unsupervised Exemplar-Based Image-to-Image Translation and Cascaded Vision Transformers for Tagged and Untagged Cardiac Cine MRI Registration.
Meng Ye, Mikael Kanski, Dong Yang, Leon Axel, Dimitris N. Metaxas. In IEEE Winter Conference on Applications of Computer Vision (WACV), 2024. [[Paper](https://openaccess.thecvf.com/content/WACV2024/html/Ye_Unsupervised_Exemplar-Based_Image-to-Image_Translation_and_Cascaded_Vision_Transformers_for_Tagged_WACV_2024_paper.html)] [[Project page](https://github.com/DeepTag/ECaT)]

[13] Fill the K-Space and Refine the Image: Prompting for Dynamic and Multi-Contrast MRI Reconstruction.
Bingyu Xin, Meng Ye, Leon Axel, Dimitris N. Metaxas. In International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) Workshop STACOM, 2023. (Double winner solution of the CMRxRecon2023 challenge) [[News](https://www.cs.rutgers.edu/news-events/news/news-item/ph-d-students-bingyu-xin-and-meng-ye-awarded-two-accolades-at-miccai-conference)] [[Code](https://github.com/hellopipu/PromptMR)]

[12] Neural Deformable Models for 3D Bi-Ventricular Heart Shape Reconstruction and Modeling from 2D Sparse Cardiac Magnetic Resonance Imaging.
Meng Ye, Dong Yang, Mikael Kanski, Leon Axel, Dimitris N. Metaxas. In IEEE International Conference on Computer Vision (ICCV), 2023. [[Paper](https://arxiv.org/abs/2307.07693)] [[Project page](https://github.com/DeepTag/NeuralDeformableModels)]

[11] Deformer: Integrating Transformers with Deformable Models for 3D Shape Abstraction from A Single Image.
Di Liu, Xiang Yu, Meng Ye, Qilong Zhangli, Zhuowei Li, Zhixing Zhang, Dimitris N. Metaxas. In IEEE International Conference on Computer Vision (ICCV), 2023.

[10] SequenceMorph: A Unified Unsupervised Learning Framework for Motion Tracking on Cardiac Image Sequences.
Meng Ye, Dong Yang, Qiaoying Huang, Mikael Kanski, Leon Axel, Dimitris N. Metaxas. In IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023. [[Project page](https://github.com/DeepTag/SequenceMorph)]

[9] DeepRecon: Joint 2D Cardiac Segmentation and 3D Volume Reconstruction via A Structure-Specific Generative Method.
Qi Chang, Zhennan Yan, Mu Zhou, Di Liu, Khalid Sawalha, Meng Ye, Qilong Zhangli, Mikael Kanski, Subhi Al Aref, Leon Axel, Dimitris Metaxas. In International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI), 2022.

[8] An unsupervised 3D recurrent neural network for slice misalignment correction in cardiac MR imaging.
Qi Chang, Zhennan Yan, Meng Ye, Mikael Kanski, Subhi Al’Aref, Leon Axel, Dimitris Metaxas. In International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) Workshop STACOM, 2021.

[7] DeepTag: An Unsupervised Deep Learning Method for Motion Tracking on Cardiac Tagging Magnetic Resonance Images.
Meng Ye, Mikael Kanski, Dong Yang, Qi Chang, Zhennan Yan, Qiaoying Huang, Leon Axel, Dimitris Metaxas. In IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021. (Oral) [[Paper](https://arxiv.org/abs/2103.02772)] [[Code](https://github.com/DeepTag/cardiac_tagging_motion_estimation)] 

[6] Deep Learning-assisted MRI Prediction of Tumor Response to Chemotherapy in Patients with Colorectal Liver Metastases.
Haibin Zhu*, Da Xu*, Meng Ye, Li Sun, Xiaoyan Zhang, Xiaoting Li, Pei Nie, Baocai Xing, Yingshi Sun. In International Journal of Cancer (IJC), 2021. [[Paper](https://drive.google.com/file/d/1w3lqOuUtP_wjbqlmM90aZ7NYujL77jDc/view)]

[5] Cardiac MR Image Sequence Segmentation with Temporal Motion Encoding.
Pengxiang Wu, Qiaoying Huang, Jingru Yi, Hui Qu, Meng Ye, Leon Axel, Dimitris N. Metaxas. In European Conference on Computer Vision (ECCV) Workshop BIC, 2020.

[4] PC-U Net: Learning to Jointly Reconstruct and Segment the Cardiac Walls in 3D from CT Data.
Meng Ye, Qiaoying Huang, Dong Yang, Pengxiang Wu, Jingru Yi, Leon Axel, Dimitris Metaxas. In International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) Workshop STACOM, 2020. [[Paper](https://arxiv.org/pdf/2008.08194)]  

[3] Predicting Rectal Cancer Response to Neoadjuvant Chemoradiotherapy Using Deep Learning of Diffusion Kurtosis MRI.
Xiaoyan Zhang*, Lin Wang*, Haitao Zhu, Zhongwu Li, Meng Ye, Xiaoting Li, Yanjie Shi, Huici Zhu, Yingshi Sun. In Radiology, 2020. [[Paper](https://drive.google.com/file/d/1DQJEs42heq20V5Rv0A-Pm-7klG5BB0-D/view)] [[Editorial Commentary](https://drive.google.com/file/d/19SOxD2V1MvB2H59Gr0eB4ehATx2sr8Ut/view)]

[2] Prediction of Pathological Complete Response to Neoadjuvant Chemotherapy in Breast Cancer Using Deep Learning (DL) Method.
Yuhong Qu*, Haitao Zhu*, Kun Cao, Xiaoting Li, Meng Ye, Yingshi Sun. In Thoracic Cancer, 2020. [[Paper](https://drive.google.com/file/d/10f_ynt06HVN2oi-1MJNBDXeUw_QM8BIk/view)]

[1] Feasibility Study of Whole Heart T1 Mapping with SMS in A Single Breath Hold.
Wenbo Sun*, Meng Ye*, Yuan Zheng, Lele Zhao, Nan Liu, Yanqun Teng, Lan Lan, Jian Xu, Haibo Xu. In Joint Annual Meeting ISMRM-ESMRMB, 2018. [[Poster](https://cds.ismrm.org/protected/18MProceedings/PDFfiles/4880.html)]

# 🎖 Honors and Awards
- *2024.10* Double champion of the CMRxRecon2024 challenge [[News](https://www.cs.rutgers.edu/news-events/news/news-item/cs-ph-d-students-bingyu-xin-and-meng-ye-win-first-place-at-miccai-2024)]. 
- *2023.10* Double champion of the CMRxRecon2023 challenge [[News](https://www.cs.rutgers.edu/news-events/news/news-item/ph-d-students-bingyu-xin-and-meng-ye-awarded-two-accolades-at-miccai-conference)]. 

# 📖 Educations
- *2019.09 - 2025.06*, Ph.D. Computer Science, Rutgers University, New Brunswick, NJ, USA.
- *2013.09 - 2016.06*, M.E. Biomedical Engineering, Tsinghua University, Beijing, China.
- *2007.09 - 2011.06*, B.E. Nuclear Science and Engineering, North China Electric Power University, Beijing, China.

# 💬 Invited Talks
- *2025.02*, AI-Driven Correspondence Learning for Dynamic Heart Function Analysis Using MRI. Job talk, UTA.

# 💻 Internships
- *2023.06 - 2023.08*, Computer Vision Research Intern, UII America, Boston, MA.
- *2021.06 - 2021.08*, Machine Learning Research Intern, Siemens Healthineers, Princeton, NJ.

# Working Experience
- *2018.08 - 2019.07*, Research Assistant, Peking University Cancer Hospital and Institute, Beijing, China.
- *2017.12 - 2018.07*, Data Analyst, 12 Sigma Technologies, Shanghai, China.
- *2016.07 - 2017.11*, MRI Pulse Sequence Design and Image Reconstruction Engineer, United Imaging Healthcare, Shanghai, China.

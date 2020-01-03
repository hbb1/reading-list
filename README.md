- # reading-list

## Basic Network

* **AlexNet** MLA Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems. 2012. ⭐️⭐️⭐️⭐️⭐️ `extensive experiment` `thinking`

* G. E. Hinton, N. Srivastava, A. Krizhevsky, I. Sutskever, and

  R. R. Salakhutdinov. Improving neural networks by preventing

  co-adaptation of feature detectors. arXiv preprint

  arXiv:1207.0580, 2012.

* **Dropout**  Nitish Srivastava, Geoffrey Hinton, Alex Krizhevsky, Ilya Sutskever. Ruslan Salakhutdinov Dropout: A Simple Way to Prevent Neural Networks from Overfitting. 2014. ⭐️⭐️⭐️⭐️ `ensemble architecture` `adding noise`

* **GoogLeNet** Christian Szegedy  et al. "Going deeper with convolutions"  [InceptionV1] CVPR 2015.  ⭐️⭐️⭐️⭐️⭐️ `efficient` `multi-scale` `1x1 conv` 

* **VGG** Karen Simonyan & Andrew Zisserman. "Very Deep Convolutional Networks for Large-Scale Image Recongnition".

* **PReLU & msra Initilization**: He, Kaiming, et al. "Delving deep into rectifiers: Surpassing human-level performance on imagenet classification." Proceedings of the IEEE international conference on computer vision. 2015. ⭐️⭐️⭐️⭐️⭐️

* **Batch Normalization & Inception V2** Sergey Ioffe et al.  Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift. ICML2015.⭐️⭐️⭐️⭐️⭐️ `stable` `fast convergency`

  [PDF]: https://arxiv.org/abs/1502.03167

- **InceptinV3** Christian Szegedy  et al. Rethinking the Inception Architecture for Computer Vision. CVPR 2016. 

  [pdf]: https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.pdf

  ⭐️⭐️⭐️⭐️⭐️`design principles` `label smoothing` `reduce`
  
- **Warmup & LR** Priya Goyal, Piotr Dollar, Ross Grishick et al. Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour. 2018.

- **Identity ResNet** He, Kaiming, et al. "Identity mappings in deep residual networks." European Conference on Computer Vision. Springer International Publishing, 2016. ⭐️⭐️⭐️⭐️ `pre-activation`

- **ResNet**: He, Kaiming, et al. "Deep residual learning for image recognition." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016. ⭐️⭐️⭐️⭐️⭐️ ##CVPR 2016 Best Paper

- **ResNeXt** Xie, Saining, et al. "Aggregated residual transformations for deep neural networks." arXiv preprint arXiv:1611.05431 (2016). ⭐️⭐️⭐️⭐️ `cardinality`

- **InceptionV4 & Inception-ResNet**: Szegedy, Christian, et al. "Inception-v4, inception-resnet and the impact of residual connections on learning." arXiv preprint arXiv:1602.07261 (2016). ⭐️⭐️⭐️⭐️  `Inception& residual`

- **PolyNet**: Zhang, Xingcheng, et al. "Polynet: A pursuit of structural diversity in very deep networks." arXiv preprint arXiv:1611.05725 (2016). [Slides](http://image-net.org/challenges/talks/2016/polynet_talk.pdf) ⭐️⭐️⭐️⭐️ `divsersity`

- **Xception**: Chollet, François. "Xception: Deep Learning with Depthwise Separable Convolutions." arXiv preprint arXiv:1610.02357 (2016). ⭐️⭐️⭐️ `channel correlation` `decoupled`

- **SENet**: Hu, Jie, Li Shen, and Gang Sun. "Squeeze-and-excitation networks."In CVPR (2018). ⭐️⭐️⭐️⭐️⭐️ `decouple` `channel excited `

- **DenseNet**: Huang, Gao, et al. "Densely connected convolutional networks." arXiv preprint arXiv:1608.06993 (2016). ⭐️⭐️⭐️⭐️⭐️ `features reuse`  ##CVPR 2017 Best Paper

- **Rethinking ImageNet Pre-training**： He, Kaiming, Ross Girshick, and Piotr Dollár. "Rethinking ImageNet Pre-training." arXiv preprint arXiv:1811.08883 (2018). ⭐️⭐️⭐️

- **Non-local Neural Network**: Wang, Xiaolong, Ross Girshick, Abhinav Gupta, and Kaiming He. "Non-local Neural Networks." arXiv preprint arXiv:1711.07971 (2017). ⭐️⭐️⭐️⭐️

  


##3D vision

###Point cloud

- **PointNet** Charles R Qi, Hao Su et al. "PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation". arXiv: 1612.00593v2  (CVPR 2017). ⭐️⭐️⭐️
- **PointNet++**: C. R. Qi et al. "Deep Hierarchical Feature Learning on Point Sets in a Metric Space". (NeurIPS 2017) [[pdf\]](http://xxx.itp.ac.cn/pdf/1706.02413.pdf) [[Github\]](https://github.com/charlesq34/pointnet2) ⭐️ ⭐️ ⭐️ ⭐️ 
- **PointCNN**:  Y. Li et al. "Convolution On X-Transformed Points" (NeurIPS 2018). [[pdf\]](https://arxiv.org/pdf/1801.07791.pdf) [[Github\]](https://github.com/yangyanli/PointCNN) ⭐️ ⭐️ ⭐️
- **RS-CNN**： Y. Liu et al. "Relation-Shape Convolutional Neural Network for Point Cloud Analysis" ⭐️⭐️⭐️⭐️

  



## Object detection

- **SPP**: He, Kaiming, et al. "Spatial pyramid pooling in deep convolutional networks for visual recognition." European Conference on Computer Vision. Springer International Publishing, 2014. ⭐️⭐️⭐️⭐️⭐️
- **Fast RCNN**: Girshick, Ross. "Fast r-cnn." Proceedings of the IEEE International Conference on Computer Vision. 2015. ⭐️⭐️⭐️⭐️⭐️
- **Faster RCNN**: Ren, Shaoqing, et al. "Faster r-cnn: Towards real-time object detection with region proposal networks." Advances in neural information processing systems. 2015. ⭐️⭐️⭐️⭐️⭐️
- **YOLO**: You Only Look Once:Unified, Real-Time Object Detection. ⭐️⭐️⭐️⭐️⭐️



##vision & language

### Visual Grounding / Referring Expressions (Images):

1. Karpathy, Andrej, Armand Joulin, and Li F. Fei-Fei. **Deep fragment embeddings for bidirectional image sentence mapping.** Advances in neural information processing systems. 2014. [[Paper\]](http://papers.nips.cc/paper/5281-deep-fragment-embeddings-for-bidirectional-image-sentence-mapping.pdf)
2. Karpathy, Andrej, and Li Fei-Fei. **Deep visual-semantic alignments for generating image descriptions.** Proceedings of the IEEE conference on computer vision and pattern recognition. 2015. *Method name: Neural Talk*. [[Paper\]](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Karpathy_Deep_Visual-Semantic_Alignments_2015_CVPR_paper.pdf) [[Code\]](https://github.com/karpathy/neuraltalk) [[Torch Code\]](https://github.com/karpathy/neuraltalk2) [[Website\]](https://cs.stanford.edu/people/karpathy/deepimagesent/)
3. Hu, Ronghang, et al. **Natural language object retrieval.** Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016. *Method name: Spatial Context Recurrent ConvNet (SCRC)* [[Paper\]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Hu_Natural_Language_Object_CVPR_2016_paper.pdf) [[Code\]](https://github.com/ronghanghu/natural-language-object-retrieval) [[Website\]](http://ronghanghu.com/text_obj_retrieval/)
4. Mao, Junhua, et al. **Generation and comprehension of unambiguous object descriptions.** Proceedings of the IEEE conference on computer vision and pattern recognition. 2016. [[Paper\]](https://arxiv.org/pdf/1511.02283.pdf) [[Code\]](https://github.com/mjhucla/Google_Refexp_toolbox)
5. Wang, Liwei, Yin Li, and Svetlana Lazebnik. **Learning deep structure-preserving image-text embeddings.** Proceedings of the IEEE conference on computer vision and pattern recognition. 2016. [[Paper\]](http://slazebni.cs.illinois.edu/publications/cvpr16_structure.pdf) [[Code\]](https://github.com/lwwang/Two_branch_network)
6. Yu, Licheng, et al. **Modeling context in referring expressions.** European Conference on Computer Vision. Springer, Cham, 2016. [[Paper\]](https://arxiv.org/pdf/1608.00272.pdf)[[Code\]](https://github.com/lichengunc/refer)
7. Nagaraja, Varun K., Vlad I. Morariu, and Larry S. Davis. **Modeling context between objects for referring expression understanding.** European Conference on Computer Vision. Springer, Cham, 2016.[[Paper\]](https://arxiv.org/pdf/1608.00525.pdf) [[Code\]](https://github.com/varun-nagaraja/referring-expressions)
8. Rohrbach, Anna, et al. **Grounding of textual phrases in images by reconstruction.** European Conference on Computer Vision. Springer, Cham, 2016. *Method Name: GroundR* [[Paper\]](https://arxiv.org/pdf/1511.03745.pdf) [[Tensorflow Code\]](https://github.com/kanchen-usc/GroundeR) [[Torch Code\]](https://github.com/ruotianluo/refexp-comprehension)
9. Wang, Mingzhe, et al. **Structured matching for phrase localization.** European Conference on Computer Vision. Springer, Cham, 2016. *Method name: Structured Matching* [[Paper\]](https://pdfs.semanticscholar.org/9216/2ec88ad974cc5082d9688c8bfee672ad59ad.pdf) [[Code\]](https://github.com/princeton-vl/structured-matching)
10. Hu, Ronghang, Marcus Rohrbach, and Trevor Darrell. **Segmentation from natural language expressions.** European Conference on Computer Vision. Springer, Cham, 2016. [[Paper\]](https://arxiv.org/pdf/1603.06180.pdf) [[Code\]](https://github.com/ronghanghu/text_objseg) [[Website\]](http://ronghanghu.com/text_objseg/)
11. Fukui, Akira et al. **Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding.** EMNLP (2016). *Method name: MCB* [[Paper\]](https://arxiv.org/pdf/1606.01847.pdf)[[Code\]](https://github.com/akirafukui/vqa-mcb)
12. Endo, Ko, et al. **An attention-based regression model for grounding textual phrases in images.** Proc. IJCAI. 2017. [[Paper\]](https://www.ijcai.org/proceedings/2017/0558.pdf)
13. Chen, Kan, et al. **MSRC: Multimodal spatial regression with semantic context for phrase grounding.** International Journal of Multimedia Information Retrieval 7.1 (2018): 17-28. [[Paper -Springer Link\]](https://link.springer.com/article/10.1007/s13735-017-0139-6)
14. Wu, Fan et al. **An End-to-End Approach to Natural Language Object Retrieval via Context-Aware Deep Reinforcement Learning.** CoRR abs/1703.07579 (2017): n. pag. [[Paper\]](https://arxiv.org/pdf/1703.07579.pdf) [[Code\]](https://github.com/jxwufan/NLOR_A3C)
15. Yu, Licheng, et al. **A joint speakerlistener-reinforcer model for referring expressions.** Computer Vision and Pattern Recognition (CVPR). Vol. 2. 2017. [[Paper\]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yu_A_Joint_Speaker-Listener-Reinforcer_CVPR_2017_paper.pdf) [[Code\]](https://github.com/lichengunc/speaker_listener_reinforcer)[[Website\]](https://vision.cs.unc.edu/refer/)
16. Hu, Ronghang, et al. **Modeling relationships in referential expressions with compositional modular networks.** Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on. IEEE, 2017. [[Paper\]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Hu_Modeling_Relationships_in_CVPR_2017_paper.pdf) [[Code\]](https://github.com/ronghanghu/cmn)
17. Luo, Ruotian, and Gregory Shakhnarovich. **Comprehension-guided referring expressions.** Computer Vision and Pattern Recognition (CVPR). Vol. 2. 2017. [[Paper\]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Luo_Comprehension-Guided_Referring_Expressions_CVPR_2017_paper.pdf) [[Code\]](https://github.com/ruotianluo/refexp-comprehension)
18. Liu, Jingyu, Liang Wang, and Ming-Hsuan Yang. **Referring expression generation and comprehension via attributes.** Proceedings of CVPR. 2017. [[Paper\]](http://faculty.ucmerced.edu/mhyang/papers/iccv2017_referring_expression.pdf)
19. Xiao, Fanyi, Leonid Sigal, and Yong Jae Lee. **Weakly-supervised visual grounding of phrases with linguistic structures.** arXiv preprint arXiv:1705.01371 (2017). [[Paper\]](https://arxiv.org/pdf/1705.01371.pdf)
20. Plummer, Bryan A., et al. **Phrase localization and visual relationship detection with comprehensive image-language cues.** Proc. ICCV. 2017. [[Paper\]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Plummer_Phrase_Localization_and_ICCV_2017_paper.pdf) [[Code\]](https://github.com/BryanPlummer/pl-clc)
21. Yu, Licheng, et al. **Mattnet: Modular attention network for referring expression comprehension.** Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018. [[Paper\]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_MAttNet_Modular_Attention_CVPR_2018_paper.pdf) [[Code\]](https://github.com/lichengunc/MAttNet) [[Website\]](http://vision2.cs.unc.edu/refer/comprehension)
22. Chen, Yen-Chun, et al. **UNITER: Learning UNiversal Image-TExt Representations.** arXiv preprint arXiv:1909.11740 (2019). [[Paper\]](https://arxiv.org/pdf/1909.11740.pdf)



## Person ReID

* **AlignedReID**  Xuan Zhang, Hao Luo et al. AlignedReID: Surpassing Human-Level Performance in Person Re-Identification. 2015. ⭐️⭐️⭐️⭐️ `stripe-based` `local distance`

* Mahdi M. Kalayeh et al. Human Semantic Parsing for Person Re-identification. CVPR ( 2018 ). ⭐️ `segamentic` `transfer`  

* Huo et al. Interaction-and-Aggregation Network for Person Re-identification. CVPR ( 2019 ).  ⭐️⭐️⭐️⭐️ `adaptively localize parts by modeling spatial feature `  `self-attention` 

* Luo et al. Bag of Tricks and A Strong Baseline for Deep Person Re-identification. CVPR ( 2019 ). ⭐️⭐️⭐️⭐️ `tricks` `bnneck` `inter-intra-class`

* Zheng et al. Joint Discriminative and Generative Learning for Person Re-identification. CVPR( 2019 ).

* Wang et al. Spatial-Temporal Person Re-identification. CVPR( 2019 ).

  

## NIPS

- Max Jaderberg Karen Simonyan Andrew Zisserman Koray Kavukcuoglu. Spatial Transformer Networks. NIPS (2015) ⭐️⭐️⭐️⭐️ `affine transform` `learnable layer`


[pdf]: MaxJaderbergKarenSimonyanAndrewZissermanKorayKavukcuoglu








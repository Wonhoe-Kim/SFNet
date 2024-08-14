# Enhanced fringe-to-phase framework using deep learning

[paper](https://doi.org/10.1016/j.imavis.2024.105204)

[dataset](https://www.dropbox.com/scl/fo/pb3nlmwpxmmcbn9ma7q05/ABO-rcmSAmSl3XNQn9kjsUs?rlkey=9sejey926zz1n3d7d5shc5g34&st=5ys43y60&dl=0)

## **Graphical Abstract**

<br/>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/630ada5c-0c00-47d0-90a6-0770d7d02657">
</p>

<br/><br/>

## **Abstract**

<br/>
  
In Fringe Projection Profilometry (FPP), achieving robust and accurate 3D reconstruction with a limited number of fringe patterns remains a challenge in structured light 3D imaging. Conventional methods require a set of fringe images, but using only one or two patterns complicates phase recovery and unwrapping. In this study, we introduce SFNet, a symmetric fusion network that transforms two fringe images into an absolute phase. To enhance output reliability, Our framework predicts refined phases by incorporating information from fringe images of a different frequency than those used as input. This allows us to achieve high accuracy with just two images. Comparative experiments and ablation studies validate the effectiveness of our proposed method.  

<br/><br/>

## **Method**

<center> Pipeline of the proposed method </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/dbdfdfe2-a23b-4623-8627-96135e9a55d3">
</p>

<center> Architecture of SFNet </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/f5c55956-a39f-45ad-82e3-c52607a285b5">
</p>


<br/><br/>

## **Experiments**

<br/>

<center> Quantative results of differents methods on the SynthFringe test dataset </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/8fea601c-e1e3-4ddb-8e81-cf95aefb8299">
</p>

<br/>

<center> Qualitive results of differents methods on the SynthFringe test dataset </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/7fc6dccd-5f91-40ed-b676-eb89437e06d5">
</p>

  
<br/><br/>

## **Datasets**

<br/>

Our newly constructed dataset, named the **_SynthFringe_** dataset, not only contains a greater number of image pairs compared to other datasets but also encompasses images of diverse frequencies. Moreover, we made efforts to design our dataset with a variety of scenes to make it applicable to more general situations.

<br/>

<center> Representative samples in the dataset </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/ed2e60fa-8fb0-457b-9b63-61c319e149f3">
</p>

<br/>

<center> Examples of the collected data, where each column represents the same fringe pattern and each row represents the same view </center>

<p align="center">
  <img src="https://github.com/Wonhoe-Kim/SFNet/assets/157447883/6645c43d-7747-462d-8839-542dbda3f1f9">
</p>

---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

# Research: Model-data integration in hydrology

<div style="text-align: center;">
  <figure style="max-width: 500px; margin-left: auto; margin-right: auto;">
    <img src="/images/model_data.png" alt="model_data">
    <figcaption>A loop of model-data integration for hydrology, including model calibration and modeling informed data collection.</figcaption>
  </figure>
</div>

## Uncertainty quantification for mountainous watersheds
- Study site: East River, Colorado, United States
<div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      This project studys the impacts of uncertain factors, which range from bedrock to canopy to climate disturbances, within diverse floodplains and hillslopes situated in mountainous watersheds. We leverage advanced modeling, machine learning and decision science to learn the importance of underlying factors, ultimately enhancing our ability to quantify the uncertainty of both water quantity and quality in the near future. 
    </p>
    <p>
      Papers are in preparation. 
    </p>
  </div>   
  <div style="width: 50%; margin-top: 0px;"> <!-- Set width to 60% for the figure -->
      <img src="/images/ER_watershed_KM.png" alt="UQ_watersheds" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
      <figcaption>The East River Watershed. The site photo is provided by Professor Kate Maher at Stanford University</figcaption>
  </div>
</div>


## Surrogate modeling for process-based modeling
- Study site: Savannah River Site, South Carolina, United States
<div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      Understanding the climate impact on groundwater contamination requires us to quantify the uncertainty from both subsurface and climate properties. Doing so requires fast and accurate numerical simulations. We address the computational cost challenge for numerical models using a physics-informed neural network, where we combine the Neural Opertor with the physics-informed loss functions. We demonstrate our surrogate modeling approach at one testbed: Savannah River Site (SRS) F-Area. The faster surrogate model can help us assess the spatiotemporal variations of groundwater contamination under uncertain climate disturbances more efficiently. The ultimate goal is to provide decision solutions for contaminated sites monitoring. 
    </p>
    <p> <!-- Add this for line spacing -->
      Conference proceedings: <a href="https://arxiv.org/abs/2211.10884"> Wang et al., Machine Learning and the Physical Sciences workshop, NeurIPS 2022</a>
    </p>
    <p> 
      Journal paper is under review. 
    </p>
  </div>
  <div style="width: 50%; margin-top: 50px;"> <!-- Set width to 60% for the figure -->
    <a href="https://arxiv.org/abs/2211.10884">
      <img src="/images/Digitaltwin.png" alt="digitaltwin" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
    </a>
  </div>
</div>


## Statistical modeling as the alternative to process-based modeling
- Study site: Jutland, Denmark
 <div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      Agricultural nitrate pollutants infiltrate into the subsurface and contaminate groundwater. The redox environment in the subsurface is important for the natural removal of nitrate by denitrification. However, the redox structure modeling in 3D requires additional assumptions and the process-based modeling is difficult to formulate and to solve. This project combines the geophysical survey: towed transient electromagnetic resistivity (tTEM) and redox boreholes to model 3D redox architecture stochastically using statistical learning, geostatistics and local inversion methods. This statistical learning framework also provides important resistivity structures for domain experts to understand what controls the redox conditions. The highly accurate redox architecture supports a better agricultural regulation decision. 
    </p>
    <p>
      Paper: <a href="https://link.springer.com/article/10.1007/s10040-023-02640-7">Wang et al., Hydrogeology Journal, 2023</a>
    </p>
  </div>
  <div style="width: 50%; margin-top: 0px;"> <!-- Set width to 60% for the figure -->
    <a href="https://link.springer.com/article/10.1007/s10040-023-02640-7">
      <img src="/images/Denmark.png" alt="Denmark" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
    </a>
  </div>
</div>


## Machine learning-based inversion methods
<div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      Bayesian inversion is commonly applied to quantify uncertainty of hydrological variables. However, Bayesian inversion is usually focused on spatial hydrological properties instead of hyperparameters or non-gridded physical global variables. This project presents a hierarchical Bayesian framework to quantify uncertainty of both global and spatial variables. We propose a machine learning-based inversion method to estimate the joint distribution of data and global variables directly without introducing a statistical likelihood. We propose a new local dimension reduction method: local principal component analysis (local PCA) to update large-scale spatial fields with local data more efficiently. With the help of machine learning and efficient dimension reduction, the inversion becomes approachable for high-resolution hydrologic models. 
    </p>
    <p> <!-- Add this for line spacing -->
      Paper: <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021WR031610">Wang et al., Water Resources Research, 2022</a>
    </p>
  </div>
  <div style="width: 50%; margin-top: 50px;"> <!-- Set width to 60% for the figure -->
    <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021WR031610">
      <img src="/images/Workflow_hierarchicalBayes.jpeg" alt="hierarchicalBayes" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
    </a>
  </div>
</div>


## Data-knowledge-driven geological interfaces modeling
- Study site: Greenland and South Australia, Australia

<div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      Modeling complex geological interfaces is a common task in geosciences. Many data sources are available for geological interface modeling, including borehole data and geophysical surveys. Geological knowledge, such as the delineation from geologists, is difficult to quantify but likely adds value to geological interface modeling. To integrate all information, this project presents a data-knowledge-driven trend surface analysis method to construct stochastic geological interfaces. A Metropolis–Hastings sampling framework is designed to sample stochastic trend interfaces and quantify the uncertainty of geological interfaces. We demonstrate our method in three different test cases: modeling stochastic interfaces of Greenland subglacial topography, magmatic intrusion, and buried river valleys in Australia.
    </p>
    <p> <!-- Add this for line spacing -->
      Paper: <a href="https://www.sciencedirect.com/science/article/pii/S0098300423001231">Wang et al., Computers & Geosciences, 2023</a>
    </p>
  </div>
  <div style="width: 50%; margin-top: 0px;"> <!-- Set width to 60% for the figure -->
    <a href="https://www.sciencedirect.com/science/article/pii/S0098300423001231">
      <img src="/images/Inteface_modeling.jpg" alt="Interface modeling" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
    </a>
  </div>
</div>

## Active learning to iteratively label new geophysical data
<div style="display: flex; flex-direction: row; justify-content: space-between;">
  <div style="width: 50%; font-size: 16px; text-align: justify; margin-right: 10px;"> <!-- Set width to 40% for text and add margin for spacing -->
    <p>
      Seismic interpretation plays an essential role in locating subsurface horizons and understanding geological formations. This project investigates how to use semi-supervised segmentation to improve horizon predictions, even if we have only a few labeled horizons. An active learning framework is also proposed to label the most uncertain unlabeled sections, given the uncertainty estimation using deep ensembles. We believe our work helps geophysicists reduce the amount of labeling effort and achieve higher facies classification accuracy with the same amount of labeling work.
    </p>
    <p> <!-- Add this for line spacing -->
      Paper: <a href="https://library.seg.org/doi/abs/10.1190/geo2021-0365.1">Wang et al., Geophysics, 2023</a>
    </p>
  </div>
  <div style="width: 50%; margin-top: 0px;"> <!-- Set width to 60% for the figure -->
    <a href="https://library.seg.org/doi/abs/10.1190/geo2021-0365.1">
      <img src="/images/Active_Learning.jpg" alt="Geophysics Active Learning" width="500" style="display: block; margin: 0 auto;"> <!-- Adjust width for larger figure -->
    </a>
  </div>
</div>



<!-- ## Current Research
[Uncertainty quantification in mountainous watersheds]

[When physical modeling is fast]
Paper: 
[When physical modeling is not availbel]
Paper:



## General research interests

- Model-data integration for hydrology
- Machine learning-based inverse methods
- Surrogate modeling with neural networks
- Bayesian inference
- Decision making for uncertain hydrologic systems

## Research 

- Uncertainty quantification and decision making for hydrologic systems
	1. **Watershed**: Beavers' influence on hydrodynamics in an intermountain floodplain aquifer using hydrologic modeling and calibration (In prep.)
	2. **Groundwater contamination sites, Nuclear waste**: Spatial-temporal groundwater contamination prediction using surrogate modeling ([Conference paper](https://arxiv.org/abs/2211.10884))
	3. **Groundwater contamination sites, Agriculture**: Mapping redox condition in Danish farmlands using statistical learning ([Journal Paper](https://link.springer.com/article/10.1007/s10040-023-02640-7))

- Algorithm development for model-data integration in hydrology
	1. **Stochastic modeling (prior)**: Stochastic explicit and implicit subsurface geomodeling with various datasets and geological knowledge ([Journal Paper](https://www.sciencedirect.com/science/article/pii/S0098300423001231))
	2. **Model calibration and inverse methods 1**: Machine learning-based inverse methods for hierarchical formulation of hydrologic models ([Journal Paper](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021WR031610))
	3. **Model calibration and inverse methods 2**: Measure theory formulation of inverse problems  ([Preprint](https://eartharxiv.org/repository/view/5435/))
	4. **Decision making (posterior)**: Efficacy of information  ([Journal paper](https://link.springer.com/article/10.1007/s11053-022-10030-1))

For more of my research work, please refer to [the Publications page](https://lijingwang.github.io/publication/). 

<!-- \hyperlink{https://arxiv.org/abs/2211.10884}{\textbf{L. Wang}, T. Kurihana, A. Meray, I. Mastilovic, S. Praveen, Z. Xu, M. Memarzadeh, A. Lavin, H. Murakami-Wainwright, Multi-scale Digital Twin: Developing a fast and physics-infused surrogate model for groundwater contamination with uncertain climate models, \textit{Machine Learning and the Physical Sciences Workshop at the 36th conference on Neural Information Processing Systems}, 2022}

\textbf{[1]} \hyperlink{https://openaccess.thecvf.com/content_CVPRW_2019/papers/cv4gc/Rustowicz_Semantic_Segmentation_of_Crop_Type_in_Africa_A_Novel_Dataset_CVPRW_2019_paper.pdf}{R. M. Rustowicz, R. Cheong,  \textbf{L. Wang}, S. Ermon, M. Burke, D. Lobell, Semantic segmentation of crop type in Africa: A novel dataset and analysis of deep learning methods, \textit{Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops}, 2019}


\textbf{[1]} \hyperlink{https://www.cambridge.org/highereducation/books/data-science-for-the-geosciences/64E10197819920B0B5F36472B3B872C4#overview}{\textbf{L. Wang},  Z. Yin, J. Caers, Data Science for the Geosciences, \textit{Cambridge University Press}, 2023}

\textbf{[12]} \textbf{L. Wang}, Z. Perzan, T. Babey, M. Briggs, S. Pierce, B. Rogers, J. Bargar, K. Maher, Revealing Beavers' Influence on Flow Dynamics: Hydrologic Modeling and Calibration in an Intermountain Floodplain Aquifer, 2023 (in prep.)

\textbf{[11]} \hyperlink{https://eartharxiv.org/repository/view/5435/}{A. Miltenberger, \textbf{L. Wang}, T. Mukerji, J. Caers, Formulating and Solving the Data-Consistent Geophysical Inverse Problem for Subsurface Modeling Applications,} EarthArXiv, 2023 

 
\textbf{[10]} \textbf{L. Wang}, L. Peeters, E.J. MacKie, J. Caers, Unraveling the uncertainty of geological interfaces through data-knowledge-driven trend surface analysis, \textit{Computers \& Geosciences}, 2023 (under review)

\textbf{[9]} \hyperlink{https://egusphere.copernicus.org/preprints/2022/egusphere-2022-1224/}{E.J. MacKie, M. Field, \textbf{L. Wang}, Z. Yin, N. Schoedl, M. Hibbs, A. Zhang,  GStatSim V1.0: a Python package for geostatistical interpolation and simulation, \textit{Geoscientific Model Development}, 2023}

\textbf{[8]} \textbf{L. Wang}, H. Kim,  A. V.  Christiansen, B. Hansen, J. Caers, Statistical modeling of 3D redox architecture from non-colocated redox borehole and transient electromagnetic data, \textit{Hydrogeology Journal}, 2023 (accepted, in press, SI: Geostatistics and Hydrogeology)

\textbf{[7]} \hyperlink{https://library.seg.org/doi/10.1190/geo2021-0365.1}{\textbf{L. Wang}, F. Joncour, P. Barrallon, T. Harribey, L. Castanie, S. Yousfi, S. Guillon, Semi-supervised semantic segmentation for seismic interpretation, \textit{Geophysics}, 2023 }

\textbf{[6]} \hyperlink{https://link.springer.com/article/10.1007/s11053-022-10078-z}{T. Hall, C. Scheidt, \textbf{L. Wang}, Z. Yin, T. Mukerji, J. Caers, Sequential value of information for subsurface exploration drilling, \textit{Natural Resources Research}, 2022}


\textbf{[5]} \hyperlink{https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021WR031610}{\textbf{L. Wang}, P. Kitanidis, J. Caers, Hierarchical Bayesian inversion of global variables and large-scale spatial fields, \textit{Water Resources Research}, 2022}


\textbf{[4]} \hyperlink{https://link.springer.com/article/10.1007/s11053-022-10030-1}{J. Caers, C. Scheidt, Z. Yin, \textbf{L. Wang}, T. Mukerji, K. House, Efficacy of information in mineral exploration drilling, \textit{Natural Resources Research}, 2022}

\textbf{[3]} \hyperlink{https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021JB021767}{A. Miltenberger, S. Uhlemann, T. Mukerji, K. Williams,  B. Dafflon, \textbf{L. Wang}, H. Murakami-Wainwright, Probabilistic evaluation of geoscientific hypotheses with geophysical data: application to electrical resistivity imaging of a fractured bedrock zone, \textit{Journal of Geophysical Research - Solid Earth}, 2021}


\textbf{[2]} \hyperlink{https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021GL094038}{E. C. Johnston, F. Davenport, \textbf{L. Wang}, J. Caers, S. Muthukrishnan, M. Burke, N. S. Diffenbaugh, Quantifying the influence of precipitation intensity on landslide hazard in urbanized and non-urbanized areas, \textit{Geophysical Research Letters}, 2021} 

\textbf{[1]} \hyperlink{https://www.liebertpub.com/doi/10.1089/ees.2020.0365}{Q. Li, \textbf{L. Wang}, Z. Perzan, J. Caers, G. Brown, J. Bargar, K. Maher, Global sensitivity analysis of a reactive transport model for mineral scale formation during hydraulic fracturing, \textit{Environmental Engineering Science}, 2021}


 -->
<!-- ## Publications

1. Uncertainty quantification of 3D subsurface redox architecture from non-collocated redox borehole and transient electromagnetic data        
**Lijing Wang**, Hyojin Kim, Troels N. Vilhelmsen, Anders V. Christiansen, Birgitte Hansen, Jef Caers
*Hydrogeology Journal*, 2022 (in prep.)     


2. Uncertainty quantification of water exchanges due to beaver-induced inundation   
**Lijing Wang**, Zach Perzan, Tristan Babey, Martin Briggs, Sam Pierce, Brian Rogers, John Bargar, Kate Maher, 2022 (in prep.)


3. Stochastic sampling of non-stationary geological interfaces accounting for geological realism    
**Lijing Wang**, Luk Peeters, Emma MacKie, and Jef Caers, 2022 (in prep.)


4. [Hierarchical Bayesian inversion of global variables and large-scale spatial fields](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021WR031610)    
**Lijing Wang**, Peter Kitanidis, and Jef Caers, *Water Resources Research*, 2022


5. [Efficacy of information in mineral exploration drilling](https://link.springer.com/article/10.1007/s11053-022-10030-1)    
Jef Caers, Celine Scheidt, Zhen Yin, **Lijing Wang**, Tapan Mukerji, Kurt House, *Natural Resources Research*, 2021


6. Sequential value of information for subsurface exploration drilling    
Tyler Hall, Celine Scheidt, **Lijing Wang**, Zhen Yin, Tapan Mukerji, Jef Caers, *Natural Resources Research*, 2021 (under review)


7. Semi-supervised semantic segmentation for seismic interpretation  
**Lijing Wang**, Frederic Joncour, Pierre-Emmanuel Barrallon, Thibault Harribey, Chanchal Chatterjee, Laurent Castanie, Sonia Yousfi, and Sebastien Guillon, *Geophysics*, 2021 (under review)


8. [Quantifying the influence of precipitation intensity on landslide hazard in urbanized and non-urbanized areas](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021GL094038)     
Elizabeth Johnston, Frances Davenport, **Lijing Wang**, Jef Caers, Suresh Muthukrishnan, Marshall Burke, and Noah Diffenbaugh, *Geophysical Research Letters*, 2021 

9. [Probabilistic evaluation of geoscientific hypotheses with geophysical data: application to electrical resistivity imaging of a fractured bedrock zone](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021JB021767)      
Alex Miltenberger, Sebastian Uhlemann, Tapan Mukerji, Ken Williams, Baptiste Dafflon, **Lijing Wang**, Haruko Murakami-Wainwright, *Journal of Geophysical Research - Solid Earth*, 2021

10. [Global sensitivity analysis of a reactive transport model for mineral scale formation during hydraulic fracturing](https://www.liebertpub.com/doi/full/10.1089/ees.2020.0365)   
Qingyun Li, **Lijing Wang**, Zach Perzan, Jef Caers, Gordon E. Brown Jr., John R. Bargar, and Kate Maher, *Environmental Engineering Science*, 2021

11. [Semantic segmentation of crop type in Africa: A novel dataset and analysis of deep learning methods](https://openaccess.thecvf.com/content_CVPRW_2019/papers/cv4gc/Rustowicz_Semantic_Segmentation_of_Crop_Type_in_Africa_A_Novel_Dataset_CVPRW_2019_paper.pdf)   
Rose Rustowicz, Robin Cheong, **Lijing Wang**, Stefano Ermon, Marshall Burke, David Lobell, *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops*, 2019
 -->
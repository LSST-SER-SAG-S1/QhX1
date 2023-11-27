<b>QhX: Quasar harmonics eXplorer </b>
 Framework for 2D Hybrid Method; 


<ol> 
    <li> <a href="#intro"> Introduction to package. </a></li>
    <li> <a href="#inkind"> Introduction to in-kind proposal. </a></li>
    <li> <a href="#links"> Quick links </a> </li>
    
 </ol>
 
 
 <h3 id="intro"> Introduction to <u> QhX </u> package </h3>
 
  <p>
    The package will be separated into a few different modules: </p>
    <ol>
        <li> In response to the inherent nonlinearity of the physical processes and signatures observed in quasar light curves, our package incorporates a method for detecting periodic variability through the cross-correlation of wavelet matrices. 2D Hybrid technique (Kovacevic et al 2018, 2019, Kovacevic et al 2020a, 2021} is based on the calculation of the
Wavelet tranforms of light curves (LC). These WTs are cross-correlated
𝑀 = 𝐶𝑜𝑟𝑟(𝑊𝑇(𝐿𝐶1), 𝑊𝑇(𝐿𝐶2)) and presented as 2D heatmaps (M). It is also possible to autocorrelate WT of one
light curve with itself and obtain a detection of oscillations in one light curve. M provides information about the
presence of coordinated or independent signals and relative directions of signal variations. 
Given a sample of quasar light curves, it provides:

summary statistics, such as detected periods in at least two bands, where reference bands is u band, with lower and upper errors, and significance
comparison statistics between detected periods in band pairs, such as Intersection over Union metric (IoU).
quantification of robustnes of detected periods 
numerical catalogue of objects with detected periods and flags related to robustness
visualisation of numerical catalogue
For more information, please refer to our guide.
</li>
 

<b> Usage Examples </b> <br>
Please refer to the Tutorials for a  usage guide.


<a href=""> Tutorial 1 </a>
<a href=""> Tutorial 2 </a>




![image](https://user-images.githubusercontent.com/78701856/191952700-d104bc04-72a4-4258-961b-2c139619e673.png)


 
 
 
 
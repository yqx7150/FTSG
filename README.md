# FTSG
Fluorescence molecular tomography via score-based generative model       
The Code is created based on the method described in the following paper:            
P. He, J. Lin, Y. Zhu, Q. Wan, C. Wu, W. Wan, Q. Liu, Fluorescence molecular tomography via score-based generative model, Optics and Lasers in Engineering, Vol. 187, 2025, 108863.    
https://www.sciencedirect.com/science/article/pii/S0143816625000508       
        
## Abstract     
Fluorescence Molecular Tomography (FMT) imaging is a non-invasive quantitative detection technique that locates and quantifies fluorescent molecular probes in biological tissue. However, due to the light scattering effect and the ill-posed nature of the inverse problem, it is difficult to accurately reconstruct the fluorescence distribution. Traditional iterative reconstruction methods rely on the selection of regularization parameters, and data-driven deep learning methods have insufficient interpretability. In order to improve the imaging quality, fluorescence molecular tomography via score-based generative model (FTSG) is proposed. Prior information about the fluorescence target distribution is extracted via score-based generative model, which is used as a regularization term constraint for an iterative process based on the physical model. FTSG is validated through simulations and experiments using fluorescent targets with different radii and edge-to-edge distances. Compared with traditional methods, FTSG offers better resolution and reconstruction quality. This method can effectively distinguish two fluorescent targets with an edge-to-edge distance of 1 mm.      

##FTSG Reconstruction Flow Chart.
![image](https://github.com/user-attachments/assets/54be9eee-9629-4d4e-84e3-482c5fdd9894)
##Reconstruction results for fluorescence targets with different EEDs. (a) The ground truth, fluorescent yields images reconstructed using (b) ART, (c) MTV, (d) FISTA, (e) FTSG and (f) x-profile. The first to fourth rows respectively display the reconstruction results under EED = 1 mm, 2 mm, 3 mm, and 4 mm. The fluorescence yield of both fluorescent targets is 0.02 mm⁻¹, the radius of the two targets is 2.5 mm, the black dotted line in the figure indicates the ground truth of the fluorescent targe.
![image](https://github.com/user-attachments/assets/41753978-e510-4230-ae51-f94a2beed015)

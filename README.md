# Defect-Detection-in-Solar-Modules-Using-ICA-Basis-Images
The following repository is a defect detection prediction algorithm for electroluminescence (EL) images of solar cells using independent component analysis (ICA).  

##Training the data:    
The ICA-based defect detection is highly dependent on defect free images."labels.csv" has well labelled images of solar cells with probability of defect(0.0-> defect-free, 1.0-> defective). We use 40 defect-free images randomly from the "images" set for a training set. Those 40 images are trained using ICA algorithm to get a matrix **U**. The separated components in **U**, called independent components (ICs), are required to be as mutually independent as possible.   
## Sample Images   
### Defect free Image   
![alt defect_free](https://github.com/a0n0k0i0t/Defect-Detection-in-Solar-Modules-Using-ICA-Basis-Images/blob/main/images/cell0173.png?raw=true)   
### Defective Image   
![alt defective](https://github.com/a0n0k0i0t/Defect-Detection-in-Solar-Modules-Using-ICA-Basis-Images/blob/main/images/cell0277.png?raw=true)

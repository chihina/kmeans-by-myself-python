# kmeans-by-myself-python
This repository include implements of k-means and k-means++ by myself using python 

## Contents of repocitory
### kmeans.ipynb  
This file include implement of kmeans.  
when I use kmeans the algorithm, I got some failure case.  
Failure cases are causeed by problem of centroid initialization.  
                
### kmeans++.ipynb  
This file include implement of kmeans++.  
The algorithm solve problems of kmeans.  
Centoroids initialization of the algorithm is based on weights of euclid disntances between centoroid and dataset.
Centoirds are assigned from datasets.

## Example (kmeans and kmeans++)
In this section, I show clustering example with iris datasets.

### kmeans example
Show result of each iteration.  
In this case, clustering fail.  
![kmeans image](https://github.com/chihina/Scratch_autoencoder/blob/master/autoencoder_0402_gpu_ver6/ori_image_validation_3.png)  


### kmeans++ example
Show result of each iteration.  
In this case, clustering succeed.  
![kmeans++ image](https://github.com/chihina/Scratch_autoencoder/blob/master/autoencoder_0402_gpu_ver6/ori_image_validation_3.png)  

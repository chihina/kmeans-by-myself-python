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

### Ground-trurh of iris dataset  
![iris image](https://github.com/chihina/kmeans-by-myself-python/blob/master/iris_example.png)  

### kmeans example
Show result of each iteration.  
In this case, clustering fail.  
![kmeans image](https://github.com/chihina/kmeans-by-myself-python/blob/master/kmeans_example.png)  


### kmeans++ example
Show result of each iteration.  
In this case, clustering succeed.  
![kmeans++ image](https://github.com/chihina/kmeans-by-myself-python/blob/master/kmeans%2B%2B_example.png)  

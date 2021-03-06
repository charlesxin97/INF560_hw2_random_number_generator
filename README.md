# INF560_hw2/ Random number generator

[![DOI](https://zenodo.org/badge/297318397.svg)](https://zenodo.org/badge/latestdoi/297318397)  
[![CC BY 4.0][cc-by-shield]][cc-by]  

This repository contains a python notebook runnable in mybinder:  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/charlesxin97/INF560_hw2_random_number_generator/master?filepath=HW2.ipynb)  

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

This repository is for INF560 hw2, it contains the scripts for:   
1.Generation of 1000 random numbers in the range of 0-1000.  
2.Take the random numbers and transform them using an equation of y = 3x +6.  
3.Visualization of the points.  

## Screen shots  
![image](/images_readme/1.png)  
![image](/images_readme/2.png)  

## Comparison of the dependencies  
Extracted:  
![image](/images_readme/3.png)  
Installed:  
Numpy == 1.19.3  
Matplotlib == 3.3.2  


## Instructions for creating virtual environment  

Firstly, install the package.  
  
```
pip install virtualenv  
```
  
Secondly, create the virtual environment in the repository  
  
``` 
python3 -m venv dsdi560H4  
```  
  
Thirdly, source the activate and activate the virtual environment

``` 
source ./dsdi560H4/bin/activate 
. ./dsdi560H4/bin/activate  
```

Then you are in the virtual environment and start to install the packages in this virtual environment.  
  

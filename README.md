# Image segmentation using deeplab solution 
##Image segmentation
● An image is a collection or set of different pixels.
● We group together the pixels that have similar attributes using image segmentation
● Image segmentation could involve separating foreground from background, or
clustering regions of pixels based on similarities in color or shape

##Atrous convolutio
###Features 
Modify filter’s field-of view.
  ●Small field-of-view
  ●Large field-of-view 
Control the feature response without any increase in parameters.
Makes the output feature map larger.


##Followig are the steps to run the code
1 . Unzip the deeplab_model.tar.zip and extract deeplab_model.tar.gz from it and put it in the same folder were deeplab.py is present

2. Create a virtual evironment (All the steps here are using anaconda)
    conda create --name your_env_name python=3.7 -y
    
3. Install all the requirements 
    pip install -r requirements.txt
    
4. Run deeplab.py
    python deeplab.py
    
    
 OUTPUT 
 ![Image description](https://www.google.co.in/url?sa=i&url=https%3A%2F%2Fwww.pyimagesearch.com%2F2018%2F09%2F03%2Fsemantic-segmentation-with-opencv-and-deep-learning%2F&psig=AOvVaw2ZNRYZ3_2Jq8GZ9SNkwkAt&ust=1590585773459000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCLiqnoLS0ekCFQAAAAAdAAAAABAD)
 






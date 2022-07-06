# Point_Cloud_Semantic_Segmentation

Point Cloud Classification with PointNet. We are going to load in a dataset with point clouds of different objects. We will create the PointNet architecture from the bottom, train it on the dataset, and then do predictions on new point clouds that the neural network has not seen before. The code is commented will go through the process, explaining  what point clouds are, and evaluate the results.

Typical convolutional architectures require highly regular input data formats, like those of image grids or 3D voxels, in order to perform weight sharing and other kernel optimizations. Since point clouds or meshes are not in a regular format, most researchers typically transform such data to regular 3D voxel grids or collections of images (e.g, views) before feeding them to a deep net architecture. This data representation transfor- mation, however, renders the resulting data unnecessarily voluminous — while also introducing quantization artifacts that can obscure natural invariances of the data.

3D point cloud segmentation is the process of classifying point clouds into multiple homogeneous regions, the points in the same region will have the same properties. The segmentation is challenging because of high redundancy, uneven sampling density, and lack explicit structure of point cloud data. This problem has many applications in robotics such as intelligent vehicles, autonomous mapping and navigation.

Dependencies: 
Keras
Tensorflow

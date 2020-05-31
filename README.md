# Locally-Injective-Mappings-Benchmark

Injectively mapping a source mesh into a target domain is an important but challenging task in computer graphics and geometry processing. We publish this dataset as a benchmark for this task. The dataset contains 11647 triangle and tetrahedron source meshes, as well as their target domains. The method in our paper [Lifting Simplices to Find Injectivity](https://duxingyi-charles.github.io/publication/lifting-simplices-to-find-injectivity/) is able to compute locally injective mappings for all the meshes in the dataset. We also publish these results with the dataset. We believe this is the first dataset for locally injective mapping at this scale, and hope it will help future research in this area.

This dataset is not limited to locally injective mapping, you may also find it useful for mesh parameterization, deformation, or simply as a source for a large number of meshes.

## Dataset organization

The dataset contains 10743 triangle mesh examples and 904 tetrahedron mesh examples. They are divided into 3 categories, 2D parameterization, 3D parameterization and 3D deformation. Each category has 3 groups of examples. The following table shows the number of examples in each group.

![](figure/dataset_example_count.png)

### 2D Parameterization



#### Simple

{{<figure alt="2D Parameterization" src="figure/2D_Param_Simple.png" title="Figure 2. Four examples in the 2D parameterization category derived from [Liu et al. 2018], where methods FF and LBD failed to find injective embeddings. Inverted triangles are colored in red, and the numbers of inversion are marked in red.">}}

![](figure/2D_Param_Simple.png)

#### Letters

![](figure/2D_Param_Letters.png)

#### Liu 

![](figure/2D_Param_Liu.png)

### 3D Parameterization

![](figure/3D_Param.png)

### 3D Deformation

![](figure/3D_Deform.png)

## Data format


## Cite

If you use our dataset, please cite our paper:

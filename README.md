## Project Description

Here is the link to my [project proposal](https://www.jasom.com)

### Introduction

3D cut optimization is a problem within computational geometry and computer graphics that deals with flattening 3D objects. Specifically, we are interested in the cuts that should be made to minimize the amount of distortion that occurs when the object is flattened along the cuts into a 2D surface. There are various ways of measuring distortion; one might look at how much the boundaries of each cut patch stretches, or one might also look at the dirichlet distortion term for conformal flattening.

### Project Mentors

For this project, I will be working with professor [**Keenan Crane**](https://www.cs.cmu.edu/~kmcrane/) as my faculty mentor and his PhD student **[Nick Sharp**] (http://nmwsharp.com/). Nick has already been working on the 3D cut optimization problem and is planning to publish a paper on the topic soon. He has been getting me up to speed in the area and part of my research will involve making contributions to his project.

### Current Research

Part of my research project will involve finishing up my current research in 3D cut optimization. Specifically, I am working on supporting compatability between the current cuts-algorithm and real world material fabrication.

```
Current Workflow:

1. Extract all cut patches from the 3D mesh into individual edges
2. Collect edges into individual patches through an algorithm like DFS/Union Find
3. Walk along the edges of each patch and make annotations if an edge and its 'twin' 
   should be placed together
4. Convert to SVG format and perform scaling.
5. Print using a cut printer (Silhouette Cameo) and assemble patches into model.
```

### Future Research

### Motivation

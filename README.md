## Goals

* **Understand, and judge** the advantages and disadvantages of the medical visualization algorithms, as well as their applicability to a specific **medical problem**.
* **Propose** suitable solutions to a problem, backed by sound knowledge of the underlying theory and the practical possibilities.
* **Design, implement, test and discuss** these solutions, consisting of a number of **medical visualization algorithms**.

## Introduction (L1)

* Medical Imaging
* General Intro Vis
  * 3 goals of Vis (Communicate, analyze, explore)
  * Vis Pipeline

## Basic Concepts (L1-2)

* Definition Image => digital images; Sampling and Quantization Intro (L1)
* Beyond Scalar Images: Vector fields (Tensors, High Dim?) (L1)
* Basics of Image Analysis (L1)
  * Fourier Transform
    * Basic image processing in the fourier domain
    * Convolution
* Sampling <= FT  (L1)
  * Aliasing
* Interpolation (L2)
  * perfect reconstruction using sinc
  * truncation artifacts <= FT
  * other interpolation kernels
    * nearest
    * linear
    * cubic
    * b-spline
  * bi/trilinear

## Applications

* cardio-vascular disease (L3) <= MPR/CPR
  * Stenosis
  * Aneurysms
* Virtual colonoscopy (L5) <= VolVis
* Blood Flow Analysis. (L6) <= FlowVis
* Brain/Connectome Analysis (L7) <= Tensor Vis

## Modalities (L3,6)

* X-Ray (L3)
* CT (L3)
  * Reconstruction <= FT
  * Hounsfield Units
* MRI (L6)
  * K-Space <= FT
  * DW MRI

## Volume Visualization (L2-5)

* mpr/cpr (L3)
  * **Application: Angiography/CVD**
* marching squares/cubes (L2)
  * Phong shading
  * gradient
* DVR (L3-5)
  * MPR
  * Compositing
  * Transfer functions
  * Pre/Post classification
  * Illustrative
  * **Application: virtual colonoscopy**

## Vector Field Visualization (L6)

* Vector Field Integration
  * streamlines/pathlines/streaklines
  * integration methods (Euler/RK)
* **Application: Blood flow w/ PC-MRI**

## Diffusion Tensor Visualization (L7)

* scalar fields (fractional anisotropy ...)
* glyphs
* tensor lines
* **Application: brain strucutral connectivity**



## (Imaging) Cytometry

* high-dimensional data
* visualization of hd data
  * direct (PCP/SPM)
  * indirect (dimensionality reduction)
* **Application: immunology research, immunotherapy**

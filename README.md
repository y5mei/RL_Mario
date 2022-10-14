## How to Get Start With Mario Project

1. Create a new conda environment from the `tensor.yml` file for another platform:

`cd RLTest01`

`conda env create --file tensor.yml`

2. In the new conda environment, you will also need to manually install the GPU lib/drivers that compatible with your hardware if you want to train on GPU
   * PyTouch 
   * Tensorflow_v2 or Tensorflow v1 + tensorflow_gpu, 
   * Nvidia CUDA, 
   * [Nvidia cuDNN](https://developer.nvidia.com/cudnn) 

3. In case if you want to export your conda environment, run the command below: 
`conda env export --from-history >> tensor.yml`

4. Run the `HelloWorld.ipynb` to the end, you should be able to see a trained Mario in a separate window (this cannot be done in colab)
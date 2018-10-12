Project for showing abseil compilation errors with CUDA.

Steps to reproduce

```bash
git clone https://github.com/erikman/cuda-abseil.git
cd cuda-abseil
git submodules update --init

mkdir _debug
cd _debug
cmake ..

make
```

See https://devtalk.nvidia.com/default/topic/1042599/cuda-programming-and-performance/nvcc-preprocessor-bug-causes-compilation-failure/post/5288689/

# miniTorch_sentiment

Assignment 1 of 11-868 LLM Systems.

Goal: A basic deep learning framework capable of CUDA-optimized tensor operations and automatic differentiation.
- Model is a simple neural network for sentiment classification

## 1. Compile the CUDA kernels
```nvcc -o minitorch/cuda_kernels/combine.so --shared src/combine.cu -Xcompiler -fPIC```

## 2. Train Model
```python project/run_sentiment.py```

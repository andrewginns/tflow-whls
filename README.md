# TensorFlow Optimized Wheels
Collection of Tensorflow wheels for various hardware for the MSc project 

### Target Hardware 
* AMD K10 cores, No AVX - https://en.wikipedia.org/wiki/AMD_10h

* SP4 i7-6650u Virtual Box, AVX AVX2 SSE4.2

Avoids:
```
The TensorFlow library wasn't compiled to use AVX instructions, but these are available on your machine and could speed up CPU computations.
The TensorFlow library wasn't compiled to use AVX2 instructions, but these are available on your machine and could speed up CPU computations.
The TensorFlow library wasn't compiled to use SSE4.1 instructions, but these are available on your machine and could speed up CPU computations.
The TensorFlow library wasn't compiled to use SSE4.2 instructions, but these are available on your machine and could speed up CPU computations.

or:
Your CPU supports instructions that this TensorFlow binary was not compiled to use: SSE4.1 SSE4.2 AVX AVX2 FMA
```

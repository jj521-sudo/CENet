# Complex End-to-End OCE Reconstruction Network (CENet)
Input: F_0∈R^(B×C×Y×R×T×Z),where B denotes the batch size, and Y and R represent the lateral and elevational spatial dimensions, respectively, T denotes the temporal dimension, and Z represents the depth dimension. The two input channels C = 2 correspond to the real and imaginary components of the complex OCT signal.
Output: F_0∈R^(B×1×Y×R)

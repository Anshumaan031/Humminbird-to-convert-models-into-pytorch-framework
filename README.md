# Hummingbird-to-convert-models-into-pytorch-framework
 With an aim of enabling the traditional ML libraries to take advantage of hardware acceleration and optimizations implemented for the neural networks without restructuring the model, Microsoft launched a library named Hummingbird.</br>


Widely used Deep Learning frameworks such as PyTorch, ONNX Runtime and TensorFlow use a single abstraction called tensors as the basic unit of any computation. Due to lack of any such common abstraction, traditional ML libraries require (m*n) number of implementations to achieve hardware acceleration (where m and n denote the number of operators in the computation and the number of hardware backends available respectively). This makes the libraries computationally more expensive to use than the optimized neural networks. Hummingbird library resolves this issue by converting the conventional ML pipelines into tensor-oriented computations. The traditional ML models can then be deployed faster in real-time.</br>
![image](https://user-images.githubusercontent.com/67821036/141846880-be32efea-745c-4704-aa96-5c10df444008.png)

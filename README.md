# onnx2caffe
## Code mainly from https://github.com/xxradon/ONNXToCaffe


## 
I want to convert the ShuffleNet  model from pytorch to caffe ，so here is the code

##  How to use
To convert onnx model to caffe:
python convertCaffe.py ShuffleNet.onnx ShuffleNet.prototxt ShuffleNet.caffemodel


Current support operation
Conv
Relu
LeakyRelu
PRelu
Transpose
ReduceMean
MatMul
BatchNormalization
Add
Mul
Add
Reshape
MaxPool
AveragePool
GlobalAveragePool
Dropout
Gemm (InnerProduct only)
Upsample (nearest and bilinear all supported)
Concat
ConvTranspose
Sigmoid
Flatten
Sqrt
Softmax
Unsqueeze
Slice
Split
Resize


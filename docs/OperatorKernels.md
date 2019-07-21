## Supported Operators Data Types
*This file is automatically generated from the
            [def files](/onnxruntime/core/providers/cpu/cpu_execution_provider.cc) via [this script](/tools/python/gen_opkernel_doc.py).
            Do not modify directly and instead edit operator definitions.*



## Operators implemented by CPUExecutionProvider

| Op Name | OpSet Versions | Parameter | Types Supported |
|---------|----------------|-----------|------------------|
**Operator Domain:** *ai.onnx.ml*
|Abs|6+|T|tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown|
|Acos|7+|T|tensor(float)|
|Acosh|9+|T|tensor(float)|
|Add|7+|T|tensor(float), tensor(int32), tensor(int64)|
|Affine|1+|T|tensor(float)|
|And|7+|T|tensor(bool)|
|ArgMax|1+|T|tensor(float), tensor(int32)|
|ArgMin|1+|T|tensor(float), tensor(int32)|
|ArrayFeatureExtractor|1+|T|tensor(float), tensor(string), tensor(int32), tensor(int64), tensor(double)|
|Asin|7+|T|tensor(float)|
|Asinh|9+|T|tensor(float)|
|Atan|7+|T|tensor(float)|
|Atanh|9+|T|tensor(float)|
|AveragePool|10+|T|tensor(float)|
| |[7, 9]|T|tensor(float)|
|BatchNormalization|[7, 9]|B|tensor(float)|
| ||X|tensor(float)|
| ||mean|tensor(float)|
| ||scale|tensor(float)|
| ||var|tensor(float)|
|Binarizer|1+|T|tensor(float)|
|Cast|9+|T1|tensor(string)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| |[6, 9]|T1|tensor(bool), tensor(uint16), tensor(double), tensor(float), tensor(int32), tensor(int16), tensor(int64), tensor(uint32), tensor(uint64), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|CastMap|1+|T1|unknown|
| ||T2|tensor(float), tensor(int64), tensor(string)|
|CategoryMapper|1+|T1|tensor(string), tensor(int64)|
| ||T2|tensor(string), tensor(int64)|
|Ceil|6+|T|tensor(float)|
|Clip|6+|T|tensor(float)|
|Compress|9+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Concat|4+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|ConstantOfShape|9+|T1|tensor(int64)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Conv|1+|T|tensor(float)|
|ConvInteger|10+|T1|tensor(uint8)|
| ||T2|tensor(uint8)|
| ||T3|tensor(int32)|
|ConvTranspose|1+|T|tensor(float)|
|Cos|7+|T|tensor(float)|
|Cosh|9+|T|tensor(float)|
|Crop|1+|T|tensor(float)|
|DepthToSpace|[1, 4]|T|tensor(float)|
|DequantizeLinear|10+|x|tensor(uint8), unknown|
| ||x_scale|tensor(float)|
| ||x_zero_point|tensor(uint8), unknown|
| ||y|tensor(float)|
|DictVectorizer|1+|T1|unknown|
| ||T2|tensor(float), tensor(string), tensor(int64), tensor(double)|
|Div|7+|T|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Dropout|10+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| ||T1|tensor(bool)|
| |[7, 9]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|DynamicSlice|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Elu|6+|T|tensor(float)|
|Equal|7+|T|tensor(bool), tensor(int32), tensor(int64)|
|Erf|9+|T|tensor(float)|
|Exp|6+|T|tensor(float)|
|Expand|8+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|EyeLike|9+|T1|tensor(float), tensor(int32), tensor(int64), tensor(double), tensor(uint64)|
| ||T2|tensor(float), tensor(int32), tensor(int64), tensor(double), tensor(uint64)|
|FeatureVectorizer|1+|T1|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Flatten|9+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| |[1, 8]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Floor|6+|T|tensor(float)|
|GRU|7+|T|tensor(float), tensor(double)|
| ||T1|tensor(int32)|
|Gather|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Gemm|[7, 9]|T|tensor(float)|
|GlobalAveragePool|1+|T|tensor(float)|
|GlobalLpPool|2+|T|tensor(float)|
|GlobalMaxPool|1+|T|tensor(float)|
|Greater|9+|T|tensor(int32)|
| |[7, 9]|T|tensor(float)|
|HardSigmoid|6+|T|tensor(float)|
|Hardmax|1+|T|tensor(float)|
|Identity|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|If|1+|B|tensor(bool)|
| ||V|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|ImageScaler|1+|T|tensor(float)|
|Imputer|1+|T|tensor(float), tensor(int64)|
|InstanceNormalization|6+|T|tensor(float)|
|IsInf|10+|T1|tensor(float), tensor(double)|
| ||T2|tensor(bool)|
|IsNaN|9+|T1|tensor(float), tensor(MLFloat16)|
| ||T2|tensor(bool)|
|LRN|1+|T|tensor(float)|
|LSTM|7+|T|tensor(float), tensor(double)|
| ||T1|tensor(int32)|
|LabelEncoder|1+|T1|tensor(string), tensor(int64)|
| ||T2|tensor(string), tensor(int64)|
|LeakyRelu|6+|T|tensor(float)|
|Less|9+|T|tensor(int32)|
| |[7, 9]|T|tensor(float)|
|LinearClassifier|1+|T1|tensor(float), tensor(int32), tensor(int64), tensor(double)|
| ||T2|tensor(string), tensor(int64)|
|LinearRegressor|1+|T|tensor(float)|
|Log|6+|T|tensor(float)|
|LogSoftmax|1+|T|tensor(float)|
|Loop|1+|B|tensor(bool)|
| ||I|tensor(int64)|
| ||V|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|LpNormalization|1+|T|tensor(float)|
|LpPool|2+|T|tensor(float)|
|MatMul|[1, 9]|T|tensor(float), tensor(double)|
| |[9, 9]|T|tensor(uint64), tensor(int32), tensor(int64), tensor(uint32)|
|MatMulInteger|10+|T1|tensor(uint8)|
| ||T2|tensor(uint8)|
| ||T3|tensor(int32)|
|Max|8+|T|tensor(float)|
| |[6, 7]|T|tensor(float)|
|MaxPool|10+|I|tensor(int64)|
| ||T|tensor(float)|
| |[1, 7]|T|tensor(float)|
| |[8, 9]|I|tensor(int64)|
| ||T|tensor(float)|
|MaxRoiPool|1+|T|tensor(float)|
|MaxUnpool|9+|I|tensor(int64)|
| ||T|tensor(float)|
| ||Y|tensor(float)|
|Mean|8+|T|tensor(float)|
| |[6, 7]|T|tensor(float)|
|MeanVarianceNormalization|9+|T|tensor(float)|
| |[1, 8]|T|tensor(float)|
|Min|8+|T|tensor(float)|
| |[6, 7]|T|tensor(float)|
|Mod|10+|T|tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Mul|7+|T|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Multinomial|7+|T1|tensor(float)|
| ||T2|tensor(int32), tensor(int64)|
|Neg|6+|T|tensor(float), tensor(int32), unknown|
|NonZero|9+|T|tensor(float), tensor(bool), tensor(int32), tensor(int64)|
|Normalizer|1+|T|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Not|1+|T|tensor(bool)|
|OneHot|9+|T1|tensor(float), tensor(int64)|
| ||T2|tensor(float), tensor(int64)|
| ||T3|tensor(float), tensor(int32), tensor(int64), tensor(string)|
|OneHotEncoder|1+|T|tensor(float), tensor(string), tensor(int64), tensor(double)|
|Or|7+|T|tensor(bool)|
|PRelu|[7, 9]|T|tensor(float)|
|Pad|2+|T|tensor(float)|
|ParametricSoftplus|1+|T|tensor(float)|
|Pow|7+|T|tensor(float)|
|QLinearConv|10+|T1|tensor(uint8)|
| ||T2|tensor(uint8)|
| ||T3|tensor(uint8)|
|QLinearMatMul|10+|T1|tensor(uint8)|
| ||T2|tensor(uint8)|
| ||T3|tensor(uint8)|
|QuantizeLinear|10+|x|tensor(float)|
| ||y|tensor(uint8)|
| ||y_scale|tensor(float)|
| ||y_zero_point|tensor(uint8)|
|RNN|7+|T|tensor(float)|
| ||T1|tensor(int32)|
|RandomNormal|1+|T|tensor(float), tensor(double)|
|RandomNormalLike|1+|T1|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T2|tensor(float), tensor(double)|
|RandomUniform|1+|T|tensor(float), tensor(double)|
|RandomUniformLike|1+|T1|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T2|tensor(float), tensor(double)|
|Reciprocal|6+|T|tensor(float)|
|ReduceL1|1+|T|tensor(float), tensor(int32)|
|ReduceL2|1+|T|tensor(float), tensor(int32)|
|ReduceLogSum|1+|T|tensor(float), tensor(int32)|
|ReduceLogSumExp|1+|T|tensor(float), tensor(int32)|
|ReduceMax|1+|T|tensor(float), tensor(int32)|
|ReduceMean|1+|T|tensor(float), tensor(int32)|
|ReduceMin|1+|T|tensor(float), tensor(int32)|
|ReduceProd|1+|T|tensor(float), tensor(int32)|
|ReduceSum|1+|T|tensor(float), tensor(int32)|
|ReduceSumSquare|1+|T|tensor(float), tensor(int32)|
|Relu|6+|T|tensor(float)|
|Reshape|5+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||shape|tensor(int64)|
|Reshape_1|[1, 4]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Resize|10+|T|tensor(float), tensor(int32), tensor(uint8)|
|ReverseSequence|10+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|RoiAlign|10+|T|tensor(float), tensor(double)|
| ||T2|tensor(int64)|
|SVMClassifier|1+|T1|tensor(float), tensor(int32), tensor(int64), tensor(double)|
| ||T2|tensor(int64), tensor(string)|
|SVMRegressor|1+|T|tensor(float)|
|Scale|1+|T|tensor(float)|
|ScaledTanh|1+|T|tensor(float)|
|Scaler|1+|T|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Scan|9+|I|tensor(int64)|
| ||V|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| |[8, 8]|I|tensor(int64)|
| ||V|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Scatter|9+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Selu|6+|T|tensor(float)|
|Shape|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T1|tensor(int64)|
|Shrink|9+|T|tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Sigmoid|6+|T|tensor(float)|
|Sign|9+|T|tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Sin|7+|T|tensor(float)|
|Sinh|9+|T|tensor(float)|
|Size|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown|
|Slice|10+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
| |[1, 9]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Softmax|1+|T|tensor(float)|
|Softplus|1+|T|tensor(float)|
|Softsign|1+|T|tensor(float)|
|SpaceToDepth|1+|T|tensor(float)|
|Split|2+|T|tensor(float), tensor(int32), tensor(string)|
|Sqrt|6+|T|tensor(float)|
|Squeeze|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|StringNormalizer|10+|T|tensor(string)|
|Sub|7+|T|tensor(float), tensor(int32), tensor(int64), tensor(double)|
|Sum|8+|T|tensor(float)|
| |[6, 7]|T|tensor(float)|
|Tan|7+|T|tensor(float)|
|Tanh|6+|T|tensor(float)|
|TfIdfVectorizer|9+|T|tensor(int32), tensor(string), tensor(int64)|
| ||T1|tensor(float)|
|ThresholdedRelu|1+|T|tensor(float)|
| |10+|T|tensor(float)|
|Tile|6+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown|
|TopK|10+|I|tensor(int64)|
| ||T|tensor(float)|
| |[1, 9]|I|tensor(int64)|
| ||T|tensor(float)|
|Transpose|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|TreeEnsembleClassifier|1+|T1|tensor(float), tensor(int32), tensor(int64), tensor(double)|
| ||T2|tensor(int64), tensor(string)|
|TreeEnsembleRegressor|1+|T|tensor(float)|
|Unsqueeze|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Upsample|[7, 9]|T|tensor(float), tensor(int32), tensor(uint8)|
|Where|9+|T|tensor(float), tensor(int32), tensor(string)|
|Xor|7+|T|tensor(bool)|
|ZipMap|1+|T|unknown|
| |
| |
**Operator Domain:** *com.microsoft*
|AttnLSTM|1+|T|tensor(float), tensor(double)|
| ||T1|tensor(int32)|
|ConvTransposeWithDynamicPads|1+|T|tensor(float)|
|CropAndResize|1+|T|tensor(float)|
| ||T2|tensor(int32)|
|ExpandDims|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||axis|tensor(int32)|
|FusedConv|1+|T|tensor(float)|
|FusedGemm|1+|T|tensor(float)|
|GatherND|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|MaxpoolWithMask|1+|X|tensor(float)|
|MurmurHash3|1+|T1|tensor(int32), tensor(string), tensor(uint32)|
| ||T2|tensor(int32), tensor(uint32)|
|Pad|1+|T|tensor(float)|
|Range|1+|T|tensor(float), tensor(int32), tensor(int64), tensor(double), tensor(int16)|
|SampleOp|1+|T|tensor(float)|
|Tokenizer|1+|T|tensor(string)|
|Unique|1+|T|tensor(float)|
|WordConvEmbedding|1+|T|tensor(int32)|
| ||T1|tensor(float)|
| |
| |
**Operator Domain:** *com.microsoft.nchwc*
|AveragePool|1+|T|tensor(float)|
|Conv|1+|T|tensor(float)|
|GlobalAveragePool|1+|T|tensor(float)|
|GlobalMaxPool|1+|T|tensor(float)|
|MaxPool|1+|T|tensor(float)|
|ReorderInput|1+|T|tensor(float)|
|ReorderOutput|1+|T|tensor(float)|
| |
| |


## Operators implemented by CUDAExecutionProvider

| Op Name | OpSet Versions | Parameter | Types Supported |
|---------|----------------|-----------|------------------|
**Operator Domain:** *ai.onnx.ml*
|Abs|6+|T|tensor(uint16), tensor(double), tensor(float), tensor(int32), tensor(int16), tensor(int64), tensor(uint32), tensor(uint64), tensor(uint8), unknown, tensor(MLFloat16)|
|Add|7+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
|Affine|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|And|7+|T|tensor(bool)|
|ArgMax|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ArgMin|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|AveragePool|10+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[7, 9]|I|tensor(int64)|
| ||T|tensor(float), tensor(double), tensor(MLFloat16)|
|BatchNormalization|9+|B|tensor(float), tensor(double), tensor(MLFloat16)|
| ||X|tensor(float), tensor(double), tensor(MLFloat16)|
| ||mean|tensor(float), tensor(double), tensor(MLFloat16)|
| ||scale|tensor(float), tensor(double), tensor(MLFloat16)|
| ||var|tensor(float), tensor(double), tensor(MLFloat16)|
| |[7, 8]|B|tensor(float), tensor(double), tensor(MLFloat16)|
| ||X|tensor(float), tensor(double), tensor(MLFloat16)|
| ||mean|tensor(float), tensor(double), tensor(MLFloat16)|
| ||scale|tensor(float), tensor(double), tensor(MLFloat16)|
| ||var|tensor(float), tensor(double), tensor(MLFloat16)|
|Cast|9+|T1|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| |[6, 8]|T1|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Ceil|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Compress|9+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Concat|4+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|ConstantOfShape|9+|T1|tensor(int64)|
| ||T2|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Conv|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ConvTranspose|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Crop|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Div|7+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
|Dropout|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|DynamicSlice|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Elu|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Equal|7+|T|tensor(bool), tensor(int32), tensor(int64)|
|Erf|9+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Exp|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Expand|8+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Flatten|9+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| |[1, 8]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Floor|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|GRU|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| ||T1|tensor(int32)|
|Gather|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Gemm|9+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[7, 8]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|GlobalAveragePool|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|GlobalMaxPool|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Greater|9+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
| |[7, 8]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|HardSigmoid|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Identity|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|ImageScaler|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|InstanceNormalization|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|LRN|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|LSTM|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| ||T1|tensor(int32)|
|LeakyRelu|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Log|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|MatMul|9+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[1, 8]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Max|8+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[6, 7]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|MaxPool|10+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[1, 7]|I|tensor(int64)|
| ||T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[8, 9]|I|tensor(int64)|
| ||T|tensor(float), tensor(double), tensor(MLFloat16)|
|MemcpyFromHost|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|MemcpyToHost|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Min|8+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |[6, 7]|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Mul|7+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
|Neg|6+|T|tensor(double), tensor(int32), tensor(int16), tensor(int64), tensor(float), unknown, tensor(MLFloat16)|
|Or|7+|T|tensor(bool)|
|PRelu|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Pad|2+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ParametricSoftplus|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Pow|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|RNN|7+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| ||T1|tensor(int32)|
|Reciprocal|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceL1|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceL2|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceLogSum|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceLogSumExp|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceMax|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceMean|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceMin|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceProd|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceSum|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ReduceSumSquare|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Relu|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Reshape|5+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||shape|tensor(int64)|
|Reshape_1|[1, 4]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Resize|10+|T|tensor(float), tensor(int32), tensor(double), tensor(uint8), tensor(MLFloat16)|
|ScaledTanh|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Selu|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Shape|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||T1|tensor(int64)|
|Shrink|9+|T|tensor(uint16), tensor(double), tensor(float), tensor(int32), tensor(int16), tensor(int64), tensor(uint32), tensor(uint64), tensor(uint8), unknown, tensor(MLFloat16)|
|Sigmoid|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Slice|10+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
| |[1, 9]|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
| ||Tind|tensor(int32), tensor(int64)|
|Softmax|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Softplus|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Softsign|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Split|2+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Sqrt|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Squeeze|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Sub|7+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
|Sum|8+|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
| |[6, 7]|T|tensor(double), tensor(float), tensor(int32), tensor(int64), tensor(uint32), tensor(uint64), tensor(MLFloat16)|
|Tanh|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|ThresholdedRelu|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
| |10+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Tile|6+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Transpose|1+|T|tensor(float), tensor(double), tensor(MLFloat16)|
|Unsqueeze|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Upsample|[7, 9]|T|tensor(float), tensor(int32), tensor(double), tensor(uint8), tensor(MLFloat16)|
|Xor|7+|T|tensor(bool)|
| |
| |
**Operator Domain:** *com.microsoft*
|ConvTransposeWithDynamicPads|1+|T|tensor(float)|
| |
| |


## Operators implemented by MKLDNNExecutionProvider

| Op Name | OpSet Versions | Parameter | Types Supported |
|---------|----------------|-----------|------------------|
**Operator Domain:** *ai.onnx.ml*
|AveragePool|[7, 8]|T|tensor(float)|
|BatchNormalization|7+|T|tensor(float)|
|Conv|1+|T|tensor(float)|
|Gemm|7+|T|tensor(float)|
|GlobalAveragePool|[1, 8]|T|tensor(float)|
|GlobalMaxPool|[1, 8]|T|tensor(float)|
|LRN|1+|T|tensor(float)|
|MaxPool|[1, 7]|T|tensor(float)|
| |[8, 8]|T|tensor(float)|
|MemcpyFromHost|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|MemcpyToHost|1+|T|tensor(bool), tensor(double), tensor(uint16), tensor(int32), tensor(uint64), tensor(int16), tensor(int64), tensor(string), tensor(uint32), tensor(bfloat16), tensor(float), tensor(uint8), unknown, tensor(MLFloat16)|
|Relu|6+|T|tensor(float)|
|Sum|6+|T|tensor(float)|
| |
| |
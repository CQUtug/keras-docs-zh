# keras-docs-zh
PDF version of the Keras Chinese (zh-cn) translation docs 
site_name: Keras 中文文档
theme: readthedocs
docs_dir: sources
repo_url: https://github.com/keras-team/keras-docs-zh
site_url: http://keras.io/zh/
# theme_dir: ../keras/docs/theme
site_description: 'Keras，Python 深度学习库中文文档。'

dev_addr: '0.0.0.0:8000'
google_analytics: ['UA-61785484-1', 'keras.io']


pages:
- 主页: index.md
- 为什么选择 Keras?: why-use-keras.md
- 快速开始:
  - Sequential 顺序模型指引: getting-started/sequential-model-guide.md
  - 函数式 API 指引: getting-started/functional-api-guide.md
  - FAQ 常见问题解答: getting-started/faq.md
- 模型:
  - 关于 Keras 模型: models/about-keras-models.md
  - Sequential 顺序模型 API: models/sequential.md
  - 函数式 API: models/model.md
- Layers:
  - 关于 Keras 网络层: layers/about-keras-layers.md
  - 核心网络层: layers/core.md
  - 卷积层 Convolutional: layers/convolutional.md
  - 池化层 Pooling: layers/pooling.md
  - 局部连接层 Locally-connected: layers/local.md
  - 循环层 Recurrent: layers/recurrent.md
  - 嵌入层 Embedding: layers/embeddings.md
  - 融合层 Merge: layers/merge.md
  - 高级激活层 Advanced Activations: layers/advanced-activations.md
  - 标准化层 Normalization: layers/normalization.md
  - 噪声层 Noise: layers/noise.md
  - 层封装器 wrappers: layers/wrappers.md
  - 编写你自己的层: layers/writing-your-own-keras-layers.md
- 数据预处理:
  - 序列预处理: preprocessing/sequence.md
  - 文本预处理: preprocessing/text.md
  - 图像预处理: preprocessing/image.md
- 损失函数 Losses: losses.md
- 评估标准 Metrics: metrics.md
- 优化器 Optimizers: optimizers.md
- 激活函数 Activations: activations.md
- 回调函数 Callbacks: callbacks.md
- 常用数据集 Datasets: datasets.md
- 应用 Applications: applications.md
- 后端 Backend: backend.md
- 初始化 Initializers: initializers.md
- 正则化 Regularizers: regularizers.md
- 约束 Constraints: constraints.md
- 可视化 Visualization: visualization.md
- Scikit-learn API: scikit-learn-api.md
- 工具: utils.md
- 贡献: contributing.md

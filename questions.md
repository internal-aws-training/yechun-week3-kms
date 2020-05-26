1. What is KMS , and KMS can handle which problems?

AWS Key Management Service (AWS KMS) 是一项托管服务，可让您轻松创建和控制客户主密钥 (CMK)，这是用于加密数据的加密密钥。

1. The approaches to use KMS.

- AWS KMS CLI
- AWS SDK

3. You can do which action by using KMS (you should know at least  5 or more) ?
- 可以对 AWS KMS 客户主密钥 (CMK) 执行以下基本管理操作：
- 创建和查看对称和非对称 CMK，以及编辑其属性。
- 启用和禁用 CMK
- 创建和查看 CMK 的访问控制策略和授予
- 启用和禁用 CMK 中加密材料的自动轮换
- 标记您的 CMK，从而更加轻松地识别、分类和跟踪使用情况和成本
- 创建、删除、列出和更新别名，即您的 CMK 的友好名称
- 删除 CMK 来完成密钥生命周期

此外，可以使用 CMK 执行以下加密操作。有关示例，请参阅 编程 AWS KMS API。

- 使用对称或非对称 CMK 对数据进行加密、解密和重新加密
- 使用非对称 CMK 对消息进行签名和验证
- 生成可导出的对称数据密钥和非对称数据密钥对
- 生成适用于加密应用程序的随机数

还可以使用 AWS KMS 的高级功能
- 将加密材料导入 CMK
- 在 AWS CloudHSM 集群支持的您自己的自定义密钥存储中创建 CMK。
- 通过 VPC 中的私有终端节点直接连接到 AWS KMS
- 使用混合后量子 TLS 可对发送到 AWS KMS 的数据进行前瞻性的传输中加密
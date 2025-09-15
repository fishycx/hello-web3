# MetaMask使用指南

## 1. MetaMask简介

### 1.1 什么是MetaMask？
MetaMask是一个**浏览器扩展钱包**，允许用户与以太坊区块链交互。它是目前最流行的以太坊钱包之一。

### 1.2 主要功能
- **钱包管理**：创建和管理以太坊账户
- **交易处理**：发送和接收ETH及代币
- **DApp交互**：与去中心化应用交互
- **网络切换**：支持多个以太坊网络
- **代币管理**：添加和管理ERC-20代币

### 1.3 支持平台
- **浏览器扩展**：Chrome、Firefox、Edge、Brave
- **移动应用**：iOS、Android
- **硬件钱包**：支持Ledger、Trezor

---

## 2. 安装MetaMask

### 2.1 浏览器扩展安装
**步骤：**
1. 访问 https://metamask.io/
2. 点击"Download"按钮
3. 选择你的浏览器
4. 点击"Install MetaMask"
5. 在浏览器中确认安装

### 2.2 移动应用安装
**步骤：**
1. 在应用商店搜索"MetaMask"
2. 下载并安装应用
3. 打开应用开始设置

---

## 3. 创建钱包

### 3.1 新用户设置
**步骤：**
1. 打开MetaMask扩展
2. 点击"Get Started"
3. 选择"Create a Wallet"
4. 阅读并同意服务条款
5. 创建密码（至少8位）
6. 观看安全视频
7. 备份助记词

### 3.2 助记词备份
**重要提示：**
- 助记词是恢复钱包的唯一方式
- 必须安全保存，不要截图
- 建议写在纸上，放在安全地方
- 不要分享给任何人

**助记词示例：**
```
abandon abandon abandon abandon abandon abandon abandon abandon abandon abandon abandon about
```

### 3.3 验证助记词
**步骤：**
1. 按顺序点击助记词
2. 确认顺序正确
3. 完成钱包创建

---

## 4. 导入钱包

### 4.1 使用助记词导入
**步骤：**
1. 选择"Import wallet"
2. 输入12或24个助记词
3. 设置新密码
4. 完成导入

### 4.2 使用私钥导入
**步骤：**
1. 选择"Import account"
2. 选择"Private key"
3. 输入私钥
4. 完成导入

---

## 5. 网络配置

### 5.1 默认网络
- **Ethereum Mainnet**：以太坊主网
- **Goerli Testnet**：测试网（已废弃）
- **Sepolia Testnet**：当前测试网
- **Localhost 8545**：本地网络

### 5.2 添加自定义网络
**步骤：**
1. 点击网络下拉菜单
2. 选择"Add network"
3. 填写网络信息：
   - Network Name：网络名称
   - RPC URL：RPC地址
   - Chain ID：链ID
   - Currency Symbol：代币符号
   - Block Explorer URL：区块浏览器

### 5.3 常用测试网配置
**Sepolia测试网：**
- Network Name：Sepolia test network
- RPC URL：https://sepolia.infura.io/v3/YOUR_PROJECT_ID
- Chain ID：11155111
- Currency Symbol：ETH
- Block Explorer URL：https://sepolia.etherscan.io

---

## 6. 账户管理

### 6.1 创建新账户
**步骤：**
1. 点击账户头像
2. 选择"Create Account"
3. 输入账户名称
4. 点击"Create"

### 6.2 导入账户
**步骤：**
1. 点击账户头像
2. 选择"Import Account"
3. 选择导入方式（私钥或JSON文件）
4. 完成导入

### 6.3 账户设置
**功能：**
- 重命名账户
- 导出私钥
- 导出账户
- 删除账户

---

## 7. 交易操作

### 7.1 发送ETH
**步骤：**
1. 点击"Send"按钮
2. 输入接收地址
3. 输入发送金额
4. 选择Gas费用
5. 确认交易
6. 等待确认

### 7.2 接收ETH
**步骤：**
1. 点击"Receive"按钮
2. 复制钱包地址
3. 分享给发送方
4. 等待到账

### 7.3 Gas费用设置
**选项：**
- **Slow**：慢速，费用低
- **Standard**：标准，费用中等
- **Fast**：快速，费用高
- **Custom**：自定义费用

---

## 8. 代币管理

### 8.1 添加代币
**步骤：**
1. 点击"Import tokens"
2. 输入代币合约地址
3. 确认代币信息
4. 点击"Add Custom Token"

### 8.2 常见代币
- **USDT**：0xdAC17F958D2ee523a2206206994597C13D831ec7
- **USDC**：0xA0b86a33E6441b8c4C8C0C8C0C8C0C8C0C8C0C8C
- **DAI**：0x6B175474E89094C44Da98b954EedeAC495271d0F

### 8.3 代币操作
- 查看余额
- 发送代币
- 接收代币
- 移除代币

---

## 9. 安全设置

### 9.1 密码管理
- 使用强密码
- 定期更换密码
- 不要重复使用密码

### 9.2 助记词安全
- 离线存储
- 不要截图
- 不要分享
- 备份多份

### 9.3 交易安全
- 验证接收地址
- 检查交易金额
- 确认Gas费用
- 使用硬件钱包

---

## 10. 常见问题

### Q1: 忘记密码怎么办？
A: 使用助记词重新导入钱包，设置新密码。

### Q2: 助记词丢失怎么办？
A: 如果助记词丢失，无法恢复钱包，资产将永久丢失。

### Q3: 交易一直pending怎么办？
A: 可以尝试提高Gas费用或取消交易重新发送。

### Q4: 如何降低Gas费用？
A: 选择网络不拥堵的时间，或使用Layer 2解决方案。

### Q5: 如何连接硬件钱包？
A: 在MetaMask中选择"Connect Hardware Wallet"，按照提示操作。

---

## 11. 最佳实践

### 11.1 安全建议
- 使用硬件钱包存储大额资金
- 定期备份助记词
- 不要在公共网络使用
- 验证网站真实性

### 11.2 使用建议
- 测试网练习
- 小额测试
- 了解Gas机制
- 关注网络状态

### 11.3 故障排除
- 清除浏览器缓存
- 重新安装扩展
- 检查网络连接
- 联系技术支持

---

**记住：MetaMask是进入Web3世界的门户，安全使用最重要！** 🚀

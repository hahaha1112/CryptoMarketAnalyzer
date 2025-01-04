# CryptoMarketAnalyzer

一个基于Python的加密货币市场分析机器人，用于实时监控和分析加密货币市场数据。

## 功能特点

- 实时监控多个交易对(BTC/USDT, ETH/USDT等)
- 自动分析市场深度数据
- 智能识别市场趋势和交易信号
- 支持多种技术分析指标
- 可配置的风险管理参数
- 详细的日志记录系统

## 安装要求

```bash
pip install -r requirements.txt
```

## 配置说明

在 `config/config.yaml` 中配置:

- API密钥和密码
- 交易对列表
- 市场分析参数
- 日志设置
- 代理设置(可选)

## 快速开始

1. 克隆项目
```bash
git clone https://github.com/yourusername/CryptoMarketAnalyzer.git
cd CryptoMarketAnalyzer
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置参数
```bash
cp config/config.yaml.example config/config.yaml
# 编辑 config.yaml 添加你的配置
```

4. 运行程序
```bash
python main.py
```

## 项目结构

```
CryptoMarketAnalyzer/
├── config/
│   └── config.yaml     # 配置文件
├── src/
│   ├── analyzers/      # 市场分析模块
│   ├── exchange/       # 交易所接口
│   ├── models/         # 数据模型
│   ├── utils/          # 工具函数
│   └── bot.py         # 主程序逻辑
├── main.py            # 入口文件
├── requirements.txt   # 项目依赖
└── README.md         # 项目说明
```

## 注意事项

- 请确保在使用前正确配置API密钥
- 建议先在测试网络中测试
- 注意风险控制，合理设置交易参数

## License

MIT License

## 贡献指南

欢迎提交Issue和Pull Request来帮助改进项目。

## 免责声明

本项目仅供学习和研究使用，不构成投资建议。使用本项目进行交易造成的任何损失由使用者自行承担。

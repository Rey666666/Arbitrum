---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

---

# {你的名字}

1. 自我介绍 小白rey
2. 你认为你会完成本次残酷学习吗？yes

## Notes

<!-- Content_START -->

### 2024.12.10
Refer:https://docs.arbitrum.io/welcome/arbitrum-gentle-introduction
一.ARB的使命，特点及原理
1.使命
  以太坊的设计中，TPS的吞吐量相对较低，原因主要涉及到安全性、去中心化和可扩展性三个核心的区块链设计原则。传统的以太坊主链无法满足大规模应用（如去中心化金融 DeFi、大量的 NFT 操作等）对交易吞吐量的需求。因此，Layer 2 解决方案被提出。
2.特点
  （1）.Arbitrum Rollup：Arbitrum在 Layer 2 上处理交易，但这些交易的状态更新会定期提交到以太坊主链。即假设交易是有效的，除非有人提出挑战。即使存在错误或欺诈行为，也可以通过挑战期解决问题，确保系统的最终正确性。与L1不同，我们不要求以太坊节点处理每笔 Arbitrum 交易；相反，以太坊对 Arbitrum 采取“在被证明有罪之前无罪”的态度。第 1 层最初“乐观地假设”Arbitrum 上的活动遵循正确的规则。如果发生违规行为（即有人声称“现在我拥有了你所有的钱”），则可以在 L1 上对此索赔提出异议；欺诈将被证明，无效索赔将被忽略，恶意方将受到经济处罚。
  （2）.高吞吐量和低延迟：Arbitrum 交易是分批提交到 L1 上的；通常，单个批次（在单个 L1 交易中提交）将包含数百个 L2 交易。分批处理摊销了与 L1 交互的间接成本，因此与一次发布单个交易相比，可以节省大量成本。此外，交易数据以压缩形式发布到 L1 上（并且仅在 L2 环境中解压缩），从而进一步最大限度地减少了交易对 L1 的占用空间。
  （3）.较低的交易费用：Arbitrum 可以将大量的交易打包成一个批次提交到主链，节省了计算资源，因此交易成本大幅下降。
  （4）.兼容以太坊：Arbitrum 具有很高的兼容性，可以运行与以太坊主链完全相同的智能合约，甚至开发者可以使用现有的 Solidity 代码。这样，现有的以太坊应用可以通过简单的迁移或连接到 Arbitrum，获得更高的吞吐量和更低的交易费用，而不需要重写代码或改变架构。
  （5）.保留了以太坊去中心化的特性及安全性：输入 Arbitrum Rollup 链的数据（即用户的交易数据）直接发布在以太坊上。因此，只要以太坊本身安全运行，任何感兴趣的人都可以看到 Arbitrum 中 发生的事情，并有能力检测和证明欺诈行为。

### 2024.12.10

<!-- Content_END -->

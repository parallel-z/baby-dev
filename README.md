一：学习资料列表与阅读重点
     1.白皮书  重点梳理 **$x \cdot y = k$** 公式在包含 0.3% 手续费后的实际运作方式，以及 LP 份额的计算原则
     对 UniswapV2Pair.sol、UniswapV2Factory.sol、UniswapV2Router02.sol 进行了学习
二：Week 4 实现计划
    核心 Pair：优先实现 Math Library 和 Pair 合约。确保 Mint/Burn/Swap 逻辑正确，特别是 K 值维护和 LP 份额的计算。
    Factory：实现  Factory 合约 ，利用  create2   模 式部署和管理 Pair 实例
    Router ：编写  Router 合约 ，实现用户接口（如  addLiquidity ）并负责处理交易中的 滑点保护 和 路径路由 逻辑。
     
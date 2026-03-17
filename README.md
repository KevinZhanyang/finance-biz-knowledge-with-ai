# finance-biz-knowledge

中国金融业务知识库 — 记录金融行业的业务运转逻辑、机构协作机制和领域术语。

## 目录结构

```
├── fund/                  # 基金行业
│   ├── overview.md            # 基金行业概览（产品类型、生命周期）
│   ├── sales/                 # 基金销售
│   │   ├── direct-sales.md        # 直销（基金公司直销）
│   │   ├── distribution.md        # 代销（银行、券商、第三方代销）
│   │   ├── subscription.md        # 认购/申购/赎回流程
│   │   └── fee-structure.md       # 费率结构（申购费、管理费、托管费等）
│   ├── registration/          # 登记结算
│   │   ├── ta-system.md           # TA 系统（转让代理）
│   │   ├── clearing.md            # 清算交收
│   │   └── day-end.md             # 日终处理（日终跑批、估值、份额确认）
│   ├── valuation/             # 估值与核算
│   │   ├── nav-calculation.md     # 净值计算
│   │   └── accounting.md          # 基金会计
│   └── custody.md             # 托管业务
│
├── institution/           # 机构与角色
│   ├── fund-company.md        # 基金管理公司（公募/私募）
│   ├── distributor.md         # 销售机构（银行、券商、独立销售机构）
│   ├── custodian.md           # 托管银行
│   ├── ta-agent.md            # 注册登记机构（中登/基金公司自建TA）
│   ├── csdc.md                # 中国结算（中登公司）
│   ├── csrc.md                # 证监会及监管体系
│   └── exchange.md            # 交易所（场内基金 ETF/LOF）
│
├── research/              # 投研体系
│   ├── investment-process.md  # 投研流程（研究→决策→交易→归因）
│   ├── asset-allocation.md    # 大类资产配置
│   ├── risk-management.md     # 风控体系
│   └── compliance.md          # 合规管理
│
├── insurance/             # 保险行业
│   ├── overview.md            # 保险行业概览
│   ├── product-types.md       # 产品类型（寿险、财险、健康险等）
│   ├── distribution.md        # 销售渠道（代理人、银保、经纪）
│   └── operations.md          # 运营机制（核保、理赔、精算）
│
├── integration/           # 系统对接与数据交换
│   ├── protocols.md           # 行业接口协议（Open/恒生、深证通等）
│   ├── data-formats.md        # 数据文件格式（TXT 接口文件、电子对账）
│   └── message-flow.md        # 业务报文流转
│
├── glossary/              # 术语表
│   ├── fund-terms.md          # 基金术语
│   ├── trading-terms.md       # 交易结算术语
│   └── general-terms.md       # 通用金融术语
│
└── README.md
```

## 内容原则

- **重业务逻辑**：记录"行业怎么运转的"，而非金融理论或投资策略
- **重流程对接**：关注机构间如何协作、数据如何流转
- **实操导向**：结合实际业务场景，附带流程图和示例
- **术语先行**：每个领域先梳理核心术语，再展开业务流程

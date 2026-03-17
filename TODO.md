# TODO List

## 基金行业 fund/

- [x] fund/overview.md — 基金行业概览（分类、生命周期）
- [x] fund/sales/distribution.md — 代销流程、收入模式、数据交换
- [ ] fund/sales/direct-sales.md — 直销模式、机构客户直销通道
- [ ] fund/sales/subscription.md — 认购/申购/赎回流程详解（未知价法、确认时效、巨额赎回）
- [ ] fund/sales/fee-structure.md — 费率结构（申购费分档、管理费、托管费、C类费率对比）
- [x] fund/registration/day-end.md — 日终处理全流程
- [ ] fund/registration/ta-system.md — TA 系统详解（自建TA vs 中登TA、账户体系、数据交互）
- [ ] fund/registration/clearing.md — 清算交收（资金划付流程、清算文件、多级清算）
- [ ] fund/valuation/nav-calculation.md — 净值计算（估值方法、摊余成本法 vs 市值法）
- [ ] fund/valuation/accounting.md — 基金会计（科目设置、费用计提、收益分配）
- [ ] fund/custody.md — 托管业务（托管职责、托管费、净值复核流程）

## 机构与角色 institution/

- [ ] institution/fund-company.md — 基金管理公司（组织架构、牌照、公募vs私募）
- [ ] institution/distributor.md — 销售机构（三大渠道对比、牌照资质、适当性管理）
- [ ] institution/custodian.md — 托管银行（主要托管行、职责、与基金公司的关系）
- [ ] institution/ta-agent.md — 注册登记机构（中登TA vs 基金公司TA）
- [ ] institution/csdc.md — 中国结算（中登公司职能、在基金行业的角色）
- [ ] institution/csrc.md — 证监会及监管体系（监管架构、法规体系）
- [ ] institution/exchange.md — 交易所（场内基金机制、ETF/LOF交易）

## 投研体系 research/

- [ ] research/investment-process.md — 投研流程（研究→决策→交易→归因）
- [ ] research/asset-allocation.md — 大类资产配置
- [ ] research/risk-management.md — 风控体系
- [ ] research/compliance.md — 合规管理

## 保险行业 insurance/

- [ ] insurance/overview.md — 保险行业概览（行业格局、监管体系）
- [ ] insurance/product-types.md — 产品类型（寿险、财险、健康险、年金险）
- [ ] insurance/distribution.md — 销售渠道（代理人、银保、经纪、互联网）
- [ ] insurance/operations.md — 运营机制（核保、理赔、精算、再保险）

## 系统对接 integration/

- [ ] integration/protocols.md — 行业接口协议（Open协议、恒生接口、深证通、中登接口）
- [ ] integration/data-formats.md — 数据文件格式（TXT接口文件、字段定义、编码规范）
- [ ] integration/message-flow.md — 业务报文流转（申购/赎回全链路数据流）

## 术语表 glossary/

- [x] glossary/fund-terms.md — 基金术语（60+术语）
- [ ] glossary/trading-terms.md — 交易结算术语
- [ ] glossary/general-terms.md — 通用金融术语

---

## 优先级建议

**P0 — 基金核心流程闭环**
1. fund/sales/subscription.md（申购赎回是最基础的业务流程）
2. fund/registration/ta-system.md（TA 是连接销售和结算的中枢）
3. fund/registration/clearing.md（清算交收完成资金闭环）

**P1 — 机构全景**
4. institution/fund-company.md
5. institution/distributor.md
6. institution/csdc.md

**P2 — 系统对接（技术视角）**
7. integration/protocols.md
8. integration/data-formats.md
9. integration/message-flow.md

**P3 — 扩展领域**
10. research/ 投研体系
11. insurance/ 保险行业
12. glossary/ 补充术语表

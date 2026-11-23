# 跨境包裹时效分布与改道承诺评估

物流资料包含合成的包裹件组、扫描事件、路线版本和状态代码。

项目中的记录和字段约定均为本地合成资料，不能代表真实个人、机构或交易。`fixtures/schema.json` 说明资料字段，`fixtures/records.json` 提供少量可复现的交接记录。

使用 Node.js 22.23.4。首次准备可执行 `npm ci --ignore-scripts --offline`，检查资料使用 `npm run check:materials`，运行构建检查使用 `npm run build`，运行测试使用 `npm test`。项目只依赖 Node.js 标准库。


## 业务资料

`fixtures/domain-materials.json` 收录跨境件组 SLA、生存时效与备用运力相关的字段约定及小型演练资料。资料用于练习业务记录的含义与关联，所有名称、状态和数值均为本地合成。

使用 Node.js 22.23.4。执行 `npm test` 检查资料及现有入口，执行 `npm run build` 验证项目脚本，执行 `npm run check:materials` 检查通用资料入口。

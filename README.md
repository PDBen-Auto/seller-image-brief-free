# 卖家图片策划 Free

把商品资料与有权使用的评论，整理成最多三张可交给摄影师／设计师执行的商品图任务单。每图包含买家问题、FABE、画面、短文案、拍摄与验收，未知证据单列。输出是策划，不是成品照片。

**[打开Free说明页与案例](https://pdben-auto.github.io/seller-image-brief-free/)** · **[本地页面源文件](docs/index.html)** · **[安装与使用](INSTALL.md)** · **[Free使用与分发说明](FREE-LICENSE.md)**

这是卖家图片策划Free的项目说明与分发仓库：[GitHub仓库](https://github.com/PDBen-Auto/seller-image-brief-free)。Free说明页已通过Pages构建与匿名HTTP读回：[在线说明页](https://pdben-auto.github.io/seller-image-brief-free/)。源文件在docs目录，仍可直接本地打开。公开状态可能随服务变化，网站可访问不等于索引收录、实际宿主运行或成交。Red Skill口令和购买入口未配置。

## 适用任务 / English summary

用于电商商品图策划、FABE卖点梳理、产品拍摄brief与摄影／设计交接；汽车改装件与饰品是当前合成教学案例。

Seller Image Brief Free is an Agent Skill for e-commerce product-image planning. It turns supplied product facts and permitted reviews into up to three complete briefs with FABE reasoning, copy, composition, shooting requirements, acceptance checks, and evidence gaps. Bring your own Agent and model; model costs are yours. It creates plans, not product photos. Free under custom terms, not an open-source license.

## 先看交付长什么样

- 主案例：[尾门折叠桌输入](docs/examples/automotive-input.md) → [三张完整策划输出](docs/examples/automotive-output.md)。汽车三图是单独生成的AI概念，非实拍、非安装或适配证明；不是Free自动生图或汽车实际Agent运行证据。
- 次级案例：[饰品任务与证据边界](docs/examples/jewelry.md)。五张图卡的模拟规格只属于教学案例，不是真实SKU或客户效果。
- 页面可以按图查看FABE、布局、动作与验收，并取得完整两文件。没有评论时不会编占比，没有实测时不写性能。

## Free与Pro的真实差异

|项目|Free|Pro（本仓库不提供源码）|
|---|---|---|
|完整结果|一个商品最多三张完整图卡，不为凑数降低质量|按任务和证据安排整款图序与取舍|
|执行深度|每图问题、FABE、布局、短文案、拍摄、证据与验收|逐帧拍摄、素材缺口与证据矩阵、批次／命名及摄影设计交接|
|文件能力|默认对话；按请求输出Markdown|提供HTML／CSV／JSON等导出与交接工具，依赖与输入契约另核|
|边界|不抓评论、不生图、不验证事实、不代发布|同样不把计划变实测，不含生图摄影检测或效果承诺|
|选择|免费且完整，升级自愿可关闭|已确认价19.9元人民币一次买断，持续使用所购当前版本；当前无购买入口|

Pro附完整安装／使用说明；购买后7天协助安装和首次运行，工作日48小时内首次回应，不保证解决时限。不含代做、无限答疑、终身免费升级或模型额度。支持期不一概免除包缺陷或适用渠道退款义务。详见[条款与FAQ](docs/terms.md)。

## 运行条件与安装

自备能读取Skill与文本／CSV的Agent和可用模型，费用自担；模型如何处理／留存资料以实际服务条款为准。Free本身不需Python或密钥，不含安装器。只把 `skills/seller-image-brief-free` 完整两文件复制到已确认的Skill目录；已有同名目录先停止。[详细安装、调用、卸载、异常恢复](INSTALL.md)。

可在新对话用 `$seller-image-brief-free` 显式调用，附真实商品资料，评论和证明可选；说“不推荐升级”即可关闭推荐。图卡完整交付不以升级为条件。Skill只是Agent可读取的指令，宿主需实际识别或明确手动加载，不能保证所有宿主自动发现。

## 文件与许可

`skills/seller-image-brief-free` 仅含经核对的SKILL.md及references/upgrade.md。`docs/downloads` 是同两文件的原字节镜像，用于独立静态网站下载，不包含Pro。Free中保留的“Pro筹备、无价格链接”是该固定运行版本的保守提示；本页说明当前已确认的19.9元条件，但实际购买入口仍未配置，未改动运行文件。

免费使用不等于开源：见[Free使用与分发说明](FREE-LICENSE.md)，不擅用MIT等许可。可将生成策划用于自己或客户商用、为自用修改；原包不得转售或公开再分发，版权不转让。输入、素材、模型及平台权利仍须分别核实。[案例来源与限制](docs/asset-notes.md)。

## 反馈与公开状态

欢迎最小脱敏报错或使用建议：宿主／系统、文件SHA、失败阶段、输入概要、预期与实际及已试动作。不要提交密码、密钥或顾客资料。反馈入口为[本仓库Issues](https://github.com/PDBen-Auto/seller-image-brief-free/issues)；请只提交最小脱敏信息，不建立收集表或遥测。

仓库／Free说明页的发布与核验边界见[PUBLISHING.md](PUBLISHING.md)。项目文档页只用于免费说明、案例和安装下载，购买及支付入口保持关闭。访问、下载、首次运行、购买及退款均无本仓库的真实统计，不展示虚构用户、收入或转化。

# 卖家图片策划 Free

[简体中文](README.zh-CN.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português](README.pt.md)

按用户明确指定的语言输出，否则跟随请求语言。保留命令、技能 ID、JSON 键、枚举值、单位和来源原文；翻译与原文分开，不通过语言推定国家、币种或司法辖区。先读取完整规范中与任务相关的详细引用，执行原有校验和授权要求。

## 安装与使用

下载或克隆仓库，将下列技能目录连同其 references、scripts、assets 等现有依赖一起放入宿主的技能目录。保留目录名和 SKILL.md；仅更换说明语言无需重复安装。安装命令供用户自行选择，不表示已安装或启用。

```sh
git clone https://github.com/PDBen-Auto/seller-image-brief-free.git
```

## 卖家图片策划 Free

`seller-image-brief-free`

用提供的产品事实与评论按FABE策划最多三张各司其职的商品图，交付可执行任务单而非成图。

技能目录: `skills/seller-image-brief-free`

**实现依据与依赖**

能读文本/CSV/表格的Agent与模型、用户产品资料；核心不需外部账号/API/网络，模型费用由宿主环境承担；可公开声明还需证据与当前平台规则。

**输入**

必需产品/类别/版本/市场；可选获准评论、照片/尺寸/测试、语言和画幅；最多三图。用户可关闭升级提示，可用时SELLER_IMAGE_NO_UPSELL=1也关闭。

**输出**

聊天或指定Markdown：证据范围、买家问题、最多三图卡，逐图F/A/B/E、布局、角度、短文案、证据状态及验收，另列未决声明。

[执行流程 · 边界与停止条件 · 示例请求](skills/seller-image-brief-free/references/i18n/zh-CN.md)

> 请使用 `$seller-image-brief-free` — 隔板收纳盒可用产品事实支持分区使用图；没有测试不能称防水；用简体中文输出，保留证据、未知项与操作边界。

## 语言覆盖与验证

这是本技能的本地化操作指南，覆盖用途、依赖、输入输出、步骤、示例及边界，不是全部引用文档的逐句翻译。详细技术引用、历史案例、脚本错误、示例网页及图片保留原文；助手可按请求解释它们。本次文档经过结构、链接和关键约束核对，尚无逐语种母语人工审校。

交付前逐项核对输入、证据、缺失值、输出文件和原有完成标准；未执行的步骤标为未验证，不把脚本退出成功当业务成功。

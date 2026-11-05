# Free 安装、首次使用与卸载

先自备能加载Skill文件的Agent和可用模型。Free运行只有两个Markdown文件，不需要本仓库安装器、Python、API密钥或新账号；模型费用和宿主的数据处理条款另核。其他Agent目录机制不同，下面Codex路径只是明确示例，不承诺所有环境兼容。

## 取得完整两文件

本仓库根目录 `skills/seller-image-brief-free` 即完整运行目录。若通过仓库下载整个目录，保留 `SKILL.md` 与 `references/upgrade.md` 的层级；若从[介绍页](docs/index.html#install)分别下载，则在本机新建同名目录和references子目录，按下方结构放置。不是把两文件平铺或另存成HTML。

```text
seller-image-brief-free/
  SKILL.md
  references/
    upgrade.md
```

SHA256（字节改变需重新核对）：

```text
53b6b67b001262680efade6f5b1398b812157423d25816fa0ecd28871449f7fc  SKILL.md
296b2283f04dfe90fb09c9b56c7e4f629430a9e723671454d875c67d2970ab43  references/upgrade.md
```

## 安装到你确认的目录

Codex常见目录是用户的 `.codex/skills`；设置了 `CODEX_HOME` 时通常为其 `skills` 子目录。先核宿主当前设置、输出的实际路径与权限；不猜路径、不覆盖同名文件。关闭或刷新Skill列表的方式按宿主实际支持操作。

最直接方式：把完整的 `seller-image-brief-free` 文件夹复制到已确认的Skill目录。已有同名目录就停止，先备份并核版本，不合并、不覆盖。不要上传模型密钥或浏览器资料。

Windows PowerShell可从**本仓库根目录**分两段执行。第一段仅计算并显示路径（自定义宿主请改成已核目录）：

```powershell
$source = Join-Path (Get-Location) 'skills/seller-image-brief-free'
$skillsRoot = if ($env:CODEX_HOME) { Join-Path $env:CODEX_HOME 'skills' } else { Join-Path $env:USERPROFILE '.codex/skills' }
$target = Join-Path $skillsRoot 'seller-image-brief-free'
$source
$target
```

确认路径正确再执行第二段；目录存在即拒绝覆盖：

```powershell
if (!(Test-Path -LiteralPath (Join-Path $source 'SKILL.md') -PathType Leaf)) { throw '缺少SKILL.md，请回到仓库根目录' }
if (!(Test-Path -LiteralPath (Join-Path $source 'references/upgrade.md') -PathType Leaf)) { throw '缺少references/upgrade.md' }
if (Test-Path -LiteralPath $target) { throw '目标已存在，请先备份并核对版本；本步骤不覆盖' }
New-Item -ItemType Directory -Force -Path $skillsRoot | Out-Null
Copy-Item -LiteralPath $source -Destination $target -Recurse
```

## 显式调用与成功证据

刷新Skill列表或重开宿主，在新对话显式调用，并贴你有权使用的商品资料：

```text
使用 $seller-image-brief-free，根据以下product、reviews（可选）、proof（可选）和market_and_format，完成最多三张职责不同的完整商品图策划。每图含买家问题、FABE、布局、短文案、拍摄和验收，未知单列，不编事实、不发布。不推荐升级。
```

成功应分别确认：两文件完整复制 → 宿主实际识别／显式加载该Skill → 你自己的任务得到可读策划。文件复制不等于自动发现或任务成功。本候选安装检查只做隔离目录复制，不是全新机器或真实买家模型测试。

找不到Skill时先核路径、文件名、层级与实际宿主机制，刷新后仍失败保留脱敏报错；可手动将SKILL.md及其引用交给Agent作临时加载，并明确记录为手动加载，不能称自动安装成功。不要重复复制到猜测目录。

输入不完整时提供可读文本／CSV，缺失证据单列。发布商品图需核真实样品和当前平台规则；Free不抓评论、不生图、不测性能、不代发布。升级提示可在对话中说“关闭升级提示”，不影响Free任务；环境允许时可仅将SELLER_IMAGE_NO_UPSELL设为1，但不是必需安装步骤。

## 卸载、恢复与反馈

退出正在使用该Skill的任务；核对安装目录，备份自己的修改后，只移走该目录中的 `seller-image-brief-free` 文件夹，再按宿主支持方式刷新。保留自己的输入和输出，不删除整个skills目录，也不更动其他Skill。恢复时将备份完整放回，仍须核同名冲突。

反馈附：宿主／系统、两文件版本或SHA、失败阶段（复制／发现／调用／输出）、最小脱敏输入、预期与实际、报错和已试动作。不要附账号密码、密钥、订单隐私或顾客资料。当前没有公开反馈URL时，使用你已核实的作者联系渠道；后续公开仓库配置了Issues后才从其真实入口提交。

使用前阅读[Free说明](FREE-LICENSE.md)。[合成输入](docs/examples/automotive-input.md)与[可读输出](docs/examples/automotive-output.md)可用于理解格式，不能继承它们的商品事实。

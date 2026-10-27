# 什么！我的大学生活怎么会被五个女生霸占 · galgame 插件图包

角色卡《什么！我的大学生活怎么会被五个女生霸占》的远程图包，给 [galgame 界面插件](https://github.com/bigmalove/galgame) 用。图片由 NovelAI Diffusion V5 生成，全部健全向。

| 文件夹 | 内容 | 数量 |
| --- | --- | --- |
| `sprites/` | 立绘（透明底），五人 × 日常/私服/睡衣 × 五种表情 | 75 |
| `backgrounds/` | 背景，文件名就是场景名 | 51 |
| CG | 在另一个仓库 [huanghuayu123/xieka-galgame-cg](https://github.com/huanghuayu123/xieka-galgame-cg)（jsDelivr 不加速超过 150 MB 的仓库，所以分开放） | 563 |

## 立绘表情

文件名里的表情用插件内置的名字：默认、微笑、害羞、难过、生气。插件找不到 AI 写的表情时会改用“默认”，所以 AI 写了“惊讶”“思考”之类没有对应图的表情，也会显示“默认”那张。

索引里同一张图还登记了几个别名，一共 150 条：

| 图 | 索引里能用的表情名 |
| --- | --- |
| 默认 | 默认、平静 |
| 微笑 | 微笑、开心、大笑、搞怪 |
| 难过 | 难过、失落 |
| 害羞 | 害羞 |
| 生气 | 生气 |

“平静”“开心”“失落”是旧版图包的表情名，留着是为了让旧聊天里的台词也能找到立绘。

## 在插件里使用

推荐用插件资源管理器的“导入远程链接JSON”，选本仓库的 `remote_assets.json`。也可以在远程地址里填：

- 仓库地址：`https://github.com/huanghuayu123/xieka-galgame-assets`（插件会自动换成 jsDelivr 加速地址）
- 索引文件：`https://cdn.jsdelivr.net/gh/huanghuayu123/xieka-galgame-assets@main/remote_assets.json`

`remote_assets.json` 里的图片网址指向奶昔图床（img.naixiai.cn）；图床用不了时改用 `remote_assets-jsdelivr.json`，图片从本仓库和 CG 仓库经 jsDelivr 加载。两个索引都按插件“导出远程资源包”的格式写成，图片在用到时才从网上加载。

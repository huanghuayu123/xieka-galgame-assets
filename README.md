# 什么！我的大学生活怎么会被五个女生霸占 · galgame 插件图包

角色卡《什么！我的大学生活怎么会被五个女生霸占》的远程图包，给 [galgame 界面插件](https://github.com/bigmalove/galgame) 用。图片由 NovelAI Diffusion V5 生成，全部健全向。

| 文件夹 | 内容 | 数量 |
| --- | --- | --- |
| `sprites/` | 立绘（透明底），五人 × 日常/私服/睡衣 × 五种表情 | 75 |
| `backgrounds/` | 背景，文件名就是场景名 | 51 |
| CG | 在另一个仓库 [huanghuayu123/xieka-galgame-cg](https://github.com/huanghuayu123/xieka-galgame-cg)（jsDelivr 不加速超过 150 MB 的仓库，所以分开放） | 563 |

## 在插件里使用

打开插件的资源管理器，在远程地址里填下面任意一个：

- 仓库地址：`https://github.com/huanghuayu123/xieka-galgame-assets`（插件会自动换成 jsDelivr 加速地址）
- 索引文件：`https://cdn.jsdelivr.net/gh/huanghuayu123/xieka-galgame-assets@main/remote_assets.json`

现在 `remote_assets.json` 里的图片网址都指向奶昔图床（img.naixiai.cn）。图床用不了时，可以改填 `remote_assets-jsdelivr.json`，图片从本仓库和 CG 仓库经 jsDelivr 加载。

两个索引都按插件“导出远程资源包”的格式写成，列出了全部立绘、背景和 CG 的网址（CG 指向另一个仓库）；图片在用到时才从网上加载。

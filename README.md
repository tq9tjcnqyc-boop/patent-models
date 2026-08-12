# patent-models

专利3D模型存档（Rhino .3dm），文件名 = 专利标题。

## 存放规则

- `models/` 目录：≤100MB 的模型，git 直接管理
- 大模型（>100MB）：走 Release 附件，链接在对应文章的「模型下载」行

## 链接格式

- jsDelivr CDN（≤20MB）：`https://cdn.jsdelivr.net/gh/tq9tjcnqyc-boop/patent-models@main/models/<file>`
- GitHub 直链（20~100MB）：`https://github.com/tq9tjcnqyc-boop/patent-models/raw/main/models/<file>`
- Release 附件（>100MB）：`https://github.com/tq9tjcnqyc-boop/patent-models/releases/download/<tag>/<file>`

⚠️ 文件内容变更必须改文件名（加 -v2）绕 jsDelivr 永久缓存。

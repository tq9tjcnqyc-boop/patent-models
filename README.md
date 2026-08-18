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

## 大模型附件命名（2026-08-17 起）

GitHub Release 附件不支持中文文件名（上传接口会自动改名），因此 >100MB 的模型以 `model-NN.3dm` 命名上传，中文标题与附件的对应关系见 [large-models-mapping.csv](large-models-mapping.csv)。

下载地址：`https://github.com/tq9tjcnqyc-boop/patent-models/releases/download/large-models-v1/model-NN.3dm`

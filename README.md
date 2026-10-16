# xiangtong-releases

「想通」（逻辑思维训练 App）已发布的题包。App 的“在线检查更新”只读取这里的 `manifest.json` 和它列出的文件，不上传任何数据。

- `manifest.json`：更新清单（格式见源码仓库 Technical Spec 10.12），由 `tools/publish_manifest.py` 生成，不手改。
- `packs/<PACK_ID>/<N>.json`：已发布的题包，发布后不再修改。

这里不放代码和文档。暂不发布安装包。

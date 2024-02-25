# Autumn

## 描述

Autumn是负责存储文件和附件的微服务。

**特点：**

- 本地或在S3上保存文件。
- 支持带有不同文件要求的不同标签/桶。
- 从JPEG和视频文件中剥离元数据。

## 技术栈

- [Actix-Web](https://actix.rs/)
- [rust-s3](https://github.com/durch/rust-s3)
- [MongoDB](https://mongodb.com/)

## 资源

### Revolt

- [Revolt 项目看板](https://github.com/revoltchat/revolt/discussions)（在此提交功能请求）
- [Revolt 测试者服务器](https://app.revolt.chat/invite/Testers)
- [贡献指南](https://developers.revolt.chat/contributing)

## 命令行指令

| 命令               | 描述                                                                                      |
| ------------------ | ----------------------------------------------------------------------------------------- |
| `cargo build`      | 构建/编译Autumn。                                                                          |
| `cargo run`        | 运行Autumn。                                                                               |
| `cargo fmt`        | 格式化Autumn。不建议用于PR，以避免意外格式化未格式化的文件。                                |

## 贡献

贡献指南位于 [developers.revolt.chat/contributing](https://developers.revolt.chat/contributing)。
请注意，一个拉取请求应该只处理一个问题，以便我们可以快速审查。

## 许可证

Autumn根据[GNU Affero 通用公共许可证 v3.0](https://github.com/revoltchat/autumn/blob/master/LICENSE)授权。

## 待办事项

- 使EXIF剥离可选，但默认开启。（?exif=false）

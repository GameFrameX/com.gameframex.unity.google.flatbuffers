
# 非常强大的序列化和反序列化库(主要用来加载配置表[lazy+offset])

**FlatBuffers** is a cross platform serialization library architected for
maximum memory efficiency. It allows you to directly access serialized data without parsing/unpacking it first, while still having great forwards/backwards compatibility.

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。


# 使用方式(三种方式)
1. 直接在 `manifest.json` 文件中添加以下内容
   ```json
      {"com.google.flatbuffers": "https://github.com/AlianBlank/com.google.flatbuffers.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/com.google.flatbuffers.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加 `Packages` 的支持
2. 增加 `link.xml` 的支持


# 当前版本 `23.5.26`

# 同步版本

https://github.com/google/flatbuffers/commit/129ef422e8a4e89d87a7216a865602673a6d0bf3

# 使用文档

https://flatbuffers.dev/
# hongguo-web 模块

红果短剧站源模块（独立维护版，与上游区分）：播放走网页备用线路接口。

## 安装

应用内 模块页 → 手动 → 输入下载地址：

```
https://github.com/StupidYan/hgmodule/releases/latest/download/hongguo-web.zip
```

或镜像：

```
https://cdn.jsdelivr.net/gh/StupidYan/hgmodule@main/hongguo-web.zip
```

## 更新记录

- v1.0.9（2026-11-25）：网页取流改为直接调用受保护播放备用接口，跳过易被 404 的播放页校验；模块身份改为 hongguo-web 与上游区分
- v1.0.8（2026-11-25）：网页取流改用受保护播放的备用接口（播放页不再内嵌 video_player_info）

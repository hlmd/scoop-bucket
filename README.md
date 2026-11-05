# hlmd 的 Scoop bucket

[redis-insight-chinese](https://github.com/hlmd/redis-insight-chinese)（Redis Insight 桌面端非官方中文本地化工具，支持简体中文与繁體中文）的 Scoop 安装源。

```powershell
scoop bucket add hlmd https://github.com/hlmd/scoop-bucket
scoop install hlmd/redis-insight-chinese

redis-insight-chinese            # 注入翻译（先完全退出 Redis Insight；繁体加 --lang zh-TW）
redis-insight-chinese restore    # 还原英文
scoop update redis-insight-chinese
```

`bucket/` 下的清单由主仓库发版时的 GitHub Actions 自动更新，请勿手改。

> 非官方项目，与 Redis Ltd. 无关；"Redis" 与 "Redis Insight" 是其商标。

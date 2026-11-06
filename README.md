# hlmd 的 Scoop bucket

hlmd 系列桌面端非官方中文本地化工具的 Scoop 安装源。

| 应用 | 说明 |
|------|------|
| [redis-insight-chinese](https://github.com/hlmd/redis-insight-chinese) | Redis Insight 桌面端非官方中文本地化工具，支持简体中文与繁體中文 |
| [postman-chinese-injector](https://github.com/hlmd/postman-chinese-injector) | Postman 桌面端非官方汉化工具 |

```powershell
scoop bucket add hlmd https://github.com/hlmd/scoop-bucket
```

### redis-insight-chinese

```powershell
scoop install hlmd/redis-insight-chinese

redis-insight-chinese            # 注入翻译（先完全退出 Redis Insight；繁体加 --lang zh-TW）
redis-insight-chinese restore    # 还原英文
scoop update redis-insight-chinese
```

### postman-chinese-injector

```powershell
scoop install hlmd/postman-chinese-injector

postman-chinese-injector              # 注入汉化（先完全退出 Postman）
postman-chinese-injector --restore    # 还原英文
scoop update postman-chinese-injector
```

`bucket/` 下的清单由主仓库发版时的 GitHub Actions 自动更新，请勿手改。

> 非官方项目，与 Redis Ltd.、Postman, Inc. 无关；"Redis"、"Redis Insight"、"Postman" 是各自所有者的商标。

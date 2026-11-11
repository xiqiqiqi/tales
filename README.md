# tales.xiqiqi.com

离奇故事 · 千奇百怪

失踪悬案、骗局伪造、离奇死亡、幽灵船、都市传说。

## 配置

- channel: `tales`
- domain: `tales.xiqiqi.com`
- accent: `#3E5548`
- core: `^0.1.0`

## 部署

- 发布：GitHub Actions（`.github/workflows/deploy.yml`）
- 构建时检出 `oddities-core` 与 `oddities-and-mysteries`
- 自定义域名：见 `CNAME`，并在 Pages 设置中绑定
- 构建由 `oddities-core` 统一执行，本仓不写页面代码

## 目录

```text
site.config.ts   # 站点配置
CNAME            # 自定义域名
package.json     # core 版本
```

页面代码在 `oddities-core`，内容在 `oddities-and-mysteries`。
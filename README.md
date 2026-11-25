# flag-icons

给 FlClash 地区分组用的国家/地区旗帜图标库，文件按 ISO 3166-1 alpha-2 代码命名（例如 `nl` 是荷兰、`jp` 是日本；`xk` 是科索沃，非 ISO 代码，源图库自带）。

## 目录

- `flags/` — 圆形国旗 SVG 原版，共 249 个
- `flags-png/` — 圆形国旗 PNG 版（256×256），由上面的 SVG 转换而来
- `flags-v2/` — v2 版 PNG（256×256）：标准旗面居中裁圆，统一描边
- `flags-v3/` — v3 版 PNG（256×256）：标准旗面圆角方形，统一描边（脚本现用这套）

## 使用（jsDelivr CDN）

```
https://cdn.jsdelivr.net/gh/duan0115/flag-icons@main/flags-v3/nl.png
https://cdn.jsdelivr.net/gh/duan0115/flag-icons@main/flags-png/nl.png
https://cdn.jsdelivr.net/gh/duan0115/flag-icons@main/flags/nl.svg
```

把路径里的文件夹和代码换成需要的那面旗即可。

## 来源与许可

- `flags/` 的 SVG 来自 [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags)（MIT 许可）
- `flags-v2/` 的旗面来自 [lipis/flag-icons](https://github.com/lipis/flag-icons)（MIT 许可），居中裁圆与描边为本仓库自行处理

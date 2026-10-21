# Third-party notices

本文件记录本次 `npm ci` 实际安装的 Vite 及其构建依赖。版本来自已提交的锁文件与安装包元数据。各原始许可／版权文本逐字节复制到 `third_party/licenses/`；Vite 与 Rollup 许可文件包含的内部组件声明也完整保留。

这些第三方声明仅覆盖列出的第三方软件，不为本项目原创游戏源码、像素美术或音乐授予任何项目级许可证。

| 软件 | 锁定安装版本 | 包内声明 | 原始许可／通知文本 |
| --- | --- | --- | --- |
| `@esbuild/darwin-arm64` | 0.21.5 | MIT | 本平台包未附独立文本；[上游 esbuild 原文](third_party/licenses/esbuild/LICENSE.md) |
| `@rollup/rollup-darwin-arm64` | 4.64.12 | MIT | 本平台包未附独立文本；[上游 rollup 原文](third_party/licenses/rollup/LICENSE.md) |
| `@types/estree` | 1.0.9 | MIT | [LICENSE](third_party/licenses/@types/estree/LICENSE) |
| `esbuild` | 0.21.5 | MIT | [LICENSE.md](third_party/licenses/esbuild/LICENSE.md) |
| `fsevents` | 2.3.3 | MIT | [LICENSE](third_party/licenses/fsevents/LICENSE) |
| `nanoid` | 3.3.20 | MIT | [LICENSE](third_party/licenses/nanoid/LICENSE) |
| `picocolors` | 1.1.1 | ISC | [LICENSE](third_party/licenses/picocolors/LICENSE) |
| `postcss` | 8.5.31 | MIT | [LICENSE](third_party/licenses/postcss/LICENSE) |
| `rollup` | 4.64.12 | MIT | [LICENSE.md](third_party/licenses/rollup/LICENSE.md) |
| `source-map-js` | 1.2.2 | BSD-3-Clause | [LICENSE](third_party/licenses/source-map-js/LICENSE) |
| `vite` | 5.4.21 | MIT | [LICENSE.md](third_party/licenses/vite/LICENSE.md) |

## 平台可选依赖

`@esbuild/darwin-arm64` 与 `@rollup/rollup-darwin-arm64` 是本次安装的平台二进制包；它们的包元数据均声明 MIT，但各自的 npm 包未附独立许可文件。上表明确区分该元数据与实际保留的上游原始文本。

锁文件还列有其他平台的可选构建二进制。本机未安装或分发那些平台二进制；`node_modules/` 不纳入公开源码提交。

## 游戏素材

本冻结版本未接入 Kenney Tiny Town、Buch Floating Islands 或其他候选 CC0 图集。原始候选素材、概念图片和模型调用日志未包含在本目录中。

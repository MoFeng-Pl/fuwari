# 壁纸来源

本站随机壁纸功能使用的图片，全部来自 [Picsum](https://picsum.photos/)（图片源为 [Unsplash](https://unsplash.com/)），
遵循 [Unsplash License](https://unsplash.com/license)：可免费用于个人及商业项目，无需署名。
下表仍记录作者与来源，便于日后追溯。

所有图片均已裁切为 **3840 × 2160（4K UHD）** 并转为 WebP。

| 文件 | 主题 | 作者 | 来源 |
| ---- | ---- | ---- | ---- |
| `01-mountain-panorama.webp` | 山脉全景 | Aleksandra Boguslawska | https://picsum.photos/id/231 |
| `02-snow-peaks.webp` | 雪山 | Ryan Schroeder | https://picsum.photos/id/327 |
| `03-coast-cliff.webp` | 海岸线 | Ma. Alejandra | https://picsum.photos/id/374 |
| `04-lake-view.webp` | 湖光山色 | Nick West | https://picsum.photos/id/381 |
| `05-forest-stream.webp` | 森林溪流 | Jerry Adney | https://picsum.photos/id/28 |
| `06-misty-hills.webp` | 雾中山峦 | Forrest Cavale | https://picsum.photos/id/353 |
| `07-sunset-field.webp` | 日落原野 | Kenneth Thewissen | https://picsum.photos/id/110 |
| `08-sea-skyline.webp` | 海上天际线 | Isaak Dury | https://picsum.photos/id/74 |

## 使用方式

把任意图片放进本目录（支持 png / jpg / webp / avif）即可自动参与随机，
无需改代码——`src/layouts/MainGridLayout.astro` 会用 `import.meta.glob` 收集本目录下的所有图片。

建议规格：横构图（16:9）、长边 ≥ 2560px、单张控制在 500KB 以内。

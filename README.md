# 家装 3D 模型资源库

> 收集中文家装场景下**能直接用于网页装修设计器**的免费 3D 模型资源。
> 只做**链接索引 + 授权说明 + 导入方法**，不搬运模型文件本体（避免版权风险）。

**配套工具**：[house-plan-designer](https://github.com/ZWD11/house-plan-designer) —— 2D 户型 + 3D 鸟瞰/漫游 + 家具布置的网页设计器，支持导入 `.glb` 家具模型（带贴图、自动识别米/厘米/毫米单位、导入后可改尺寸旋转）。

---

## 一、怎么用（3 步）

1. 从下面站点下载 **GLB / glTF (.glb)** 格式（优先选 CC0 或 CC BY）
2. 打开设计器 → 工具栏点 **导入 GLB 家具模型** 按钮（`glbBtn`，立方体图标）→ 选择文件（可多选）
3. 模型进平面后：拖动摆位、右侧属性栏改尺寸/旋转、填品牌和价格；3D 视图里实时看效果

> 单位问题不用慌：设计器自动识别米/厘米/毫米。若模型比例不对，直接在属性栏调尺寸。

---

## 二、资源站点（按推荐度排序）

### 🟢 第一梯队：CC0，无署名要求，直接商用

| 站点 | 地址 | 内容 | 格式 | 备注 |
|---|---|---|---|---|
| **Poly Haven** | https://polyhaven.com/models | 高质量 PBR 家具/室内道具：沙发、扶手椅、餐桌、床、边桌、电视、灯具等 | BLEND / FBX / **glTF** | 全部 CC0，无需署名；更新稳定 |
| **Mixos（家具专页）** | https://www.mixos.io/free-models/furniture | 84 个 CC0 家具，带 PBR 贴图，源自 Poly Haven | **GLB**（textured, game-ready） | CC0 1.0，无需署名，网页直接预览 |
| **Poly Pizza** | https://poly.pizza | 10,700+ 低多边形模型，含家具、Apartment 等室内件 | **GLB / GLTF** | 免费模型多；注意逐个看授权（有 CC0 也有 CC BY） |
| **Kenney** | https://kenney.nl/assets/category:3D | Mini 系列家具、Room Kit、城市/室内套件 | GLB / OBJ / FBX | CC0，风格统一（低多边形），适合快速搭场景 |
| **Quaternius** | https://quaternius.com/ | Interiors & Furniture 套装（189 个免费件） | GLB / OBJ | CC0，1 unit = 1 m，可整套下载 |
| **Grab3D** | https://grab3d.com/models/furniture | 单件家具带尺寸标注、在线预览/改色 | **GLB** / FBX / OBJ / USDZ | CC0，无需登录无需署名，标了真实尺寸（米） |

### 🟡 第二梯队：免费但需逐条核对授权

| 站点 | 地址 | 说明 |
|---|---|---|
| Sketchfab · 家具分类 | https://sketchfab.com/categories/furniture-home | 量最大，按 License 筛选「CC0 / CC BY」；下载前看每条的许可证和是否能下 GLB |
| Sketchfab · 家具搜索 | https://sketchfab.com/search?type=models&q=furniture | 同上，关键词搜具体家具 |
| CGTrader · 家具 | https://www.cgtrader.com/3d-models/furniture | 有免费区，质量高；逐条看授权（部分仅个人用） |
| Free3D · 家具 | https://free3d.com/3d-models/furniture | 免费基础款多；注意来源和授权 |
| Blend Swap · 家具 | https://www.blendswap.com/blends?keyword=furniture | 以 .blend 为主，需转 GLB；授权多样需核对 |
| 3D Warehouse | https://3dwarehouse.sketchup.com/ | SketchUp 生态，家具单品多，尺寸较规范；多为 SKP 需转格式 |
| vision-ai 聚合库 | https://vision-ai.org/3d/en | 5,830 家具 + 材质 + HDRI，标称 CC0、Ready GLB（聚合站，下载前核对原始授权） |

### 🔴 避坑提醒

- **CC BY** 类要署名（作者名 + 链接），别当 CC0 用；**CC BY-NC** 不能商用。
- Sketchfab 上标 **NoAI** 的模型不能用于 AI 训练，装修自用一般没问题，但别上传做 AI 数据集。
- 下载时优先 **GLB**（单文件含贴图）；OBJ+MTL+贴图多文件在设计器里不如 GLB 方便。
- 高精模型（几十万面）会让网页卡；家装用建议 5k–50k 三角面、贴图 1K–2K。

---

## 三、按房间找模型（速查）

| 房间 | 需要的模型关键词（英文搜） | 推荐源 |
|---|---|---|
| 客厅 | sofa, coffee table, TV stand, armchair, rug, floor lamp | Poly Haven / Mixos / Grab3D |
| 卧室 | bed, nightstand, wardrobe, dresser, pendant light | Poly Haven / Quaternius |
| 厨房 | kitchen cabinet, sink, stove, refrigerator, dining table | Poly Haven / Poly Pizza |
| 卫生间 | toilet, washbasin, shower, bathtub, mirror cabinet | Sketchfab / Poly Pizza |
| 餐厅 | dining table, dining chair, sideboard, wine rack | Mixos / Poly Haven |
| 装饰 | plant, painting, vase, books, curtain | Poly Pizza / Kenney |

---

## 四、贡献

发现好的免费源或具体模型，欢迎提 Issue 或 PR，按「站点 / 授权 / 格式 / 直链」四要素补充。

## License

本仓库只存链接和说明，文本采用 CC0；**各模型的版权归原作者，使用前请以原站点标注为准**。

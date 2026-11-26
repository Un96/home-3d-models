# 家装 3D 模型库（GLB）

> **510 个 CC0 3D 模型**，全部来自 [Poly Haven](https://polyhaven.com/)，已打包成**单文件 GLB**（含 1k 贴图），可被 [house-plan-designer](https://github.com/ZWD11/house-plan-designer) 网页设计器**直接导入**。
>
> 按品类/风格/材质多维索引。已剔除 8 个超过 GitHub 100MB 限制的巨型树木模型，剩余单文件最大 44MB。
>
> CC0 1.0 = 可商用、无需署名、无水印。模型版权归原作者，授权以 [Poly Haven License](https://polyhaven.com/license) 为准。

---

## 一、怎么用

1. 在下面任一索引里找到模型，下载 `.glb` 文件
2. 打开装修设计器 → 工具栏点 **导入 GLB 家具模型** 按钮（立方体图标，可多选）
3. 模型进平面后拖动摆位、右侧属性栏改尺寸/旋转、填品牌和价格；3D 视图实时看效果

> 单位自动识别（米/厘米/毫米）；比例不对就在属性栏直接调尺寸。

---

## 二、多维索引（同一个模型，多种分类方式）

| 索引 | 分类维度 | 适合场景 |
|---|---|---|
| [CATALOG.md](CATALOG.md) | **品类**：座椅沙发 / 桌椅 / 床 / 柜子收纳 / 灯具 / 厨房 / 卫浴 / 家电数码 / 装饰植物 / 户外 / 杂物 | 按房间装修采买时 |
| [BY_STYLE.md](BY_STYLE.md) | **风格**：现代简约 / 复古古典 / 工业风 / 北欧自然 / 卡通低多边形 | 确定整体风格后挑件 |
| [BY_MATERIAL.md](BY_MATERIAL.md) | **材质**：木质 / 金属 / 布艺 / 玻璃陶瓷 / 石材混凝土 / 塑料 | 搭配材质时 |
| [BY_SOURCE.md](BY_SOURCE.md) | **来源站**：Poly Haven（CC0） | 核对授权溯源 |
| [index.json](index.json) | 机器可读：面数、尺寸(m)、体积、贴图数、品类 | 写脚本筛选 |

> 标签由模型名称关键词自动推断，供快速筛选，不一定 100% 精确。

**关于品牌分类**：CC0 站点不会放宜家/顾家等品牌家具（商标和版权限制）。需要品牌感时用「风格 + 材质」两个维度组合筛选，效果接近。

---

## 三、其他免费资源站（需自行下载转换）

不搬运文件，只列链接，下载前核对每条授权：

| 站点 | 授权 | 格式 |
|---|---|---|
| [Poly Haven](https://polyhaven.com/models) | CC0 | glTF，可转 GLB |
| [Mixos 家具](https://www.mixos.io/free-models/furniture) | CC0 | GLB（源自 Poly Haven） |
| [Poly Pizza](https://poly.pizza) | 逐条看（CC0 / CC BY） | GLB / GLTF |
| [Kenney 3D](https://kenney.nl/assets/category:3D) | CC0 | GLB / OBJ / FBX |
| [Quaternius](https://quaternius.com/) | CC0 | GLB / OBJ |
| [Grab3D 家具](https://grab3d.com/models/furniture) | CC0 | GLB / FBX / OBJ / USDZ |
| [Sketchfab 家具](https://sketchfab.com/categories/furniture-home) | 逐条看（筛 CC0 / CC BY） | 多为 GLB |
| [CGTrader 家具](https://www.cgtrader.com/3d-models/furniture) | 逐条看 | 多为 FBX/OBJ |
| [Free3D 家具](https://free3d.com/3d-models/furniture) | 逐条看 | 混合 |
| [Blend Swap 家具](https://www.blendswap.com/blends?keyword=furniture) | 逐条看 | BLEND 需转 |
| [3D Warehouse](https://3dwarehouse.sketchup.com/) | 逐条看 | SKP 需转 |
| [vision-ai 聚合库](https://vision-ai.org/3d/en) | 标称 CC0 | GLB ready |

---

## 四、避坑

- **CC BY** 要署名，**CC BY-NC** 不能商用；本仓库只收 CC0。
- 高精模型（几十万面）会让网页卡；家装建议 5k–50k 面、贴图 1K–2K（本仓库已按 1k 打包）。
- Sketchfab 标 **NoAI** 的模型不能用于 AI 训练，装修自用一般没问题。
- 想加新模型：提 PR，附「来源 / 授权 / GLB 直链」三要素。

## License

本仓库的说明文本采用 CC0；3D 模型版权归各自原作者，使用请以原站点标注为准。

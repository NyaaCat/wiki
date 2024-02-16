# 喵窝交通线路图（光棱版）

最后更新：2024 年 2 月

本页面提供的交通图由[地铁路线绘制器](https://railmapgen.github.io/rmp/)生成，工程文件在 GitHub 上，支持协作更新。

## 下界交通线路图

[下界交通搭乘指南](tutorial/map-navi/railway-nether)

<details><summary>图例说明</summary>

线路颜色

1. 黑色/灰色线路为 [Y5 交通网线路](tutorial/map-navi/railway-nether#y5)
2. 彩色线路为 [基岩之上交通网线路](tutorial/map-navi/railway-nether#y130)
3. 基岩之上交通网的线路颜色与站点装潢对应，可通过颜色快速辨识车站方位。

站点名称

1. 带 \* 号的站点代表单向传送门

站点坐标

1. 🔼 代表基岩之上交通网坐标
2. 🔽 代表 Y5 交通网坐标
3. 🔥 代表下界普通坐标
4. 🚪 代表传送门坐标（和 🔼 或者 🔽 连通）（仅简化地图使用。等比例地图使用支线表示传送门位置）
</details>

![下界交通线路图](railway-len/nether-simple.svg)


<details><summary>等比例路线图体积较大，建议在新标签页中打开。</summary>

![等比例下界交通路线图](railway-len/nether-full.svg)
</details>

## 协作更新指南

请先阅读 [NyaaWiki 协作指南](wiki/contribute)。

1. 将工程文件下载后，在[地铁路线绘制器](https://railmapgen.github.io/rmp/)中导入编辑
2. 编辑完成后导出 SVG 和工程文件

> 下界交通线路图

- 等距图工程文件：`railway-len/nether-full.json`
- 等距图：`railway-len/nether-full.svg`
- 简化图工程文件：`railway-len/nether-simple.json`
- 简化图：`railway-len/nether-simple.svg`

地图编辑约定：

1. 坐标尽量选择 10 的倍数、5 的倍数，或者特殊数字（128、256、512、1024、……）
2. 不要使用地铁路线绘制器的斜线功能（倒数第四个按钮），也不要绘制 45 度以外的斜线，只使用直线和 135 度折线（倒数第六个按钮）
3. 简化图中，两站坐标间隔为 75，支线建议对齐横纵线路上的相近站点（例如月望谷）
4. 等距离图中，当离开主线路到传送门超过 150 距离后，可以在地图上用新站点标记，并使用支线连接。此类站点站名惯例：“极东站”（在基岩线路上）和“极东”（传送门的实际位置）。简化图一般情况下应该使用单一站点表示。
5. 支线使用与主线路相近的颜色

# 9.3 大阅兵 - 国际阵营情况

根据国家国际阵营划分，在地图上展示不同国家的分布情况。

## 功能特点

- 世界地图全屏展示  
- **中国红色标记（主办国）**  
- **不同阵营以不同颜色标记国家**  
  - 盟友阵营  
  - 对手阵营  
  - 中立阵营  
- 非阵营国家灰色显示  
- 鼠标悬停显示国家名称  
- 右侧显示各阵营国家列表  

## 在线预览

项目地址：[https://xyy277.github.io/map93/](https://xyy277.github.io/map93/)

## 部署方式

1. 确保仓库包含 `index.html` 页面及依赖文件（如 `assets/geo/world.json`）  
2. 打开仓库 **Settings → Pages**  
3. 选择 **Branch: main**  
4. 选择 **Folder: / (root)** 或 `docs/` 文件夹  
5. 保存后等待几分钟即可通过 GitHub Pages 访问  

## 技术栈

- HTML / CSS / JavaScript  
- [ECharts 5](https://echarts.apache.org/) 可视化库  
- GeoJSON 世界地图数据  

## 使用说明

1. 克隆或下载仓库到本地  
2. 若要本地预览，启动本地服务器（防止 CORS 问题）：

```bash
python -m http.server 8080

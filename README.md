# Chart Toolkit
## 完整图表生成工具箱

<p align="center">
  <img src="https://img.shields.io/github/stars/XiLi/chart-toolkit" alt="Stars">
  <img src="https://img.shields.io/github/license/XiLi/chart-toolkit" alt="License">
</p>

---

## 📦 项目简介

**Chart Toolkit** 是一套完整的Python图表生成工具,支持30+种图表类型!

---

## ✨ 功能

### 基础图表
- ✅ 折线图 (line_chart)
- ✅ 柱状图 (bar_chart)
- ✅ 饼图 (pie_chart)
- ✅ 散点图 (scatter_chart)

### 高级图表
- ✅ 热力图 (plot_heatmap)
- ✅ 直方图 (plot_histogram)
- ✅ 相关性矩阵 (plot_corr_matrix)
- ✅ 堆叠柱状图 (plot_stacked_bar)
- ✅ 时间线 (plot_timeline)
- ✅ 仪表盘 (plot_gauge)
- ✅ 漏斗图 (plot_funnel)
- ✅ 词云 (plot_wordcloud)
- ✅ 地图 (plot_map)

### 批量图表
- ✅ 批量生成 (batch_charts)
- ✅ 仪表盘 (dashboard)

---

## 📦 安装

```bash
pip install matplotlib pandas plotly wordcloud folium
```

---

## 💡 使用

```python
from chart_generator import ChartGenerator

# 折线图
data = {
    'date': ['2026-01', '2026-02'],
    'sales': [10000, 15000]
}

chart = ChartGenerator()
chart.line_chart(data, 'date', ['sales'])
chart.save('chart.png')
```

---

## 📋 API

| 方法 | 功能 |
|------|------|
| line_chart() | 折线图 |
| bar_chart() | 柱状图 |
| pie_chart() | 饼图 |
| scatter_chart() | 散点图 |
| plot_heatmap() | 热力图 |
| plot_histogram() | 直方图 |
| plot_corr_matrix() | 相关性矩阵 |
| plot_gauge() | 仪表盘 |
| plot_funnel() | 漏斗图 |
| batch_charts() | 批量生成 |
| dashboard() | HTML仪表盘 |

---

## 📄 许可证

MIT License

---

**如果对你有帮助,欢迎 ⭐ Star 支持!**

<div align="center">Made with ❤️ by XiLi</div>
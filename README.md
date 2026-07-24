# 🗺️ 香港小众旅行地图

> 7月31日－8月1日 · 尖沙咀出发 · 含曼城观赛

**点此查看地图 → https://shaykiin-leung.github.io/hk-trip-map/**

小红书收藏的地点整理成交互式地图，一键导航到原笔记。

## 📍 功能

- 地图上标记所有打卡点，点击查看详情和小红书链接
- 按日期切换 Day1 / Day2 路线
- 蓝线标识路线 + 地铁交通时间
- 天星小轮过海体验

## 📌 如何加新地点

直接编辑 `index.html` 底部 `const DATA = {...}` 中的 `locations` 数组，按格式添加：

```js
{
  id: "new-place",
  name: "地点名",
  lat: 22.XXXX,
  lng: 114.XXXX,
  note: "推荐语",
  url: "小红书链接",
  category: "美食/拍照/日落/看球",
  day: 1 // 第几天
}
```

欢迎 PR 补充！

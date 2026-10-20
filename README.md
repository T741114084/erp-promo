# 装修公司 ERP 落地案例 —— FDE 工作室商业宣传页

> FDE 工作室业务系统定制案例展示页。驻场梳理业务流程，交付可直接上线跑通的业务系统。

## 项目结构

```
装修ERP-商业宣传版/
├── index.html                    # 宣传展示页（唯一入口）
└── assets/
    ├── business-closed-loop.jpg  # 最小业务闭环示意图
    ├── demo-cover.jpg            # 演示视频封面
    ├── value-points.jpg          # 三大价值点示意
    └── wechat-qr.jpg             # 微信二维码
```

## 运行

双击 `index.html` 即可本地查看，或部署到任意静态托管（GitHub Pages / Vercel）。

## 说明

- 页面含可点击拨打电话（tel: 13265528512）与微信二维码卡片
- 演示视频引用外部 CDN，需离线展示时替换 `index.html` 中 `<source>` 的 `src`

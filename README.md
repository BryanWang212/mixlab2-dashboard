# 男装期货开发「四维」匹配看板

PRADA F/W 2013 视觉风格 · 男装期货企划匹配看板 · 单文件 HTML 应用

## 在线访问

部署后访问 `https://your-project.vercel.app`

## 特性

- **双维度匹配**：layer（价格/角色）× series（产品线/风格）
- **款色双层结构**：16 款 × 3 色 = 48 SKU
- **中期锁定机制**：开发初期仅锁系列，中期再补 layer
- **通用文件解析**：自动识别款色总表 / 节点进度表 / 分层调整表 / 销售复盘表
- **PRADA 视觉**：Bodoni 衬线 + 直角 + flat 阴影 + Warm Olive 背景

## 项目结构

```
.
├── index.html          # 单文件应用（HTML + CSS + JS）
├── vercel.json         # Vercel 部署配置
├── docs/
│   ├── SPEC.md         # 业务 + 功能规格
│   └── DESIGN.md       # PRADA 设计系统
└── README.md
```

## 本地预览

直接打开 `index.html` 即可，或用：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 5 大模块

1. **企划基线**（双维度 · 分层 × 系列规划 + 矩阵）
2. **款维度总览**（进度更新 + 分层完成 + 款卡）
3. **色维度总览**（48 SKU 展开）
4. **销售联动**（POS 数据 + 价格带）
5. **决策输出**（风险款 + 整改清单）

## 设计参考

- 配色：PRADA F/W 2013 Campaign（Dane DeHaan Portrait）
- 字体：Bodoni 72 / Didot (Serif) + Sans-Serif
- 形状：strict rectilinear (border-radius: 0)

详细见 `docs/DESIGN.md`。
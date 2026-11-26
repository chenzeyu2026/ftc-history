# d 与 ∫ 的四次改义

一份关于**牛顿-莱布尼兹公式（微积分基本定理）符号史**的中文长文，单页 HTML。

文章追问一个具体问题：为什么今天写 `∫f(x)dx` 和 `dy/dx` 时，这两个符号看起来"自己会算"？答案不在定理本身，而在 `d` 与 `∫` 这两个记号被反复改写的历史里。全文沿四次改义展开：

1. **不可分量**（阿基米德、卡瓦列里、沃利斯、费马、巴罗）——把图形拆成原子；
2. **流数法**（牛顿）——把量看成运动；
3. **微分记号**（莱布尼兹）——让符号自己会算；
4. **极限**（达朗贝尔、柯西、波尔查诺、魏尔斯特拉斯、戴德金）——把无穷小问题取消掉。

另有两条支线：非标准分析对无穷小的复活，以及 19 世纪英国"点派"（dot-age）改宗莱布尼兹记号的插曲。

文中附 30 条文献出处，并按〈确证〉〈通行〉〈存疑〉三级标注史实可靠度；判词部分（冤／不冤／部分冤）为分析性判断，与史实分开标注。

## 打开方式

本文是**纯离线**单文件 HTML，不依赖任何 CDN 或外部字体服务。但有一个前提：

> `ftc-history.html` 与 `_shared/fonts/` 必须保持相对位置不变。

```text
ftc-history/
├── ftc-history.html          # 正文，约 100 KB
└── _shared/
    └── fonts/                # IBM Plex Serif / Mono，共 4 个 ttf
```

**推荐做法**：克隆或下载整个仓库，双击 `ftc-history.html` 用浏览器打开即可。

```bash
git clone https://github.com/chenzeyu2026/ftc-history.git
```

只单独拷走 `ftc-history.html` 也能读，但字体回退到系统衬线体，字重层级和等宽排版会与设计意图不同。

## 引用格式

作者字段目前以 GitHub 帐号 `chenzeyu2026` 占位；如用于正式发表，请替换为真实署名。

**BibTeX**

```bibtex
@misc{ftc_history_2026,
  author       = {{chenzeyu2026}},
  title        = {d 与 ∫ 的四次改义：牛顿-莱布尼兹公式的数学史},
  year         = {2026},
  month        = nov,
  howpublished = {\url{https://github.com/chenzeyu2026/ftc-history}},
  note         = {单文件 HTML 长文，版本 1.0}
}
```

**GB/T 7714—2015**

```text
chenzeyu2026. d 与 ∫ 的四次改义: 牛顿-莱布尼兹公式的数学史[EB/OL]. (2026-11)[2026-11-26].
https://github.com/chenzeyu2026/ftc-history.
```

**APA 7**

```text
chenzeyu2026. (2026). d 与 ∫ 的四次改义：牛顿-莱布尼兹公式的数学史 [Web article]. GitHub.
https://github.com/chenzeyu2026/ftc-history
```

**Chicago（注释体）**

```text
chenzeyu2026, "d 与 ∫ 的四次改义：牛顿-莱布尼兹公式的数学史," GitHub, November 2026,
https://github.com/chenzeyu2026/ftc-history.
```

## 版本

- v1.0 — 2026-11，初版。

引用时建议注明访问日期；若后续修订，`git log` 与 Releases 可查具体版本差异。

# Python 28 天学习计划 · 知识点 PPT

一套为 **数据分析实习 → 求职落地** 准备的按天知识点课件。2026-11-02 起按天推进，一天一份。
接在 SQL 23 天那套（[sql-knowledge-ppt](https://github.com/chaojiwudi328/sql-knowledge-ppt)）后面，把 SQL 的分析套路换成 Python。

- **28 份单日课件**：Python 语法 → 函数 / 文件 IO → numpy → pandas → 清洗 / 筛选 / groupby / merge → 透视 / 时序 / 可视化 → Excel → 统计与 AB → Tableau 看板 → 简历与投递 → 总验收。
- **4 本合订本**：基础期 1-9、分析期 10-18、冲刺期 19-28，另加一本全量总复习册 —— 面试前一晚直接过。
- **每条知识点对应当天要做的题**，不是通用教程，而是「今天做完这些题，要记住什么」的收口。
- **PDF 与 pptx 同步更新**：pptx 在 GitHub 上只能下载再打开，而 PDF 能直接在浏览器里翻页、双指放大 —— 平板看 PDF，本地改 pptx，脚本负责两边一致。

<!-- 平板直达:START -->

## 📱 平板上直接看（不用下载）

> 点开下面任意一条，GitHub 会**直接在浏览器里把 PDF 渲染出来**，能翻页、能双指放大。
> 这些 PDF 与仓库里的 pptx **同步更新**（课件一改，这里就跟着改），所以永远是最新的。

**今天（11/12）** → [第 11 天 · 筛选与排序：布尔索引、query、lociloc、多列排序](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC11%E5%A4%A9-11%E6%9C%8812%E6%97%A5-%E7%AD%9B%E9%80%89%E4%B8%8E%E6%8E%92%E5%BA%8F%EF%BC%9A%E5%B8%83%E5%B0%94%E7%B4%A2%E5%BC%95%E3%80%81query%E3%80%81lociloc%E3%80%81%E5%A4%9A%E5%88%97%E6%8E%92%E5%BA%8F.pdf)

| 天 | 日期 | 主题 | 直接打开 |
|---|---|---|---|
| 第 1 天 | 11/2 | 脚本骨架：变量、四种类型、格式化、输入 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC01%E5%A4%A9-11%E6%9C%882%E6%97%A5-%E8%84%9A%E6%9C%AC%E9%AA%A8%E6%9E%B6%EF%BC%9A%E5%8F%98%E9%87%8F%E3%80%81%E5%9B%9B%E7%A7%8D%E7%B1%BB%E5%9E%8B%E3%80%81%E6%A0%BC%E5%BC%8F%E5%8C%96%E3%80%81%E8%BE%93%E5%85%A5.pdf) |
| 第 2 天 | 11/3 | 分支与循环：ifelif、whilefor、range、breakcontinue | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC02%E5%A4%A9-11%E6%9C%883%E6%97%A5-%E5%88%86%E6%94%AF%E4%B8%8E%E5%BE%AA%E7%8E%AF%EF%BC%9Aifelif%E3%80%81whilefor%E3%80%81range%E3%80%81breakcontinue.pdf) |
| 第 3 天 | 11/4 | 容器四件套：list  tuple  dict  set，切片与排序 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC03%E5%A4%A9-11%E6%9C%884%E6%97%A5-%E5%AE%B9%E5%99%A8%E5%9B%9B%E4%BB%B6%E5%A5%97%EF%BC%9Alist%20%20tuple%20%20dict%20%20set%EF%BC%8C%E5%88%87%E7%89%87%E4%B8%8E%E6%8E%92%E5%BA%8F.pdf) |
| 第 4 天 | 11/5 | ★Excel 一天速成：数据透视表 + XLOOKUPVLOOKUP + SUMIFS | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC04%E5%A4%A9-11%E6%9C%885%E6%97%A5-%E2%98%85Excel%20%E4%B8%80%E5%A4%A9%E9%80%9F%E6%88%90%EF%BC%9A%E6%95%B0%E6%8D%AE%E9%80%8F%E8%A7%86%E8%A1%A8%20%2B%20XLOOKUPVLOOKUP%20%2B%20SUMIFS.pdf) |
| 第 5 天 | 11/6 | 函数：参数、返回值、作用域、lambda | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC05%E5%A4%A9-11%E6%9C%886%E6%97%A5-%E5%87%BD%E6%95%B0%EF%BC%9A%E5%8F%82%E6%95%B0%E3%80%81%E8%BF%94%E5%9B%9E%E5%80%BC%E3%80%81%E4%BD%9C%E7%94%A8%E5%9F%9F%E3%80%81lambda.pdf) |
| 第 6 天 | 11/7 | 面向对象 + 模块与包 + 常用标准库 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC06%E5%A4%A9-11%E6%9C%887%E6%97%A5-%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%20%2B%20%E6%A8%A1%E5%9D%97%E4%B8%8E%E5%8C%85%20%2B%20%E5%B8%B8%E7%94%A8%E6%A0%87%E5%87%86%E5%BA%93.pdf) |
| 第 7 天 | 11/8 | 文件 IO + 异常处理 + CSVJSON 读写（W4 收尾验收） | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC07%E5%A4%A9-11%E6%9C%888%E6%97%A5-%E6%96%87%E4%BB%B6%20IO%20%2B%20%E5%BC%82%E5%B8%B8%E5%A4%84%E7%90%86%20%2B%20CSVJSON%20%E8%AF%BB%E5%86%99%EF%BC%88W4%20%E6%94%B6%E5%B0%BE%E9%AA%8C%E6%94%B6%EF%BC%89.pdf) |
| 第 8 天 | 11/9 | numpy：ndarray、向量化、广播、布尔索引 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC08%E5%A4%A9-11%E6%9C%889%E6%97%A5-numpy%EF%BC%9Andarray%E3%80%81%E5%90%91%E9%87%8F%E5%8C%96%E3%80%81%E5%B9%BF%E6%92%AD%E3%80%81%E5%B8%83%E5%B0%94%E7%B4%A2%E5%BC%95.pdf) |
| 第 9 天 | 11/10 | pandas 读数据 + SeriesDataFrame + 一眼看清一张表 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC09%E5%A4%A9-11%E6%9C%8810%E6%97%A5-pandas%20%E8%AF%BB%E6%95%B0%E6%8D%AE%20%2B%20SeriesDataFrame%20%2B%20%E4%B8%80%E7%9C%BC%E7%9C%8B%E6%B8%85%E4%B8%80%E5%BC%A0%E8%A1%A8.pdf) |
| 第 10 天 | 11/11 | 清洗第一课：缺失值、重复行、类型转换、字符串规整 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC10%E5%A4%A9-11%E6%9C%8811%E6%97%A5-%E6%B8%85%E6%B4%97%E7%AC%AC%E4%B8%80%E8%AF%BE%EF%BC%9A%E7%BC%BA%E5%A4%B1%E5%80%BC%E3%80%81%E9%87%8D%E5%A4%8D%E8%A1%8C%E3%80%81%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2%E8%A7%84%E6%95%B4.pdf) |
| 第 11 天 | 11/12 | 筛选与排序：布尔索引、query、lociloc、多列排序 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC11%E5%A4%A9-11%E6%9C%8812%E6%97%A5-%E7%AD%9B%E9%80%89%E4%B8%8E%E6%8E%92%E5%BA%8F%EF%BC%9A%E5%B8%83%E5%B0%94%E7%B4%A2%E5%BC%95%E3%80%81query%E3%80%81lociloc%E3%80%81%E5%A4%9A%E5%88%97%E6%8E%92%E5%BA%8F.pdf) |
| 第 12 天 | 11/13 | groupby 分组聚合：agg、transform、多列分组 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC12%E5%A4%A9-11%E6%9C%8813%E6%97%A5-groupby%20%E5%88%86%E7%BB%84%E8%81%9A%E5%90%88%EF%BC%9Aagg%E3%80%81transform%E3%80%81%E5%A4%9A%E5%88%97%E5%88%86%E7%BB%84.pdf) |
| 第 13 天 | 11/14 | merge 连接：how 四种取值、连接键对不上怎么办 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC13%E5%A4%A9-11%E6%9C%8814%E6%97%A5-merge%20%E8%BF%9E%E6%8E%A5%EF%BC%9Ahow%20%E5%9B%9B%E7%A7%8D%E5%8F%96%E5%80%BC%E3%80%81%E8%BF%9E%E6%8E%A5%E9%94%AE%E5%AF%B9%E4%B8%8D%E4%B8%8A%E6%80%8E%E4%B9%88%E5%8A%9E.pdf) |
| 第 14 天 | 11/15 | ★W5 总验收：给一份脏 CSV，独立清洗成可分析表并说清每一步 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC14%E5%A4%A9-11%E6%9C%8815%E6%97%A5-%E2%98%85W5%20%E6%80%BB%E9%AA%8C%E6%94%B6%EF%BC%9A%E7%BB%99%E4%B8%80%E4%BB%BD%E8%84%8F%20CSV%EF%BC%8C%E7%8B%AC%E7%AB%8B%E6%B8%85%E6%B4%97%E6%88%90%E5%8F%AF%E5%88%86%E6%9E%90%E8%A1%A8%E5%B9%B6%E8%AF%B4%E6%B8%85%E6%AF%8F%E4%B8%80%E6%AD%A5.pdf) |
| 第 15 天 | 11/16 | pivot_table 透视表：indexcolumnsvaluesaggfunc 四件套 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC15%E5%A4%A9-11%E6%9C%8816%E6%97%A5-pivot_table%20%E9%80%8F%E8%A7%86%E8%A1%A8%EF%BC%9Aindexcolumnsvaluesaggfunc%20%E5%9B%9B%E4%BB%B6%E5%A5%97.pdf) |
| 第 16 天 | 11/17 | 时间序列：to_datetime、resample、rolling、同比环比 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC16%E5%A4%A9-11%E6%9C%8817%E6%97%A5-%E6%97%B6%E9%97%B4%E5%BA%8F%E5%88%97%EF%BC%9Ato_datetime%E3%80%81resample%E3%80%81rolling%E3%80%81%E5%90%8C%E6%AF%94%E7%8E%AF%E6%AF%94.pdf) |
| 第 17 天 | 11/18 | applymaplambda + 多级索引：什么时候该用、什么时候别用 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC17%E5%A4%A9-11%E6%9C%8818%E6%97%A5-applymaplambda%20%2B%20%E5%A4%9A%E7%BA%A7%E7%B4%A2%E5%BC%95%EF%BC%9A%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%AF%A5%E7%94%A8%E3%80%81%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%88%AB%E7%94%A8.pdf) |
| 第 18 天 | 11/19 | 可视化：matplotlib 中文设置 + 三张有业务含义的图 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC18%E5%A4%A9-11%E6%9C%8819%E6%97%A5-%E5%8F%AF%E8%A7%86%E5%8C%96%EF%BC%9Amatplotlib%20%E4%B8%AD%E6%96%87%E8%AE%BE%E7%BD%AE%20%2B%20%E4%B8%89%E5%BC%A0%E6%9C%89%E4%B8%9A%E5%8A%A1%E5%90%AB%E4%B9%89%E7%9A%84%E5%9B%BE.pdf) |
| 第 19 天 | 11/20 | ★Excel 进阶：Power Query 清洗 + 条件格式 + 图表；下午开投 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC19%E5%A4%A9-11%E6%9C%8820%E6%97%A5-%E2%98%85Excel%20%E8%BF%9B%E9%98%B6%EF%BC%9APower%20Query%20%E6%B8%85%E6%B4%97%20%2B%20%E6%9D%A1%E4%BB%B6%E6%A0%BC%E5%BC%8F%20%2B%20%E5%9B%BE%E8%A1%A8%EF%BC%9B%E4%B8%8B%E5%8D%88%E5%BC%80%E6%8A%95.pdf) |
| 第 20 天 | 11/21 | 把 W4–W6 的脚本收成「一个能讲的项目」 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC20%E5%A4%A9-11%E6%9C%8821%E6%97%A5-%E6%8A%8A%20W4%E2%80%93W6%20%E7%9A%84%E8%84%9A%E6%9C%AC%E6%94%B6%E6%88%90%E3%80%8C%E4%B8%80%E4%B8%AA%E8%83%BD%E8%AE%B2%E7%9A%84%E9%A1%B9%E7%9B%AE%E3%80%8D.pdf) |
| 第 21 天 | 11/22 | ★简历第一版 + W6 总验收 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC21%E5%A4%A9-11%E6%9C%8822%E6%97%A5-%E2%98%85%E7%AE%80%E5%8E%86%E7%AC%AC%E4%B8%80%E7%89%88%20%2B%20W6%20%E6%80%BB%E9%AA%8C%E6%94%B6.pdf) |
| 第 22 天 | 11/23 | 统计专项：描述统计、抽样与置信区间、假设检验、P 值三种误用 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC22%E5%A4%A9-11%E6%9C%8823%E6%97%A5-%E7%BB%9F%E8%AE%A1%E4%B8%93%E9%A1%B9%EF%BC%9A%E6%8F%8F%E8%BF%B0%E7%BB%9F%E8%AE%A1%E3%80%81%E6%8A%BD%E6%A0%B7%E4%B8%8E%E7%BD%AE%E4%BF%A1%E5%8C%BA%E9%97%B4%E3%80%81%E5%81%87%E8%AE%BE%E6%A3%80%E9%AA%8C%E3%80%81P%20%E5%80%BC%E4%B8%89%E7%A7%8D%E8%AF%AF%E7%94%A8.pdf) |
| 第 23 天 | 11/24 | 上午 AB 实验设计 + 下午指标体系（一天两段，各出 300 字） | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC23%E5%A4%A9-11%E6%9C%8824%E6%97%A5-%E4%B8%8A%E5%8D%88%20AB%20%E5%AE%9E%E9%AA%8C%E8%AE%BE%E8%AE%A1%20%2B%20%E4%B8%8B%E5%8D%88%E6%8C%87%E6%A0%87%E4%BD%93%E7%B3%BB%EF%BC%88%E4%B8%80%E5%A4%A9%E4%B8%A4%E6%AE%B5%EF%BC%8C%E5%90%84%E5%87%BA%20300%20%E5%AD%97%EF%BC%89.pdf) |
| 第 24 天 | 11/25 | Tableau 看板 13：连接数据、字段类型、第一张工作表 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC24%E5%A4%A9-11%E6%9C%8825%E6%97%A5-Tableau%20%E7%9C%8B%E6%9D%BF%2013%EF%BC%9A%E8%BF%9E%E6%8E%A5%E6%95%B0%E6%8D%AE%E3%80%81%E5%AD%97%E6%AE%B5%E7%B1%BB%E5%9E%8B%E3%80%81%E7%AC%AC%E4%B8%80%E5%BC%A0%E5%B7%A5%E4%BD%9C%E8%A1%A8.pdf) |
| 第 25 天 | 11/26 | Tableau 看板 23：计算字段、筛选器、参数、仪表板拼装 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC25%E5%A4%A9-11%E6%9C%8826%E6%97%A5-Tableau%20%E7%9C%8B%E6%9D%BF%2023%EF%BC%9A%E8%AE%A1%E7%AE%97%E5%AD%97%E6%AE%B5%E3%80%81%E7%AD%9B%E9%80%89%E5%99%A8%E3%80%81%E5%8F%82%E6%95%B0%E3%80%81%E4%BB%AA%E8%A1%A8%E6%9D%BF%E6%8B%BC%E8%A3%85.pdf) |
| 第 26 天 | 11/27 | Tableau 看板 33：第二三屏 + 导出 3 张截图进简历 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC26%E5%A4%A9-11%E6%9C%8827%E6%97%A5-Tableau%20%E7%9C%8B%E6%9D%BF%2033%EF%BC%9A%E7%AC%AC%E4%BA%8C%E4%B8%89%E5%B1%8F%20%2B%20%E5%AF%BC%E5%87%BA%203%20%E5%BC%A0%E6%88%AA%E5%9B%BE%E8%BF%9B%E7%AE%80%E5%8E%86.pdf) |
| 第 27 天 | 11/28 | 投递冲刺：把简历、项目、看板三件套对齐 JD | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC27%E5%A4%A9-11%E6%9C%8828%E6%97%A5-%E6%8A%95%E9%80%92%E5%86%B2%E5%88%BA%EF%BC%9A%E6%8A%8A%E7%AE%80%E5%8E%86%E3%80%81%E9%A1%B9%E7%9B%AE%E3%80%81%E7%9C%8B%E6%9D%BF%E4%B8%89%E4%BB%B6%E5%A5%97%E5%AF%B9%E9%BD%90%20JD.pdf) |
| 第 28 天 | 11/29 | ★W7 总验收 + 三周复盘：从 SQL 到 Python 到看板 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E7%AC%AC28%E5%A4%A9-11%E6%9C%8829%E6%97%A5-%E2%98%85W7%20%E6%80%BB%E9%AA%8C%E6%94%B6%20%2B%20%E4%B8%89%E5%91%A8%E5%A4%8D%E7%9B%98%EF%BC%9A%E4%BB%8E%20SQL%20%E5%88%B0%20Python%20%E5%88%B0%E7%9C%8B%E6%9D%BF.pdf) |

**合订本**

| 合订本 | 直接打开 |
|---|---|
| 冲刺期 · 第 19-28 天 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E5%90%88%E8%AE%A2%E6%9C%AC/%E5%86%B2%E5%88%BA%E6%9C%9F%20%C2%B7%20%E7%AC%AC%2019-28%20%E5%A4%A9.pdf) |
| 分析期 · 第 10-18 天 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E5%90%88%E8%AE%A2%E6%9C%AC/%E5%88%86%E6%9E%90%E6%9C%9F%20%C2%B7%20%E7%AC%AC%2010-18%20%E5%A4%A9.pdf) |
| 基础期 · 第 1-9 天 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E5%90%88%E8%AE%A2%E6%9C%AC/%E5%9F%BA%E7%A1%80%E6%9C%9F%20%C2%B7%20%E7%AC%AC%201-9%20%E5%A4%A9.pdf) |
| 总复习册 · Python 28 天 | [看 PDF](https://github.com/chaojiwudi328/python-knowledge-ppt/blob/main/PDF/%E5%90%88%E8%AE%A2%E6%9C%AC/%E6%80%BB%E5%A4%8D%E4%B9%A0%E5%86%8C%20%C2%B7%20Python%2028%20%E5%A4%A9.pdf) |

*（本区块由 `导出-知识点PPT为PDF.py` 自动生成，手工改这里会在下次同步时被覆盖；要改说明文字请改本区块之外的部分。）*

<!-- 平板直达:END -->

---

## 目录结构

```
知识点PPT-Python28天/
├─ 第NN天-M月D日-主题.pptx      28 份单日课件（交给脚本生成，不要手改）
├─ PDF/                          平板直接看的 PDF（由 导出-知识点PPT为PDF.py 生成）
│  └─ 合订本/                    4 本合订本的 PDF
├─ 合订本/                       4 本合订本 pptx（由 合并-知识点PPT-Python28天.py 生成）
├─ 知识点PPT清单.csv             天序号 / 日期 / 主题 / 本地路径
└─ README.md                     本文件（平板直达表由脚本维护）
```

## 怎么更新

在本机 `D:\DSH工作区\00-学习中心\30-使用说明\` 下：

| 要做的事 | 命令 |
|---|---|
| 重出某天的 PDF | `python 导出-知识点PPT为PDF.py --repo "…\知识点PPT-Python28天" --web <仓库地址> --only 第09天` |
| 全部重导 PDF + 刷新本页直达表 | 同上，去掉 `--only 第09天` |
| 重做合订本 | `python 合并-知识点PPT-Python28天.py`（单本用 `--stage 分析期`） |
| 同步到 GitHub | `python 同步-知识点PPT到GitHub.py --repo "…\知识点PPT-Python28天" --remote <仓库地址>.git --web <仓库地址>` |

> 合订本必须在单日课件定稿后再重跑 —— 页码会全部重排。

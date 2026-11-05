# PDF获取与提交状态报告

更新：2026-11-05（Asia/Shanghai）。用户修订范围为五篇，04取消。全文分析已完成。

| 编号 | PDF来源与核验 | 本地保存 | 公开提交决策 |
|---|---|---|---|
| 01 | arXiv 2407.12304v2，20页；题名作者/格式核验通过 | 01_MAGIC-VFM/paper.pdf | CC BY4.0，可署名再分发，纳入提交 |
| 02 | arXiv 2504.16923v1，11页；题名作者/格式核验通过 | 02_Meta-Adaptation-Offroad/paper.pdf | arXiv CC BY4.0，纳入提交 |
| 03 | MDPI官方静态PDF，16页；题名作者DOI/格式核验通过 | 03_Offroad-Traction-LPV/paper.pdf | 首页CC BY4.0，纳入提交 |
| 04 | 未取得全文，用户明确取消 | 无 | 不提交PDF，不以摘要代替精读 |
| 05 | 用户人工提供出版商21页全文，标题作者DOI匹配 | 05_Residual-RL-Handling/private/paper.pdf | All rights reserved，无再分发授权，仅本地且Git忽略 |
| 06 | 用户人工提供出版商16页全文，标题作者DOI匹配 | 06_SAC-PID-Antislip/private/paper.pdf | All rights reserved，无再分发授权，仅本地且Git忽略 |

02的RSS会议版另在仓库外work/02-RSS2025.pdf，11页但文本提取为空；未完成该版本逐页比对及独立许可检查，未提交。精读底本为完整、可阅读且明确许可的arXiv版本。

全部使用的PDF均检查文件头、EOF、解析页数、首页题名与作者及完整正文末尾；没有HTML错误页面冒充PDF。文件字节数、SHA-256、取得日期、下载入口及版权证据见对应source.md。

01–03原始PDF未改动；05、06不在公开仓库中，公开README不链接本地私有文件。文献05/06的ScienceDirect本轮返回403，但用户提供的完整PDF已核验，因此不再构成全文获取阻碍。

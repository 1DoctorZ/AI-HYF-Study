# 进度与断点恢复记录

更新：2026-11-05（Asia/Shanghai）。**文献整理、质量检查、本地提交及GitHub推送均已完成。最终范围为五篇全文精读，04已取消。**

## 仓库与范围

- 仓库：`https://github.com/1DoctorZ/AI-HYF-Study.git`，本地位于当前工作区 `work/AI-HYF-Study`。
- 分支：`literature/two-stage-traction-control`。克隆时远程为空、main无提交，无既有研究代码或未提交修改。
- 仓库内仅新增本目录。未执行强制推送、硬重置、清理或合并main。
- 用户已确认本次提交署名 `Codex <codex@localhost>`；通过单次命令参数设置，不修改全局配置。
- 提交沿用用户最初指定的subject `docs: add six literature reviews for two-stage traction control`，提交正文说明后续范围调整：五篇精读加04取消记录。**subject中的six不是六篇全文已完成的事实声明。**
- 本文件随最终文档提交保存。具体提交哈希可由该分支的 `git log` 读取；远程是否已同步应以 `git ls-remote` 与本地HEAD比较，避免在文件中写入自身提交哈希造成循环。

## 文献状态

| 编号 | 获取/核验 | 全文精读 | PDF公开状态 |
|---|---|---|---|
| 01 MAGIC-VFM | arXiv v2，20页；格式、身份及许可已核验 | 完成10项与6核心公式，关键页视觉核对 | CC BY4.0，paper.pdf公开 |
| 02 Meta-adaptation | arXiv v1，11页；RSS题录DOI核验 | 完成10项与6核心公式，关键页视觉核对 | arXiv CC BY4.0公开；会议图片版不提交 |
| 03 LPV | MDPI正式版16页；格式、身份及许可核验 | 完成10项与6核心公式，关键页视觉核对 | CC BY4.0，paper.pdf公开 |
| 04 MPC vs RL | 无完整PDF；用户明确取消 | 不分析、不纳入综合结论；保留取消说明 | 无PDF |
| 05 Residual RL | 用户提供21页完整出版商PDF，身份核验通过 | 完成10项与6核心公式，关键页视觉核对 | 保留版权，private/paper.pdf仅本地 |
| 06 SAC-PID | 用户提供16页完整出版商PDF，身份核验通过 | 完成10项与6核心公式，关键页视觉核对 | 保留版权，private/paper.pdf仅本地 |

## 已完成文档

五篇README及source；04取消README及历史source；总README、COMPARISON、RESEARCH_IDEAS、DOWNLOAD_STATUS、QUALITY_CHECK、本PROGRESS。所有公式、关键实验数据及相对链接已检查。原文疑点和严格复现所缺资源见QUALITY_CHECK，不伪称原实验已复现。

## 人工等待与剩余事项

当前不等待任何论文或用户资料；04取消已解除原全文阻碍。文献任务无未完成分析。尚不能解决的作者公式/数据疑点属于严格复现前核验项，已如实记录，不阻碍本轮整理交付。

如果Git提交或推送因环境中断，恢复时先检查当前分支、git status、git log及远程分支指纹；已有提交则不要重复制作。只暂存本目录，使用普通push，不强推；private目录始终忽略。最终上传结果由当前聊天报告及远程分支确认。

## 已有全文与中间资料

01–03公开全文在各目录paper.pdf；05–06完整全文在各目录private/paper.pdf（忽略Git）。仓库外当前工作区work下保留全文提取、关键页面渲染及公式检查工具，不提交。后续修订直接利用已有文件，不重复下载或将未公开全文加入Git。

## GitHub上传确认

2026-11-05，用户完成GitHub登录后恢复推送。直连发生网络重置/超时；检测到Windows已启用本机代理，改用单次命令参数 `http.proxy=http://127.0.0.1:7890` 后普通push成功，未修改全局Git配置。

- 文献内容提交：`fe3fffd871eb51c6f1c25053751fbaa8bce45b88`。
- 远程分支：`literature/two-stage-traction-control`。
- 已通过 `git ls-remote` 确认远程分支包含上述相同提交。
- 分支跟踪关系已设置；没有合并main或强制推送。
- 本次进度状态更新作为独立后续提交保存，保留已上传文献提交历史。
- 05、06的版权PDF仍仅在本地private目录，未进入Git历史或交付压缩包。

[GitHub阅读入口](https://github.com/1DoctorZ/AI-HYF-Study/tree/literature/two-stage-traction-control/Literature/Two-Stage-Traction-Control)

当前无待完成上传或文献分析事项。后续严格复现的原文疑点继续以QUALITY_CHECK.md为准。

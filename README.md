# iBizSim软件预测模拟程序

## iBizSim 软件介绍

iBizSim是由来自北京大学光华管理学院的教授带领专业团队开发的一款企业竞争模拟软件。学员组成虚拟公司的高层管理团队，在模拟的市场环境里展开竞争，进行多期经营决策的演练，通过竞赛对抗的手段，锻炼学员正确制定企业的经营决策，并培养其宏观企业管理的能力。主要用于大学MBA教学、大学生创业教育、企业管理层培训等。

网址：http://www.ibizsim.cn/

## iBizsim prediction软件介绍

作者:Peony Guo
开发目的：方便参加企业模拟大赛同学更加智能方便的进行比赛的辅助软件。

## 预测模拟实现功能清单

- **客户端**
- [ ] 初始比赛参数一键导出
- [ ] 一键更新往期数据
- [ ] 一键提交决策（用规范模板）
- [ ] 添加GUI界面

- **服务器端**
- [ ] 自动预测每期决策，与每期模拟结束后5分钟自动提交下一期预测结果（无需手动提交）
- [ ] 自动预测每期决策，一键在模板生成预测数据方便修改


## 开发计划

1. 实现爬虫功能，分辨实现参数导出，数据更新，提交决策功能。

2. 爬取现在已有的比赛数据（173654场），保存到数据库。

3. 建立预测模型，通过已有的比赛数据进行机器学习训练。

4. 实现自动预测决策功能。

5. 实现客户端GUI。

6. 将程序逻辑分为客户端和服务器端。
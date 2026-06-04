# Bingo Lottery Simulator

一个纯前端的 5×5 Bingo 抽奖模拟器，规则来自原 Python 模拟代码。

## 功能

- 5×5 Bingo 翻格抽奖盘
- 每个格子可设置不同抽中权重
- 支持“开启一次”“开启十次”“开启 N 次”
- 已翻开的格子会显示本轮累计抽中次数，重复抽中会继续累加数字
- 自动判断 5 行、5 列、2 条对角线，共 12 条奖励线
- 支持批量 Monte Carlo 模拟
- 输出“获得第 n 个奖励的平均抽数”与“指定抽数内至少获得第 n 个奖励的概率”

## 使用方式

直接双击打开 `index.html` 即可使用。

也可以在 GitHub Pages 中部署：

1. 进入仓库 Settings
2. 打开 Pages
3. Source 选择 `Deploy from a branch`
4. Branch 选择 `main`，目录选择 `/root`
5. 保存后等待生成网页链接

## 技术说明

本项目只有一个 `index.html` 文件，不需要后端、数据库或 Node.js。

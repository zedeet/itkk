# 智能旅游路线生成系统

## 项目简介
智能旅游路线生成系统是一个基于MCP服务的智能旅游规划工具，旨在为用户提供个性化的旅游路线推荐。系统结合了地理信息、用户偏好和实时数据，自动生成最优化的旅游路线。

## 功能特点
- **智能路线规划**：根据用户输入的起点、终点和偏好，自动生成最优旅游路线
- **MCP服务集成**：集成高德地图API，提供精准的地理位置服务和路线导航
- **多日行程规划**：支持生成多日旅游行程，合理安排每日景点游览顺序
- **实时数据更新**：整合实时天气、交通等数据，动态调整路线建议

## 使用方法
1. 克隆本项目到本地
2. 安装依赖：`npm install`
3. 启动开发服务器：`npm run dev`
4. 访问 `http://localhost:3000` 使用系统

## 技术栈
- 前端：React + Vite
- 后端：Node.js + Express
- 数据库：MySQL
- 地图服务：高德地图API

## 贡献指南
欢迎贡献代码！请遵循以下步骤：
1. Fork 本项目
2. 创建新的分支 (`git checkout -b feature/your-feature`)
3. 提交更改 (`git commit -m 'Add some feature'`)
4. 推送分支 (`git push origin feature/your-feature`)
5. 创建 Pull Request

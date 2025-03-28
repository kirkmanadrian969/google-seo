# AdsPower本地API使用指南：功能详解与操作教程

## 什么是AdsPower本地API？

AdsPower本地API是一款强大的程序化接口工具，能够通过代码实现以下核心功能：

- 账户信息检索与管理
- 浏览器启动与关闭控制
- 多账户搜索功能
- 与Selenium/Puppeteer等自动化框架集成
- 高级订阅用户可享受更多定制化接口功能

👉 [【点击查看】2025年最新AdsPower优惠码及特价活动方案汇总](https://bit.ly/adspower_free)

## 详细使用步骤

### 准备工作
1. **获取API密钥**：联系官方客服获取专属API访问权限
2. **登录客户端**：确保AdsPower应用保持登录状态
3. **验证设置**：通过"账户管理 → 设置"确认API配置状态

### 常用API接口示例

#### 1. 本地HTTP请求 - 启动浏览器
http
GET /api/v1/browser/start?user_id=12345

#### 2. 云端HTTP请求 - 创建分组
http
POST /api/v1/group/create
{
    "group_name": "营销团队"
}

#### 3. 云端HTTP请求 - 搜索分组
http
GET /api/v1/group/search?keyword=重要客户

## 获取API权限说明

目前AdsPower本地API仅面向高级订阅用户开放，订阅方案包含：

- 基础版：$100/月起
- 企业版：$500/月起（含专属技术支持）

建议需要API功能的用户提前规划订阅方案，以获得完整的自动化功能支持。
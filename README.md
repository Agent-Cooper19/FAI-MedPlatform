# 项目目录结构

```text
FAI-MedPlatform/
│
├── frontend/                     # Vue3 前端
│   ├── src/
│   │   ├── api/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── router/
│   │   ├── views/
│   │   ├── App.vue
│   │   └── main.js
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/                      # FastAPI 后端
│   ├── app.py
│   ├── config.py
│   ├── requirements.txt
│   ├── routers/
│   ├── services/
│   ├── database/
│   ├── models/
│   └── utils/
│
├── ai/                           # AI 模型
│   ├── segmentation/
│   ├── mesh2ssm/
│   ├── medgemma/
│   ├── fusion/
│   └── common/
│
├── database/                     # SQLite 数据库
│
├── uploads/                      # 用户上传数据
│
├── outputs/                      # 模型输出结果
│
├── logs/                         # 日志文件
│
├── docs/                         # 项目文档
│
└── README.md
```

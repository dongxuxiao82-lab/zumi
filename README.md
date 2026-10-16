# Zumi - Node Express Skeleton

这是为 FDEAABH6/zumi 提供的最小 Node.js + Express 启动骨架，便于在本机或 Docker 上运行。

本地运行:
1. 安装依赖:
   npm install
2. 启动:
   npm start
3. 打开: http://localhost:3000

使用 Docker:
1. 构建镜像:
   docker build -t zumi-skeleton .
2. 运行:
   docker run -p 3000:3000 zumi-skeleton

或使用 docker-compose:
   docker-compose up --build

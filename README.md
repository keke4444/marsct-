# MarsCTF 本地部署

## 快速启动

```bash
# 复制环境变量配置
cp .env.example .env
# 编辑 .env 设置密码
vim .env
# 启动
docker-compose up -d
```

## 环境变量

| 变量 | 说明 | 默认值 |
|------|------|--------|
| `MYSQL_ROOT_PASSWORD` | MySQL root 密码 | `123456` |
| `MYSQL_PASSWORD` | marsdb 用户密码 | `marsdb` |

## 访问

- Web: http://localhost:7991
- API: http://localhost:7991/api

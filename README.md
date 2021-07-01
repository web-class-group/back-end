# Flaskr项目说明

## 环境依赖
 - python版本：3.8.10
 - 第三方库：flask 2.0.1

## 部署步骤

首先在gitpod中打开该仓库，在控制台中输入下列命令：
1. pip install flask
2. export FLASK_APP=flaskr
3. export FLASK_ENV=development
4. flask run --host=0.0.0.0
5. 选择 make public
6. 打开对应的端口链接，Open Brower

## 运行截图

[![R06FxO.md.png](https://z3.ax1x.com/2021/06/30/R06FxO.md.png)](https://imgtu.com/i/R06FxO)
[![R06PG6.md.png](https://z3.ax1x.com/2021/06/30/R06PG6.md.png)](https://imgtu.com/i/R06PG6)
[![R06iRK.md.png](https://z3.ax1x.com/2021/06/30/R06iRK.md.png)](https://imgtu.com/i/R06iRK)

## 目录结构
```
.
├── flaskr
│   ├── auth.py
│   ├── blog.py
│   ├── db.py
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── auth.cpython-38.pyc
│   │   ├── blog.cpython-38.pyc
│   │   ├── db.cpython-38.pyc
│   │   └── __init__.cpython-38.pyc
│   ├── schema.sql
│   ├── static
│   │   ├── apple-touch-icon.png
│   │   ├── favicon.ico
│   │   └── style.css
│   └── templates
│       ├── auth
│       │   ├── login.html
│       │   └── register.html
│       ├── base.html
│       └── blog
│           ├── create.html
│           ├── index.html
│           └── update.html
├── instance
│   └── flaskr.sqlite
├── LICENSE
└── README.md
```

## 版权和许可信息
本项目采用[MIT许可](LICENSE)


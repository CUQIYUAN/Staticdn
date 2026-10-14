# Staticdn

> 静态文件 CDN
> 个人自用

## 文件结构

```txt
Staticdn/
├── assets/                 # 长期静态资源
├── data/                   # 数据文件
│
└── README.md
```

## CDN 地址

### jsDelivr

> jsDelivr 支持通过 CDN 访问 GitHub 公开仓库中的静态文件，适用于 JS、CSS、图片、字体、JSON 等资源。

**基本格式：**

```url
https://cdn.jsdelivr.net/gh/{用户名}/{仓库名}@{版本或分支}/{文件路径}
```

#### 指定版本

通过版本号访问文件，适合生产环境使用。

```url
https://cdn.jsdelivr.net/gh/CUQIYUAN/Staticdn@1.0.0/{path/to/file}
```

#### 指定最新版本

通过 `latest` 引用仓库最新发布的 GitHub Release 版本。

```url
https://cdn.jsdelivr.net/gh/CUQIYUAN/Staticdn@latest/{path/to/file}
```

#### 指定分支

通过分支名访问文件，适合开发和测试。

```url
https://cdn.jsdelivr.net/gh/CUQIYUAN/Staticdn@main/{path/to/file}
```

#### 指定标签

通过 Git Tag 访问文件。

```url
https://cdn.jsdelivr.net/gh/CUQIYUAN/Staticdn@v1.0.0/{path/to/file}
```

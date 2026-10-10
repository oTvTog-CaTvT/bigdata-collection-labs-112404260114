# 大数据采集与处理实验

- 姓名：杨佳慧
- 学号：112404260114
- 班级：数据1241
- GitHub 用户名：oTvTog-CaTvT

## 仓库结构

```text
bigdata-collection-labs-112404260114/
├── README.md
└── lab01/
    ├── lab1_html_api.ipynb   # 实验一代码：静态页面与 API 数据采集
    ├── REPORT.md             # 实验一报告
    ├── data/
    │   ├── companies.json    # Company 采集结果（60 条）
    │   └── devices.json      # Device 采集结果（5000 条）
    └── images/
        ├── 01_device_api.png
        ├── 02_company_source.png
        ├── 03_company_next.png
        └── 04_validation.png
```

## 实验平台

- SmartPark DataLab：`https://115.159.159.82`（教学环境，自签名证书）
- 目标数据：
  - Device：`/devices` 页面，动态加载（API：`/api/devices`），共 5000 条；
  - Company：`/companies` 页面，静态加载，采集前 3 页共 60 条。

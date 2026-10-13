# Fitness Database

个人与家庭成员长期健身数据仓库。

目标：建立可持续多年使用的训练、身体变化、照片、分析数据库。

## 核心结构

```
Fitness-Database/
├── README.md
├── TEMPLATE/                 # 所有记录模板
├── Members/                  # 家庭成员数据
│   └── Member-Name/
│       ├── Profile.md        # 基础档案
│       ├── Training/         # 每次训练记录
│       ├── Measurements/     # 身体检测记录
│       ├── Photos/           # 相册索引
│       ├── Nutrition/        # 饮食记录
│       └── Reviews/          # 阶段复盘
├── Database/                 # 公共数据库
│   ├── Exercise-Library.md
│   ├── Equipment.md
│   └── Standards.md
└── Analytics/                # 数据分析
    ├── Strength.md
    ├── Body-Change.md
    └── Progress.md
```

## 数据规范

- 日期：YYYY-MM-DD
- 重量：kg；哑铃注明单只重量
- 训练必须记录：动作、重量、次数、组数、组间休息、RPE、备注
- 身体照片不直接上传 GitHub，仅保存相册链接和索引
- 每位成员独立目录
- 数据设计兼容未来 Excel/数据库导入

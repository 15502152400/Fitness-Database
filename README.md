# Fitness Database

个人与家庭成员健身数据管理库。

## 目标

记录长期健身过程中的：

- 训练计划与训练日志
- 身体状态变化
- 体测数据
- 身体照片记录
- 动作表现变化
- 阶段总结与调整依据

## 数据结构

```
Fitness-Database/
├── README.md
├── TEMPLATE/
│   ├── Training-Log.md
│   ├── Body-Profile.md
│   ├── Body-Measurement.md
│   └── Monthly-Review.md
├── Members/
│   └── member-name/
│       ├── Profile.md
│       ├── Training/
│       ├── Measurements/
│       ├── Photos/
│       └── Reviews/
└── Database/
    ├── Exercise-Library.md
    └── Equipment.md
```

## 记录原则

- 日期统一使用 YYYY-MM-DD
- 重量单位默认 kg，哑铃单只重量单独注明
- 每次训练保留动作、重量、次数、组数、组间休息
- 身体照片只保存外部相册链接，不直接上传隐私照片
- 所有成员独立管理，方便长期追踪

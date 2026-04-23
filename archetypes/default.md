---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags: []
draft: false

# 1. 躯体与生理系统 (Soma)
soma:
  energy: 3
  health: []

# 2. 心智与认知系统 (Psyche)
psyche:
  mood: "平静"
  focus: 3
  epiphany: false

# 3. 社交与人脉网络 (Nexus)
nexus:
  people: []
  intensity: 3

# 4. 事业与创造输出 (Opus)
opus:
  missions: [] # [{name: "项目名", status: "active/resolved"}]
  milestone: false

# 5. 上下文与环境 (Context)
context:
  location: "北京"
  weather: ""

# 6. 灵感与创作系统 (Muses)
muses:
  type: []
  status: "seed"
  payload: ""

# 7. 财务与资源系统 (Fiscus)
fiscus:
  flow: 0.0
  category: ""
  status: "steady"
  note: ""

# 8. 时间轴与蓝图 (Chronos)
chronos: [] # [{event: "事件名", date: "YYYY-MM-DD", type: "reminder/plan"}]
---

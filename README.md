# 小游戏合集

这个仓库用于收纳多个静态网页小游戏。当前包含第一款游戏：M9S `血蝠死斗（蝙蝠转转转）` 机制练习器。

## 结构

```text
my-mini-games/
├─ index.html
├─ game-1/
│  ├─ index.html
│  ├─ style.css
│  ├─ script.js
│  └─ assets/
└─ README.md
```

## 运行

直接打开根目录 `index.html` 可以进入小游戏合集首页。

第一款游戏也可以直接打开 `game-1/index.html`。游戏会加载 `game-1/assets/M9S-MAP.jpg` 作为场地底图，并使用 `game-1/assets/M9S-BOSS.jpg` 作为 Boss 贴图。

## 第一款游戏操作

- `WASD` 或方向键移动玩家。
- 空格暂停/继续。
- 点击 `开始练习` 开始一轮。
- 点击 `重新随机` 重新生成塔位、蝙蝠方向和蝙蝠 AoE。

## GitHub Pages

部署到 GitHub Pages 时，发布源使用 `main` 分支的 `/root`。
